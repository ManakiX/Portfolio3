
<template>
  <footer class="footer-clean">
    <div class="container">
      <div class="footer-row">
        <div class="footer-col">
          <h3>More About Me</h3>
          <ul>
            <li>- Studied Web development at <br><a href="#">Life Choices Coding Academy</a></li>
            <li>- I enjoy online competitive games,<br> chess, and reading books <a href="#"></a></li>
            <li>- Dogs are superior<a href="#"></a></li>
            <li>- Just Hire Me</li>
          </ul>
        </div>
        <div class="footer-col">
          <h3>Services</h3>
          <ul>
            <li><a href="#">Web Design</a></li>
            <li><a href="#">Full-Stack Development</a></li>
            <li><a href="#">UI/UX Design</a></li>
          </ul>
        </div>
        <div class="footer-col">
          <h3>Contact Details</h3>
          <ul>
            <li><a><i class="fa fa-envelope " aria-hidden="true"></i>  Email:<br>sogeyanaluntu@gmail.com</a></li>
            <li><a><i class="fa fa-phone " aria-hidden="true"></i>  Phone:<br>+27 67 826 7299</a></li>
            <li><a><i class="fa fa-home" aria-hidden="true"></i>  Home area:<br>Delft South, The Hague</a></li>
          </ul>
        </div>
      </div>
      <div class="footer-row">
        <div class="footer-col footer-social">
          <h3>Follow Me</h3>
          <a target="_blank" href="https://www.linkedin.com/in/luntu-sogeyana-011118270/"><i class="fab fa-linkedin"></i></a>
          <a target="_blank" href="https://github.com/ManakiX"><i class="fab fa-github"></i></a>
          <a target="_blank" href="https://www.facebook.com/lukhanyiso.nk"><i class="fab fa-facebook"></i></a>
        </div>
      </div>
      <div class="footer-row">
        <div class="footer-col text-center">
          <p class="mt-4 mb-0">
            &copy; 2023 Luntu Sogeyana Portfolio. All rights reserved.
          </p>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style scoped>

li {
  color: white;
}
.footer-clean {
  padding: 30px 0;
  padding-bottom: 0%;
  background-color: rgb(62, 61, 61);
  color: yellow;
}

/* .footer-row {
  color: white !important;
} */

.footer-clean h3 {
  margin-top: 0;
  margin-bottom: 12px;
  font-weight: bold;
  font-size: 16px;
}

.footer-clean ul {
  padding: 0;
  list-style: none;
  line-height: 1.6;
  font-size: 14px;
  margin-bottom: 0;
}

.footer-clean ul a {
  color: inherit;
  text-decoration: none;
  opacity: 0.8;
}

h3{
  font-size: x-large !important;
}

li {
  font-size: large;
}

a, i {
  transition: 0.1s linear;
}

a:hover i {
 transform: scale(1.1);
 /* color: blue; */
}
.footer-clean ul a:hover {
  opacity: 1;
}

.footer-clean .footer-row {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.footer-clean .footer-col {
  flex-basis: 100%;
  max-width: 300px;
  text-align: center;
  margin-bottom: 30px;
}

.footer-clean .footer-social a {
  display: inline-block;
  width: 40px;
  height: 40px;
  line-height: 40px;
  text-align: center;
  border-radius: 50%;
  border: 1px solid yellow;
  margin: 0 5px;
  font-size: 24px;
  opacity: 0.75;
  color: yellow;
}

.footer-clean .footer-social a:nth-child(2):hover {
  color: rgb(53, 53, 254);
  background-color: yellow;
}
.footer-clean .footer-social a:nth-child(3):hover {
  color: black;
  background-color: yellow;
}
.footer-clean .footer-social a:nth-child(4):hover {
  color: rgb(69, 69, 252);
  background-color: yellow;
}
.footer-clean .footer-social a:nth-child(5):hover {
  color: rgb(230, 64, 230);
  background-color: yellow;

}
.footer-clean .footer-social a:nth-child(6):hover {
  color: blue;
  background-color: yellow;

}
.footer-clean .footer-social a:nth-child(7):hover {
  color: black;
  background-color: yellow;

}

.footer-clean .text-center {
  text-align: center;
}

.footer-clean p {
  margin-top: 14px;
  margin-bottom: 0;
  font-size: 13px;
  opacity: 0.6;
}
</style>

  