# operator1-witness

Public witness of the daily journal root of the agreement operator
**operator1.seamlean.com**.

Once a day at 00:00 UTC the operator commits the root of its append-only
journal here. Together with an RFC 3161 timestamp from an independent time
stamping authority this lets anyone check later that a journal entry existed
at a given time and was not rewritten.

Only the operator server writes to this repository. The file format and the
verification procedure are published with the first root.
