################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include misc/templ/subdir.mk
-include misc/others/subdir.mk
-include misc/os/subdir.mk
-include misc/mem/subdir.mk
-include misc/math/subdir.mk
-include misc/gfx/fonts/subdir.mk
-include misc/gfx/subdir.mk
-include misc/fs/ufs/subdir.mk
-include misc/fs/linuxfs/subdir.mk
-include misc/fs/fat32/option/subdir.mk
-include misc/fs/fat32/subdir.mk
-include misc/fs/subdir.mk
-include misc/comm/subdir.mk
-include misc/subdir.mk
-include lvgl/lv_objx/subdir.mk
-include lvgl/lv_obj/subdir.mk
-include lvgl/lv_examples/3_3_app_com/subdir.mk
-include lvgl/lv_examples/3_2_app_run/subdir.mk
-include lvgl/lv_examples/3_1_app_desktop/subdir.mk
-include lvgl/lv_examples/2_4_mouse_ctrl/subdir.mk
-include lvgl/lv_examples/2_3_keyboard_ctrl/subdir.mk
-include lvgl/lv_examples/2_2_encoder_ctrl/subdir.mk
-include lvgl/lv_examples/2_1_button_ctrl/subdir.mk
-include lvgl/lv_examples/1_8_new_obj_type/subdir.mk
-include lvgl/lv_examples/1_7_gui/subdir.mk
-include lvgl/lv_examples/1_6_anti_aliasing/subdir.mk
-include lvgl/lv_examples/1_5_animations/subdir.mk
-include lvgl/lv_examples/1_4_responsive/subdir.mk
-include lvgl/lv_examples/1_3_styles/subdir.mk
-include lvgl/lv_examples/1_2_objects/subdir.mk
-include lvgl/lv_examples/1_1_hello_world/subdir.mk
-include lvgl/lv_draw/subdir.mk
-include lvgl/lv_appx/subdir.mk
-include lvgl/lv_app/lv_app_util/subdir.mk
-include lvgl/lv_app/subdir.mk
-include hw/per/psp/pic32mz/subdir.mk
-include hw/per/psp/pic32mx/subdir.mk
-include hw/per/psp/pic24f_33f/subdir.mk
-include hw/per/psp/pc/subdir.mk
-include hw/per/psp/kea/subdir.mk
-include hw/per/subdir.mk
-include hw/dev/wifi/subdir.mk
-include hw/dev/ui/subdir.mk
-include hw/dev/tp/subdir.mk
-include hw/dev/sens/subdir.mk
-include hw/dev/io_exp/subdir.mk
-include hw/dev/gsm/subdir.mk
-include hw/dev/ext_mem/subdir.mk
-include hw/dev/dispc/subdir.mk
-include hw/subdir.mk
-include hal/systick/subdir.mk
-include hal/indev/subdir.mk
-include hal/disp/subdir.mk
-include subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: lv_proj_pc

# Tool invocations
lv_proj_pc: $(OBJS) $(USER_OBJS)
	@echo 'Building target: $@'
	@echo 'Invoking: Cross GCC Linker'
	gcc  -o "lv_proj_pc" $(OBJS) $(USER_OBJS) $(LIBS)
	@echo 'Finished building target: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(EXECUTABLES)$(OBJS)$(C_DEPS) lv_proj_pc
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets
