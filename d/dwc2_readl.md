# Function: <code>dwc2_readl</code>

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
In drivers/usb/dwc2/core.c (ffffffff816219e7)
Location: drivers/usb/dwc2/core.h:47
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
Location: drivers/usb/dwc2/core.h:47
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
Location: drivers/usb/dwc2/core.h:47
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81626914)
Location: drivers/usb/dwc2/core.h:47
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
Location: drivers/usb/dwc2/core.h:47
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
Location: drivers/usb/dwc2/core.h:47
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162e839)
Location: drivers/usb/dwc2/core.h:47
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
In drivers/usb/dwc2/core.c (ffffffff81683c5d)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
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
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
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
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81683cac)
Location: drivers/usb/dwc2/core.h:106
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
In drivers/usb/dwc2/platform.c (ffffffff8168470b)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8168aab6)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_init_fs_ls_pclk_sel
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8168cdf9)
Location: drivers/usb/dwc2/core.h:106
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168da81)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168f5e5)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
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
In drivers/usb/dwc2/core.c (ffffffff816b01ed)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_force_mode_if_needed
  - drivers/usb/dwc2/core.c:dwc2_force_mode_if_needed
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
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
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff816b023c)
Location: drivers/usb/dwc2/core.h:106
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
In drivers/usb/dwc2/platform.c (ffffffff816b0cde)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/params.c (ffffffff816b26cd)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b8bd6)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_init_fs_ls_pclk_sel
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816baee9)
Location: drivers/usb/dwc2/core.h:106
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bbb51)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bd694)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
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
In drivers/usb/dwc2/core.c (ffffffff816c53ad)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_force_mode_if_needed
  - drivers/usb/dwc2/core.c:dwc2_force_mode_if_needed
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
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
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff816c53fc)
Location: drivers/usb/dwc2/core.h:106
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
In drivers/usb/dwc2/platform.c (ffffffff816c5e3e)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/params.c (ffffffff816c670d)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816ccf16)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_init_fs_ls_pclk_sel
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816cf089)
Location: drivers/usb/dwc2/core.h:106
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816cfcb4)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d16e0)
Location: drivers/usb/dwc2/core.h:106
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
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
In drivers/usb/dwc2/core.c (ffffffff8173168d)
Location: drivers/usb/dwc2/core.h:107
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_force_mode_if_needed
  - drivers/usb/dwc2/core.c:dwc2_force_mode_if_needed
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
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
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff817316dc)
Location: drivers/usb/dwc2/core.h:107
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
In drivers/usb/dwc2/platform.c (ffffffff8173212e)
Location: drivers/usb/dwc2/core.h:107
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/params.c (ffffffff81732ac5)
Location: drivers/usb/dwc2/core.h:107
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81739506)
Location: drivers/usb/dwc2/core.h:107
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_init_fs_ls_pclk_sel
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8173b6c9)
Location: drivers/usb/dwc2/core.h:107
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173c2f4)
Location: drivers/usb/dwc2/core.h:107
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173dd60)
Location: drivers/usb/dwc2/core.h:107
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
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
In drivers/usb/dwc2/core.c (ffffffff817708aa)
Location: drivers/usb/dwc2/core.h:107
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff817709fc)
Location: drivers/usb/dwc2/core.h:107
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
In drivers/usb/dwc2/platform.c (ffffffff81771a2e)
Location: drivers/usb/dwc2/core.h:107
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/params.c (ffffffff81772e45)
Location: drivers/usb/dwc2/core.h:107
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81779a2c)
Location: drivers/usb/dwc2/core.h:107
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8177be99)
Location: drivers/usb/dwc2/core.h:107
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177cb83)
Location: drivers/usb/dwc2/core.h:107
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177e6f3)
Location: drivers/usb/dwc2/core.h:107
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
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
In drivers/usb/dwc2/core.c (ffffffff817952d9)
Location: drivers/usb/dwc2/core.h:1194
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff817955f8)
Location: drivers/usb/dwc2/core.h:1194
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
In drivers/usb/dwc2/platform.c (ffffffff81796c2a)
Location: drivers/usb/dwc2/core.h:1194
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/params.c (ffffffff81797fb5)
Location: drivers/usb/dwc2/core.h:1194
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179f9a7)
Location: drivers/usb/dwc2/core.h:1194
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817a2205)
Location: drivers/usb/dwc2/core.h:1194
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a30fe)
Location: drivers/usb/dwc2/core.h:1194
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a4dff)
Location: drivers/usb/dwc2/core.h:1194
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
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
In drivers/usb/dwc2/core.c (ffffffff817d3e91)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff817d5048)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff817d5c73)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/params.c (ffffffff817d6be5)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817de489)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817e0f26)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e28f5)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e4022)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
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
In drivers/usb/dwc2/core.c (ffffffff81804d61)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81805ef8)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff81806b23)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/params.c (ffffffff81807a75)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180f3d9)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81811e16)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818137e5)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81814ee2)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
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
In drivers/usb/dwc2/core.c (ffffffff818d5a36)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff818d6e22)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/core_intr.c:dwc2_read_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_read_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_read_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_disconnect_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
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
In drivers/usb/dwc2/platform.c (ffffffff818d7362)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_check_core_version
```
```
In drivers/usb/dwc2/params.c (ffffffff818d88d5)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e00e9)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
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
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_cleanup_channels
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_cleanup_channels
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_gusbcfg_init
  - drivers/usb/dwc2/hcd.c:dwc2_gahbcfg_init
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818e33a0)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_rx_fifo_level_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e4f49)
Location: drivers/usb/dwc2/core.h:1214
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e6a92)
Location: drivers/usb/dwc2/core.h:1214
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
In drivers/usb/dwc2/core.c (ffffffff818dfd56)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_hs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_fs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff818e1002)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/core_intr.c:dwc2_read_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_read_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_read_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_disconnect_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
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
In drivers/usb/dwc2/platform.c (ffffffff818e1802)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_check_core_version
```
```
In drivers/usb/dwc2/drd.c (ffffffff818e2299)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_ovr_bvalid
  - drivers/usb/dwc2/drd.c:dwc2_ovr_avalid
```
```
In drivers/usb/dwc2/params.c (ffffffff818e2dd5)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e9f49)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
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
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_cleanup_channels
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_cleanup_channels
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_gusbcfg_init
  - drivers/usb/dwc2/hcd.c:dwc2_gahbcfg_init
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818ecc00)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
  - drivers/usb/dwc2/hcd_intr.c:dwc2_rx_fifo_level_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ee419)
Location: drivers/usb/dwc2/core.h:1216
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818efba2)
Location: drivers/usb/dwc2/core.h:1216
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
In drivers/usb/dwc2/core.c (ffffffff818c2eef)
Location: drivers/usb/dwc2/core.h:1225
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff818c3ef8)
Location: drivers/usb/dwc2/core.h:1225
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
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff818c4a56)
Location: drivers/usb/dwc2/core.h:1225
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_check_core_version
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
```
```
In drivers/usb/dwc2/drd.c (ffffffff818c55b9)
Location: drivers/usb/dwc2/core.h:1225
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_ovr_bvalid
  - drivers/usb/dwc2/drd.c:dwc2_ovr_avalid
```
```
In drivers/usb/dwc2/params.c (ffffffff818c5e65)
Location: drivers/usb/dwc2/core.h:1225
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818cc6e7)
Location: drivers/usb/dwc2/core.h:1225
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
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
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818d0286)
Location: drivers/usb/dwc2/core.h:1225
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_port_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d1c19)
Location: drivers/usb/dwc2/core.h:1225
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d3352)
Location: drivers/usb/dwc2/core.h:1225
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 dwc2_readl(struct dwc2_hsotg *hsotg, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff8195a1a2)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff8195b80f)
Location: drivers/usb/dwc2/core.h:1227
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff8195c5a7)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_check_core_version
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
```
```
In drivers/usb/dwc2/drd.c (ffffffff8195d4af)
Location: drivers/usb/dwc2/core.h:1227
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
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
```
In drivers/usb/dwc2/params.c (ffffffff8195e195)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8196627d)
Location: drivers/usb/dwc2/core.h:1227
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8196a865)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196c5fd)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196de37)
Location: drivers/usb/dwc2/core.h:1227
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff8195a3a0-ffffffff8195a3d1: dwc2_readl (STB_LOCAL)
ffffffff81d18a68-ffffffff81d18a7c: dwc2_readl.cold (STB_LOCAL)
ffffffff8195e980-ffffffff8195e9b1: dwc2_readl (STB_LOCAL)
ffffffff81d1a761-ffffffff81d1a775: dwc2_readl.cold (STB_LOCAL)
ffffffff81967d80-ffffffff81967db1: dwc2_readl (STB_LOCAL)
ffffffff81d1d22c-ffffffff81d1d240: dwc2_readl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 dwc2_readl(struct dwc2_hsotg *hsotg, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81ab4032)
Location: drivers/usb/dwc2/core.h:1233
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81ab563c)
Location: drivers/usb/dwc2/core.h:1233
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ab660b)
Location: drivers/usb/dwc2/core.h:1233
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_check_core_version
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/drd.c (ffffffff81ab749e)
Location: drivers/usb/dwc2/core.h:1233
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_ovr_bvalid
  - drivers/usb/dwc2/drd.c:dwc2_ovr_avalid
```
```
In drivers/usb/dwc2/params.c (ffffffff81ab84d5)
Location: drivers/usb/dwc2/core.h:1233
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ac047f)
Location: drivers/usb/dwc2/core.h:1233
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81ac4bd4)
Location: drivers/usb/dwc2/core.h:1233
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac6a9d)
Location: drivers/usb/dwc2/core.h:1233
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac843a)
Location: drivers/usb/dwc2/core.h:1233
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81ab4240-ffffffff81ab4279: dwc2_readl (STB_LOCAL)
ffffffff81ee3b39-ffffffff81ee3b4d: dwc2_readl.cold (STB_LOCAL)
ffffffff81ab5df0-ffffffff81ab5e29: dwc2_readl (STB_LOCAL)
ffffffff81ee467c-ffffffff81ee4690: dwc2_readl.cold (STB_LOCAL)
ffffffff81ab8d90-ffffffff81ab8dc9: dwc2_readl (STB_LOCAL)
ffffffff81ee589e-ffffffff81ee58b2: dwc2_readl.cold (STB_LOCAL)
ffffffff81ac1ec0-ffffffff81ac1ef9: dwc2_readl (STB_LOCAL)
ffffffff81ee8a7e-ffffffff81ee8a92: dwc2_readl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 dwc2_readl(struct dwc2_hsotg *hsotg, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81c3c8e2)
Location: drivers/usb/dwc2/core.h:1203
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81c3df0c)
Location: drivers/usb/dwc2/core.h:1203
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff81c3efdb)
Location: drivers/usb/dwc2/core.h:1203
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_check_core_version
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/drd.c (ffffffff81c3ff9e)
Location: drivers/usb/dwc2/core.h:1203
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_ovr_bvalid
  - drivers/usb/dwc2/drd.c:dwc2_ovr_avalid
```
```
In drivers/usb/dwc2/params.c (ffffffff81c41735)
Location: drivers/usb/dwc2/core.h:1203
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c49f2f)
Location: drivers/usb/dwc2/core.h:1203
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81c4ec04)
Location: drivers/usb/dwc2/core.h:1203
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c50c4d)
Location: drivers/usb/dwc2/core.h:1203
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c527ca)
Location: drivers/usb/dwc2/core.h:1203
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81c3e730-ffffffff81c3e769: dwc2_readl (STB_LOCAL)
ffffffff820a0729-ffffffff820a073d: dwc2_readl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 dwc2_readl(struct dwc2_hsotg *hsotg, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81ca3ce2)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81ca52fc)
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ca6578)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_check_core_version
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/drd.c (ffffffff81ca751e)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_ovr_bvalid
  - drivers/usb/dwc2/drd.c:dwc2_ovr_avalid
```
```
In drivers/usb/dwc2/params.c (ffffffff81ca8cf5)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81cb152f)
Location: drivers/usb/dwc2/core.h:1205
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81cb61d4)
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb81cd)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cb9d8a)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81ca5bc0-ffffffff81ca5bf9: dwc2_readl (STB_LOCAL)
ffffffff82121cf1-ffffffff82121d05: dwc2_readl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 dwc2_readl(struct dwc2_hsotg *hsotg, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81d58932)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_phy_init
  - drivers/usb/dwc2/core.c:dwc2_phy_init
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
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81d59f4c)
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_usb_suspend_intr
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff81d5b1c8)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_suspend
  - drivers/usb/dwc2/platform.c:dwc2_check_core_version
  - drivers/usb/dwc2/platform.c:dwc2_driver_remove
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/drd.c (ffffffff81d5c16e)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_suspend
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_ovr_bvalid
  - drivers/usb/dwc2/drd.c:dwc2_ovr_avalid
```
```
In drivers/usb/dwc2/params.c (ffffffff81d5d985)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d6623f)
Location: drivers/usb/dwc2/core.h:1205
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_hc_init
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81d6af24)
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6cf3d)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6eafa)
Location: drivers/usb/dwc2/core.h:1205
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81d5a810-ffffffff81d5a849: dwc2_readl (STB_LOCAL)
ffffffff822034c8-ffffffff822034dc: dwc2_readl.cold (STB_LOCAL)
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
In drivers/usb/dwc2/core.c (ffff800010a3c064)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_force_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_iddig_filter_enabled
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffff800010a3d580)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffff800010a3e3c4)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/params.c (ffff800010a3f858)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a481a0)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
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
```
```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a4b14c)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4caa4)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4e0b0)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffff800010a404f8-ffff800010a40524: dwc2_readl.isra.0 (STB_LOCAL)
ffff800010a48828-ffff800010a48854: dwc2_readl.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c0b0ef9c)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (c0b10330)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (c0b10f0c)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/params.c (c0b12450)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (c0b1a8e4)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (c0b1d414)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (c0b1ec6c)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b2019c)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (c000000000afa8c8)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (c000000000afcbec)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (c000000000afe134)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/params.c (c000000000affd04)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (c000000000b0d4b0)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_set_even_odd_frame
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (c000000000b119b4)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (c000000000b13cd8)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b159fc)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 dwc2_readl(struct dwc2_hsotg *hsotg, u32 offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffe000657840)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffe000659384)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/params.c (ffffffe00065b50a)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffe000665028)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_set_even_odd_frame
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_disable_host_interrupts
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe000667e4a)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe00066958e)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066aaa2)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffe00065bcb2-ffffffe00065bcfe: dwc2_readl (STB_LOCAL)
ffffffe000665624-ffffffe000665670: dwc2_readl (STB_LOCAL)
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
In drivers/usb/dwc2/core.c (ffffffff817bd141)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff817be2d8)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff817bef03)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/params.c (ffffffff817bfe55)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c77b9)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817ca1f6)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cbbc5)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cd2c2)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
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
In drivers/usb/dwc2/core.c (ffffffff817f9be1)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff817fad78)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff817fb9a3)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/params.c (ffffffff817fc8f5)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81804259)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81806c96)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81808665)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81809d62)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
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
In drivers/usb/dwc2/core.c (ffffffff81813e21)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core.c:dwc2_init_fs_ls_pclk_sel
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_hw_is_device
  - drivers/usb/dwc2/core.c:dwc2_hw_is_host
  - drivers/usb/dwc2/core.c:dwc2_disable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_enable_global_interrupts
  - drivers/usb/dwc2/core.c:dwc2_is_controller_alive
  - drivers/usb/dwc2/core.c:dwc2_enable_acg
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
  - drivers/usb/dwc2/core.c:dwc2_backup_global_registers
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81814fa8)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/platform.c (ffffffff81815ab3)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
```
In drivers/usb/dwc2/params.c (ffffffff81816a05)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
  - drivers/usb/dwc2/params.c:dwc2_get_hwparams
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181e369)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
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
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_backup_host_registers
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_get_frame_number
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_get_future_frame_number
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_wakeup_detected
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
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
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_hc_halt
  - drivers/usb/dwc2/hcd.c:dwc2_read_packet
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_calc_frame_interval
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_config_fifos
  - drivers/usb/dwc2/hcd.c:dwc2_enable_common_interrupts
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81820da6)
Location: drivers/usb/dwc2/core.h:1204
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
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_n_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_chhltd_intr_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_frmovrun_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ahberr_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_babble_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nyet_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_ack_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_nak_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_stall_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_complete_periodic_xfer
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hcd_save_data_toggle
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81822775)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81823e72)
Location: drivers/usb/dwc2/core.h:1204
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
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
