# S3c24XX Platform Support
snd-soc-s3c24xx-objs := dma.o
snd-soc-s3c-dma-objs := dmaengine.o
snd-soc-idma-objs := idma.o
snd-soc-s3c24xx-i2s-objs := s3c24xx-i2s.o
snd-soc-s3c2412-i2s-objs := s3c2412-i2s.o
snd-soc-ac97-objs := ac97.o
snd-soc-s3c-i2s-v2-objs := s3c-i2s-v2.o
snd-soc-samsung-spdif-objs := spdif.o
snd-soc-pcm-objs := pcm.o
snd-soc-i2s-objs := i2s.o
snd-soc-lpass-objs := lpass.o
snd-soc-compr-objs := compr.o visualizercap-dummydai.o
snd-soc-eax-dai-objs := eax-dai.o
snd-soc-eax-dma-objs := eax-dma.o
snd-soc-esa-sa-effect-objs := esa_sa_effect.o

obj-$(CONFIG_SND_SOC_SAMSUNG) += snd-soc-s3c24xx.o
obj-$(CONFIG_SND_S3C24XX_I2S) += snd-soc-s3c24xx-i2s.o
obj-$(CONFIG_SND_SAMSUNG_AC97) += snd-soc-ac97.o
obj-$(CONFIG_SND_S3C2412_SOC_I2S) += snd-soc-s3c2412-i2s.o
obj-$(CONFIG_SND_S3C_I2SV2_SOC) += snd-soc-s3c-i2s-v2.o
obj-$(CONFIG_SND_SAMSUNG_SPDIF) += snd-soc-samsung-spdif.o
obj-$(CONFIG_SND_SAMSUNG_PCM) += snd-soc-pcm.o
obj-$(CONFIG_SND_SAMSUNG_I2S) += snd-soc-i2s.o
obj-$(CONFIG_SND_SAMSUNG_I2S) += snd-soc-idma.o
obj-$(CONFIG_SND_SAMSUNG_COMPR) += snd-soc-compr.o

ifeq ($(CONFIG_SND_SAMSUNG_AUDSS),y)
obj-$(CONFIG_SOC_EXYNOS5422) += lpass.o lpass-exynos5422.o
obj-$(CONFIG_SOC_EXYNOS5430) += lpass.o lpass-exynos5430.o
obj-$(CONFIG_SOC_EXYNOS5433) += lpass.o lpass-exynos5433.o
obj-$(CONFIG_SOC_EXYNOS7420) += lpass.o lpass-exynos7420.o
obj-$(CONFIG_SOC_EXYNOS7580) += lpass.o lpass-exynos7580.o
obj-$(CONFIG_SOC_EXYNOS7890) += lpass.o lpass-exynos7890.o
obj-$(CONFIG_SOC_EXYNOS8890) += lpass.o lpass-exynos8890.o
obj-$(CONFIG_SOC_EXYNOS7870) += lpass-exynos7870.o
endif
obj-$(CONFIG_SND_SOC_SAMSUNG) += snd-soc-eax-dai.o snd-soc-eax-dma.o
obj-$(CONFIG_SND_ESA_SA_EFFECT) += snd-soc-esa-sa-effect.o

# S3C24XX Machine Support
snd-soc-jive-wm8750-objs := jive_wm8750.o
snd-soc-neo1973-wm8753-objs := neo1973_wm8753.o
snd-soc-smdk2443-wm9710-objs := smdk2443_wm9710.o
snd-soc-ln2440sbc-alc650-objs := ln2440sbc_alc650.o
snd-soc-s3c24xx-uda134x-objs := s3c24xx_uda134x.o
snd-soc-s3c24xx-simtec-objs := s3c24xx_simtec.o
snd-soc-s3c24xx-simtec-hermes-objs := s3c24xx_simtec_hermes.o
snd-soc-s3c24xx-simtec-tlv320aic23-objs := s3c24xx_simtec_tlv320aic23.o
snd-soc-h1940-uda1380-objs := h1940_uda1380.o
snd-soc-rx1950-uda1380-objs := rx1950_uda1380.o
snd-soc-smdk-wm8580-objs := smdk_wm8580.o
snd-soc-smdk-wm8994-objs := smdk_wm8994.o
snd-soc-snow-objs := snow.o
snd-soc-smdk-wm9713-objs := smdk_wm9713.o
snd-soc-s3c64xx-smartq-wm8987-objs := smartq_wm8987.o
snd-soc-goni-wm8994-objs := goni_wm8994.o
snd-soc-smdk-spdif-objs := smdk_spdif.o
snd-soc-smdk-wm8580pcm-objs := smdk_wm8580pcm.o
snd-soc-smdk-wm8994pcm-objs := smdk_wm8994pcm.o
snd-soc-speyside-objs := speyside.o
snd-soc-tobermory-objs := tobermory.o
snd-soc-lowland-objs := lowland.o
snd-soc-littlemill-objs := littlemill.o
snd-soc-bells-objs := bells.o
snd-soc-odroidx2-max98090-objs := odroidx2_max98090.o
snd-soc-universal8890-dummy-objs := universal8890_dummy.o
snd-soc-smdk7870-cod3026x-objs := smdk7870-cod3026.o
ifeq ($(CONFIG_SND_SOC_EXYNOS_AUDMIXER_VER),2)
snd-soc-universal7870-cod3026x-v2-objs := universal7870-cod3026-v2.o
else
snd-soc-universal7870-cod3026x-objs := universal7870-cod3026.o
endif
snd-soc-universal7870-rt5659-objs := universal7870-rt5659.o
snd-soc-universal7870-rt5665-objs := universal7870-rt5665.o jack_rt5665_sysfs_cb.o
snd-soc-sec-audio-objs := sec_audio_sysfs.o
snd-soc-espresso8890-wm5110-objs := cp_dummy.o espresso8890_wm5110.o

obj-$(CONFIG_SND_SOC_SAMSUNG_JIVE_WM8750) += snd-soc-jive-wm8750.o
obj-$(CONFIG_SND_SOC_SAMSUNG_NEO1973_WM8753) += snd-soc-neo1973-wm8753.o
obj-$(CONFIG_SND_SOC_SAMSUNG_SMDK2443_WM9710) += snd-soc-smdk2443-wm9710.o
obj-$(CONFIG_SND_SOC_SAMSUNG_LN2440SBC_ALC650) += snd-soc-ln2440sbc-alc650.o
obj-$(CONFIG_SND_SOC_SAMSUNG_S3C24XX_UDA134X) += snd-soc-s3c24xx-uda134x.o
obj-$(CONFIG_SND_SOC_SAMSUNG_SIMTEC) += snd-soc-s3c24xx-simtec.o
obj-$(CONFIG_SND_SOC_SAMSUNG_SIMTEC_HERMES) += snd-soc-s3c24xx-simtec-hermes.o
obj-$(CONFIG_SND_SOC_SAMSUNG_SIMTEC_TLV320AIC23) += snd-soc-s3c24xx-simtec-tlv320aic23.o
obj-$(CONFIG_SND_SOC_SAMSUNG_H1940_UDA1380) += snd-soc-h1940-uda1380.o
obj-$(CONFIG_SND_SOC_SAMSUNG_RX1950_UDA1380) += snd-soc-rx1950-uda1380.o
obj-$(CONFIG_SND_SOC_SAMSUNG_SMDK_WM8580) += snd-soc-smdk-wm8580.o
obj-$(CONFIG_SND_SOC_SAMSUNG_SMDK_WM8994) += snd-soc-smdk-wm8994.o
obj-$(CONFIG_SND_SOC_SNOW) += snd-soc-snow.o
obj-$(CONFIG_SND_SOC_SAMSUNG_SMDK_WM9713) += snd-soc-smdk-wm9713.o
obj-$(CONFIG_SND_SOC_SMARTQ) += snd-soc-s3c64xx-smartq-wm8987.o
obj-$(CONFIG_SND_SOC_SAMSUNG_SMDK_SPDIF) += snd-soc-smdk-spdif.o
obj-$(CONFIG_SND_SOC_GONI_AQUILA_WM8994) += snd-soc-goni-wm8994.o
obj-$(CONFIG_SND_SOC_SMDK_WM8580_PCM) += snd-soc-smdk-wm8580pcm.o
obj-$(CONFIG_SND_SOC_SMDK_WM8994_PCM) += snd-soc-smdk-wm8994pcm.o
obj-$(CONFIG_SND_SOC_SPEYSIDE) += snd-soc-speyside.o
obj-$(CONFIG_SND_SOC_TOBERMORY) += snd-soc-tobermory.o
obj-$(CONFIG_SND_SOC_LOWLAND) += snd-soc-lowland.o
obj-$(CONFIG_SND_SOC_LITTLEMILL) += snd-soc-littlemill.o
obj-$(CONFIG_SND_SOC_BELLS) += snd-soc-bells.o
obj-$(CONFIG_SND_SOC_ODROIDX2) += snd-soc-odroidx2-max98090.o
obj-$(CONFIG_SND_SOC_SAMSUNG_ESPRESSO8890_WM5110) += snd-soc-espresso8890-wm5110.o
obj-$(CONFIG_SND_SOC_SAMSUNG_UNIVERSAL8890_DUMMY) += snd-soc-universal8890-dummy.o
obj-$(CONFIG_SND_SOC_SAMSUNG_SMDK7870_COD3026X) += snd-soc-smdk7870-cod3026x.o
ifeq ($(CONFIG_SND_SOC_EXYNOS_AUDMIXER_VER),2)
obj-$(CONFIG_SND_SOC_SAMSUNG_UNIVERSAL7870_COD3026X) += snd-soc-universal7870-cod3026x-v2.o
else
obj-$(CONFIG_SND_SOC_SAMSUNG_UNIVERSAL7870_COD3026X) += snd-soc-universal7870-cod3026x.o
endif
obj-$(CONFIG_SND_SOC_SAMSUNG_UNIVERSAL7870_RT5659) += snd-soc-universal7870-rt5659.o
obj-$(CONFIG_SND_SOC_SAMSUNG_UNIVERSAL7870_RT5665) += snd-soc-universal7870-rt5665.o
obj-$(CONFIG_SND_SOC_SAMSUNG_AUDIO) += snd-soc-sec-audio.o

obj-$(CONFIG_SND_SAMSUNG_SEIREN) += seiren/
