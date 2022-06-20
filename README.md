# Concurrent.Thread
JavaScript Multithread Framework for Asynchronous Processing
## Abstract
Although Ajax is widely used in the development of Web applications, it is well known
that Ajax development is much more difficult than traditional Web development. There are
two reasons: (1) Ajax developers have to write complex asynchronous program on a single
thread; (2) asynchronous communication on JavaScript can be programmed only in event
driven style, which causes control-flow difficulty. To resolve this problem, we provide multithread library to JavaScript programmers. The proposed library has the following features:
(1) it is portable among popular Web browsers; (2) it provides preemptive scheduling; (3)
it provides object-oriented API. The proposed system converts JavaScript programs written
in multithreaded-style into those in continuation-based style that are executable on existing
systems, and then executes them concurrently on a runtime-library called thread-scheduler.
To see the effectiveness of the library, we implemented an Ajax application using the library.
The overhead of the converted programs is not a serious problem in practice because the
overhead is smaller enough than communication delay of Ajax applications. details is included in `thesis-en.pdf` and `thesis-jp.pdf`
