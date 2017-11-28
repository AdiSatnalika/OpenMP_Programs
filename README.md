# OpenMP_Programs
In this part I will be presenting some of the frequently asked parallel programming Programs By Using Open MP concept in Visual Studio.

Step 1: Create your project

The simplest way to test your first OpenMP program would be to create a new project. For this tutorial, we will be creating a Win32 Console Application. If you select Visual C++ -> Win32, you should see the Console Application as an option. On the next dialog, click application settings, then clear the checkbox next to “Precompiled Header”. Click the “Finish” button.


Step 2: Enable OpenMP

OpenMP does a lot of things automatically for us programmers. However, that means that it’s very complicated for the compiler to handle OpenMP. We’ll need to manually enable OpenMP. Right-click on your project, and select properties. Select C/C++ -> Language, and change “OpenMP Support” to ‘Yes’. Click ok, and make sure your application still compiles and runs.


Step 3: Include omp.h

While you may not need it right away, it’s a good idea to go ahead and include omp.h in your source code. Visual Studio will already know the location, so all you have to do is type “#include <omp.h>” at the top of your source code.
