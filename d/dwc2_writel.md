# Function: <code>dwc2_writel</code>

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
In drivers/usb/dwc2/core.c (ffffffff816219fa)
Location: drivers/usb/dwc2/core.h:59
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
In drivers/usb/dwc2/core_intr.c (ffffffff816256b4)
Location: drivers/usb/dwc2/core.h:59
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
Location: drivers/usb/dwc2/core.h:59
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
Location: drivers/usb/dwc2/core.h:59
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
Location: drivers/usb/dwc2/core.h:59
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162e857)
Location: drivers/usb/dwc2/core.h:59
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
In drivers/usb/dwc2/core.c (ffffffff81683be7)
Location: drivers/usb/dwc2/core.h:111
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
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
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81683d57)
Location: drivers/usb/dwc2/core.h:111
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
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8168ab90)
Location: drivers/usb/dwc2/core.h:111
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_init_fs_ls_pclk_sel
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8168cf9b)
Location: drivers/usb/dwc2/core.h:111
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168e21c)
Location: drivers/usb/dwc2/core.h:111
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168f5fd)
Location: drivers/usb/dwc2/core.h:111
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/core.c (ffffffff816b0177)
Location: drivers/usb/dwc2/core.h:111
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
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
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff816b02e7)
Location: drivers/usb/dwc2/core.h:111
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
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b8cb0)
Location: drivers/usb/dwc2/core.h:111
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_init_fs_ls_pclk_sel
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816bb07f)
Location: drivers/usb/dwc2/core.h:111
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bc2e5)
Location: drivers/usb/dwc2/core.h:111
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bd6ac)
Location: drivers/usb/dwc2/core.h:111
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/core.c (ffffffff816c5337)
Location: drivers/usb/dwc2/core.h:111
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
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
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff816c5490)
Location: drivers/usb/dwc2/core.h:111
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
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816ccff0)
Location: drivers/usb/dwc2/core.h:111
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_init_fs_ls_pclk_sel
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816cf22a)
Location: drivers/usb/dwc2/core.h:111
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816d00b9)
Location: drivers/usb/dwc2/core.h:111
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d16f8)
Location: drivers/usb/dwc2/core.h:111
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/core.c (ffffffff81731617)
Location: drivers/usb/dwc2/core.h:112
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
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
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81731770)
Location: drivers/usb/dwc2/core.h:112
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
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817395e0)
Location: drivers/usb/dwc2/core.h:112
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_init_fs_ls_pclk_sel
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8173b870)
Location: drivers/usb/dwc2/core.h:112
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173c6ff)
Location: drivers/usb/dwc2/core.h:112
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173dd78)
Location: drivers/usb/dwc2/core.h:112
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/core.c (ffffffff81770837)
Location: drivers/usb/dwc2/core.h:112
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81770ad0)
Location: drivers/usb/dwc2/core.h:112
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
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81779a1f)
Location: drivers/usb/dwc2/core.h:112
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8177bf34)
Location: drivers/usb/dwc2/core.h:112
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177d02f)
Location: drivers/usb/dwc2/core.h:112
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177e70b)
Location: drivers/usb/dwc2/core.h:112
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/core.c (ffffffff81794d49)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff8179572d)
Location: drivers/usb/dwc2/core.h:1205
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
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179f99a)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817a23ef)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a35bf)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a4e24)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/core.c (ffffffff817d3ef4)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff817d5160)
Location: drivers/usb/dwc2/core.h:1215
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817de47c)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817e0fe0)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e2dd1)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e4047)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/core.c (ffffffff81804dc4)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81806010)
Location: drivers/usb/dwc2/core.h:1215
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180f3cc)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81811ed0)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81813cc1)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81814f07)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/core.c (ffffffff818d5a46)
Location: drivers/usb/dwc2/core.h:1225
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff818d7068)
Location: drivers/usb/dwc2/core.h:1225
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_disconnect_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_session_req_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_conn_id_status_change_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_conn_id_status_change_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff818d7377)
Location: drivers/usb/dwc2/core.h:1225
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e00dc)
Location: drivers/usb/dwc2/core.h:1225
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_cleanup_channels
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_cleanup_channels
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_gusbcfg_init
  - drivers/usb/dwc2/hcd.c:dwc2_gahbcfg_init
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818e3471)
Location: drivers/usb/dwc2/core.h:1225
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e4f5c)
Location: drivers/usb/dwc2/core.h:1225
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e6ab5)
Location: drivers/usb/dwc2/core.h:1225
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
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
In drivers/usb/dwc2/core.c (ffffffff818dfd66)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff818e1248)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_disconnect_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_session_req_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_conn_id_status_change_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_conn_id_status_change_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff818e1817)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/drd.c (ffffffff818e22ae)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_ovr_bvalid
  - drivers/usb/dwc2/drd.c:dwc2_ovr_avalid
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e9f3c)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_cleanup_channels
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_cleanup_channels
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_gusbcfg_init
  - drivers/usb/dwc2/hcd.c:dwc2_gahbcfg_init
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818eccd1)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ee42c)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818efbc5)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
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
In drivers/usb/dwc2/core.c (ffffffff818c2f2a)
Location: drivers/usb/dwc2/core.h:1236
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff818c400c)
Location: drivers/usb/dwc2/core.h:1236
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff818c4a6e)
Location: drivers/usb/dwc2/core.h:1236
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/drd.c (ffffffff818c55d1)
Location: drivers/usb/dwc2/core.h:1236
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_ovr_bvalid
  - drivers/usb/dwc2/drd.c:dwc2_ovr_avalid
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818cc700)
Location: drivers/usb/dwc2/core.h:1236
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818d04b5)
Location: drivers/usb/dwc2/core.h:1236
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d1c2f)
Location: drivers/usb/dwc2/core.h:1236
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d3377)
Location: drivers/usb/dwc2/core.h:1236
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_writel(struct dwc2_hsotg *hsotg, u32 value, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff8195a231)
Location: drivers/usb/dwc2/core.h:1238
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff8195b984)
Location: drivers/usb/dwc2/core.h:1238
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff8195c5d8)
Location: drivers/usb/dwc2/core.h:1238
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/drd.c (ffffffff8195d4dc)
Location: drivers/usb/dwc2/core.h:1238
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
```
In drivers/usb/dwc2/hcd.c (ffffffff819662be)
Location: drivers/usb/dwc2/core.h:1238
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8196ab03)
Location: drivers/usb/dwc2/core.h:1238
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196c636)
Location: drivers/usb/dwc2/core.h:1238
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196de75)
Location: drivers/usb/dwc2/core.h:1238
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff8195a3e0-ffffffff8195a42d: dwc2_writel (STB_LOCAL)
ffffffff81d18a7c-ffffffff81d18a97: dwc2_writel.cold (STB_LOCAL)
ffffffff8195e9c0-ffffffff8195ea0d: dwc2_writel (STB_LOCAL)
ffffffff81d1a775-ffffffff81d1a790: dwc2_writel.cold (STB_LOCAL)
ffffffff81967dc0-ffffffff81967e0d: dwc2_writel (STB_LOCAL)
ffffffff81d1d240-ffffffff81d1d25b: dwc2_writel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_writel(struct dwc2_hsotg *hsotg, u32 value, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81ab40ba)
Location: drivers/usb/dwc2/core.h:1244
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81ab5785)
Location: drivers/usb/dwc2/core.h:1244
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ab663f)
Location: drivers/usb/dwc2/core.h:1244
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/drd.c (ffffffff81ab74d0)
Location: drivers/usb/dwc2/core.h:1244
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_ovr_bvalid
  - drivers/usb/dwc2/drd.c:dwc2_ovr_avalid
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ac04b3)
Location: drivers/usb/dwc2/core.h:1244
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81ac4e91)
Location: drivers/usb/dwc2/core.h:1244
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac6acc)
Location: drivers/usb/dwc2/core.h:1244
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac8478)
Location: drivers/usb/dwc2/core.h:1244
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81ab4280-ffffffff81ab42e1: dwc2_writel (STB_LOCAL)
ffffffff81ee3b4d-ffffffff81ee3b68: dwc2_writel.cold (STB_LOCAL)
ffffffff81ab5e30-ffffffff81ab5e91: dwc2_writel (STB_LOCAL)
ffffffff81ee4690-ffffffff81ee46ab: dwc2_writel.cold (STB_LOCAL)
ffffffff81ab8dd0-ffffffff81ab8e31: dwc2_writel (STB_LOCAL)
ffffffff81ee58b2-ffffffff81ee58cd: dwc2_writel.cold (STB_LOCAL)
ffffffff81ac1f00-ffffffff81ac1f61: dwc2_writel (STB_LOCAL)
ffffffff81ee8a92-ffffffff81ee8aad: dwc2_writel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_writel(struct dwc2_hsotg *hsotg, u32 value, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81c3c96a)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81c3e0a6)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff81c3f00f)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/drd.c (ffffffff81c3ffd0)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_ovr_bvalid
  - drivers/usb/dwc2/drd.c:dwc2_ovr_avalid
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c49f63)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81c4ee57)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c50c7c)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c52808)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81c3e780-ffffffff81c3e7e1: dwc2_writel (STB_LOCAL)
ffffffff820a073d-ffffffff820a0758: dwc2_writel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_writel(struct dwc2_hsotg *hsotg, u32 value, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81ca3d6a)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81ca54c9)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ca65ac)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/drd.c (ffffffff81ca7550)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_ovr_bvalid
  - drivers/usb/dwc2/drd.c:dwc2_ovr_avalid
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81cb1563)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81cb6401)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb81fc)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cb9dc8)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81ca5c10-ffffffff81ca5c71: dwc2_writel (STB_LOCAL)
ffffffff82121d05-ffffffff82121d20: dwc2_writel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void dwc2_writel(struct dwc2_hsotg *hsotg, u32 value, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81d589ba)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81d5a119)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff81d5b1fc)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/drd.c (ffffffff81d5c1a0)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_ovr_bvalid
  - drivers/usb/dwc2/drd.c:dwc2_ovr_avalid
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d66273)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81d6b154)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6cf6c)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6eb38)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81d5a860-ffffffff81d5a8c1: dwc2_writel (STB_LOCAL)
ffffffff822034dc-ffffffff822034f7: dwc2_writel.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffff800010a3c10c)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffff800010a3d6d0)
Location: drivers/usb/dwc2/core.h:1215
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a4818c)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
```
```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a4b2d8)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4cf60)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4e0dc)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffff800010a40150-ffff800010a40168: dwc2_writel.isra.0.part.0 (STB_LOCAL)
ffff800010a48858-ffff800010a48870: dwc2_writel.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void dwc2_writel(struct dwc2_hsotg *hsotg, u32 value, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0f010)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (c0b10450)
Location: drivers/usb/dwc2/core.h:1215
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/hcd.c (c0b1a8d0)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (c0b1d5f8)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (c0b1f068)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b201bc)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
c0b0f488-c0b0f4e0: dwc2_writel (STB_LOCAL)
c0b12cf4-c0b12d4c: dwc2_writel (STB_LOCAL)
c0b1b200-c0b1b258: dwc2_writel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void dwc2_writel(struct dwc2_hsotg *hsotg, u32 value, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000afa998)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (c000000000afcea8)
Location: drivers/usb/dwc2/core.h:1215
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/hcd.c (c000000000b0d498)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (c000000000b12044)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (c000000000b14360)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b15b60)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
c000000000b00b80-c000000000b00bd4: dwc2_writel (STB_LOCAL)
c000000000b0dc10-c000000000b0dc64: dwc2_writel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void dwc2_writel(struct dwc2_hsotg *hsotg, u32 value, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe0006578de)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffe000659556)
Location: drivers/usb/dwc2/core.h:1215
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffe000664ffc)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe000667ffc)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe0006699ca)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066aac2)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffe00065c06e-ffffffe00065c0e2: dwc2_writel (STB_LOCAL)
ffffffe000665670-ffffffe0006656e4: dwc2_writel (STB_LOCAL)
```
</details>
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
In drivers/usb/dwc2/core.c (ffffffff817bd1a4)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff817be3f0)
Location: drivers/usb/dwc2/core.h:1215
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c77ac)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817ca2b0)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cc0a1)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cd2e7)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff817f9c44)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff817fae90)
Location: drivers/usb/dwc2/core.h:1215
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180424c)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81806d50)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81808b41)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81809d87)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/core.c (ffffffff81813e84)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
  - drivers/usb/dwc2/core.c:dwc2_restore_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff818150b4)
Location: drivers/usb/dwc2/core.h:1215
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181e35c)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_restore_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_write_packet
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81820e5e)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81822c51)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81823e97)
Location: drivers/usb/dwc2/core.h:1215
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
