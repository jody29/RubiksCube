# CSS TO THE RESCUE

## Week 1
When I started to build a rubik's cube, I decided to first try and build a single cube. One `<ul>` element will be a single cube and the `<li>` elements will be the sides of the cube. I created 26 `<ul>` elements with each 6 `<li>` elements in it. I centered all the li elements and then rotated every li to finally form a single cube. All the ul elements where inside a `<section>` element. I made sure that all 26 blocks where centered, so I could rotate the blocks to the right position. At first I located the blocks randomly. I used a calc inside the translate and then rotated all the blocks to the right position. Finally I discovered that this way, I won't be able to rotate one side of the cube, so I knew I had to recreate my cube next week and creating the cube by layer (bottom > middle > upper). This way I could easily select the lower side (first 9 blocks).

![Schermafbeelding 2022-03-04 om 01 23 17](https://user-images.githubusercontent.com/66092262/156675547-6a0a08fe-7959-4a25-be6f-945e51818709.png)

## Week 2
