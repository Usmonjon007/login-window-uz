# Usmonjon Hasanov's login window project

# index.html

```html
<!DOCTYPE html>
<html lang="uz">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Box :: Usmonjon Hasanov</title>
    <meta name="author" content="Usmonjon Hasanov">
    <link rel="stylesheet" href="./style.css">
    <link rel="stylesheet" href="./fonts.css">
</head>

<body>
    <div class="container">
        <div class="left">
            <div class="left-darker"></div>
            <div class="text">
                <h2 class="title">Assalomu alaykum!</h2>
                <p class="desc">Agar hali ro‘yxatdan o‘tmagan bo‘lsangiz,
                    ro‘yxatdan otishingizni taklif qilamiz!</p>
            </div>
            <a href="#" class="btn btn-register">RO‘YXATDAN O‘TISH</a>
        </div>
        <div class="right">
            <h2 class="title">Profilga kirish</h2>
            <ul class="socials">
                <li class="social">
                    <a href="#" class="social-link" title="Google Plus">
                        <svg width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <circle cx="24" cy="24" r="23.5" stroke="white" />
                            <path
                                d="M34.6455 22.8442C34.6368 22.0854 34.6339 21.321 34.631 20.5593H32.2852C32.2765 21.3182 32.2707 22.0798 32.2649 22.8442C31.4752 22.847 30.6913 22.8526 29.9075 22.8611V25.1347C30.6913 25.1431 31.481 25.1488 32.2649 25.1572C32.2736 25.916 32.2736 26.6776 32.2794 27.4364H34.6281C34.631 26.6776 34.6368 25.916 34.6426 25.1516C35.4323 25.1431 36.2161 25.1403 37 25.1319V22.8583C36.219 22.8526 35.4294 22.8526 34.6455 22.8442ZM19.2585 22.8555C19.2556 23.7632 19.2585 24.6738 19.2614 25.5816C20.8349 25.6321 22.4114 25.6097 23.9849 25.6321C23.291 29.0131 18.5443 30.1092 16.033 27.9002C13.4491 25.9638 13.5711 21.7172 16.2566 19.9186C18.1349 18.4684 20.803 18.8253 22.6814 20.0816C23.4188 19.4211 24.1097 18.7129 24.7746 17.9822C23.2127 16.7765 21.2965 15.9165 19.2585 16.0065C15.0024 15.8687 11.0917 19.4773 11.0221 23.6002C10.7492 26.9699 13.0369 30.2722 16.2653 31.4638C19.482 32.6638 23.6075 31.846 25.663 29.0468C27.0188 27.2791 27.312 25.0026 27.1523 22.8639C24.5191 22.8442 21.8888 22.847 19.2585 22.8555Z"
                                fill="white" />
                        </svg>
                    </a>
                </li>
                <li class="social">
                    <a href="#" class="social-link" title="Facebook">
                        <svg width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <circle cx="24" cy="24" r="23.5" stroke="white" />
                            <g clip-path="url(#clip0_0_18)">
                                <path
                                    d="M21.0633 36V24.7385H18V20.6838H21.0633V17.2206C21.0633 14.4992 22.8728 12 27.0423 12C28.7305 12 29.9788 12.1573 29.9788 12.1573L29.8805 15.9437C29.8805 15.9437 28.6074 15.9317 27.2181 15.9317C25.7145 15.9317 25.4737 16.6052 25.4737 17.7232V20.6838H30L29.8031 24.7385H25.4737V36H21.0633Z"
                                    fill="white" />
                            </g>
                            <defs>
                                <clipPath id="clip0_0_18">
                                    <rect width="12" height="24" fill="white" transform="translate(18 12)" />
                                </clipPath>
                            </defs>
                        </svg>
                    </a>
                </li>
                <li class="social">
                    <a href="#" class="social-link" title="Google">
                        <svg width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <circle cx="24" cy="24" r="23.5" stroke="white" />
                            <path
                                d="M31.8531 22.5438H24.1628V25.6396H28.5561C28.3666 26.6403 27.7919 27.4866 26.9256 28.0537C26.1934 28.5332 25.259 28.8167 24.1607 28.8167C22.0343 28.8167 20.2357 27.4095 19.5929 25.5187C19.4312 25.0392 19.3375 24.5264 19.3375 23.999C19.3375 23.4715 19.4312 22.9587 19.5929 22.4792C20.2379 20.5905 22.0365 19.1833 24.1628 19.1833C25.3612 19.1833 26.4361 19.5878 27.2832 20.3799L29.6246 18.0847C28.2091 16.7922 26.3637 16 24.1628 16C20.9722 16 18.2115 17.7928 16.8684 20.407C16.315 21.4869 16 22.7085 16 24.001C16 25.2936 16.315 26.5131 16.8684 27.593C18.2115 30.2072 20.9722 32 24.1628 32C26.368 32 28.2155 31.2829 29.565 30.0612C31.1082 28.6687 32 26.6173 32 24.1803C32 23.6133 31.9489 23.0692 31.8531 22.5438Z"
                                fill="white" />
                        </svg>
                    </a>
                </li>
            </ul>
            <form class="form" id="form">
                <p class="form-title">Emailingizni va parolingizni kiriting</p>
                <div class="inputs">
                    <label for="email" class="label">
                        <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <g opacity="0.5">
                                <path
                                    d="M15 3H3C2.175 3 1.5075 3.675 1.5075 4.5L1.5 13.5C1.5 14.325 2.175 15 3 15H15C15.825 15 16.5 14.325 16.5 13.5V4.5C16.5 3.675 15.825 3 15 3ZM15 6L9 9.75L3 6V4.5L9 8.25L15 4.5V6Z"
                                    fill="#E1BB97" />
                            </g>
                        </svg>
                        <input type="email" title="Emailingizni kiriting" placeholder="Emailingiz" id="email"
                            class="form-control">
                    </label>
                    <label for="password" class="label">
                        <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <g opacity="0.5">
                                <path
                                    d="M15 9C15 8.17275 14.3273 7.5 13.5 7.5H12.75V5.25C12.75 3.18225 11.0677 1.5 9 1.5C6.93225 1.5 5.25 3.18225 5.25 5.25V7.5H4.5C3.67275 7.5 3 8.17275 3 9V15C3 15.8273 3.67275 16.5 4.5 16.5H13.5C14.3273 16.5 15 15.8273 15 15V9ZM6.75 5.25C6.75 4.0095 7.7595 3 9 3C10.2405 3 11.25 4.0095 11.25 5.25V7.5H6.75V5.25Z"
                                    fill="#E1BB97" />
                            </g>
                        </svg>
                        <input type="password" title="Parolingizni kiriting" placeholder="Parol" id="password"
                            class="form-control">
                    </label>
                </div>
                <div class="bottom">
                    <button type="submit" class="btn btn-submit">KIRISH</button>
                    <a href="#" class="forgot">Parolni unutdingizmi?</a>
                </div>
            </form>
        </div>
    </div>
</body>

</html>

```

# style.css
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'HelveticaNeueCyr', sans-serif;
}

body {
    width: 100%;
    height: 100vh;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container {
    width: 979px;
    height: 701px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-radius: 15px;
}

.container .left {
    width: 452px;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    gap: 30px;
    background: url('./img.jpg'), lightgray 50% / cover no-repeat;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    position: relative;
    color: #fff;
}

.container .left .left-darker {
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    background: #000;
    opacity: 0.5;
    z-index: 0;
}

.container .left .text {
    padding: 0 61px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    gap: 20px;
    position: relative;
    z-index: 1;
}

.container .left .text .title {
    color: #FFF;
    font-size: 35px;
    font-weight: 700;
}

.container .left .text .desc {
    color: #E1BB97;
    text-align: center;
    font-size: 15px;
    font-weight: 400;
}

.container .left .btn {
    color: #FFF;
    text-align: center;
    font-size: 22px;
    font-weight: 500;
    width: 328px;
    height: 53px;
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 2;
    text-decoration: none;
    border-radius: 26.5px;
    border: 1px solid #E1BB97;
}

.container .right {
    width: 527px;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    gap: 30px;
    color: #fff;
    background: #181818;
}

.container .right .title {
    color: #FFF;
    font-size: 35px;
    font-weight: 700;
}

.container .right .socials {
    list-style: none;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 12px;
}

.container .right .socials .social .social-link svg circle,
.container .right .socials .social .social-link svg path {
    transition: all .3s ease;
}

.container .right .socials .social .social-link:hover svg circle {
    stroke: #E1BB97;
}

.container .right .socials .social .social-link:hover svg path {
    fill: #E1BB97;
}

.container .right .form {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    gap: 20px;
}

.container .right .form .form-title {
    color: #FFF;
    font-size: 15px;
    font-weight: 400;
}

.container .right .form .inputs {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    gap: 30px;
}

.container .right .form .inputs .label {
    width: 328px;
    height: 53px;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    gap: 7px;
    border-radius: 26.5px;
    border: 1px solid #E1BB97;
    cursor: text;
}

.container .right .form .inputs .label svg {
    margin-left: 19px;
}

.container .right .form .inputs .label .form-control {
    background-color: transparent;
    border: none;
    outline: none;
    color: #7C6957;
    font-size: 12px;
    font-weight: 400;
}

.container .right .form .inputs .label .form-control::placeholder {
    color: inherit;
}

.container .right .form .bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    gap: 15px;
}

.container .right .form .bottom .btn {
    width: 328px;
    height: 53px;
    border-radius: 26.5px;
    border: 2px solid #E1BB97;
    background: #E1BB97;
    color: #FFF;
    text-align: center;
    font-size: 22px;
    font-weight: 700;
    cursor: pointer;
    transition: all .3s ease;
}

.container .right .form .bottom .btn:hover {
    color: #000;
    background-color: #fff;
    border-color: #fff;
}

.container .right .form .bottom .forgot {
    color: #FFF;
    font-size: 15px;
    font-weight: 400;
    text-decoration-line: underline;
}

```

# fonts.css
```css
@font-face {
    font-family: 'HelveticaNeueCyr';
    src: url('./fonts/HelveticaNeueCyr-Bold.ttf');
    font-weight: 700;
}

@font-face {
    font-family: 'HelveticaNeueCyr';
    src: url('./fonts/HelveticaNeueMedium.otf');
    font-weight: 500;
}

@font-face {
    font-family: 'HelveticaNeueCyr';
    src: url('./fonts/helveticaneuecyr_roman.otf');
    font-weight: 400;
}

```
