Development process
===================

LAVA development process is based on git. The source code is available
in https://git.linaro.org/gitweb/?s=lava%2F Launchpad is used for bug
management.

Most of the work is done by the members of the Linaro Validation Team
(you can learn more about this team, in particular here:
http://www.linaro.org/linux-on-arm/meet-the-team/lava-team). Having
said that, the code is free and open source software, we welcome third
party contributions and new team members.

Our team is spread geographically around the world, with some members in
Europe, America, Asia and Oceania. We are usually talking on our IRC channel
#linaro-lava.


Release process
^^^^^^^^^^^^^^^

LAVA is being developed on a monthly release schedule. Each release is tagged
around 25th of each month.

Launchpad release tarballs are following our YYYY.MM (year, month) pattern.
Should we need to release an upgrade to any existing release (such as a
critical bug fix) we append a sequential number preceded by a dash
(YYYY.MM-NN).


Reporting Bugs
^^^^^^^^^^^^^^

New bugs can be reported here https://bugs.launchpad.net/lava/+filebug.

If you are not sure which component is affected simply report it to any of the
LAVA sub-projects and let us handle the rest. As with any bug reports please
describe the problem and the version of LAVA you ware using.

If you were using our public LAVA instance, the one used by Linaro for daily
activities (http://validation.linaro.org) try to include a link to a page
that manifests the problem as that makes debugging easier.


Patches, fixes and code
^^^^^^^^^^^^^^^^^^^^^^^

If you'd like to offer a patch (whether it is a bug fix, documentation update,
new feature or even a simple typo) it is best to follow this simple check-list:

1. Clone the master of the correct project.
2. Add your code, change any existing files as needed.
3. Create a patch from your changes.
4. Send the patch to
   http://lists.linaro.org/mailman/listinfo/linaro-validation mailing
   list. (Subscribing to this mailing list is recommended since patch
   follow-ups will be easier.)

**NOTE:** The above process will be replaced by
http://review.linaro.org in future. Right now we have
http://staging.review.linaro.org
