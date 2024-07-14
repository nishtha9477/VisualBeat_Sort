# VisualBeat Sort 🎵

I am excited to share my latest project, **VisualBeat Sort**! This project showcases a unique combination of visual and auditory elements, demonstrating the Bubble Sort algorithm using HTML5 Canvas and Web Audio API.

## Live Demo

You can view the live demo of the project [here](https://nishtha9477.github.io/VisualBeat_Sort/).

## Key Highlights

### 🖌 Canvas Setup

We set up an HTML5 Canvas element with a width of 600 pixels and a height of 400 pixels, creating the perfect stage for our visualization.

###  Constants and Variables Initialization

We initialize important constants like margin, n (the number of columns), and an array to hold column heights. Additionally, a variable called "moves" stores the sequence of sorting actions.

###  Web Audio API Integration

Our code leverages the power of the Web Audio API to generate sound during the sorting process. Functions like `playNote()` create oscillators, set frequencies, and connect them to an audio destination.

### Initialization

The `init()` function sets up the array with random values and positions the columns accordingly.

###  Sorting Algorithm

Our `bubbleSort()` function implements the Bubble Sort algorithm, efficiently sorting the array while recording each swapping action in the "moves" array.

###  Animation Loop

The `animate()` function ensures a smooth animation by clearing the canvas, drawing the columns, and playing sounds based on the sorting moves. We utilize `requestAnimationFrame()` for a seamless experience.

###  Column Class

Each column in the visualization is represented by the `Column` class, which provides methods for smooth movement and jumping. We achieve this by interpolating between start and end positions/colors over a certain number of frames.

###  Interpolation Function

The `lerp()` function performs linear interpolation between two values, enhancing the fluidity of our animation.

###  Drawing and Color

The visualization draws columns on the canvas, representing the array elements. During the sorting process, the color and height of the columns dynamically change, offering a captivating visual representation.

###  Sound Feedback

To enrich the experience, different sounds are played based on sorting actions, such as swapping or jumping. This auditory feedback enhances your understanding of the sorting process.




