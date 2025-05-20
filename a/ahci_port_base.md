# Function: <code>ahci_port_base</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libahci.c (ffff8000109bbd50)
Location: drivers/ata/ahci.h:434
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_pmp_detach
  - drivers/ata/libahci.c:ahci_pmp_attach
  - drivers/ata/libahci.c:ahci_disable_fbs
  - drivers/ata/libahci.c:ahci_enable_fbs
  - drivers/ata/libahci.c:ahci_set_aggressive_devslp
  - drivers/ata/libahci.c:ahci_thaw
  - drivers/ata/libahci.c:ahci_freeze
  - drivers/ata/libahci.c:ahci_qc_issue
  - drivers/ata/libahci.c:ahci_handle_port_intr
  - drivers/ata/libahci.c:ahci_multi_irqs_intr_hard
  - drivers/ata/libahci.c:ahci_handle_port_interrupt
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_postreset
  - drivers/ata/libahci.c:ahci_pmp_retry_softreset
  - drivers/ata/libahci.c:ahci_bad_pmp_check_ready
  - drivers/ata/libahci.c:ahci_check_ready
  - drivers/ata/libahci.c:ahci_kick_engine
  - drivers/ata/libahci.c:ahci_dev_classify
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_stop_engine
  - drivers/ata/libahci.c:ahci_start_engine
  - drivers/ata/libahci.c:ahci_scr_read
  - drivers/ata/libahci.c:ahci_show_port_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libahci.c (c0a86310)
Location: drivers/ata/ahci.h:434
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_pmp_detach
  - drivers/ata/libahci.c:ahci_pmp_attach
  - drivers/ata/libahci.c:ahci_disable_fbs
  - drivers/ata/libahci.c:ahci_enable_fbs
  - drivers/ata/libahci.c:ahci_set_aggressive_devslp
  - drivers/ata/libahci.c:ahci_thaw
  - drivers/ata/libahci.c:ahci_freeze
  - drivers/ata/libahci.c:ahci_qc_issue
  - drivers/ata/libahci.c:ahci_handle_port_intr
  - drivers/ata/libahci.c:ahci_multi_irqs_intr_hard
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_postreset
  - drivers/ata/libahci.c:ahci_pmp_retry_softreset
  - drivers/ata/libahci.c:ahci_bad_pmp_check_ready
  - drivers/ata/libahci.c:ahci_check_ready
  - drivers/ata/libahci.c:ahci_kick_engine
  - drivers/ata/libahci.c:ahci_dev_classify
  - drivers/ata/libahci.c:ahci_init_controller
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_start_fis_rx
  - drivers/ata/libahci.c:ahci_stop_engine
  - drivers/ata/libahci.c:ahci_start_engine
  - drivers/ata/libahci.c:ahci_scr_write
  - drivers/ata/libahci.c:ahci_show_port_cmd
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
