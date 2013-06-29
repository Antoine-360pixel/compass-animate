# Compass Animate

Mixins and aniations for Compass

## Usage
import the "animations" folder in your project

```scss
.box {
    @extend %fadeIn;
}
```

`fadeIn`, `fadeOut`, `fadeInUp`, `fadeInDown`, `fadeOutDown`, `fadeInLeft`, `fadeOutLeft`, `fadeInRight`, `fadeOutRight`, `bounceIn`, `bounceOut`

##Example 
```scss
@import "animate/animations";

.box{
    @extend %fadeIn;
}