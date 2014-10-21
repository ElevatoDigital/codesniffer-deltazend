codesniffer-deltazend
=====================

A minor fork of the Zend CodeSniffer standard to better fit practices at Delta Systems.
The primary change right now is that we drop the 80 character line length limit warning
(while keeping the 120 character error).  We may introduce other minor changes and custom
sniffs down the line, but it will stay roughly in line with the ZF1 style guide, while
including some additional stuff from PSR-2, if it's not incompatible with the Zend style.
