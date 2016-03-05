# psy496-mturk-project
This repository exists to showcase my work as a research assistant for the Interactive Measurement Group at UNLV.
Programs that use Amazon Web Services API to perform tasks in Amazon MTurk.

Explanation of files:
* NotifyWorkers.pl
  * Uses the NotifyWorkers Amazon MTurk API operation to send emails to a list of workers provided in id.txt, which must exist in the        same folder as the program.
  * The professor used this program to ask past MTurk study participants if they would like to participate in future studies.
  * Credit to huber.research.yale.edu/materials/26_appendix.pdf for providing a starting point, with which I used to get the program to      work correctly.
* AssignQualification.pl
  * Uses the AssignQualification Amazon MTurk API operation to assign qualifications to a list of workers provided in id.txt, which must     exist in the same folder as the program.
  * The professor used this program to assign a name and value to each study participant, marking them as participants.  To prevent          duplicate participants in future studies, future studies required workers that did not have this.
  * Credit to huber.research.yale.edu/materials/26_appendix.pdf for providing a starting point, which I changed to accomodate a different     API call.
