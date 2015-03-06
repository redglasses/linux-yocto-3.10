snd-soc-sst-platform-objs := sst_platform.o
snd-soc-ssp-platform-objs := mid_ssp.o
snd-soc-mfld-machine-objs := mfld_machine.o

# Medfield board
obj-$(CONFIG_SND_MFLD_MACHINE) += snd-soc-mfld-machine.o

# Baytrail board
obj-$(CONFIG_SND_SST_PLATFORM) += snd-soc-sst-platform.o
obj-$(CONFIG_SND_SSP_PLATFORM) += snd-soc-ssp-platform.o

snd-soc-byt-ak-machine-objs := byt_bin_ak4614.o byt_ia_ak4614.o
obj-$(CONFIG_SND_BYT_AK4614) += snd-soc-byt-ak-machine.o

snd-soc-byt-sample-machine-objs := byt_bin_sample.o byt_ia_sample.o
obj-$(CONFIG_SND_BYT_SAMPLE) += snd-soc-byt-sample-machine.o

snd-soc-byt-rt-machine-objs := byt_bl_rt5642.o
obj-$(CONFIG_SND_BYT_RT5642) += snd-soc-byt-rt-machine.o

# SST Compress framework driver
snd-compress-sst-objs := compress_sst.o
obj-$(CONFIG_SND_COMPRESS_SST) += snd-compress-sst.o

# DSP driver
obj-$(CONFIG_SND_INTEL_SST) += sst/
obj-$(CONFIG_SND_INTEL_SSP) += ssp/

# Audio Comms
snd-soc-comms-machine-objs := mfld_comms_machine.o
snd-soc-ssp-objs := mfld_ssp.o
obj-$(CONFIG_SND_MFLD_COMMS_MACHINE) += snd-soc-comms-machine.o
obj-$(CONFIG_SND_SOC_SSP) += snd-soc-ssp.o
