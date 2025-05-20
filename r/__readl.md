# Function: <code>__readl</code>

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
In lib/iomap.c (ffffffff814028b0)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff81474d6a)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81505a5d)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
```
```
In drivers/usb/dwc2/core.c (ffffffff816219e7)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
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
  - drivers/usb/dwc2/core.c:dwc2_core_init
  - drivers/usb/dwc2/core.c:dwc2_enable_host_interrupts
  - drivers/usb/dwc2/core.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/core.c:dwc2_hc_init
  - drivers/usb/dwc2/core.c:dwc2_hc_init
  - drivers/usb/dwc2/core.c:dwc2_hc_halt
  - drivers/usb/dwc2/core.c:dwc2_hc_halt
  - drivers/usb/dwc2/core.c:dwc2_hc_halt
  - drivers/usb/dwc2/core.c:dwc2_hc_halt
  - drivers/usb/dwc2/core.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/core.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/core.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/core.c:dwc2_hc_do_ping
  - drivers/usb/dwc2/core.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/core.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/core.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/core.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/core.c:dwc2_read_packet
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
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
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff8162560c)
Location: arch/x86/include/asm/io.h:62
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
In drivers/usb/dwc2/platform.c (ffffffff816262eb)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81626914)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
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
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8162ab8f)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8162d6c2)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162e839)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
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
In lib/iomap.c (ffffffff8144a5a0)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
```
```
In lib/iomap_copy.c (ffffffff8144a955)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff814c3269)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8155720d)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
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
In lib/iomap.c (ffffffff81468f60)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
```
```
In lib/iomap_copy.c (ffffffff81469315)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff814e5259)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81525e1d)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81583a0d)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
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
In lib/iomap.c (ffffffff8146e629)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
```
```
In lib/iomap_copy.c (ffffffff8146ea15)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff814f0fc4)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815389a9)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81597e1d)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81725c1a)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
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
In lib/iomap.c (ffffffff8149a95e)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
```
```
In lib/iomap_copy.c (ffffffff8149adf5)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff81531687)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8159a24d)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fca5d)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8179726a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
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
In lib/iomap.c (ffffffff814cfc21)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
```
```
In lib/iomap_copy.c (ffffffff814d00a5)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff8156704a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d1b7a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81635e3a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817d9e2a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
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
In lib/iomap.c (ffffffff814e4531)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap.c:ioread32be
```
```
In lib/iomap_copy.c (ffffffff814e49c5)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff8157eaba)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815eb19a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816540ea)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8180103a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
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
In lib/iomap.c (ffffffff81511078)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81511370)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff815af0d5)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161cf49)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81688b3a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8184234a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
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
In lib/iomap.c (ffffffff81531ae8)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81531de0)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff815d0055)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163e9f9)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ab1ca)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81873cca)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
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
In lib/iomap.c (ffffffff81595e98)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81596320)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff81679aa5)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816ebb08)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175de5a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81947f3c)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c4f2d)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
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
In lib/iomap.c (ffffffff815b1928)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In lib/iomap_copy.c (ffffffff815b1db4)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff81699b24)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81709164)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81778cda)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f843b)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194dd4c)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c515d)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
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
In lib/iomap.c (ffffffff815bc738)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In lib/iomap_copy.c (ffffffff815bcbc4)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff8167c964)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816ea78e)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175c70a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dcbcb)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819318bc)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819aa121)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
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
In lib/iomap.c (ffffffff81623588)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81623e84)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff816f16cf)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8176458d)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e034a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff818685cb)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d4b9c)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81a57a41)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
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
In lib/iomap.c (ffffffff816f3a1b)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In lib/iomap_copy.c (ffffffff816f4254)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff8181df9a)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff818986d4)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8191f06a)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b100b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b374ec)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81bc7541)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
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
In lib/iomap.c (ffffffff817e59eb)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In lib/iomap_copy.c (ffffffff817e6294)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff8194d26a)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819e0a0d)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7b49a)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b25698)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccc9fc)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81d6fe31)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
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
In lib/iomap.c (ffffffff81825a2b)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81826264)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff81991420)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a28798)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/tty/serial/8250/8250_rt288x.c (ffffffff81ad3410)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_rt288x.c:au_putc
  - drivers/tty/serial/8250/8250_rt288x.c:au_serial_dl_read
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b75787)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d3475c)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_swab
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81dddaf1)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
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
In lib/iomap.c (ffffffff8187743b)
Location: arch/x86/include/asm/io.h:62
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81877c74)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff819db400)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:color_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a73968)
Location: arch/x86/include/asm/io.h:62
Inline: True
```
```
In drivers/tty/serial/8250/8250_rt288x.c (ffffffff81b26ff0)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_rt288x.c:au_putc
  - drivers/tty/serial/8250/8250_rt288x.c:au_serial_dl_read
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc95fe)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32le_relaxed
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e939b1)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_get
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
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
In lib/iomap.c (ffffffff8152a0c8)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In lib/iomap_copy.c (ffffffff8152a3c0)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff815c4065)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8160a429)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81670c3a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
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
In lib/iomap.c (ffffffff8151a3a8)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In lib/iomap_copy.c (ffffffff8151a6a0)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fc069)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8164fd3a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
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
In lib/iomap.c (ffffffff81526158)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In lib/iomap_copy.c (ffffffff81526450)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff815c45f5)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81632839)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169f00a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8186917a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
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
In lib/iomap.c (ffffffff8153fad8)
Location: arch/x86/include/asm/io.h:63
Inline: True
```
```
In lib/iomap_copy.c (ffffffff8153fdd0)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - lib/iomap_copy.c:__ioread32_copy
```
```
In drivers/video/fbdev/core/cfbimgblt.c (ffffffff815de195)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
  - drivers/video/fbdev/core/cfbimgblt.c:cfb_imageblit
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164cb69)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b94ca)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:au_serial_dl_read
  - drivers/tty/serial/8250/8250_port.c:au_serial_in
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8188310a)
Location: arch/x86/include/asm/io.h:63
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
```
</details>
</li>
</ul>

## Differences
