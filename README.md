           <li class="navbar__btn">
                    <a href="/" class="button">Sign Up</a>
                </li>



<!--Footer Section-->
    <div class="footer__container">
        <div class="footer__links">
            <div class="footer__link--wrapper">
                <div class="footer__link--items">
                    <h2>About Us.</h2>
                    <a href="/">How it Works?</a>
                    <a href="/">Testimonials.</a>
                    <a href="/">Careers.</a>
                    <a href="/">Invest.</a>
                    <a href="/">Terms of Service.</a>
                </div>
                <div class="footer__link--items">
                    <h2>Connect.</h2>
                    <a href="/">Feedback.</a>
                    <a href="/">Participation.</a>
                    <a href="/">Stocks.</a>
                    <a href="/">Share.</a>
                    <a href="/">Terms of Service.</a>
                </div>
            </div>
            <div class="footer__link--wrapper">
                <div class="footer__link--items">
                    <h2>Shift.</h2>
                    <a href="/">Stores.</a>
                    <a href="/">Quantum Systems.</a>
                    <a href="/">Improvements.</a>
                    <a href="/">Submit applications.</a>
                    <a href="/">Terms of Service.</a>
                </div>
                <div class="footer__link--items">
                    <h2>Origins.</h2>
                    <a href="/">Motive.</a>
                    <a href="/">Founders.</a>
                    <a href="/">Goals.</a>
                    <a href="/">Why?</a>
                    <a href="/">Terms of Service.</a>
                </div>
            </div>
        </div>
        <div class="social__media">
            <div class="social__media--wrap">
                <div class="footer__logo">
                    <a href="/" id="footer__logo"><i class="fas faa-gem"></i>Quest</a>
                </div>
                <p class="website__right">®Quest 2022. All Rights Reserved.</p>
                <div class="social__icons">
                    <a href="/" class="social__icon--link" target="_blank">
                        <i class="fab fa-Youtube."></i>
                    </a>
                    <a href="/" class="social__icon--link" target="_blank">
                        <i class="fab fa-IBM"></i>
                    </a>
                    <a href="/" class="social__icon--link" target="_blank">
                        <i class="fab fa-Quanta"></i>
                    </a>
                    <a href="/" class="social__icon--link" target="_blank">
                        <i class="fab fa-NEXT"></i>
                    </a>
                </div>
            </div>
        </div>
    </div>
.services h1 {
    background-color: #ff8177;
    background-image: linear-gradient(to right, #ff8177 0%, #ff867a 0%, #ff8c7f 21%, #f99185 52%, #cf556c 78%, #b12a5b 100%);
    background-size: 100%;
    margin-bottom: 5rem;
    font-size: 2.5rem;
    -webkit-background-clip: text;
    -moz-background-clip: text;
    -webkit-text-fill-color: transparent;
    -moz-text-fill-color: transparent;
}

.services__container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.services__card {
    margin: 1rem;
    height: 525px;
    width: 400px;
    border-radius: 4px;
    background-image: linear-gradient(to bottom, rgba(0,0,0,0) 0%, rgba(17,17,17,0.6) 100%);
    background-size: cover;
    position: relative;
    color: #fff;
}

.services__card:nth-child(2) {
    background-image: linear-gradient(to bottom, rgba(0,0,0,0) 0%, rgba(17,17,17,0.6) 100%);
}

.services h2 {
    position: absolute;
    top: 350px;
    left: 30px;
}

.services__card p {
    position: absolute;
    top: 400px;
    left: 30px;
}

.services__card button {
    color: #fff;
    padding: 10px 20px;
    border: none;
    outline: none;
    border-radius: 40px;
    background: #f77062;
    position: absolute;
    top: 440px;
    left: 30px;
    font-size: 1rem;
    cursor: pointer;
}

.services__card:hover {
    transform: scale(1.075);
    transition: 0.2s ease-in;
    cursor: pointer;
}

@media screen and (max-width: 960px) {
    .services {
        height: 1600px;
    }

    .services h1 {
        font-size: 2rem;
        margin-top: 12rem;
    }
}

@media screen and (max-width: 480px) {
    .services {
        height: 1400px;
    }

    .services h1 {
        font-size: 1.2rem;
    }

    .services__card {
        width: 300px;
    }
}