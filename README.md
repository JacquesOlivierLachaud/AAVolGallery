# AAVolGallery
Anti-Aliased 3D vol files. Input volume files comes from VolGallery [github.com/VolGalleray]

# 128^3 files have been anti-aliased using VCM estimator and the following command line
volAntiAliasing -i [input.vol] -o [output.vol] --lambda 0.1 -e VCM -R 10 -r 3 -t 2

# 256^3 files have been anti-aliased using VCM estimator and the following command line
volAntiAliasing -i [input.vol] -o [output.vol] --lambda 0.1 -e VCM -R 20 -r 3.5 -t 2

# 512^3 files have been anti-aliased using VCM estimator and the following command line
volAntiAliasing -i [input.vol] -o [output.vol] --lambda 0.1 -e VCM -R 20 -r 3.5 -t 2
