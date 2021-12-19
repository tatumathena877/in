# in
Dim $info[11] ; elements numbered 0 to 10, but you can ignore 0  $info[1] = "Alpha" $info[2] = "Bravo" $info[3] = "Charlie" ; ... remaining statements go here $info[10] = "etc"  For $i = 1 to 10 ; stuff goes here   Send( $info[$i] ) ; other stuff Next
