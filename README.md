Loading these palettes into a dithered image requires Dither Boy: https://studioaaa.com/ditherboy/

You can create your own palettes using Color Cat!
- https://studioaaa.com/product/color-cat/

# Hello Dither Boy Enjoyer

You have found my archive of Dither Boy palettes, if you would like to format your own palettes manually, here is how you can do that:

## Palette Formatting Guide

Despite the fact that I am british, most people who use Dither Boy are american, so we use "color" instead of "colour" so, sorry if i switch between those two in this.

**Colours work best when ordered darkest → lightest** (top → bottom) with lowest luminance first, highest luminance last.

```json
{
  "category": "Nature",          // will be grouped based on this name in dither boy 
  "name": "Forest",               
  "color_count": 4,                
  "colors": [                      
    {
      "r": 12,
      "g": 20,
      "b": 7,
      "percentage": 35.0
    },
    {
      "r": 34,
      "g": 60,
      "b": 22,
      "percentage": 28.0
    },
    {
      "r": 78,
      "g": 102,
      "b": 54,
      "percentage": 22.0
    },
    {
      "r": 160,
      "g": 190,
      "b": 120,
      "percentage": 15.0
    }
  ]
}
```
Remember - 
1. `r`, `g`, `b` – integers 0-255.
2. `percentage` – optional, may be used in futrue Dither Boy update. floating-point 0-100 (**not required to sum to 100**).
3. Extra keys are ignored by the app, so you can add metadata if needed.

