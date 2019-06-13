CFLAGS_devfreq_trace.o		:= -I$(src)

obj-$(CONFIG_PM_DEVFREQ)	+= devfreq.o
obj-$(CONFIG_PM_DEVFREQ)       += devfreq_trace.o
obj-$(CONFIG_ADRENO_REAL_IDLER)		+= adreno_idler.o
adreno_idler-objs	:= adreno_real_idler.o
obj-$(CONFIG_DEVFREQ_GOV_PERFORMANCE)	+= governor_performance.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_ADRENO_PLUS)	+= governor_msm_adreno_plus.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_ADRENO_TZ)	+= governor_msm_adreno_tz.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_ADRENO_BALANCED)	+= governor_msm_adreno_balanced.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_ADRENO_GUARDIAN)	+= governor_msm_adreno_guardian.o
obj-$(CONFIG_DEVFREQ_GOV_POWERSAVE)	+= governor_powersave.o
obj-$(CONFIG_DEVFREQ_GOV_USERSPACE)	+= governor_userspace.o
obj-$(CONFIG_DEVFREQ_GOV_SIMPLE_ONDEMAND)	+= governor_simpleondemand.o
obj-$(CONFIG_DEVFREQ_GOV_CPUFREQ)	+= governor_cpufreq.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_GPUBW_MON)	+= governor_bw_vbif.o
obj-$(CONFIG_MSM_BIMC_BWMON)		+= bimc-bwmon.o
obj-$(CONFIG_ARMBW_HWMON)		+= armbw-pm.o

# DEVFREQ Drivers
obj-$(CONFIG_MSM_DEVFREQ_DEVBW)		+= devfreq_devbw.o
obj-$(CONFIG_DEVFREQ_SIMPLE_DEV)       += devfreq_simple_dev.o
