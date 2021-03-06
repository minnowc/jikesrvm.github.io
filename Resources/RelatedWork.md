---
layout: default
title: Related Work
---

This page captures work related to the Jikes RVM.

# Class Libraries

## Classpath

The [GNU Classpath](http://www.classpath.org/) project is creating an open source replacement to the Java libraries provided by proprietary JVM developers. The Jikes RVM uses the GNU Classpath libraries by default. The Classpath libraries are released under the [GPL](http://www.gnu.org/software/classpath/license.html) with exception.

## OpenJDK

The [OpenJDK](http://openjdk.dev.java.net/) is the open source JVM and class library from Sun. Previously this code has been closed source, but as of April 2007 this code (except for portions that Sun doesn't own the copyright for) has been released. The OpenJDK uses the [GPL](http://www.gnu.org/software/classpath/license.html) with exception, the same as Classpath.

## Harmony

The [Apache Harmony](http://harmony.apache.org/) project was trying to create a world class, certified implementation of the Java Platform Standard Edition. It has reached its end of life and has been moved to the [Apache Attic](http://attic.apache.org/).

The project was creating an open source class library that could be used for closed and open source JVMs. The Apache Harmony project released most code under the [Apache License](http://harmony.apache.org/license.html).

# JVMs

Note that almost all JVMs mentioned here are licensed under the GPL. Because the GPL and the EPL are not compatible, code generally cannot be shared between these projects and the Jikes RVM.

## Maxine Research VM

[Maxine](http://labs.oracle.com/projects/maxine/) is a meta-circular JVM with a strong focus an modularity. It is being developed at Oracle Labs. Maxine uses an unmodified standard JDK as its class library and provides its own development tool, the [Maxine Inspector](https://wikis.oracle.com/display/MaxineVM/The+Maxine+Inspector).

## Metacircular Research Platform

The [Metacircular Research Platform](http://mrp.codehaus.org/) is fork of the Jikes RVM and licensed under the EPL.

## JamVM

[JamVM](http://jamvm.sourceforge.net/) is an open source JVM.

## CACAO

The [CACAO JVM](http://www.complang.tuwien.ac.at/cacaojvm/) is a JVM from the [Computer Languages group](http://www.complang.tuwien.ac.at/) at the [Vienna University of Technology](http://www.tuwien.ac.at/).

## Jato VM

[Jato](http://www.jatovm.org/) is a JIT-only JVM.

## Moxie

[Moxie](http://moxie.sourceforge.net/) describes itself via the following. "The Moxie project will create an open source platform for developing product-quality JVMs and an environment for JVM innovation. Our goal is to build the most innovation-friendly JVM development platform to date and from it, the most innovative product-quality JVMs. A product-quality JVM has outstanding performance, scalability and reliability. The development philosophy of Moxie is to leverage its openness to draw on the most experienced members of the VM research and development community, from both industry and academia."

## GCJ

[The GNU Compiler for Java](http://gcc.gnu.org/java/) is an open source Java compiler that statically compiles Java code into native code.

## Kaffe

[Kaffe](http://www.kaffe.org/) is an open source JVM.

## Squawk

[Squawk](http://research.sun.com/projects/dashboard.php?id=155) is a research virtual machine from Sun where as much of the JVM as possible has been written in Java. It is targetted at small devices.

## Joeq&nbsp;

[Joeq](http://joeq.sourceforge.net/) is&nbsp; a JVM implementation using a range of compilers and interpreters. It is written in 100% Java but has the ability to link in native.

# GC Frameworks

## GCspy

[GCspy](http://www.cs.kent.ac.uk/projects/gc/gcspy/) is a framework for spying on and visualizing the activity of a garbage collector. GCspy is supported by the [Jikes RVM and MMTk](http://docs.codehaus.org/display/RVM/Using+GCSpy).

## MPS

The [Memory Pool System Project](http://www.ravenbrook.com/project/mps/) from Ravenbrook is an open source GC framework.

# Operating Systems

## JNode

[JNode](http://jnode.org/) is an open source operating system written in Java with a JVM written in Java. Portions of the Jikes RVM have been ported to JNode.

## JX OS

[JX OS](http://www4.informatik.uni-erlangen.de/Projects/JX/) is an open source Java operating system.