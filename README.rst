.. Copyright © 2012 Martin Ueding <dev@martin-ueding.de>

############
email-rename
############

Takes a number of ``.eml`` files as command line arguments and renames the
files according to the headers in the email.

The new name is::

    {year}{month}{day}-{hour}{minute}-{from}-{subject}.eml
