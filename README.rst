This small utility displays contents of ASN.1 encoded data.

Sample output from this program (using the default format) is::

      0  70: SEQUENCE {
      2   1:   INTEGER 0
      5  31:   SEQUENCE {
      7   8:     OBJECT IDENTIFIER '1 2 643 7 1 1 1 1'
     17  19:     SEQUENCE {
     19   7:       OBJECT IDENTIFIER '1 2 643 2 2 35 1'
     28   8:       OBJECT IDENTIFIER '1 2 643 7 1 1 2 2'
           :       }
           :     }
     38  32:   OCTET STRING
           :     17 2C FC B1 67 B8 48 4F 5B CB 6E F1 62 78 67 44
           :     F0 8A 9D 5F C0 E9 E5 9A 62 B3 F4 6D B8 15 17 5B
           :   }

Original source from https://www.cs.auckland.ac.nz/~pgut001/, see there for details

