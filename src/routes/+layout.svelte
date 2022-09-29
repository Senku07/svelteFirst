<div class="nav">

<a href="/about">
   <img src="./Leviteting.png" alt="logo" style="display:flex;width:3rem;height:3rem;" >
 </a>
<div class="links">
   <a href="/">Home</a> 
   <a href="/blog">Blog</a>
   <a href="/contact">Contact</a>
   <a href="/about">About</a>   
</div>

</div>
<p>
   <slot>

   </slot>
</p>

<style>
   :global(body){
      background: linear-gradient(to right, rgb(237, 85, 237) , rgb(107, 107, 246));
   }
   .nav{
      display: flex;
      justify-content: space-between;
      align-items: center;
      color: whitesmoke;
      gap: 1rem;
      padding: 1rem 1.5rem;
      border-radius: 0.5rem;
      font-family:Arial;
      background-color: rgb(34, 32, 32,0.7);
   }
   a{
      list-style: none;
      text-decoration: none;
      color: antiquewhite;
   }
   .links{
      display: flex;
      gap: 0.6rem;
   }
</style>