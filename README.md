# less-triangle
less triangle mixin

```less
@import "../../m/triangle/index.less";
.m-triangle-example {
    &:before {
        .TRIANGLE_TOP(5px, #ABCDEF);
    }
    &:after {
        .TRIANGLE_BOTTOM(5px, blue);
    }
}
.m-triangle-demo {
    &:after {
        .TRIANGLE_LEFT(5px, orange);
    }
    &:before {
        .TRIANGLE_RIGHT(5px, pink);
    }
}
```
