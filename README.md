# Tailwind CSS Fractional Widths Issue
This repository demonstrates a common issue encountered when using Tailwind CSS fractional width classes (`w-1/2`, `w-1/3`, etc.) without specifying the width of the parent container.

## Problem
When using fractional width classes on child elements within a flex container (or any container without a defined width), the child elements might not distribute the width as expected. This is because the parent container's width is not explicitly set and it collapses to fit the content.

## Solution
To fix this, you need to specify a width for the parent container. This can be done using Tailwind CSS utility classes like `w-full`, `w-screen`, or by setting a specific width in pixels or percentages.