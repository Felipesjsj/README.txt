# README.txt
FFmpeg 64-bit static Windows build from www.gyan.dev

Version: 2023-02-13-git-2296078397-full_build-www.gyan.dev

License: GPL v3

Source Code: https://github.com/FFmpeg/FFmpeg/commit/2296078397

External Assets
frei0r plugins:   https://www.gyan.dev/ffmpeg/builds/ffmpeg-frei0r-plugins
lensfun database: https://www.gyan.dev/ffmpeg/builds/ffmpeg-lensfun-db

git-full build configuration: 

ARCH                      x86 (generic)
big-endian                no
runtime cpu detection     yes
standalone assembly       yes
x86 assembler             nasm
MMX enabled               yes
MMXEXT enabled            yes
3DNow! enabled            yes
3DNow! extended enabled   yes
SSE enabled               yes
SSSE3 enabled             yes
AESNI enabled             yes
AVX enabled               yes
AVX2 enabled              yes
AVX-512 enabled           yes
AVX-512ICL enabled        yes
XOP enabled               yes
FMA3 enabled              yes
FMA4 enabled              yes
i686 features enabled     yes
CMOV is fast              yes
EBX available             yes
EBP available             yes
debug symbols             yes
strip symbols             yes
optimize for size         no
optimizations             yes
static                    yes
shared                    no
postprocessing support    yes
network support           yes
threading support         pthreads
safe bitstream reader     yes
texi2html enabled         no
perl enabled              yes
pod2man enabled           yes
makeinfo enabled          yes
makeinfo supports HTML    yes
xmllint enabled           yes

External libraries:
avisynth                libilbc                 libtheora
bzlib                   libjxl                  libtwolame
chromaprint             liblensfun              libuavs3d
frei0r                  libmodplug              libvidstab
gmp                     libmp3lame              libvmaf
gnutls                  libmysofa               libvo_amrwbenc
iconv                   libopencore_amrnb       libvorbis
ladspa                  libopencore_amrwb       libvpx
libaom                  libopenjpeg             libwebp
libaribb24              libopenmpt              libx264
libass                  libopus                 libx265
libbluray               libplacebo              libxavs2
libbs2b                 librav1e                libxml2
libcaca                 librist                 libxvid
libcdio                 librubberband           libzimg
libdav1d                libshaderc              libzmq
libdavs2                libshine                libzvbi
libflite                libsnappy               lzma
libfontconfig           libsoxr                 mediafoundation
libfreetype             libspeex                sdl2
libfribidi              libsrt                  zlib
libgme                  libssh
libgsm                  libsvtav1

External libraries providing hardware acceleration:
amf                     dxva2                   nvenc
cuda                    ffnvcodec               opencl
cuda_llvm               libmfx                  vulkan
cuvid                   libvpl
d3d11va                 nvdec

Libraries:
avcodec                 avformat                swresample
avdevice                avutil                  swscale
avfilter                postproc

Programs:
ffmpeg                  ffplay                  ffprobe

Enabled decoders:
aac                     fraps                   pcm_u8
aac_fixed               frwu                    pcm_vidc
aac_latm                ftr                     pcx
aasc                    g2m                     pfm
ac3                     g723_1                  pgm
ac3_fixed               g729                    pgmyuv
acelp_kelvin            gdv                     pgssub
adpcm_4xm               gem                     pgx
adpcm_adx               gif                     phm
adpcm_afc               gremlin_dpcm            photocd
adpcm_agm               gsm                     pictor
adpcm_aica              gsm_ms                  pixlet
adpcm_argo              h261                    pjs
adpcm_ct                h263                    png
adpcm_dtk               h263i                   ppm
adpcm_ea                h263p                   prores
adpcm_ea_maxis_xa       h264                    prosumer
adpcm_ea_r1             h264_cuvid              psd
adpcm_ea_r2             h264_qsv                ptx
adpcm_ea_r3             hap                     qcelp
adpcm_ea_xas            hca                     qdm2
adpcm_g722              hcom                    qdmc
adpcm_g726              hdr                     qdraw
adpcm_g726le            hevc                    qoi
adpcm_ima_acorn         hevc_cuvid              qpeg
adpcm_ima_alp           hevc_qsv                qtrle
adpcm_ima_amv           hnm4_video              r10k
adpcm_ima_apc           hq_hqa                  r210
adpcm_ima_apm           hqx                     ra_144
adpcm_ima_cunning       huffyuv                 ra_288
adpcm_ima_dat4          hymt                    ralf
adpcm_ima_dk3           iac                     rasc
adpcm_ima_dk4           idcin                   rawvideo
adpcm_ima_ea_eacs       idf                     realtext
adpcm_ima_ea_sead       iff_ilbm                rka
adpcm_ima_iss           ilbc                    rl2
adpcm_ima_moflex        imc                     roq
adpcm_ima_mtf           imm4                    roq_dpcm
adpcm_ima_oki           imm5                    rpza
adpcm_ima_qt            indeo2                  rscc
adpcm_ima_rad           indeo3                  rv10
adpcm_ima_smjpeg        indeo4                  rv20
adpcm_ima_ssi           indeo5                  rv30
adpcm_ima_wav           interplay_acm           rv40
adpcm_ima_ws            interplay_dpcm          s302m
adpcm_ms                interplay_video         sami
adpcm_mtaf              ipu                     sanm
adpcm_psx               jacosub                 sbc
adpcm_sbpro_2           jpeg2000                scpr
adpcm_sbpro_3           jpegls                  screenpresso
adpcm_sbpro_4           jv                      sdx2_dpcm
adpcm_swf               kgv1                    sga
adpcm_thp               kmvc                    sgi
adpcm_thp_le            lagarith                sgirle
adpcm_vima              libaom_av1              sheervideo
adpcm_xa                libaribb24              shorten
adpcm_xmd               libdav1d                simbiosis_imx
adpcm_yamaha            libdavs2                sipr
adpcm_zork              libgsm                  siren
agm                     libgsm_ms               smackaud
aic                     libilbc                 smacker
alac                    libjxl                  smc
alias_pix               libopencore_amrnb       smvjpeg
als                     libopencore_amrwb       snow
amrnb                   libopenjpeg             sol_dpcm
amrwb                   libopus                 sonic
amv                     libspeex                sp5x
anm                     libuavs3d               speedhq
ansi                    libvorbis               speex
anull                   libvpx_vp8              srgc
apac                    libvpx_vp9              srt
ape                     libzvbi_teletext        ssa
apng                    loco                    stl
aptx                    lscr                    subrip
aptx_hd                 m101                    subviewer
arbc                    mace3                   subviewer1
argo                    mace6                   sunrast
ass                     magicyuv                svq1
asv1                    mdec                    svq3
asv2                    media100                tak
atrac1                  metasound               targa
atrac3                  microdvd                targa_y216
atrac3al                mimic                   tdsc
atrac3p                 misc4                   text
atrac3pal               mjpeg                   theora
atrac9                  mjpeg_cuvid             thp
aura                    mjpeg_qsv               tiertexseqvideo
aura2                   mjpegb                  tiff
av1                     mlp                     tmv
av1_cuvid               mmvideo                 truehd
av1_qsv                 mobiclip                truemotion1
avrn                    motionpixels            truemotion2
avrp                    movtext                 truemotion2rt
avs                     mp1                     truespeech
avui                    mp1float                tscc
ayuv                    mp2                     tscc2
bethsoftvid             mp2float                tta
bfi                     mp3                     twinvq
bink                    mp3adu                  txd
binkaudio_dct           mp3adufloat             ulti
binkaudio_rdft          mp3float                utvideo
bintext                 mp3on4                  v210
bitpacked               mp3on4float             v210x
bmp                     mpc7                    v308
bmv_audio               mpc8                    v408
bmv_video               mpeg1_cuvid             v410
bonk                    mpeg1video              vb
brender_pix             mpeg2_cuvid             vble
c93                     mpeg2_qsv               vbn
cavs                    mpeg2video              vc1
cbd2_dpcm               mpeg4                   vc1_cuvid
ccaption                mpeg4_cuvid             vc1_qsv
cdgraphics              mpegvideo               vc1image
cdtoons                 mpl2                    vcr1
cdxl                    msa1                    vmdaudio
cfhd                    mscc                    vmdvideo
cinepak                 msmpeg4v1               vmnc
clearvideo              msmpeg4v2               vnull
cljr                    msmpeg4v3               vorbis
cllc                    msnsiren                vp3
comfortnoise            msp2                    vp4
cook                    msrle                   vp5
cpia                    mss1                    vp6
cri                     mss2                    vp6a
cscd                    msvideo1                vp6f
cyuv                    mszh                    vp7
dca                     mts2                    vp8
dds                     mv30                    vp8_cuvid
derf_dpcm               mvc1                    vp8_qsv
dfa                     mvc2                    vp9
dfpwm                   mvdv                    vp9_cuvid
dirac                   mvha                    vp9_qsv
dnxhd                   mwsc                    vplayer
dolby_e                 mxpeg                   vqa
dpx                     nellymoser              vqc
dsd_lsbf                notchlc                 wady_dpcm
dsd_lsbf_planar         nuv                     wavarc
dsd_msbf                on2avc                  wavpack
dsd_msbf_planar         opus                    wbmp
dsicinaudio             paf_audio               wcmv
dsicinvideo             paf_video               webp
dss_sp                  pam                     webvtt
dst                     pbm                     wmalossless
dvaudio                 pcm_alaw                wmapro
dvbsub                  pcm_bluray              wmav1
dvdsub                  pcm_dvd                 wmav2
dvvideo                 pcm_f16le               wmavoice
dxa                     pcm_f24le               wmv1
dxtory                  pcm_f32be               wmv2
dxv                     pcm_f32le               wmv3
eac3                    pcm_f64be               wmv3image
eacmv                   pcm_f64le               wnv1
eamad                   pcm_lxf                 wrapped_avframe
eatgq                   pcm_mulaw               ws_snd1
eatgv                   pcm_s16be               xan_dpcm
eatqi                   pcm_s16be_planar        xan_wc3
eightbps                pcm_s16le               xan_wc4
eightsvx_exp            pcm_s16le_planar        xbin
eightsvx_fib            pcm_s24be               xbm
escape124               pcm_s24daud             xface
escape130               pcm_s24le               xl
evrc                    pcm_s24le_planar        xma1
exr                     pcm_s32be               xma2
fastaudio               pcm_s32le               xpm
ffv1                    pcm_s32le_planar        xsub
ffvhuff                 pcm_s64be               xwd
ffwavesynth             pcm_s64le               y41p
fic                     pcm_s8                  ylc
fits                    pcm_s8_planar           yop
flac                    pcm_sga                 yuv4
flashsv                 pcm_u16be               zero12v
flashsv2                pcm_u16le               zerocodec
flic                    pcm_u24be               zlib
flv                     pcm_u24le               zmbv
fmvc                    pcm_u32be
fourxm                  pcm_u32le

Enabled encoders:
a64multi                hevc_qsv                pcm_u16le
a64multi5               huffyuv                 pcm_u24be
aac                     jpeg2000                pcm_u24le
aac_mf                  jpegls                  pcm_u32be
ac3                     libaom_av1              pcm_u32le
ac3_fixed               libgsm                  pcm_u8
ac3_mf                  libgsm_ms               pcm_vidc
adpcm_adx               libilbc                 pcx
adpcm_argo              libjxl                  pfm
adpcm_g722              libmp3lame              pgm
adpcm_g726              libopencore_amrnb       pgmyuv
adpcm_g726le            libopenjpeg             phm
adpcm_ima_alp           libopus                 png
adpcm_ima_amv           librav1e                ppm
adpcm_ima_apm           libshine                prores
adpcm_ima_qt            libspeex                prores_aw
adpcm_ima_ssi           libsvtav1               prores_ks
adpcm_ima_wav           libtheora               qoi
adpcm_ima_ws            libtwolame              qtrle
adpcm_ms                libvo_amrwbenc          r10k
adpcm_swf               libvorbis               r210
adpcm_yamaha            libvpx_vp8              ra_144
alac                    libvpx_vp9              rawvideo
alias_pix               libwebp                 roq
amv                     libwebp_anim            roq_dpcm
anull                   libx264                 rpza
apng                    libx264rgb              rv10
aptx                    libx265                 rv20
aptx_hd                 libxavs2                s302m
ass                     libxvid                 sbc
asv1                    ljpeg                   sgi
asv2                    magicyuv                smc
av1_amf                 mjpeg                   snow
av1_nvenc               mjpeg_qsv               sonic
av1_qsv                 mlp                     sonic_ls
avrp                    movtext                 speedhq
avui                    mp2                     srt
ayuv                    mp2fixed                ssa
bitpacked               mp3_mf                  subrip
bmp                     mpeg1video              sunrast
cfhd                    mpeg2_qsv               svq1
cinepak                 mpeg2video              targa
cljr                    mpeg4                   text
comfortnoise            msmpeg4v2               tiff
dca                     msmpeg4v3               truehd
dfpwm                   msvideo1                tta
dnxhd                   nellymoser              ttml
dpx                     opus                    utvideo
dvbsub                  pam                     v210
dvdsub                  pbm                     v308
dvvideo                 pcm_alaw                v408
eac3                    pcm_bluray              v410
exr                     pcm_dvd                 vbn
ffv1                    pcm_f32be               vc2
ffvhuff                 pcm_f32le               vnull
fits                    pcm_f64be               vorbis
flac                    pcm_f64le               vp9_qsv
flashsv                 pcm_mulaw               wavpack
flashsv2                pcm_s16be               wbmp
flv                     pcm_s16be_planar        webvtt
g723_1                  pcm_s16le               wmav1
gif                     pcm_s16le_planar        wmav2
h261                    pcm_s24be               wmv1
h263                    pcm_s24daud             wmv2
h263p                   pcm_s24le               wrapped_avframe
h264_amf                pcm_s24le_planar        xbm
h264_mf                 pcm_s32be               xface
h264_nvenc              pcm_s32le               xsub
h264_qsv                pcm_s32le_planar        xwd
hap                     pcm_s64be               y41p
hdr                     pcm_s64le               yuv4
hevc_amf                pcm_s8                  zlib
hevc_mf                 pcm_s8_planar           zmbv
hevc_nvenc              pcm_u16be

Enabled hwaccels:
av1_d3d11va             hevc_nvdec              vc1_nvdec
av1_d3d11va2            mjpeg_nvdec             vp8_nvdec
av1_dxva2               mpeg1_nvdec             vp9_d3d11va
av1_nvdec               mpeg2_d3d11va           vp9_d3d11va2
h264_d3d11va            mpeg2_d3d11va2          vp9_dxva2
h264_d3d11va2           mpeg2_dxva2             vp9_nvdec
h264_dxva2              mpeg2_nvdec             wmv3_d3d11va
h264_nvdec              mpeg4_nvdec             wmv3_d3d11va2
hevc_d3d11va            vc1_d3d11va             wmv3_dxva2
hevc_d3d11va2           vc1_d3d11va2            wmv3_nvdec
hevc_dxva2              vc1_dxva2

Enabled parsers:
aac                     dvdsub                  opus
aac_latm                flac                    png
ac3                     ftr                     pnm
adx                     g723_1                  qoi
amr                     g729                    rv30
av1                     gif                     rv40
avs2                    gsm                     sbc
avs3                    h261                    sipr
bmp                     h263                    tak
cavsvideo               h264                    vc1
cook                    hdr                     vorbis
cri                     hevc                    vp3
dca                     ipu                     vp8
dirac                   jpeg2000                vp9
dnxhd                   misc4                   webp
dolby_e                 mjpeg                   xbm
dpx                     mlp                     xma
dvaudio                 mpeg4video              xwd
dvbsub                  mpegaudio
dvd_nav                 mpegvideo

Enabled demuxers:
aa                      idf                     pcm_f64le
aac                     iff                     pcm_mulaw
aax                     ifv                     pcm_s16be
ac3                     ilbc                    pcm_s16le
ace                     image2                  pcm_s24be
acm                     image2_alias_pix        pcm_s24le
act                     image2_brender_pix      pcm_s32be
adf                     image2pipe              pcm_s32le
adp                     image_bmp_pipe          pcm_s8
ads                     image_cri_pipe          pcm_u16be
adx                     image_dds_pipe          pcm_u16le
aea                     image_dpx_pipe          pcm_u24be
afc                     image_exr_pipe          pcm_u24le
aiff                    image_gem_pipe          pcm_u32be
aix                     image_gif_pipe          pcm_u32le
alp                     image_hdr_pipe          pcm_u8
amr                     image_j2k_pipe          pcm_vidc
amrnb                   image_jpeg_pipe         pjs
amrwb                   image_jpegls_pipe       pmp
anm                     image_jpegxl_pipe       pp_bnk
apac                    image_pam_pipe          pva
apc                     image_pbm_pipe          pvf
ape                     image_pcx_pipe          qcp
apm                     image_pfm_pipe          r3d
apng                    image_pgm_pipe          rawvideo
