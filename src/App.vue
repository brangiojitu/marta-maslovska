<template>
<section>
  <body>
  <div>
    <ul>
    <h1>Marta Maslovska</h1>
    <hr>
    <hr>
    <AboutMe 
    v-bind:Contacts="Contacts"
    v-bind:Aboutme="Aboutme"
    />
    <img src="@/assets/photo1.jpg" alt=""
    height="300px"
    width="300px">
    <body>
      <h2><p style="text-align: center; position:relative; left:80px; top:-190px; font-family: 'Dancing Script';">About me</p></h2>
    <center>
<p style="text-align: property; position:relative; left:80px; top:-200px; div-class:column;">I am a multimedia design student and consider myself an artist.<br />
 I chose these studies because I want to create and inspire other people with my works.<br />
 On this page you will find only four of my initial projects that I did as a first / second year student.<br />
 Every day I feel that I am learning something new and that I am improving, not only as a multimedia<br />
designer, but as a person. I believe that after completing these studies, a really good, inspiring<br />
 and just charismatic project will appear on this page. So if you are interestedin my work<br />
or just want to know more about my activities - contact me at the contacts above.</p>
</center>
<hr style="text-align: center; position:relative; top:-150px;">
      <center>
        <hr style="text-align: center; position:relative; top:-150px;">
        <h3 style="text-align: center; position:relative; left:80px; top:-155px;">Projects</h3>
        <hr style="text-align: center; position:relative; top:-160px;">
        <hr style="text-align: center; position:relative; top:-160px;">
      <img src="@/assets/project-mini-me.jpg" alt="" style="text-align: center; position:relative; top:-150px;"
    height="250px"
    width="250px"
    align="right"
    position="relative"
    top="-150px">
    <p style="text-align: left; position:relative; top:-150px;">“Mini me project” - it was my very first work through an illustrator program.<br />
         This assignment was given to us, in order to learn how to work with this very fun program.<br />
          Our class “picture” consists of each of our “mini me” imaginary characters<br />
           and our academy has print version of this project in hallway of our school.<br />
           I chose the pen tool - while I was working with this project this tool<br />
           has become one of the main tools in working with this program - in other projects.</p>
    <hr>
    <hr>
<img src="@/assets/mu.jpg" alt=""
    height="250px"
    width="250px"
    align="left">
    <p style="text-align: justify; text-justify: inter-word; position:relative; right:-65px;">“Movie app” - In the second year, when we started to delve deeper into app and website<br />
       development, we were tasked with creating xd design for the imaginary app.<br />
        I created a prototype of the movies app. In the future, I would like to implement this website / app idea.<br />
        App - an idea. The idea was a movie website / app where you can find a variety of information about the films, not<br />
         only their descriptions, but also interesting facts about the film's making, photos, and footage from the cast and<br />
          movie set. Since these days it is very difficult to choose the films we want to watch, I think that the detailed<br />
           depiction of the process can interest the viewer for film reviews. On the left you can see an example of a prototype.<br />
            This app would provide an opportunity to create a profile so that visitors to this site can subscribe to the<br />
           news, create their own list of favorite movies, and maybe in the future, even watch movies directly on the site.</p>
      <img src="@/assets/logoranka.jpg" alt="" style="text-align: left; position:relative; top:110px;"
    height="250px"
    width="250px"
    align="right">
      <hr style="text-align: center; position:relative; top:85px;">
      <hr style="text-align: center; position:relative; top:85px;">
      </center>
      </body>
    </ul>
      <p style="text-align: justify; text-justify: inter-word; position:relative; top:130px; left:10px;">
        “Logo for Idea House” - was our first logo design assignment. When I did this task, I tried to<br />
        focus more on the idea itself. After doing this task and consulting with the teacher, I realized what
        I had done well<br /> and what had gone wrong in this project. This work was completely inappropriate for
        the logo. But for me personally, it was and remains a nice job. I’m glad <br /> I already
        have an understanding of what a good logo should look.</p>
        <hr style="text-align: center; position:relative; top:225px;">
        <hr style="text-align: center; position:relative; top:225px;">
        <img src="@/assets/pjimage.jpg" alt="" style="left:50px; position:relative; top:230px;"
    height="250px"
    width="250px"
    align="left">
    <p style="text-align: right; position:relative; top:250px;">
      “Project about Hjerting” - This was one of the first more time-consuming projects.<br />
       It could be done in groups or individually. I chose to do this work individually.<br />
        Unfortunately, it wasn’t one of my best work, but it was a meaningful time spent photographing<br />
         and describing the Hjerting area. Performing this project was a very good practice working<br />
          with in design and with photoshop.</p>
    <hr style="position:relative; top:380px;">
    <hr style="position:relative; top:380px;">
    <img src="@/assets/logorent.jpg" alt="" style="right; position:relative; top:380px;"
    height="250px"
    width="250px"
    align="right">
    <p style="text-align: left; position:relative; top:400px;">
      “Rent and Go Logo” - it was a job assigned to perform in groups. We had to make a prototype for car<br />
       rental site. We divided the work. Because I wanted more practice after the first failed logo, I chose<br />
        to do the Logo for this project. I made 3 possible variants of the logo. To our prototype created at<br />
         that time, these variants of the logo was good enough.</p>
    <hr style="position:relative; top:530px;">
    <hr style="position:relative; top:530px;">
    <h4><p style="text-align: center; position:relative; top:530px;">Important Links</p></h4>
<p style="text-align: center; inter-word; position:relative; top:535px;">
 <a href=””>https://youtu.be/LKglTifUZMA</a><br /> Video CV<br />
 <a href=””>https://docdro.id/qp3nlTF</a> <br />CV
    <hr style="position:relative; top:530px;">
    <hr style="position:relative; top:530px;">
    </div>
    </body>
    </section>
</template>
<script>
import AboutMe from '@/components/AboutMe'
export default {
Contacts:[
  {title: 'Email - sowsainis@gmail.com', completed: false},
  {title: 'Phone number - +4591955487', completed: false}
],
  components: {
    AboutMe
  }
  }
</script>
<style lang="css" scoped>
@media screen and (max-width: 481px) {
#main, #subnav{
  float: left;
  padding:0;
  width: 94%;
  margin: 3%;
};
}
body {
  background-image: url('./assets/3.jpg');
  background-size: cover;
}
  </style>