<!-- Add this inside the <head> -->
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    animation: fadeIn 2s ease-in;
  }

  @keyframes fadeIn {
    0% {opacity: 0;}
    100% {opacity: 1;}
  }

  section {
    animation: slideUp 1.5s ease;
  }

  @keyframes slideUp {
    from {
      transform: translateY(30px);
      opacity: 0;
    }
    to {
      transform: translateY(0px);
      opacity: 1;
    }
  }

  nav a {
    transition: background-color 0.3s ease;
  }

  nav a:hover {
    background-color: #575757;
    transform: scale(1.1);
  }
</style>
