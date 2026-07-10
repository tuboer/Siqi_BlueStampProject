# Smart Glasses
<!---Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!-->

My project is the Smart Glasses, that can allow you to identify objects in front of you, take pictures, and play video games. It can also display time, and other information you want. It is all connected remotely to my phone, so I can run stuff through there instead of using computer. 

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Siqi F. | Basis Independent Silicon Valley | Computer Science/Electrical Engineering | Incoming Junior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

<div style="display: flex !important; align-items: center !important; gap: 20px !important;">
  <img src="Siqi F.png" style="display: inline-block !important; width: 300px !important; height: auto !important; flex-shrink: 0 !important;" alt="My Profile Photo">
</div>



![Headstone Image](logo.svg)


# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<!---For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE--->

<br>**Accomplishments:**
I've managed to make my own 3d model of the glasses I am going to use with the OLED and camera. I made a seperate piece for the mirror that is detatchable from the glasses as since the mirrors have to be at a 45 degree angle, they will be covering your view slightly. For the OLED, I have flipped the display screen so that we can see it through the mirror, as the display will be reversed by the mirror. There will be an added part in the glasses that will protrude outwards in order to show the OLED. The wires for the OLED will be extended through jumper wires, and help in place by electrical tape. 

**Biggest challenges:**
Some of the biggest challenges I faced was finding a good library for the image recognition portion of the Smart Glasses, as the guide I was given used TensorFlow Lite Object Recognition Library, however the downside of TensorFlow Lite is that it is taylored to specific objects rather than general ones. In my case it was for cups and dog breeds, something that I didn't need to recognize with the glasses. Instead I found a different image library, OpenCV. OpenCV is used most commonly by big companies for object recognition, and especially for more broad topics, which fit what I needed perfectly. Another big problem was connecting my Raspberry Pi to my phone. I wanted to use bluetooth connection, but as I have an IOS phone, connecting through bluetooth requires more tedious processes, such as connecting through BLE (Bluetooth Light Environment), and even then it was hard to find my RaspberryPi in the list of devices. Therefore, I decided connecting through wifi was easier. However this raised another problem, if wifi is required then these glasses would not be truly remote. Instead, I decided to connect to the RaspberryPi's internal hotspot instead so I could connect my phone to the OLED.

**What I learned:**
Before starting BlueStamps Engineering, I had almost no experience in CADing 3d models, especially with complex design. I had used 3d printers in the past, but most designs were relatively simply or predesigned. At BlueStamps, I learned how to use OnShape for 3d modeling objects to print, which I think will be helpful in the future if I make more similar projects. Also, the main language I used for my project was python, as the processor I used was RaspberryPi, which uses python as it's language. I think forcing myself to interact with python has helped me learn more about how to use it for future coding projects.

**Future Plans:**
After everything I've learned at BlueStamps, I plan to use this experience to keep on experimenting and building things for myself. I feel BlueStamps has given me the intiative and experience to help plan my own projects in the future. For my project, I plan to add more software aspects in them as well as fixing some unstable parts of the project, as some parts are still a bit wobbly.


# Second Milestone

<!---**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**--->

<iframe width="560" height="315" src="https://www.youtube.com/embed/ptUMADz4FMY?si=5-arr-m35SlL5tmB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<!---For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone<--->

<br>**Components:**
Aside from the original materials, I have also bought a 1.51 in transparent OLED in order to display text on a mini screen that you can see from the glasses. 

**Technical Progress:**
I've managed to get the OLED up and running, and I can run image recognition software on there. I also managed to connect it to the new library I'm using for object recognition. In the future, these OLEDs will be able to display whatever I tell it too, like video games or the time.

**Challenges:**
Originally, I had planned to use AI recognition instead of a preexisting library, however doing some research into my options for AI revealed that it was not secure, especially the option I was considering, Google Studio Gemini. Instead I had to find a new image library. I am using OpenCV instead, which is for more general recognition and has a more broad amount of recognitions compared to TensorFlow Lite, which is more for specific image recognition.

**Future Plan:**
I am planning to start making a 3d print for holding the components, as the original was too flimsy and couldn't hold up the required materials. I also want to add more fun things to the display, such as a video game. 


# First Milestone

<!---**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**-->

<iframe width="560" height="315" src="https://www.youtube.com/embed/6heKAk21Ivc?si=ubbtS4JYX64GRCiS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<!---For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project-->

<br>**Components:**
I'm using the Raspberry Pi 4 Model B and Camera Module to run the Object Recognition Software. This is all possible by using a MicroSd card inside the RaspPi. 

**Technical Progress:**
Some progress I've made is running the Camera Module, and displaying the camera on the VNC I'm using. I connected my computer to a monitor through VNC, which allows me to use the monitor remotely. The program succesfully shows the image detected, what it thinks the object is, and confidence meter.

**Challenges:**
One challenge I faced is that there was no confidence meter. I had to add that in with a new line of code. I did this by multiplying the confidence threshold inside the code by 100 to display the percentage. Another problem I faced was that the detector was displaying objects even when there was a low percentage of confidence. So I raised the confidence threshold, as well as the persistence threshold. The persistence threshold determines how much the object stays inside the screen, and the larger it is, the less likely it is to identify an object off screen. That also solved the problem where the camera was very laggy due to the large processes it was doing. A very big challenge though was that the library I was using was very outdated and inaccurate, which is why I want to change it in the future.

**Future Plan:**
My future plan is hopefully to use AI recognition in the future for more accurate identification, as well as using an OLED to display things through lenses instead of a monitor.


# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
<!---Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs.-->
This is the code from the guide that I used for TensorFlow Lite object recognition, and the modifications I made to it.
```python
# SPDX-FileCopyrightText: 2021 Limor Fried/ladyada for Adafruit Industries
# SPDX-FileCopyrightText: 2021 Melissa LeBlanc-Williams for Adafruit Industries
#
# SPDX-License-Identifier: MIT

import time
import logging
import argparse
import pygame
import os
import subprocess
import sys
import numpy as np
import signal

CONFIDENCE_THRESHOLD = 0.40   # at what confidence level do we say we detected a thing
PERSISTANCE_THRESHOLD = 0.75  # what percentage of the time we have to have seen a thing
#extrastuff
hold_counter = 0
last_valid_text = ""
last_valid_color = (255, 255, 255)

def dont_quit(signal, frame):
   print('Caught signal: {}'.format(signal))
signal.signal(signal.SIGHUP, dont_quit)

# App
from rpi_vision.agent.capturev2 import PiCameraStream
from rpi_vision.models.mobilenet_v2 import MobileNetV2Base

logging.basicConfig()
logging.getLogger().setLevel(logging.INFO)

# initialize the display
pygame.init()
screen = pygame.display.set_mode((0,0), pygame.FULLSCREEN)
capture_manager = None

def parse_args():
    parser = argparse.ArgumentParser()
    parser.add_argument('--include-top', type=bool,
                        dest='include_top', default=True,
                        help='Include fully-connected layer at the top of the network.')

    parser.add_argument('--tflite',
                        dest='tflite', action='store_true', default=False,
                        help='Convert base model to TFLite FlatBuffer, then load model into TFLite Python Interpreter')

    parser.add_argument('--rotation', type=int, choices=[0, 90, 180, 270],
                        dest='rotation', action='store', default=0,
                        help='Rotate everything on the display by this amount')
    args = parser.parse_args()
    return args

last_seen = [None] * 10
last_spoken = None

def main(args):
    global hold_counter, last_valid_text, last_valid_color
    global last_spoken, capture_manager

    capture_manager = PiCameraStream(preview=False)

    if args.rotation in (0, 180):
        buffer = pygame.Surface((screen.get_width(), screen.get_height()))
    else:
        buffer = pygame.Surface((screen.get_height(), screen.get_width()))

    pygame.mouse.set_visible(False)
    screen.fill((0,0,0))
    try:
        splash = pygame.image.load(os.path.dirname(sys.argv[0])+'/bchatsplash.bmp')
        splash = pygame.transform.rotate(splash, args.rotation)
        # Scale the square image up to the smaller of the width or height
        splash = pygame.transform.scale(splash, (min(screen.get_width(), screen.get_height()), min(screen.get_width(), screen.get_height())))
        # Center the image
        screen.blit(splash, ((screen.get_width() - splash.get_width()) // 2, (screen.get_height() - splash.get_height()) // 2))

    except pygame.error:
        pass
    pygame.display.update()

    # Let's figure out the scale size first for non-square images
    scale = max(buffer.get_height() // capture_manager.resolution[1], 1)
    scaled_resolution = tuple([x * scale for x in capture_manager.resolution])

    # use the default font, but scale it
    smallfont = pygame.font.Font(None, 24 * scale)
    medfont = pygame.font.Font(None, 36 * scale)
    bigfont = pygame.font.Font(None, 48 * scale)

    model = MobileNetV2Base(include_top=args.include_top)

    capture_manager.start()
    while not capture_manager.stopped:
        if capture_manager.frame is None:
            continue
        buffer.fill((0,0,0))
        frame = capture_manager.read()
        # get the raw data frame & swap red & blue channels
        previewframe = np.ascontiguousarray(capture_manager.frame)
        # make it an image
        img = pygame.image.frombuffer(previewframe, capture_manager.resolution, 'RGB')
        img = pygame.transform.scale(img, scaled_resolution)

        cropped_region = (
            (img.get_width() - buffer.get_width()) // 2,
            (img.get_height() - buffer.get_height()) // 2,
            buffer.get_width(),
            buffer.get_height()
        )

        # draw it!
        buffer.blit(img, (0, 0), cropped_region)

        timestamp = time.monotonic()
        if args.tflite:
            prediction = model.tflite_predict(frame)[0]
        else:
            prediction = model.predict(frame)[0]
        logging.info(prediction)
        delta = time.monotonic() - timestamp
        logging.info("%s inference took %d ms, %0.1f FPS" % ("TFLite" if args.tflite else "TF", delta * 1000, 1 / delta))
        print(last_seen)

        # add FPS & temp on top corner of image
        fpstext = "%0.1f FPS" % (1/delta,)
        fpstext_surface = smallfont.render(fpstext, True, (255, 0, 0))
        fpstext_position = (buffer.get_width()-10, 10) # near the top right corner
        buffer.blit(fpstext_surface, fpstext_surface.get_rect(topright=fpstext_position))
        try:
            temp = int(open("/sys/class/thermal/thermal_zone0/temp").read()) / 1000
            temptext = "%d\N{DEGREE SIGN}C" % temp
            temptext_surface = smallfont.render(temptext, True, (255, 0, 0))
            temptext_position = (buffer.get_width()-10, 30) # near the top right corner
            buffer.blit(temptext_surface, temptext_surface.get_rect(topright=temptext_position))
        except OSError:
            pass

        for p in prediction:
            label, name, conf = p
            if conf > CONFIDENCE_THRESHOLD:
                print("Detected", name)
                persistant_obj = False  # assume the object is not persistant
                last_seen.append(name)
                last_seen.pop(0)
		#extrastuff
		#last_valid_text = name.replace("_", " ")
		#last_valid_color = (0, 255, 0) if persistant_obj else (255,255,255)
		#hold_counter = 14

                inferred_times = last_seen.count(name)
                if inferred_times / len(last_seen) > PERSISTANCE_THRESHOLD:  # over quarter time
                         persistant_obj = True

		#detecttext = f"{name.replace('_', ' ')} ({conf*100:.1f}%)"
		#detecttextfont = None
                last_valid_text = f"{name.replace('_', ' ')} ({conf*100:.1f}%)"
                last_valid_color = (0, 255, 0) if persistant_obj else (255, 255, 255)
                hold_counter = 14

                if hold_counter > 0:
                    detecttext = last_valid_text
                    detecttext_color = last_valid_color
                    hold_counter -= 1

                    detecttextfont = None
                    for f in (bigfont, medfont, smallfont):
                        detectsize = f.size(detecttext)
                        if detectsize[0] < screen.get_width(): # it'll fit!
                            detecttextfont = f
                            break
                    else:
                        detecttextfont = smallfont
		#else:
                #    detecttextfont = smallfont # well, we'll do our best
                #detecttext_color = (0, 255, 0) if persistant_obj else (255, 255, 255)
                    detecttext_surface = detecttextfont.render(detecttext, True, detecttext_color)
                    detecttext_position = (buffer.get_width()//2, buffer.get_height() - detecttextfont.size(detecttext)[1])
                    buffer.blit(detecttext_surface, detecttext_surface.get_rect(center=detecttext_position))

                if persistant_obj and last_spoken != detecttext:
                    #subprocess.call(f"echo {detecttext} | festival --tts &", shell=True)
                    last_spoken = detecttext
                break
        else:
            last_seen.append(None)
            last_seen.pop(0)
            if last_seen.count(None) == len(last_seen):
                last_spoken = None

        screen.blit(pygame.transform.rotate(buffer, args.rotation), (0,0))
        pygame.display.update()

if __name__ == "__main__":
    args = parse_args()
    try:
        main(args)
    except KeyboardInterrupt:
        capture_manager.stop()
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Raspberry Pi 4 Model B | Running Pi | $120.0 | <a href="https://www.adafruit.com/product/4296"> Link </a> |
| Raspberry Pi Camera | Camera | $29.95 | <a href="https://www.adafruit.com/product/3099"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [TensorFlow Lite Object Recognition](https://learn.adafruit.com/running-tensorflow-lite-on-the-raspberry-pi-4/overview)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
