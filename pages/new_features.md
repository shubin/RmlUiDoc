---
layout: page
title: RmlUi Features and Changes
---

A quick glance at some of the features added in {{page.lib_name}} since libRocket.

 * [Animations, transitions, and transforms](rcss/animations_transitions_transforms.html)
 * [Density-independent pixel (dp)](rcss/syntax.html#density-independent-pixel-dp)
 * [Image-color property](rcss/colours_backgrounds.html#image-colour-the-image-color-property)
 * [Pointer-events property](rcss/user_interface.html#pointer-events-the-pointer-events-property)
 * [Border property shorthand](rcss/box_model.html#border-shorthands)
 * [:checked pseudo class](rcss/selectors.html)
 

### Various changes


 * Unlike the original branch, elements with
```css
display: inline-block;
```
will shrink to the width of their content, like in CSS.

 * The slider on the `input.range` element can be dragged from anywhere in the element.
 
 * The `font-size` property now accepts a \<length\> value instead of \<number\>, like in CSS.

 * `{{page.lib_ns}}::Core::SystemInterface::GetElapsedTime()` now returns `double` instead of `float`.
```cpp
virtual double GetElapsedTime();
```