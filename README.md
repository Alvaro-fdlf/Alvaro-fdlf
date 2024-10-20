# Álvaro Fernández

I like C, I like Linux, and sometimes I wonder what kind of enlightenment one would reach if they knew every detail about how their computer works from the hardware to the highest level. This account looks a bit empty with just one project, so it's time to fill it with open source contributions. How hard can it really be to get a decent Linux kernel commit?

I also do some competitive programming around december, along with Advent of Code. Here's my [Codeforces](https://codeforces.com/profile/alvferfue) account.

## Projects

<a href="https://www.youtube.com/watch?v=LjMCE_pQq1U">
  <img src="http://img.youtube.com/vi/LjMCE_pQq1U/0.jpg" alt="Vulkan particles demo" width="300">
</a>

This is a particle simulator inspired by this [video](https://www.youtube.com/watch?v=X-iSQQgOd1A) from Sebastian Lague. My version is made to run on Linux, and uses Direct Rendering Manager features directly. Before displaying anything, it checks whether the X window system is the DRM master, and if so it uses XCB to communicate with the server to take a DRM lease. Once the program has the lease (or X wasn't running in the first place), it obtains the necessary resources to display to the specified monitor, and then uses either Vulkan or KMS dumb buffers to draw to the screen. The speed difference between Vulkan and dumb buffers depends on the CPU and GPU, but in my experience Vulkan was around 10x faster.

<a href="https://www.youtube.com/watch?v=2lpc25hgsG0">
  <img src="http://img.youtube.com/vi/2lpc25hgsG0/0.jpg" alt="Vulkan particles demo" width="300">
</a>

 This is a mini tetris for arduino using an 8x8 LED display. It was a project for university with the main objective of testing the ability to make a robust model for a game's objects using C structures. On top of all the mandatory features, I included all the extra features like 2x1 blocks, change of speed, and keeping track of the high score.

## Languages

- C is my favorite, simple and elegant.
- C++ is the first language I've ever used to try to build anything serious. I started learning it in 2018 from Youtube videos, and tried to make a limit calculator to solve limit problems in math homework.
- Python, I had some classes in uni using it. I appreciate it when I need to make a quick script, especially dealing with http requests.
- Javascript, I once decided to read through Mozilla tutorials on web development and ended up learning how to use Node to make websites with React.
- Java, I _can_ use it if needed. I've used it with JUnit and JavaFX to contribute to a board game in a group project in uni.

## Social media

- [LinkedIn](https://www.linkedin.com/in/alvarofernandezdelafuente)
