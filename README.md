# Animate
Custom Animation Repository for Web Development
### How to Use:
Add one of the following classes to an element or a parent element.
List of Classes:
* fadeIn
* fadeOut
* fadeInUp
* fadeInDown
* fadeInLeft
* fadeInRight
* fadeOutLeft
* fadeOutRight
* flipX
* flipY
* flipXAndFadeIn
* flipXAndFadeOut
* flipYAndFadeIn
* flipYAndFadeOut
* heartBeat
* slideInUp
* slipInDown
* slideInLeft
* slideInRight
* slideOutUp
* slideOutDown
* slideOutLeft
* slideOutRight

Add these classes to an element or a parent element to start the animation.

These animations only run once and they move 40px. Change the attributes to change duration, iteration or movement distance.

## Duration and Iteration

For greater developer control, you can add some of the following classes to adapt the duration or iteration count of an animation.

#### Duration

The pre-set duration classes are as follows:

* s1 (1s)
* s1-25 (1.25s)
* s1-5 (1.5s)
* s1-75 (1.75s)
* s2 (2s)
* s2-25 (2.25s)
* s2-5 (2.5s)
* s2-75 (2.75s)
* s3 (3s)
* s3-25 (3.25s)
* s3-5 (3.5s)
* s3-75 (3.75s)
* s4 (4s)
* s4-25 (4.25s)
* s4-5 (4.5s)
* s4-75 (4.75s)
* s5 (5s)
* s5-25 (5.25s)
* s5-5 (5.5s)
* s5-75 (5.75s)
* s6 (6s)

These override the default animation duration of the animation

Alternatively, you can create your own using the following syntax:

`.class {
    animation-duration: (time in seconds)s !important;
}`

#### Iteration

Another way to control animations in CSS, is using custom or the default iteration count.

The pre-set iteration classes are as follow:

* once
* twice
* three-times
* four-times
* five-times
* infinite

These override the default animation iteration count. All animations are set to one count by default.

Alternatively, you can create your own using the following syntax:

`.class {
    animation-iteration-count: (count) !important;
}`