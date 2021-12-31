# 0x09. Implement a design from scratch

-   By Nicolas Philippot, UI/UX designer and Guillaume Salva, CTO at Holberton School

## Concepts

In this project, you will implement from scratch, without any library, a web page. You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously.

You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have a fully functional web page that looks the same as the designer file.

Here the final result:

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/60df485eb772ecbad54a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20211231%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20211231T170629Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=63ea92d9a101d07be8c20142ccfdd5a51f45c9b0a64cf0f699211ed129aa3dc6)

This webpage has been designed by Nicolas Philippot, UI/UX designer. You can find final screens  [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/622/Archive.zip "here")

### Requirements

-   you are not allowed to import external CSS framework (like Bootstrap)
-   you are not to use Javascript

## Tasks

### 0. Read and be familiar with Figma


Create an account in  [Figma](https://intranet.hbtn.io/rltoken/eumOUW-eMS4X9ZDZg9KPLg "Figma")  and open this  [project](https://intranet.hbtn.io/rltoken/2ED3P1a2wnbQqRLi8aXJKw "project")  and “Duplicate to your Drafts” to have access to all design details.

If you can’t access to it, please find here the  [Figma file](https://intranet.hbtn.io/rltoken/NxsDNicWs5KSlsR94kt52A "Figma file")

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20211231%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20211231T170629Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=58da51e81da9cebe2baa7fbb27628f7a0c91f44a7fbd9e2924c9108b024bb7b0)

Important notes with Figma:

-   if your computer doesn’t have missing fonts, you can find them here:  [source-sans-pro](https://intranet.hbtn.io/rltoken/wltHny-KZP3B8JFRvpmVjA "source-sans-pro")  and  [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/Qb96K4nTPQJO1paP_OBELw "Spin-Cycle-OT")
-   some values are in float - feel free to round them

For this task, please write an amazing  `README.md`

**Interactions note:**

-   the web page must switch to the mobile version when the screen width is 480px or less
-   links hover/active:  `#FF6565`
-   button hover/active:  `opacity: 0.9`
-   max width of the content: 1000px centered in the page

**Repo:**

-   GitHub repository:  `holberton-headphones`
-   File:  `README.md`


### 1. Header

Building a web page the right way, is not easy - expect if you put in place strong foundations:

-   reset CSS styling
-   use variables
-   simple/“as generic as you can” CSS selectors
-   avoid using super specific CSS selectors as much as possible
-   simple HTML structure -  `div`  containers are your friend!

Last advice: Personally, I always start to build a web page from outside to inside and from top to bottom. But you can try to other way - it’s fine - but you should structure the way that you will implement a component and not get lost with HTML tags.

Now, your turn!

For this first task:  **create the header/hero piece**

Here an archive of all assets needed:  [images_0x09.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/d1597894d79386c83b9b.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20211231%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20211231T170629Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=a9b2c5991de7e5b8821ffeecbc581f81d48b338755134fc0605f5693054c1c3e "images_0x09.zip")

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/4a93441c93989ad7ea72.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20211231%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20211231T170629Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8651657c8f1f565e510db518def94630e930bd60fc978e0989b7e2ab9043d9ae)

**Mobile:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/75a582f98640445a2dbf.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20211231%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20211231T170629Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=5452148021fde37ce6e5a886396decce8ec3b0f67f73091f6baa43a7e4769076)

**Repo:**

-   GitHub repository:  `holberton-headphones`
-   File:  `0-index.html, 0-styles.css`

### 2. "What we do..." section

Copy files from the previous task.

For this second task:  **create the “What we do…” section**

In this section, you will need custom font icons. Here the archive of it:  [holberton_school-icon.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20211231%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20211231T170629Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=e0df6ced2042c63a9260c32894d762c21b44cb0bbb93c44c550b42e561afc911 "holberton_school-icon.zip")  Inside you will find demo page of how to use it.

**Important:**  try to build as generic as you can… you will probably need some components in next section.

**Repo:**

-   GitHub repository:  `holberton-headphones`
-   File:  `1-index.html, 1-styles.css`


### 3. "Our results" section


Copy files from the previous task.

For this third task:  **create the “Our results” section**

Now you can reuse components form the previous task!

**Repo:**

-   GitHub repository:  `holberton-headphones`
-   File:  `2-index.html, 2-styles.css`


### 4. Contact us

Copy files from the previous task.

A good landing page has always a contact form.

You are free to add any animations and/or constraints on fields.

**Repo:**

-   GitHub repository:  `holberton-headphones`
-   File:  `3-index.html, 3-styles.css`

### 5. Footer

Copy files from the previous task.

Last piece of the page… the Footer!

When you are done, here the result:

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3b5a9f7948a58d58bd43.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20211231%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20211231T170629Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b85060d08f19bd2177152d50d9c0ae639e9c69124b93f358ab210af4656db073)

**Mobile:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/83d6311e87d4775ca4b3.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20211231%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20211231T170629Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=234fb7d4703f76121bad42f2cf9bc450914dacff173566608d8ce0ecd78d5e68)

And you are done!

**Good job!**

**Repo:**

-   GitHub repository:  `holberton-headphones`
-   File:  `4-index.html, 4-styles.css`