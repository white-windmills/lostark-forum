# 2022-4-19
- Rainbow "waving "styled `start discussion` button with css, refer to [rainbow.css](https://github.com/white-windmills/lostark-forum/blob/master/update/2022-4-19/rainbow.css) for more details.
    - Result: ![image](https://user-images.githubusercontent.com/101481353/163897602-74adb032-16dc-4bd2-a285-35c80bb9a058.png)
```css
.IndexPage-newDiscussion {
    background: linear-gradient(124deg, #ff2400, #e81d1d, #e8b71d, #e3e81d, #1de840, #1ddde8, #2b1de8, #dd00f3, #dd00f3);
    color: #fff;
    background-size: 1800% 1800%;
    -webkit-animation: rainbow 15s ease infinite;
    -z-animation: rainbow 15s ease infinite;
    -o-animation: rainbow 15s ease infinite;
    animation: rainbow 15s ease infinite;
}

@-webkit-keyframes rainbow {
    0% {
        background-position: 0% 82%
    }

    50% {
        background-position: 100% 19%
    }

    100% {
        background-position: 0% 82%
    }
}

@-moz-keyframes rainbow {
    0% {
        background-position: 0% 82%
    }

    50% {
        background-position: 100% 19%
    }

    100% {
        background-position: 0% 82%
    }
}

@-o-keyframes rainbow {
    0% {
        background-position: 0% 82%
    }

    50% {
        background-position: 100% 19%
    }

    100% {
        background-position: 0% 82%
    }
}

@keyframes rainbow {
    0% {
        background-position: 0% 82%
    }

    50% {
        background-position: 100% 19%
    }

    100% {
        background-position: 0% 82%
    }
}
```
