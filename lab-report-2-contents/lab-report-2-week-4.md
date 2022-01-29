# Incremental Programming and Debugging

## Bug 1

![image](code-change-for-bug1.png)

> [failure-inducing input](https://github.com/vumary/markdown-parse-lab-report-2/blob/main/test-file2.md)

![image](bug-1-symptom.png)

The bug was that there was no updating of the currentIndex to make the while-loop condition false if there were characters after the last link. As you can guess, the symptom is shown when the while-loop runs infinitely until you're out of memory. The specific failure-inducing input I used was adding some text after the links in the `.md` file.
## Bug 2


## Bug 3