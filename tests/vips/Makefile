include ../defines.mk

TEST_NAME = vips

SRCS = libvips/acquire/im_clamp  \
       			libvips/arithmetic/arith_dispatch \
			libvips/arithmetic/im_abs         \
			libvips/arithmetic/im_add         \
			libvips/arithmetic/im_avg         \
			libvips/arithmetic/im_bandmean    \
			libvips/arithmetic/im_cross_phase \
			libvips/arithmetic/im_deviate     \
			libvips/arithmetic/im_divide      \
			libvips/arithmetic/im_invert      \
			libvips/arithmetic/im_linreg      \
			libvips/arithmetic/im_lintra      \
			libvips/arithmetic/im_maxpos_avg  \
			libvips/arithmetic/im_maxpos      \
			libvips/arithmetic/im_maxpos_vec  \
			libvips/arithmetic/im_measure     \
			libvips/arithmetic/im_minpos      \
			libvips/arithmetic/im_multiply    \
			libvips/arithmetic/im_point_bilinear \
			libvips/arithmetic/im_recomb      \
			libvips/arithmetic/im_remainder   \
			libvips/arithmetic/im_sign        \
			libvips/arithmetic/im_stats       \
			libvips/arithmetic/im_subtract    \
			libvips/arithmetic/math           \
			libvips/arithmetic/power          \
			libvips/arithmetic/round          \
			 libvips/boolean/bool_dispatch \
			 libvips/boolean/boolean \
			 libvips/colour/colour \
			 libvips/colour/colour_dispatch \
			 libvips/colour/derived \
			 libvips/colour/im_dE00_fromLab \
			 libvips/colour/im_dECMC_fromLab \
			 libvips/colour/im_dE_fromLab \
			 libvips/colour/im_disp2XYZ \
			 libvips/colour/im_icc_transform \
			 libvips/colour/im_Lab2LabQ \
			 libvips/colour/im_Lab2LabS \
			 libvips/colour/im_Lab2LCh \
			 libvips/colour/im_Lab2XYZ \
			 libvips/colour/im_lab_morph \
			 libvips/colour/im_LabQ2disp \
			 libvips/colour/im_LabQ2Lab \
			 libvips/colour/im_LabQ2LabS \
			 libvips/colour/im_LabS2Lab \
			 libvips/colour/im_LabS2LabQ \
			 libvips/colour/im_LCh2Lab \
			 libvips/colour/im_LCh2UCS \
			 libvips/colour/im_UCS2LCh \
			 libvips/colour/im_XYZ2disp \
			 libvips/colour/im_XYZ2Lab \
			 libvips/colour/im_XYZ2Yxy \
			 libvips/colour/im_Yxy2XYZ \
			 libvips/cimg/cimg \
			 libvips/cimg/cimg_dispatch \
			libvips/conversion/conver_dispatch  \
			libvips/conversion/im_black         \
			libvips/conversion/im_c2amph        \
			libvips/conversion/im_c2imag        \
			libvips/conversion/im_c2real        \
			libvips/conversion/im_c2rect        \
			libvips/conversion/im_clip2fmt      \
			libvips/conversion/im_copy          \
			libvips/conversion/im_copy_file     \
			libvips/conversion/im_embed         \
			libvips/conversion/im_extract       \
			libvips/conversion/im_falsecolour   \
			libvips/conversion/im_fliphor       \
			libvips/conversion/im_flipver       \
			libvips/conversion/im_gaussnoise    \
			libvips/conversion/im_gbandjoin     \
			libvips/conversion/im_grid          \
			libvips/conversion/im_insert        \
			libvips/conversion/im_lrjoin        \
			libvips/conversion/im_mask2vips     \
			libvips/conversion/im_msb           \
			libvips/conversion/im_replicate     \
			libvips/conversion/im_ri2c          \
			libvips/conversion/im_rot180        \
			libvips/conversion/im_rot270        \
			libvips/conversion/im_rot90         \
			libvips/conversion/im_scale         \
			libvips/conversion/im_scaleps       \
			libvips/conversion/im_subsample     \
			libvips/conversion/im_system        \
			libvips/conversion/im_system_image  \
			libvips/conversion/im_tbjoin        \
			libvips/conversion/im_text          \
			libvips/conversion/im_vips2mask     \
			libvips/conversion/im_wrap          \
			libvips/conversion/im_zoom          \
			libvips/convolution/convol_dispatch \
			libvips/convolution/im_addgnoise    \
			libvips/convolution/im_compass       \
			libvips/convolution/im_contrast_surface\
			libvips/convolution/im_conv\
			libvips/convolution/im_conv_f\
			libvips/convolution/im_convsep\
			libvips/convolution/im_convsep_f\
			libvips/convolution/im_fastcor\
			libvips/convolution/im_gradcor\
			libvips/convolution/im_sharpen\
			libvips/convolution/im_spcor\
			 libvips/freq_filt/fft_sp \
			 libvips/freq_filt/fmask4th \
			 libvips/freq_filt/fmaskcir \
			 libvips/freq_filt/freq_dispatch \
			 libvips/freq_filt/im_disp_ps \
			 libvips/freq_filt/im_fractsurf \
			 libvips/freq_filt/im_freqflt \
			 libvips/freq_filt/im_freq_mask \
			 libvips/freq_filt/im_fwfft \
			 libvips/freq_filt/im_invfft \
			 libvips/freq_filt/im_invfftr \
			 libvips/freq_filt/im_rotquad \
			libvips/inplace/flood                       \
			libvips/inplace/im_circle                   \
			libvips/inplace/im_insertplace              \
			libvips/inplace/im_paintrect                \
			libvips/inplace/im_plotmask                 \
			libvips/inplace/inplace_dispatch            \
			libvips/inplace/line_draw                   \
			libvips/inplace/plot_point                  \
			libvips/inplace/smudge_area                 \
			libvips/iofuncs/base64                      \
			libvips/iofuncs/buf                         \
			libvips/iofuncs/buffer                      \
			libvips/iofuncs/callback                    \
			libvips/iofuncs/check                       \
			libvips/iofuncs/debug                       \
			libvips/iofuncs/dispatch_types              \
			libvips/iofuncs/error                       \
			libvips/iofuncs/header                      \
			libvips/iofuncs/im_binfile                  \
			libvips/iofuncs/im_close                    \
			libvips/iofuncs/im_cp_desc                  \
			libvips/iofuncs/im_demand_hint              \
			libvips/iofuncs/im_generate                 \
			libvips/iofuncs/im_guess_prefix             \
			libvips/iofuncs/im_histlin                  \
			libvips/iofuncs/im_image                    \
			libvips/iofuncs/im_init_world               \
			libvips/iofuncs/im_mapfile                  \
			libvips/iofuncs/im_open                     \
			libvips/iofuncs/im_open_vips                \
			libvips/iofuncs/im_partial                  \
			libvips/iofuncs/im_prepare                  \
			libvips/iofuncs/im_setbuf                   \
			libvips/iofuncs/im_setupout                 \
			libvips/iofuncs/im_unmapfile                \
			libvips/iofuncs/im_wrapmany                 \
			libvips/iofuncs/im_writeline                \
			libvips/iofuncs/init                        \
			libvips/iofuncs/memory                      \
			libvips/iofuncs/meta                        \
			libvips/iofuncs/object                      \
			libvips/iofuncs/package                     \
			libvips/iofuncs/rect                        \
			libvips/iofuncs/region                      \
			libvips/iofuncs/semaphore                   \
			libvips/iofuncs/sink                        \
			libvips/iofuncs/sinkdisc                    \
			libvips/iofuncs/sinkmemory                  \
			libvips/iofuncs/sinkscreen                  \
			libvips/iofuncs/threadpool                  \
			libvips/iofuncs/time                        \
			libvips/iofuncs/util                        \
			libvips/iofuncs/window                      \
			 libvips/morphology/im_cntlines \
			 libvips/morphology/im_dilate \
			 libvips/morphology/im_erode \
			 libvips/morphology/im_profile \
			 libvips/morphology/morph_dispatch \
			libvips/mosaicing/global_balance        \
			libvips/mosaicing/im_align_bands        \
			libvips/mosaicing/im_avgdxdy            \
			libvips/mosaicing/im_chkpair            \
			libvips/mosaicing/im_clinear            \
			libvips/mosaicing/im_improve            \
			libvips/mosaicing/im_initialize         \
			libvips/mosaicing/im_lrcalcon           \
			libvips/mosaicing/im_lrmerge            \
			libvips/mosaicing/im_lrmosaic           \
			libvips/mosaicing/im_maxpos_subpel      \
			libvips/mosaicing/im_remosaic           \
			libvips/mosaicing/im_tbcalcon           \
			libvips/mosaicing/im_tbmerge            \
			libvips/mosaicing/im_tbmosaic           \
			libvips/mosaicing/match                 \
			libvips/mosaicing/mosaic1               \
			libvips/mosaicing/mosaicing_dispatch    \
			 libvips/other/cooc_funcs \
			 libvips/other/glds_funcs \
			 libvips/other/im_benchmark \
			 libvips/other/im_dif_std \
			 libvips/other/im_eye \
			 libvips/other/im_grey \
			 libvips/other/im_make_xy \
			 libvips/other/im_meanstd \
			 libvips/other/im_simcontr \
			 libvips/other/im_sines \
			 libvips/other/im_spatres \
			 libvips/other/im_zone \
			 libvips/other/other_dispatch \
			 libvips/relational/im_blend \
			 libvips/relational/im_ifthenelse \
			 libvips/relational/relational \
			 libvips/relational/relational_dispatch \
			 libvips/video/im_video_test \
			 libvips/video/im_video_v4l1 \
			 libvips/video/video_dispatch \
			 libvips/dummy \
			 libvips/dummy2 \
			libvips/resample/bicubic               \
			libvips/resample/im_affine               \
			libvips/resample/im_rightshift_size      \
			libvips/resample/im_shrink               \
			libvips/resample/im_stretch3             \
			libvips/resample/interpolate             \
			libvips/resample/lbb                   \
			libvips/resample/nohalo                \
			libvips/resample/resample_dispatch       \
			libvips/resample/transform               \
			libvips/resample/vsqbs                 \
			libvips/deprecated/deprecated_dispatch    \
			libvips/deprecated/im_bernd               \
			libvips/deprecated/im_cmulnorm            \
			libvips/deprecated/im_convsub             \
			libvips/deprecated/im_debugim             \
			libvips/deprecated/im_fav4                \
			libvips/deprecated/im_gadd                \
			libvips/deprecated/im_gaddim              \
			libvips/deprecated/im_gfadd               \
			libvips/deprecated/im_line                \
			libvips/deprecated/im_litecor             \
			libvips/deprecated/im_print               \
			libvips/deprecated/im_printlines          \
			libvips/deprecated/im_resize_linear       \
			libvips/deprecated/im_setbox              \
			libvips/deprecated/im_slice               \
			libvips/deprecated/im_thresh              \
			libvips/deprecated/rename                 \
			libvips/format/format                  \
			libvips/format/format_dispatch         \
			libvips/format/im_analyze2vips         \
			libvips/format/im_csv2vips             \
			libvips/format/im_exr2vips             \
			libvips/format/im_jpeg2vips            \
			libvips/format/im_magick2vips          \
			libvips/format/im_png2vips             \
			libvips/format/im_ppm2vips             \
			libvips/format/im_raw2vips             \
			libvips/format/im_tiff2vips            \
			libvips/format/im_tile_cache           \
			libvips/format/im_vips2csv             \
			libvips/format/im_vips2jpeg            \
			libvips/format/im_vips2png             \
			libvips/format/im_vips2ppm             \
			libvips/format/im_vips2raw             \
			libvips/format/im_vips2tiff            \
			libvips/format/matlab                  \
			libvips/format/radiance                \
			libvips/histograms_lut/hist_dispatch     \
			libvips/histograms_lut/im_buildlut       \
			libvips/histograms_lut/im_gammacorrect   \
			libvips/histograms_lut/im_heq            \
			libvips/histograms_lut/im_hist           \
			libvips/histograms_lut/im_histeq         \
			libvips/histograms_lut/im_histgr         \
			libvips/histograms_lut/im_histindexed    \
			libvips/histograms_lut/im_histnD         \
			libvips/histograms_lut/im_histplot       \
			libvips/histograms_lut/im_histspec       \
			libvips/histograms_lut/im_hsp            \
			libvips/histograms_lut/im_identity       \
			libvips/histograms_lut/im_invertlut      \
			libvips/histograms_lut/im_lhisteq        \
			libvips/histograms_lut/im_maplut         \
			libvips/histograms_lut/im_mpercent       \
			libvips/histograms_lut/im_project        \
			libvips/histograms_lut/im_stdif          \
			libvips/histograms_lut/tone              \
			 tools/iofuncs/vips

TEST_FILES = $(SRCS)

#THREADS = $(NCORES)
THREADS = $(shell echo $(NCORES)-1 | bc)

export IM_CONCURRENCY=36

HAVE_DIR = 1

ifeq ($(DATASET), native)
	TEST_ARGS =	im_benchmark $(DATASET_HOME)/vips/orion_18000x18000.v output.v
else ifeq ($(DATASET), large)
	TEST_ARGS =	im_benchmark $(DATASET_HOME)/vips/bigben_2662x5500.v output.v
endif

CFLAGS = -std=gnu11 -I. -I./include -I./libvips/include -I./glib/include/glib-2.0 -I./glib/lib/glib-2.0/include -I./zlib/include -I./libxml2/include/libxml2 -O2 -g -funroll-loops -fprefetch-loop-arrays -fpermissive -fno-exceptions -static-libgcc -Wl,--hash-style=both,--as-needed -DPARSEC_VERSION=2.1 -fexceptions -DHAVE_CONFIG_H -DG_DISABLE_CAST_CHECKS #-no-undefined -version-info 29:2:14

LIBS = -L./zlib/lib -L./lib -L./glib/lib -L./libxml2/lib -lvips -lX11 -lxml2 -lgmodule-2.0 -lgobject-2.0 -lgthread-2.0 -lglib-2.0 -ldl -lz -lm -lstdc++

.dir:
	mkdir -p obj/common obj/libvips obj/libvips/acquire obj/libvips/arithmetic obj/libvips/cimg obj/libvips/matrix obj/libvips/mosaicing obj/libvips/resample obj/libvips/boolean obj/libvips/colour obj/libvips/conversion obj/libvips/deprecated obj/libvips/convolution obj/libvips/format obj/libvips/freq_filt obj/libvips/histograms_lut obj/libvips/inplace obj/libvips/iofuncs obj/libvips/mask obj/libvips/morphology obj/libvips/other obj/libvips/relational obj/libvips/video obj/tools/iofuncs

include $(HOME)/Default.mk
