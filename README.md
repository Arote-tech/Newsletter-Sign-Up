  <div class = "signup-container">
            <div class="icon-container">
                <i class = "far fa-envelope-open"></i>
            </div>
            <h2>Join Our Newsletter</h2>

            <p>Get the latest updates and coding tips straight to your inbox.</p>
            
            <form>
                <div class="input-group">
                    <i class = "far fa-envelope"></i>
                    <input type="email" required placeholder="Enter your email">
                </div>

                <button>Subscribe <i class = "fas fa-arrow-right"></i></button>
            </form>



:root {
    --bg-color: #121212;
    --container-bg: #1e1e1e;
    --primary-color: #bb86fc;
    --secondary--color: #03dac6;
    --text-primary: #e1e1e1;
    --text-secondary: #b0b0b0;
    --border-color: #2c2c2c;
    --input-bg: #2c2c2c;
    --shadow-color: rgba(0, 0, 0, 0.3);
}



* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}



body {
    font-family: sans-serif;
    background-color: var(--bg-color);
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    color: var(--text-primary);
}



.signup-container {
    background-color: var(--container-bg);
    width: 90%;
    max-width: 400px;
    padding: 2.5rem;
    border-radius: 16px;
    box-shadow: 0 10px 30px var(--shadow-color);
    text-align: center;
    border: 1px solid var(--border-color);
}
