# brms_online
Running bRMS experiments online. Depends on the jsPsych and GSAP javascript libraries, and their dependencies. Implemented ontop of a PsiTurk server.

## Important files
### static/js/jspsych/jspsych-brms
This is the script that executes a bRMS trial. It is written as a jsPsych function.

### static/js/task.js
This is an example of how one can build a trial structure for the experiment. Interesting for the behavioural tricks needed for a successful online experiment.

## To Do:
* Move to a more compact data structure: the vbl field containing the animation performance takes up a lot of space, and could be made shorted (thus shortening upload times, and reducing upload errors).
* Optimizing animation code, for smoother running.
* Developing tests for the start of the experiment, allowing to end experiments on crappy hardware, thus reducing participant exclusions.
