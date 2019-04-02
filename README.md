<details><summary> C A S C A D I N G &nbsp; S T Y L E &nbsp; S H E E T (CSS)</summary>
<details><summary>

```css
/* ====================================== */
/*                  S                     */
/*                  K                     */
/*                  U                     */
/*                  N                     */
/*                  K                     */
/*                                        */
/*                  W                     */
/*                  O                     */
/*                  R                     */
/*                  K                     */
/*                  S                     */
/*                                        */
/*                  C                     */
/*                  H                     */
/*                  A                     */
/*                  T                     */
/* ====================================== */
/* ====================================== */
/*          G L O S S A R Y               */
/* ====================================== */

/*
- ## Global ##
- Button Rules
    > Focus
    > Hover
    > Active
- Chat Container
- Chat Interior
- MSG Input Btn
    > Hover
    > Active
- Body
- User 1
- User 2
- App Title In App
- Background Layers Container
- Background Layer 1 ( Skunk )
- Background Layer 2 ( Blur Dark )
- Floating Skunk Icon

- ## Dev Team ##
                Andrew T. - User Auth
                Darren V. - Chat Structure
                Jason  S. - Front End
                Rene   M. - Systems
                
```
</summary>
You will see in the code above. We have taken the time to announce the app itself as well as
</details>

<details><summary>

```css

/* ====================================== */
/*            G L O B A L                 */
/* ====================================== */
    * {
                outline:            none;
        text-decoration:            none;
    }
```
</summary>
Utilizing the "*" Allows us to set a global rule that applies to every Id &amp; Class
</details>


<details><summary>

```css
/* ====================================== */
/*         B U T T O N  R U L E S         */
/* ====================================== */
.btn,
.btn:focus,
input[type="text"            ]:focus,
input[type="password"        ]:focus,
input[type="datetime"        ]:focus,
input[type="datetime-local"  ]:focus,
input[type="date"            ]:focus,
input[type="month"           ]:focus,
input[type="time"            ]:focus,
input[type="week"            ]:focus,
input[type="number"          ]:focus,
input[type="email"           ]:focus,
input[type="url"             ]:focus,
input[type="search"          ]:focus,
input[type="tel"             ]:focus,
input[type="color"           ]:focus,
.uneditable-input:focus {   
  background-color:        #55ae73;
        box-shadow:        1px 1px 30px rgb(75, 75, 75);
      border-color:      transparent;
           outline:           0 none;
             width:            398px;
             color:rgb(36, 36, 36);
}
```
</summary>
This specific segment of code was brought in from an exterior source. Doing everything we can to avoid any and all blue or green halo arround links is a priority. They look terrible and generally provide no benefit. This snipet agressivly removes this option from the table.
</details>

<details><summary>

```css
/* ====================================== */
/*        B U T T O N  S T A T I C        */
.btn {
    border-radius:           0 0 0 0;
}
```
</summary>
Rules set forth for a button that is not in use in any way. It is simply located in the viewport. The Border-radius  was left in place to ensure these rules stayed constant since we are not running a [ reset.css ] in this code
</details>

<details><summary>

```css
/* ====================================== */
/*         B U T T O N : H O V E R        */
.btn:hover {
  background-color:     #55ae73;
     border-radius:       0 0 0 0;
     outline-color:   transparent;
     box-shadow:      1px 1px 20px rgb(75, 75, 75);
     color:     rgb(39, 39, 39);
}
```
</summary>
This style rule only pertains to the mouse pointer hovering over the button. Other very popular hover features are animations, color changes &amp; different shapes to name a few. Others can be found here in the [MDN literature](https://mzl.la/2TIuQx9)
</details>


<details><summary>

```css
/* ====================================== */
/*        B U T T O N : A C T I V E       */
.btn:active {
  background-color: #55ae73;
  border-radius:      0 0 0 0;
  border-radius:      0 0 0 0;
  outline-color:  transparent;
  box-shadow:         1px 1px 10px rgb(75, 75, 75);
  color:         whitesmoke;
  }
```
</summary>
This style rule is for when the element is being activly engagued, clicking, moving etc...
</details>

<details><summary>

```css
/* ====================================== */
/*          B U T T O N : F O C U S       */
  .btn:focus {
    background-color:    #55ae73;
       border-radius:      0 0 0 0;
       outline-color:  transparent;
               color: whitesmoke;
  }
/*      B U T T O N  R U L E S  E N D     */
/* ====================================== */
```
</summary>
This style rule applies to the element once it has been engagued, presumably it will stay active while its function is in use but will stay n "focus" until another element is receiving a primary interation. Once this happens thew features of this element will resort to default.
</details>


<details><summary>

```css
/* ====================================== */
/*       C H A T  C O N T A I N E R       */
/* ====================================== */
  #chat {
    position: absolute;
     padding:        0;
      bottom:        0;
       right:        0;
        left:     76vw;
  }
```
</summary>
Container surrounding the chat window
</details>


<details><summary>

```css
/* ===================================== */
/*      C H A T  I N T E R I O R         */
/* ===================================== */
  .boxContainer {

    background-color: rgba(0, 0, 0, 0.9);
       border-radius:           0 30px 0 0;
          box-shadow: 1px -1px rgb(134, 134, 134), -1px 1px rgb(134, 134, 134);
            overflow:               hidden;
             padding:                  2px;
              margin:            0 0 0 2px;
              height:                400px;
               width:                400px;
  }
```
</summary>
Essentially the interior container of the chat app window
</details>


<details><summary>

```css
/* ====================================== */
/*    M S G  I N P U T  &  B U T T O N    */
/* ====================================== */
  #message {
             margin:         235px 0 0 4px;
              width:                 309px;
  }
```
</summary>
The button to submit the users message
</details>

<details><summary>

```css
/* ====================================== */
/*          M S G  I N P U T              */
/* ====================================== */

#sendmessage {
    background-color:         #00000067;
       border-radius:           0 8px 0 0;
               color:           #f5f5f5;
  }
```
</summary>
The input field where the user writes the text tu submit
</details>

<details><summary>

```css
/* ====================================== */
/*     M S G  I N P U T : H O V E R       */
/* ====================================== */
  #sendmessage:hover {
     border-color:              #66aeae;
            color:              #f5f5f5;
   }
```
</summary>
This style rule pertains to the mouse hovering over the selected element to apply a different style rule to the element
</details>

<details><summary>

```css
/* ======================================= */
/*    M S G  I N P U T : A C T I V E       */
/* ======================================= */
   #sendmessage:active {
    border-color:              #9acd32;
           color:              #f5f5f5;
   }
```
</summary>
This style element rule pertains to the active version of the element. This is usually when the actual element is being engagued. In the case of a button this is when the button is being clicked
</details>

<details><summary>

```css
/* ======================================= */
/*               B O D Y                   */
/* ======================================= */
#body {

               background: linear-gradient(-25deg, #7aeaaf, #029eff)no-repeat center center fixed; 
  -webkit-background-size:        cover;
     -moz-background-size:        cover;
       -o-background-size:        cover;
          background-size:        cover;
                   height:        cover;
  }
```
</summary>
This rule pertains to the primary containser of the website, the body. The body is generally the container in witch all elements are stored
</details>

<details><summary>

```css
/* ======================================== */
/*U S E R  1  P O S I T I O N  &  C O L O R*/
/* ======================================== */
  #user1 {
              text-shadow: 1px -1px rgb(0, 0, 0), -1px 1px rgb(0, 0, 0);
               text-align:         left;
                   margin:      0 0 0 0;
                    width:        300px;
                    color:    #55aeae;

  }
```
</summary>
This style rule pertains to the first person to submit a message in the chat. We may set this to be the business side of the chat window as well
</details>

<details><summary>

```css
/* ========================================*/
/*U S E R  2  P O S I T I O N  &  C O L O R*/
/* ======================================= */
  #user2 {
             text-shadow: 1px -1px rgb(0, 0, 0), -1px 1px rgb(0, 0, 0);
              text-align:        right;
                  margin:      0 0 0 0;
                   width:        300px;
                   color:    #55ae73;
  }
```
</summary>
Same as user one. The difference is it posts to the other side and is a different color to quickly tell the difference between both users in the chat room
</details>

<details><summary>

```css
/* =================================================== */
/*           A P P  T I T L E  I N  A P P              */
/* =================================================== */
#inner_title{

      letter-spacing:           1.3vw;
         font-weight:             100;
         font-family:  'Montserrat', sans-serif;
          text-align:          center;
           font-size:            14px;
              margin:      0 0 0 40px;
               color:      rgb(195, 195, 195);
}
```
</summary>
this style rule pertains to C H A T in the header of the chat window.
</details>

<details><summary>

```css
/* ================================= */
/* B A C K G R O U N D  I N  C H A T */
/* ================================= */
  #bg_1,
  #bg_2 {
             z-index:             -9;
            position:          fixed;
}
```
</summary>
This rule pertains to both the skunk outline you see in the chat window as well as the opaque back layer behind it that has been blurred to apply the apple transparency effect
</details>

<details><summary>

```css
/* ======================================== */
/*S K U N K  B A C K G R O U N D  L A Y E R*/
/* ======================================= */
#bg_1 {
            opacity:            0.95;
}
```
</summary></details>

<details>
this style sets rules to the first of the background layers inside of the chat window as to make sure the element has an opacity of 95% from the proginal 100%
<summary>

```css
/* ======================================= */
/* B L U R  B A C K G R O U N D  L A Y E R */
/* ======================================= */
#bg_2 {
           opacity:             0.63;
            filter:       blur(10px);
}
```
</summary>
this style sets rules to the first of the background layers inside of the chat window as to make sure the element has an opacity of 63% from the proginal 100%
</details>

<details><summary>

```css
/* ======================================= */
/*    S K U N K  C H A T  I C O N          */
/* ======================================= */
#skw-nc {
            width:             25px;
           margin:          0 0 0 0;
}
```
</summary>
This style element is to assign sizing and opsition to the SVG used to present the chat app when closed. Future scalability will be to set a color @animation to this element.
</details>

<details><summary>

```css
/* ======================================= */
/*                   E                     */
/*                   N                     */
/*                   D                     */
/* ======================================= */

```
</summary>
Thats all for CSS folks. We hope you enjoyed walking your way through the code and have a great day!
</details>
</details>