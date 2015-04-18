# Introduction #

SlimTune Profiler is a performance analysis tool by the SlimDX Group. It was started because there really aren't any great, truly free profilers for the .NET platform. We felt this was a bizarre state of events for such a popular development platform, and set out to remedy it. Although SlimTune is still an early beta, it's already a very effective and useful tool.

## Other SlimDX Group Projects ##
  * [SlimDX](http://code.google.com/p/slimdx/) - Full DirectX support library for C#.
  * [SlimGen](http://code.google.com/p/slimgen/) - Experimental ASM injection software for .NET assemblies.
  * [SlimBuffer](http://code.google.com/p/slimbuffer/) - Unmanaged memory buffer component.
  * [SlimMath](http://code.google.com/p/slimmath/) - Completely managed 3D vector math library.

# Unique Features #

SlimTune's approach to profiling is a little different from most other tools out there. Our unique approach means that you get features that no other tool can match.
  * **Live Profiling** - Why should you have to wait until your program has ended to see results? SlimTune reports results almost immediately, while your code is still running. See your bottlenecks in real-time, not after the fact.
  * **Remote Profiling** - Other tools must be run on the same machine as the application being profiled, which can be inconvenient and worse, can interfere with the results. Remote profiling is an integral part of SlimTune.
  * **On-Demand Profiling** - Just because your code's running doesn't mean you want the profiler interfering. SlimTune lets you profile exactly when and where you need it, so you can focus on the results you need instead of filtering uninteresting data.
  * **SQL Database Storage** - Instead of developing a custom, opaque file format, we use well known SQL database formats for our results files. That means you don't have to rely on SlimTune to be able to read your files.
  * **Multiple Visualizations** - Most performance tools offer a single preset view of your data. Don't like it, or want it sliced differently? Tough. With SlimTune, multiple visualizers ship out of the box to show you what you want to see, the way you want to see it.
  * **Plugin Support** - We're doing our best to produce the most useful visualizations, but that doesn't mean your needs are the same as everyone else. A few dozen lines of standard SQL and C# code are all it takes to drop in your own view of the performance data, focused on what YOU want to see.

SlimTune Profiler is built to work for you, not the other way around.