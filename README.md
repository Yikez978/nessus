==About==

`parse_nessus` parses Nessus CSV output into a table. Vulnerabilities are
sorted by criticality from high to low. Vulnerability entries warning of
out-dated software are merged together.

The table columns are as follows: Number (sequential), Name, Description,
Suggestion, Hosts affected.

The output file will be in opendoc format. Multiple CSV files may be merged
into one table.

==Usage==

    ./parse_nessus out.odt in1.csv in2.csv...
