# Function: <code>__writel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81402aa7)
Location: arch/x86/include/asm/io.h:70
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81402ca8)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff81474dc4)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81505a7d)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815212f5)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i965_write_entry
```
```
In drivers/usb/dwc2/core.c (ffffffff816219fa)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_enable_host_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_host_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_host_interrupts
  - drivers/usb/dwc2/core.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/core.c:dwc2_hc_init
  - drivers/usb/dwc2/core.c:dwc2_hc_init
  - drivers/usb/dwc2/core.c:dwc2_hc_init
  - drivers/usb/dwc2/core.c:dwc2_hc_init
  - drivers/usb/dwc2/core.c:dwc2_hc_init
  - drivers/usb/dwc2/core.c:dwc2_hc_init
  - drivers/usb/dwc2/core.c:dwc2_hc_init
  - drivers/usb/dwc2/core.c:dwc2_hc_halt
  - drivers/usb/dwc2/core.c:dwc2_hc_halt
  - drivers/usb/dwc2/core.c:dwc2_hc_halt
  - drivers/usb/dwc2/core.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/core.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/core.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/core.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/core.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/core.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/core.c:dwc2_hc_do_ping
  - drivers/usb/dwc2/core.c:dwc2_hc_do_ping
  - drivers/usb/dwc2/core.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/core.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/core.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/core.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81625a76)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81626962)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8162abaa)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8162db0b)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162e857)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8144a5e2)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - lib/iomap.c:iowrite32be
```
```
In lib/iomap_copy.c (ffffffff8144a928)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff814c32c3)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8155722d)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8157435b)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81468fa2)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - lib/iomap.c:iowrite32be
```
```
In lib/iomap_copy.c (ffffffff814692e8)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff814e52b3)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815264b8)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81583a2d)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a09db)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8146e66d)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - lib/iomap.c:iowrite32be
```
```
In lib/iomap_copy.c (ffffffff8146e9e8)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff814f101d)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8153941d)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81597e3d)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b463b)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81726138)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8149a9a2)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap.c:iowrite32be
```
```
In lib/iomap_copy.c (ffffffff8149adc8)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff815316e0)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8159add8)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fca7d)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161b28b)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81797788)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814cfc3f)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap.c:iowrite32be
```
```
In lib/iomap_copy.c (ffffffff814d0078)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff8156709e)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d29ad)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81635e5a)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81654f3b)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817da394)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814e454f)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap.c:iowrite32be
```
```
In lib/iomap_copy.c (ffffffff814e4998)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff8157eb0e)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ec15d)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8165410a)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8167313b)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818017b4)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815111ca)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81511357)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff815af16a)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161de3f)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81688b5a)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816a8c6b)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81842a64)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81531c3a)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81531dc7)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff815d00ea)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163f8ef)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ab1ea)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cb9ab)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818743e4)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81595fba)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81596307)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff81679dff)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816ec8ed)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175de7a)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8178065d)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81947f1a)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b1a4a)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In lib/iomap_copy.c (ffffffff815b1d97)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff81699e7d)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81709f6f)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81778cfa)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8179849d)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f833b)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194dd2e)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815bc85a)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In lib/iomap_copy.c (ffffffff815bcba7)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff8167ccbe)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eb67d)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175c72a)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8177b1cb)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dcacb)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8193189e)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816236aa)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81623e67)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff816f1bce)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81765756)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e036a)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8180126b)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff818684cb)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d4b7e)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816f365d)
Location: arch/x86/include/asm/io.h:73
Inline: True
```
```
In lib/iomap_copy.c (ffffffff816f4227)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff8181d36a)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff818998b0)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8191f08a)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8194086b)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b0f0b)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b374be)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff817e55ed)
Location: arch/x86/include/asm/io.h:73
Inline: True
```
```
In lib/iomap_copy.c (ffffffff817e6257)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff8194c9b4)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819e1c60)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7b4ca)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aa252b)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b25903)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccc9be)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8182562d)
Location: arch/x86/include/asm/io.h:73
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81826227)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff81990ed4)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a29cde)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
```
```
In drivers/tty/serial/8250/8250_rt288x.c (ffffffff81ad33e2)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_rt288x.c:au_putc
  - drivers/tty/serial/8250/8250_rt288x.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aede0b)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b759f3)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d3471e)
Location: arch/x86/include/asm/io.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8187703d)
Location: arch/x86/include/asm/io.h:70
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81877c37)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff819daeb4)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:fast_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a74eae)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
```
```
In drivers/tty/serial/8250/8250_rt288x.c (ffffffff81b26fc2)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_rt288x.c:au_putc
  - drivers/tty/serial/8250/8250_rt288x.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81b4134b)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc9750)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32le_relaxed
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8152a21a)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In lib/iomap_copy.c (ffffffff8152a3a7)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff815c40fa)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8160b31f)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81670c5a)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816913fb)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8151a4fa)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In lib/iomap_copy.c (ffffffff8151a687)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fcf5f)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8164fd5a)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8166edeb)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815262aa)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81526437)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff815c468a)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163372f)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169f02a)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816bf66b)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81869894)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153fc2a)
Location: arch/x86/include/asm/io.h:71
Inline: True
```
```
In lib/iomap_copy.c (ffffffff8153fdb7)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff815de22a)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164da5f)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b94ea)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_write
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816d9c3b)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i965_write_entry
  - drivers/char/agp/intel-gtt.c:i830_write_entry
  - drivers/char/agp/intel-gtt.c:i810_write_entry
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81883824)
Location: arch/x86/include/asm/io.h:71
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
```
</details>
</li>
</ul>

## Differences
