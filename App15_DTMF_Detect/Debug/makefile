################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/ti/ccsv5/tools/compiler/c5500_4.4.1

ORDERED_OBJS += \
$(GEN_CMDS__FLAG) \
"./Sources/usbstk5505_led.obj" \
"./Sources/usbstk5505_i2c.obj" \
"./Sources/usbstk5505_gpio.obj" \
"./Sources/usbstk5505.obj" \
"./Sources/stereo.obj" \
"./Sources/sinewaves.obj" \
"./Sources/goertzel.obj" \
"./Sources/aic3204_init.obj" \
"./Sources/aic3204.obj" \
"./Sources/PLL.obj" \
"./Sources/LEDFlasher.obj" \
"./main.obj" \
-l"rts55h.lib" \
-l"C:\Users\Roger\workspace_v5_2\usbstk5515bsl\55xdsph.lib" \
-l"C:\Users\Roger\workspace_v5_2\usbstk5515bsl\CSLc55x5h.lib" \
"../lnkx.cmd" \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include Sources/subdir_vars.mk
-include subdir_rules.mk
-include Sources/subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: App15_DTMF_Detect.out

# Tool invocations
App15_DTMF_Detect.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: C5500 Linker'
	"C:/ti/ccsv5/tools/compiler/c5500_4.4.1/bin/cl55" -v5515 --memory_model=huge -g --define=c5515 --display_error_number --diag_warning=225 --ptrdiff_size=32 -z -m"App15_DTMF_Detect.map" --stack_size=0x200 --heap_size=0x400 -i"C:/ti/ccsv5/tools/compiler/c5500_4.4.1/lib" -i"C:/ti/ccsv5/tools/compiler/c5500_4.4.1/include" --reread_libs --display_error_number --warn_sections --rom_model --sys_stacksize=0x200 -o "App15_DTMF_Detect.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(C5500_EXECUTABLE_OUTPUTS__QUOTED) "App15_DTMF_Detect.out"
	-$(RM) "main.pp" "Sources\LEDFlasher.pp" "Sources\PLL.pp" "Sources\aic3204.pp" "Sources\aic3204_init.pp" "Sources\goertzel.pp" "Sources\sinewaves.pp" "Sources\stereo.pp" "Sources\usbstk5505.pp" "Sources\usbstk5505_gpio.pp" "Sources\usbstk5505_i2c.pp" "Sources\usbstk5505_led.pp" 
	-$(RM) "main.obj" "Sources\LEDFlasher.obj" "Sources\PLL.obj" "Sources\aic3204.obj" "Sources\aic3204_init.obj" "Sources\goertzel.obj" "Sources\sinewaves.obj" "Sources\stereo.obj" "Sources\usbstk5505.obj" "Sources\usbstk5505_gpio.obj" "Sources\usbstk5505_i2c.obj" "Sources\usbstk5505_led.obj" 
	-@echo 'Finished clean'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets
