**Dear Insitec MIS Candidate,**

**Thank you for making the time to have a crack at our little coding challenge!**

To start the challenge please use [this repository as a template](https://github.com/Insitec-MIS/Puzzle-Challenge/generate) to create a **private** repository under your own github account then add the following collaborators for review:
 - [Heath-Insitec](https://github.com/Heath-Insitec)
 - [Adam-Insitec](https://github.com/Adam-Insitec)
 - [Lachlan-Insitec](https://github.com/Lachlan-Insitec)

We have provided you with a simple Visual Studio project for you to use as the starting point for the challenge. Create whatever files you feel are necessary to develop the solution... But please don’t change too many project settings (especially the build artefacts) or you might upset our checking tools.

Generally we expect candidates to spend a week on the challenge but don’t stress it if you can't finish it, just do your best to work through the bits you can and document the bits you won't code. If you have not already guessed this is one of those "show us how you approach problems" type of problems so please be ready to share your screen with us in a review session and walk us though your solution.

So what is the challenge? We want you to write a program that lists the steps necessary to solve a [slide puzzle](https://www.helpfulgames.com/subjects/brain-training/sliding-puzzle.html). Simple right? Well it would be but the catch is that the puzzle state is given to the application as a bitmap image and we are placing a constraint on the use of external libraires. The full list of requirements and constraints for the application is as follows:

- The application must be developed in C++.
- The application must not use any external libraries (stdlib is ok).
- The application must take a single argument where:
  - The argument is a path to a file.
  - The file format will be a [24bit bitmap](https://en.wikipedia.org/wiki/BMP_file_format).
- The application must write to std out:
  - The moves the blank tile must make to unscramble the image.
  - Each move should be recorded as one of; Up, Down, Left or Right.
  - Each move should be written on a new line.

We have prepared some sample image files for you to test your program with, you can find them [here](https://raw.githubusercontent.com/Insitec-MIS/Sample-Puzzles/main/Sample_01.bmp) and [here](https://raw.githubusercontent.com/Insitec-MIS/Sample-Puzzles/main/Sample_02.bmp). If you do not normally develop on Windows or with Visual Studio please download and run the windows 10 dev image from [here](https://developer.microsoft.com/en-us/windows/downloads/virtual-machines/), it will have everything you need to get going quickly. Frequent check-ins to the main branch is recommend as we expect you to be the sole contributer. If something is unclear or you have any questions please reach out to any of the revirews listed above or email us at <mis-development@insitec.com.au>.

Thanks again for giving it a crack, we hope you have some fun with it and we look forward to reviewing your solution.

Cheers,

   The Insitec MIS Engineering Team
   
