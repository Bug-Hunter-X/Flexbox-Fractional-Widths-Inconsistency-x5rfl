# Flexbox Fractional Widths Inconsistency in Tailwind CSS

This repository demonstrates an unexpected behavior when using fractional widths (e.g., `w-1/2`) within a Tailwind CSS flexbox container.  The divs don't always divide the space equally, leading to unexpected layout issues.

## Bug Report

The provided `bug.html` file shows two divs, each with `w-1/2`, inside a flex container.  While one might expect these divs to occupy exactly 50% of the container's width, they often don't due to rounding issues and the behavior of the flexbox algorithm. This can result in gaps or overlaps.