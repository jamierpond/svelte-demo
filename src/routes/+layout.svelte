
<div class="header">
  <nav>
    <a href="/">Home</a>
    <a href="/about">About</a>
    <a href="/contact">Contact</a>
    <a href="/blog">Blog</a>
  </nav>
</div>


<style>

  h1 {
    color: blue;
  }

  .footer-containter {
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;
    background-color: #000;
    color: white;
    text-align: center;
  }

  nav {
    display: flex;
    justify-content: space-around;
    padding: 1rem;
    background: #000;
  }

</style>

<slot />

<div class="footer-containter">
  <footer>
    <p>© Jamie Pond - 2024</p>
  </footer>
</div>

