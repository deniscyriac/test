HTML 5 Engine
Copyright (c) 2013 All Right Reserved, http://opentechmedia.com
This product is subject to the OpenTechMedia Permissive License.
All other rights reserved.
////////////////////////////////////////////////////////////////////////

12-10-2013
Version 3.9
SCORM test success
Tick mark for visited section

19-09-2013
Version 3.8
Fixed the slider click issue
Fixed SCORM issues

13-09-2013
Version 3.7
Request from Mike - Hilight Help, Next, Menu buttons in sync with VO in the first slide
Request from Mike - AutoAdvance to next section skipping slides
- added a <AdvanceTo>5</AdvanceTo>node in xml

d - Debugger added
Fixed - Video not pause while opening Reviewtool 

01-09-2013
Version 3.6
KeyBoard Shortcut added:
M - Menu
Space - play/pause
> - Next
< - Previous
v - Review tool
r - Reload
t - Transcript
h - Help
s - Mute

Added scroll for Left menu content - CSS change

18-08-2013
Version 3.4
SCORM Fix for Juniper LMS

URL is: sftp.yourlearningportal.com
The username is: juniper_opentechmedia
And the password is: NZ9ahGK0CUQaSobakJHP

learningportal.juniper.net


18-08-2013
Version 3.3
PlayPause state not changing after dragging slider - fixed by adding 
$playpause.attr("src", $themepath+"images/pause.png") in slider 'stop' attributes of video and audio.

28-06-2013
Version 3.2
New Requirement - If user complete atleast one module other than first and last, set the lesson status to 'completed'.

- Changed group to module in xml and app.js
- Fixed numbering issue for the module title in TOC.

27-06-2013
Version 3.1
Setting lesson status to completed after completing all the slides
scorm.set("cmi.core.lesson_status", "completed");

10-04-2013
Version 3.0
Tested on iPad and fixed the issues
Tested on Safari & FF on iPad

Version 2.06
SCORM Implemented
scorm.get("cmi.core.student_name");
scorm.get("cmi.core.student_id");
scorm.set("cmi.core.lesson_location", a);
scorm.set("cmi.suspend_data", completedSlides);

Version 2.0
Tested on different browsers IE9+, FF & Chrome
http://refresh-sf.com/yui/
