# arbo - art bot

## works on anything with a canvas, a constant brush size and and colors such as

- skribbl.io
- gartic phone, gartic.io
- sketchful.io
- ms paint

## features
  
- outline drawing like a human (kinda)
- outline drawing with random lines
- colored dithering
- black and white dithering
- quantized drawing for faster times (color by color or line by line)
- settings for colors, brushsize, speed and drawing area
- supports image urls and file paths inside the url box
- easy to use graphical user interface

> before running, install the requirements using pip make sure to calibrate it before drawing. In case you need it, 'q' is the failsafe
>
> I belive this is the fastest and most versitile one out there and it's also very easy to use. It is recommended to use clipart images for faster drawing times (not necessary for dithering)

## UI

![image](https://github.com/Nuspli/arbo/assets/108233076/e86f1300-ae2e-4bc2-acc4-85434516d38a)

- `brush size` depends on how many pixels in a row your selected brush covers. most of the time this will not be one since most brushes cover more that a single pixel the image will get scaled according to this size
- `layers only` affect the floyd steinberg dithering option. 1 layer is usually fine, but if that takes too long you can choose to skip every 2nd, 3rd, 4th, ... pixel by splitting it into multiple layers. this will give a better overview of the full picture. checking the adaptive checkbox will only draw the last 3rd of the colors as 2 layers
- to choose the colors and drawing area, click on the calibration buttons and follow the instructions
- `Image URL` accepts system file paths and image links aswell as some dropped images from google (experimental)

## Examples:

> (not real time, speed can be adjusted)

![gif1](https://github.com/Nuspli/arbo/assets/108233076/b96fb155-059e-4157-adff-a883496c2d5c)
![gif2](https://github.com/Nuspli/arbo/assets/108233076/144be571-4ae1-4755-bcc7-528ef4c02660)
![gif3](https://github.com/Nuspli/arbo/assets/108233076/717023f4-d18d-4d9f-9967-6dd005c347ae)
![gif4](https://github.com/Nuspli/arbo/assets/108233076/ee18e65e-7f59-4dbd-aa39-c2dd0771dc97)
![gif5](https://github.com/Nuspli/arbo/assets/108233076/40ef88bd-b712-486c-b18a-d49c9f877fe4)
![gif6](https://github.com/Nuspli/arbo/assets/108233076/2bb381fa-5c77-4e47-a9a3-577d5eadec9d)

> can't get it work? message me on discord: `kolmus`
