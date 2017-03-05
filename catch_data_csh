\rm catch.rpt.*
cat *.dat | grep H-OUTPUT-2_CRACK-1 -A 3       > catch.rpt.0
cat catch.rpt.0 | grep 4 -A 2       > catch.rpt.1
grep 4 catch.rpt.1 | egrep 4 > catch.rpt.2
grep 4 catch.rpt.2 | awk '{print $3}' > catch.rpt.3
sed 'n;d' catch.rpt.3 > catch.rpt.4