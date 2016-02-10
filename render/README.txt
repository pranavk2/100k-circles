make check
./render -c rgb
./render -c snow





Usage: ./render [options] scenename
Valid scenenames are: rgb, rgby, rand10k, rand100k, biglittle, littlebig, pattern, bouncingballs, fireworks, hypnosis, snow, snowsingle
Program Options:
  -b  --bench <START:END>    Benchmark mode, do not create display. Time frames [START,END)
  -c  --check                Check correctness of output
  -f  --file  <FILENAME>     Dump frames in benchmark mode (FILENAME_xxxx.ppm)
  -r  --renderer <ref/cuda>  Select renderer: ref or cuda
  -s  --size  <INT>          Make rendered image <INT>x<INT> pixels
  -?  --help                 This message
