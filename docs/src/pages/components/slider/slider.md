---
title: Slider React component
components: Slider
---

# Slider

<p class="description">Sliders allow users to make selections from a range of values.</p>

[Sliders](https://material.io/design/components/sliders.html) reflect a range of values along a bar, from which users may select a single value. They are ideal for adjusting settings such as volume, brightness, or applying image filters.

- 📦 [22 kB gzipped](/size-snapshot) (but only 8 kB without @material-ui/styles).

## Discrete sliders

Discrete sliders can be adjusted to a specific value by referencing its value indicator.
By order of demos:

1. You can generate a mark for each step with `marks={true}`.
1. You can change the default step increment.
1. You can have custom marks by providing a rich array to the `marks` prop.
1. You can restrict the selectable values to those provided with the `marks` prop with `step={null}`.
1. You can force the thumb label to be always visible with `valueLabelDisplay="on"`.

{{"demo": "pages/components/slider/DiscreteSlider.js"}}
