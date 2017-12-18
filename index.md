# Scientific Computing 3260/5260

## Course Information

* LECTURE: MWF 9:10-10:00, Jacobs Hall 298
* TEXT: None (see links below)
* INSTRUCTOR: Will French ([@frenchwr](https://www.github.com/frenchwr)) 
* INSTRUCTOR EMAIL: will@accre.vanderbilt.edu
* INSTRUCTOR OFFICE: Hill Center Suite 201
* INSTRUCTOR WORK PHONE: 615-343-4134
* OFFICE HOURS: Wednesdays, 1-3PM and Thursdays, 4-6PM in Hill Center Suite 201; please email me if you are planning to come
* GITHUB REPOS: <https://github.com/sc3260s17>
* SYLLABUS: <https://github.com/sc3260s17/syllabus>

## Unix Tutorials and Cheat Sheets

Remember, you can always type ```commands101``` from the ACCRE command line for reminders of simple commands. You can also type ```history``` to see commands you've run in previous shell sessions. Below are some helpful tutorials and cheatsheets:

* [Software Carpentry's Unix Tutorial](http://swcarpentry.github.io/shell-novice/)
* [Cheat Sheet 1](http://cheatsheetworld.com/programming/unix-linux-cheat-sheet/)
* [Cheat Sheet 2](http://www.rain.org/~mkummel/unix.html)
* [Vim for Beginners](https://computers.tutsplus.com/tutorials/vim-for-beginners--cms-21118)

## Learning C

* [Free Online IDE and Terminal with Simple Examples Added](https://goo.gl/7IFXQQ)
* [C Overview (you will NOT be expected to know all of this, but it is a useful reference)](https://www.tutorialspoint.com/cprogramming/c_quick_guide.htm)

## Readings and Resources

* [Introduction to Parallel Computing](https://computing.llnl.gov/tutorials/parallel_comp/)
* [Intel Vectorization and Autovectorization](https://d3f8ykwhia686p.cloudfront.net/1live/intel/CompilerAutovectorizationGuide.pdf)
* [OpenMP](https://computing.llnl.gov/tutorials/openMP/)
* [PThreads](https://computing.llnl.gov/tutorials/pthreads/)
* [MPI](https://computing.llnl.gov/tutorials/mpi/)
* [CUDA Programming Guide](http://docs.nvidia.com/cuda/cuda-c-programming-guide/#axzz3RIOMQW00)
* [CUDA Samples](http://docs.nvidia.com/cuda/cuda-samples/#axzz3VXLfSt6h)

## ACCRE Documentation and Resources

* [Website](http://www.accre.vanderbilt.edu/)
* [Twitter](https://twitter.com/ACCREVandy)
* [Facebook](https://www.facebook.com/accrevandy/)
* [ACCRE Scholars Summer Program](http://www.accre.vanderbilt.edu/?page_id=3063)
* [Getting Started Pages](http://www.accre.vanderbilt.edu/?page_id=303)
* [Unix Training Slides](http://www.accre.vanderbilt.edu/wp-content/uploads/2012/03/NewIntroToUnix.pdf)
* [Intro to Cluster Training Slides](http://www.accre.vanderbilt.edu/wp-content/uploads/2012/04/IntroductionToTheCluster2.pdf)
* [SLURM Training Slides](http://www.accre.vanderbilt.edu/wp-content/uploads/2016/08/intro_to_slurm.pdf)
* [SLURM Docs](http://www.accre.vanderbilt.edu/?page_id=2154)

## Course Schedule

**Date** | **Topic** | **Other**
--- | --- | ---
Mon, Jan 9 | Course Intro, Syllabus, etc. | 
Wed, Jan 11 | Intro to Unix, Day 1 | Complete sections 1-3 of Software Carpentry Unix Tutorial (see above) and VIM tutorial
Fri, Jan 13 | Intro to Unix, Day 2 | Complete sections 4-7 of Software Carpentry Unix Tutorial
Mon, Jan 16 | **MLK Day, No Class** | :no_good:
Wed, Jan 18 | Intro to the ACCRE Cluster |
Fri, Jan 20 | Using Git and GitHub |
Mon, Jan 23 | C Programming, Day 1 | Quiz :expressionless: [Start on exercises](https://github.com/sc3260s17/Cprogramming/blob/master/C-Programming-Exercises.pdf)
Wed, Jan 25 | C Programming, Day 2 | [Continue exercises](https://github.com/sc3260s17/Cprogramming/blob/master/C-Programming-Exercises.pdf)
Fri, Jan 27 | C Programming, Day 3 | [Complete exercises](https://github.com/sc3260s17/Cprogramming/blob/master/C-Programming-Exercises.pdf)
Mon, Jan 30 | Compiling Programs | [Slides](http://www.accre.vanderbilt.edu/wp-content/uploads/2017/01/compiling_programs.pdf)
Wed, Feb 1 | Intro to Molecular Dynamics Simulations |
Fri, Feb 3 | Parallel Computing, Day 1 | [Read sections 1-3](https://computing.llnl.gov/tutorials/parallel_comp/)
Mon, Feb 6 | Parallel Computing, Day 2 | [Read sections 4-7](https://computing.llnl.gov/tutorials/parallel_comp/)
Wed, Feb 8 | Parallel Computing, Day 3 | Homework 1 Due :unamused:
Fri, Feb 10 | Vectorization | [Reference 1](http://www.insideloop.io/blog/2014/10/14/arrays-part-iii-vectorization/), [Reference 2](https://d3f8ykwhia686p.cloudfront.net/1live/intel/CompilerAutovectorizationGuide.pdf), [Exercises](https://github.com/sc3260s17/vectorization)
Mon, Feb 13 | Multithreaded, Shared Memory Programming, Day 1 | [Read sections 1-4](https://computing.llnl.gov/tutorials/openMP/)
Wed, Feb 15 | Multithreaded, Shared Memory Programming, Day 2 | [Read sections 5-8](https://computing.llnl.gov/tutorials/openMP/)
Fri, Feb 17 | Multithreaded, Shared Memory Programming, Day 3 |
Mon, Feb 20 | Multithreaded, Shared Memory Programming, Day 4 | [Read sections 1-4](https://computing.llnl.gov/tutorials/pthreads/)
Wed, Feb 22 | Multithreaded, Shared Memory Programming, Day 5 | [Read sections 5-8](https://computing.llnl.gov/tutorials/pthreads/)
Fri, Feb 24 | MPI, Distributed Memory Programming, Day 1 | [Read sections 1-3](https://computing.llnl.gov/tutorials/mpi/)
Mon, Feb 27 | MPI, Distributed Memory Programming, Day 2 |
Wed, Mar 1 | MPI, Distributed Memory Programming, Day 3 | [Read sections 4-7](https://computing.llnl.gov/tutorials/mpi/), [slides](http://www.accre.vanderbilt.edu/wp-content/uploads/2014/12/mpi_02.pdf)
Fri, Mar 3 | MPI, Distributed Memory Programming, Day 4 | Homework 2 Due :unamused: [Read sections 8-11](https://computing.llnl.gov/tutorials/mpi/), [slides](http://www.accre.vanderbilt.edu/wp-content/uploads/2014/12/mpi_03.pdf)
Mon, Mar 6 | **Spring Break, No Class**  | :no_good:
Wed, Mar 8 | **Spring Break, No Class** | :no_good:
Fri, Mar 10 | **Spring Break, No Class** | :no_good:
Mon, Mar 13 | NVIDIA GPU CUDA Programming, Day 1 | [Read section 1](http://docs.nvidia.com/cuda/cuda-c-programming-guide/#axzz3RIOMQW00)
Wed, Mar 15 | NVIDIA GPU CUDA Programming, Day 2 | [Read section 2](http://docs.nvidia.com/cuda/cuda-c-programming-guide/#axzz3RIOMQW00)
Fri, Mar 17 | OpenACC, Day 1 | Guest Lecturer: [@vanzod](https://www.github.com/vanzod)
Mon, Mar 20 | OpenACC, Day 2 | Guest Lecturer: [@vanzod](https://www.github.com/vanzod)
Wed, Mar 22 | Parallel Programming in Python, Day 1 | Guest Lecturer: [@arnold-jr](https://www.github.com/arnold-jr)
Fri, Mar 24 | Parllel Programming in Python, Day 2 | Guest Lecturer: [@arnold-jr](https://www.github.com/arnold-jr)
Mon, Mar 27 | Exam Review | Homework 3 Due :unamused:, [slides](http://www.accre.vanderbilt.edu/wp-content/uploads/2017/03/Exam_Review.pdf)
Wed, Mar 29 | Exam | :tired_face:
Fri, Mar 31 | NVIDIA GPU CUDA Programming, Day 3 |
Mon, Apr 3 | NVIDIA GPU CUDA Programming, Day 4 | [Read through section 3.2.3](http://docs.nvidia.com/cuda/cuda-c-programming-guide/#axzz3RIOMQW00)
Wed, Apr 5 | NVIDIA GPU CUDA Programming, Day 5 |
Fri, Apr 7 | Work on Capstone |
Mon, Apr 10 | Work on Capstone |
Wed, Apr 12 | Work on Capstone |
Fri, Apr 14 | Work on Capstone |
Mon, Apr 17 | Capstone Presentations |
Wed, Apr 19 | Capstone Presentations |
Fri, Apr 21 | Capstone Presentations |
Mon, Apr 24 | No Class |
