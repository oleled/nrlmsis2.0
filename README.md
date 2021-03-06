# NRLMSIS 2.0

NOTE: The MSIS 2.0 license is extremely restrictive.
These CMake and Python scripts merely provide access to authorized users for authorized purposes.
We make these interfaces freely available, but users must respect the underlying MSIS 2.0 license.

This CMake script downloads MSIS 2.0 source and builds "build/libmsis2" by:

```sh
cmake -B build
cmake --build build
```

optionally run self-tests:

```sh
cd build
ctest -V
```

## MSIS 2.0 license

MSIS® (NRL-SOF-014-1) SOFTWARE

MSIS® is a registered trademark of the Government of the United States of
America, as represented by the Secretary of the Navy. Unauthorized use of
the trademark is prohibited.

The MSIS® Software (hereinafter Software) is property of the United States
Government, as represented by the Secretary of the Navy. Methods performed
by this software are covered by U.S. Patent Number 10,641,925. The Government
of the United States of America, as represented by the Secretary of the Navy,
herein grants a non-exclusive, non-transferable license to the Software for
academic, non-commercial, purposes only. A user of the Software shall not:
(i) use the Software for any non-academic, commercial purposes, (ii) make
any modification or improvement to the Software, (iii) disseminate the
Software or any supporting data to any other person or entity who will use
the Software for any non-academic, commercial purposes, or (iv) copy the
Software or any documentation related thereto except for (a) distribution
among the user’s personal computer systems, archival, or emergency repair
purposes, or (b) distribution for non-commercial, academic purposes, without
first obtaining the written consent of IP Counsel for the Naval Research
Laboratory.

As the owner of MSIS®, the United States, the United States Department of
Defense, and their employees: (1) Disclaim any warranties, express, or
implied, including but not limited to any implied warranties of
merchantability, fitness for a particular purpose, title or non-infringement,
(2) Do not assume any legal liability or responsibility for the accuracy,
completeness, or usefulness of the software, (3) Do not represent that use of
the software would not infringe privately owned rights, (4) Do not warrant
that the software will function uninterrupted, that is error-free or that any
errors will be corrected.

BY USING THIS SOFTWARE YOU ARE AGREEING TO THE ABOVE TERMS AND CONDITIONS.
