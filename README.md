# Karty-podskazhut

A HTML, CSS and Vanilla JavaScript project form Yandex.Practicum «Frontend Developer» course.

This project was created to focus on creating responsive websites, that would look good on various devices and and browsers. The website can be toggled between Dark and Light themes.

### Project Checklist

<details>
  <summary>using &lt;picture&gt; tag to load only image optimal for current device</summary>
  ```html
       <picture>
          <source srcset="./images/cards-1x.avif 1x" type="image/avif" />
          <source srcset="./images/cards-2x.avif 2x" type="image/avif" />
          <source srcset="./images/cards-1x.webp 1x" type="image/webp" />
          <source srcset="./images/cards-2x.webp 2x" type="image/webp" />
          <img
            srcset="./images/cards-1x.png 1x, ./images/cards-2x.png 2x"
            loading="lazy"
            class="content__picture"
            alt="Картинка с блокнотом, телефоном и карточкой с надписью Trust in the you of now"
          />
        </picture>
```
</details>

### Figma Layout

Click [here](<https://www.figma.com/file/wdZurx6BngCbVUyOI3paLi/%235-%D0%9A%D0%B0%D1%80%D1%82%D1%8B-%D0%BF%D0%BE%D0%B4%D1%81%D0%BA%D0%B0%D0%B6%D1%83%D1%82-(Copy)?type=design&node-id=0%3A1&mode=dev&t=voAdteEyJsmzYBzi-1>) to open Website Figma Layout

### Project Demo

Link to project website: https://practicum-karty-podskazhut.netlify.app/

Website Preview:

![Website Demo](./images/demo.gif)
