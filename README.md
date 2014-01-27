Copyright (c) Jim Barritt. All rights reserved.

# Log configuration using logback for Clojure

by Jim Barritt

This library extends the `clj-logging-config` library from Malcolm Sparks (https://github.com/malcolmsparks/clj-logging-config). You can read all about the API and rationale there. I had to separate it out because logback takes over the jvm by implementing it's own slf4j apis and so you can't put both jar files on the same classpath.

I have kept the namespace name though and added `clj-logging-config.logback`. 

The API should be the same as `clj-logging-config.log4j`, I'm currently working through the various features.

# Usage

Simple get started:

 



