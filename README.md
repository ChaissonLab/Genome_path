# Genome_path
each file contains a list of paths for download for each genome as obtained by the Accesion list from NCBI

`for r in \`cat GENOME.path.txt\`; do ascp -QT  -l 500m  -i /usr/usc/aspera/3.5.1/etc/asperaweb_id_dsa.openssh $r . ;done ` 
