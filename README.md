# Compare_peaks
The program Compare_peaks computes the overlap between two lists of genomic locations in bed format and compares it with random peaks with same number and size

INSTALL:

Download Compare_peaks.zip and run the following:

unzip Compare_peaks.zip

make
cp  Compare_peaks your_path_of_binary_files

USAGE: Compare_peaks file_bed1 file_bed2

Options:

   -t <tolerance> (in base pairs), default 0

   -r <number of random samples, default 100

   -p Print common and unique set of peaks in bed format

   -c Consider only center of first set of peaks with width 1

   -o name_of_output_file

   -h Print this help (also when no input file is specified)
   
