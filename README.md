<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
*, html,body{
  padding:0px;
  margin:0px;
  box-sizing:border-box;
  font-family:'Poppins', sans-serif;
  perspective:800px;
}
body{
  /* background-color:#227093; */
  width:100%;
  min-height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
}
.timeline{
  width:800px;
  /* background-color:#072736; */
  color:#fff;
  padding:30px 20px;
  /* box-shadow:0px 0px 10px rgba(0,0,0,.5); */
}
.timeline ul{
  list-style-type:none;
  border-left:2px solid #094a68;
  padding:10px 5px;
}
.timeline ul li{
  padding:20px 20px;
  position:relative;
  cursor:pointer;
  transition:.5s;
}
.timeline ul li span{
  display:inline-block;
  background-color:#1685b8;
  border-radius:25px;
  padding:2px 5px;
  font-size:15px;
  text-align:center;
}
.timeline ul li .content h3{
  color:#34ace0;
  font-size:17px;
  padding-top:5px;
}
.timeline ul li .content p{
  padding:5px 0px 15px 0px;
  font-size:15px;
  color:#495054;
}
.timeline ul li:before{
  position:absolute;
  content:'';
  width:20px;
  height:20px;
  background-color:#34ace0;
  border-radius:50%;
  left:-16px;
  top:28px;
  transition:.5s;
}
.timeline ul li:hover{
    background-color:#bccad0;
  /* background-color:#071f2a; */
}
.timeline ul li:hover:before{
  background-color:#0F0;
  box-shadow:0px 0px 10px 2px #0F0;
}
@media (max-width:300px){
  .timeline{
    width:100%;
    padding:30px 5px 30px 10px;
  }
  .timeline ul li .content h3{
    color:#34ace0;
    font-size:15px;
  }

}
</style>

# Terje Kvannli

<hr/>

*--testing profile layouts--*

<div class="timeline">
    <ul>
      <li>
        <span>3rd January 2023</span>
        <div class="content">
          <h3>What Is Lorem Ipsum?</h3>
          <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.
          </p>
        </div>
      </li>
      <li>
        <span>21st Jun 2019</span>
        <div class="content">
          <h3>What Is Lorem Ipsum?</h3>
          <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
          </p>
        </div>
      </li>
      <li>
        <span>15th April 2018</span>
        <div class="content">
          <h3>What Is Lorem Ipsum?</h3>
          <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
          </p>
        </div>
      </li>
      <li>
        <span>22nd Mars 2017</span>
        <div class="content">
          <h3>What Is Lorem Ipsum?</h3>
          <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard.
          </p>
        </div>
      </li>
    </ul>
  </div>