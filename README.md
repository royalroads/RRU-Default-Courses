# RRU-Default-Courses
RRU Default Courses local plugin

This custom local plugin allows an administrator to choose one or more courses
that are considered “default” courses. All users in Moodle (apart from the 
Moodle site administrator and guest accounts) will be enrolled as students in
these selected course(s). The plugin takes advantage of the Moodle CRON to 
check for new users that need to be enrolled in the default courses.
