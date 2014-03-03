## LibTinkerforge:

AUTOMAKE_OPTIONS = subdir-objects

ACLOCAL_AMFLAGS = ${ACLOCAL_FLAGS}

lib_LTLIBRARIES = libtinkerforge-@TINKERFORGE_MULTI_LIB_VERSION@.la

libtinkerforge_@TINKERFORGE_MULTI_LIB_VERSION@_la_SOURCES = 	tinkerforge/brick_dc.c \
														tinkerforge/bricklet_current25.c \
														tinkerforge/bricklet_humidity.c \
														tinkerforge/bricklet_joystick.c \
														tinkerforge/bricklet_motion_detector.c \
														tinkerforge/bricklet_rotary_poti.c \
														tinkerforge/brick_imu.c \
														tinkerforge/bricklet_distance_ir.c \
														tinkerforge/bricklet_industrial_digital_in_4.c \
														tinkerforge/bricklet_lcd_16x2.c \
														tinkerforge/bricklet_multi_touch.c \
														tinkerforge/bricklet_segment_display_4x7.c \
														tinkerforge/brick_master.c \
														tinkerforge/bricklet_ambient_light.c \
														tinkerforge/bricklet_distance_us.c \
														tinkerforge/bricklet_industrial_digital_out_4.c \
														tinkerforge/bricklet_lcd_20x4.c \
														tinkerforge/bricklet_piezo_buzzer.c \
														tinkerforge/bricklet_sound_intensity.c \
														tinkerforge/brick_servo.c \
														tinkerforge/bricklet_analog_in.c \
														tinkerforge/bricklet_dual_button.c \
														tinkerforge/bricklet_industrial_dual_0_20ma.c \
														tinkerforge/bricklet_led_strip.c \
														tinkerforge/bricklet_piezo_speaker.c \
														tinkerforge/bricklet_temperature.c \
														tinkerforge/brick_stepper.c \
														tinkerforge/bricklet_analog_out.c \
														tinkerforge/bricklet_dual_relay.c \
														tinkerforge/bricklet_industrial_quad_relay.c \
														tinkerforge/bricklet_linear_poti.c \
														tinkerforge/bricklet_ptc.c \
														tinkerforge/bricklet_temperature_ir.c \
														tinkerforge/ip_connection.c \
														tinkerforge/bricklet_barometer.c \
														tinkerforge/bricklet_gps.c \
														tinkerforge/bricklet_io16.c \
														tinkerforge/bricklet_line.c \
														tinkerforge/bricklet_remote_switch.c \
														tinkerforge/bricklet_tilt.c \
														tinkerforge/bricklet_current12.c \
														tinkerforge/bricklet_hall_effect.c \
														tinkerforge/bricklet_io4.c \
														tinkerforge/bricklet_moisture.c \
														tinkerforge/bricklet_rotary_encoder.c \
														tinkerforge/bricklet_voltage.c \
														tinkerforge/bricklet_voltage_current.c

libtinkerforge_@TINKERFORGE_MULTI_LIB_VERSION@_la_LDFLAGS = -version-info $(TINKERFORGE_SO_VERSION)

tinkerforge_includedir = $(includedir)/tinkerforge-$(TINKERFORGE_MULTI_LIB_VERSION)
nobase_tinkerforge_include_HEADERS = 	tinkerforge/bricklet_voltage_current.h \
										tinkerforge/brick_dc.h \
										tinkerforge/bricklet_current25.h \
										tinkerforge/bricklet_humidity.h \
										tinkerforge/bricklet_joystick.h \
										tinkerforge/bricklet_motion_detector.h \
										tinkerforge/bricklet_rotary_poti.h \
										tinkerforge/bricklet_voltage.h \
										tinkerforge/brick_imu.h \
										tinkerforge/bricklet_distance_ir.h \
										tinkerforge/bricklet_industrial_digital_in_4.h \
										tinkerforge/bricklet_lcd_16x2.h \
										tinkerforge/bricklet_multi_touch.h \
										tinkerforge/bricklet_segment_display_4x7.h \
										tinkerforge/brick_master.h \
										tinkerforge/bricklet_ambient_light.h \
										tinkerforge/bricklet_distance_us.h \
										tinkerforge/bricklet_industrial_digital_out_4.h \
										tinkerforge/bricklet_lcd_20x4.h \
										tinkerforge/bricklet_piezo_buzzer.h \
										tinkerforge/bricklet_sound_intensity.h \
										tinkerforge/brick_servo.h \
										tinkerforge/bricklet_analog_in.h \
										tinkerforge/bricklet_dual_button.h \
										tinkerforge/bricklet_industrial_dual_0_20ma.h \
										tinkerforge/bricklet_led_strip.h \
										tinkerforge/bricklet_piezo_speaker.h \
										tinkerforge/bricklet_temperature.h \
										tinkerforge/brick_stepper.h \
										tinkerforge/bricklet_analog_out.h \
										tinkerforge/bricklet_dual_relay.h \
										tinkerforge/bricklet_industrial_quad_relay.h \
										tinkerforge/bricklet_linear_poti.h \
										tinkerforge/bricklet_ptc.h \
										tinkerforge/bricklet_temperature_ir.h \
										tinkerforge/ip_connection.h \
										tinkerforge/bricklet_barometer.h \
										tinkerforge/bricklet_gps.h \
										tinkerforge/bricklet_io16.h \
										tinkerforge/bricklet_line.h \
										tinkerforge/bricklet_remote_switch.h \
										tinkerforge/bricklet_tilt.h \
										tinkerforge/bricklet_current12.h \
										tinkerforge/bricklet_hall_effect.h \
										tinkerforge/bricklet_io4.h \
										tinkerforge/bricklet_moisture.h \
										tinkerforge/bricklet_rotary_encoder.h \
										tinkerforge/tinkerforge.h


tinkerforge_libincludedir = $(libdir)/tinkerforge-$(TINKERFORGE_MULTI_LIB_VERSION)/include
nodist_tinkerforge_libinclude_HEADERS = config.h

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = tinkerforge-$(TINKERFORGE_MULTI_LIB_VERSION).pc

dist_noinst_SCRIPTS = autogen.sh
