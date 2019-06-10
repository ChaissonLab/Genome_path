# Genome_path
Each directory contains paths to data available for a sample. The PacBio data may be downloaded using aspera:
for r in `cat sample.PB.csv`; do 
ascp -QT  -l 500m  -i $ASPERA_PATH/etc/asperaweb_id_dsa.openssh $r . 
done 
