#Jun This lab we need to fork individually and make a pull request
# M16_lab06

Base repository for CS56 W16 lab06 (Open Source)

# Student Instructions

See: https://ucsb-cs56-m16.github.io/lab/lab06/

# Grader hints

* Use <code>ant -p</code> to see all available tasks
* The grader tasks include these:

<pre>
 gradeMPV1          run MultiPictureViewer for studentName with arg 1
 gradeMPV2          run MultiPictureViewer for studentName with arg 2
 gradeMPV3          run MultiPictureViewer for studentName with arg 3
 gradePV            run simple.PictureViewer for student in studentName property
 gradeSimpleGui1    run simpleGui1 for student in studentName property
</pre>

To run one of those tasks, overriding the student's CSIL id to jgaucho, use, for example:

<code>ant -DstudentName=jgaucho gradePV</code>

You can test this with studentName set to <code>pconrad</code>, <code>andrewberls</code>, or <code>jstaahl</code> as examples.   All of those should work on pconrad, though only the MPV tasks will work for the other two.

