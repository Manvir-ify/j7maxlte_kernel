subdir-ccflags-$(CONFIG_MTK_PMIC_CHIP_MT6335)+= -I$(srctree)/drivers/misc/mediatek/pmic/include/mt6335
subdir-ccflags-$(CONFIG_MTK_PMIC_CHIP_MT6353)+= -I$(srctree)/drivers/misc/mediatek/pmic/include/mt6353
subdir-ccflags-$(CONFIG_MTK_PMIC_CHIP_MT6355)+= -I$(srctree)/drivers/misc/mediatek/pmic/include/mt6355

obj-$(CONFIG_MTK_EXTBUCK) += extbuck/
obj-$(CONFIG_MTK_PMIC_COMMON) += common/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6313) += mt6313/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6335) += mt6335/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6336) += mt6336/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6337) += mt6337/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6353) += mt6353/
obj-$(CONFIG_MTK_PMIC_CHIP_MT6355) += mt6355/

obj-$(CONFIG_MFD_RT5081_PMU)	+= rt5081/

obj-$(CONFIG_MTK_AUXADC_INTF) += common/upmu_auxadc.o

obj-y += mtk_battery_adc_intf.o
