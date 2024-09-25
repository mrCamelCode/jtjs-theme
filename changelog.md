# 2.1.0

- Added styling for the following components added in `@jtjs/react@2.0.0`:
  - `ImageCarouselWithFullView`
  - `CarouselWithFullView`
  - `FullImageFileInput`

# 2.0.0

- Internal adjustments and improvements, no breaking changes.

# 1.3.1
- Added overlooked `.jtjs-anim_fade-out` animation.

# 1.3.0

- #6: Exposed animations for use in consuming code styles. Animations can be accessed via the named animation, or by applying the class for the animation. The classes make some assumptions about a default duratio and timing function, but these details can easily be overridden by specifying overriding styles. The animations currently exposed are:
```
.jtjs-anim_fade-in
.jtjs-anim_slide-in
.jtjs-anim_slide-out
.jtjs-anim_pop
.jtjs-anim_pop-wiggle
.jtjs-anim_shimmer
.jtjs-anim_pulse
```

# 1.2.0

- Added styles for the new dialog components.
