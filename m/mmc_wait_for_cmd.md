# Function: <code>mmc_wait_for_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816bf450)
Location: drivers/mmc/core/core.c:734
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_set_blockcount
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_send_status
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_all_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff816bf450-ffffffff816bf500: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81721e50)
Location: drivers/mmc/core/core.c:735
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blockcount
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_all_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff81721e50-ffffffff81721f00: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81754e00)
Location: drivers/mmc/core/core.c:808
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blockcount
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_all_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/mmc_ops.c:mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff81754e00-ffffffff81754eb7: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81772990)
Location: drivers/mmc/core/core.c:687
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blockcount
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/mmc_ops.c:__mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff81772990-ffffffff81772a18: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e8500)
Location: drivers/mmc/core/core.c:841
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blockcount
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/mmc_ops.c:__mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff817e8500-ffffffff817e8591: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818318f0)
Location: drivers/mmc/core/core.c:640
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blockcount
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/mmc_ops.c:__mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff818318f0-ffffffff81831981: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185d8d0)
Location: drivers/mmc/core/core.c:640
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/mmc_ops.c:__mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff8185d8d0-ffffffff8185d961: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:638
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:_mmc_select_card
  - drivers/mmc/core/mmc_ops.c:__mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff818a3d92-ffffffff818a3db8: mmc_wait_for_cmd.cold (STB_LOCAL)
ffffffff818a1520-ffffffff818a15b6: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d3810)
Location: drivers/mmc/core/core.c:638
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:_mmc_select_card
  - drivers/mmc/core/mmc_ops.c:__mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff818d3810-ffffffff818d38a1: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a5ee0)
Location: drivers/mmc/core/core.c:621
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:mmc_sleep
  - drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff819a5ee0-ffffffff819a5f6d: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a8c90)
Location: drivers/mmc/core/core.c:621
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:mmc_sleep
  - drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff819a8c90-ffffffff819a8d1d: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198d960)
Location: drivers/mmc/core/core.c:622
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff8198d960-ffffffff8198d9ed: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a38fe0)
Location: drivers/mmc/core/core.c:622
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_send_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff81a38fe0-ffffffff81a3906d: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba6090)
Location: drivers/mmc/core/core.c:622
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_send_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:__mmc_send_op_cond_cb
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff81ba6090-ffffffff81ba612c: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d483f0)
Location: drivers/mmc/core/core.c:621
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_send_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:__mmc_send_op_cond_cb
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff81d483f0-ffffffff81d4848c: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db2cf0)
Location: drivers/mmc/core/core.c:621
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_send_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:__mmc_send_op_cond_cb
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff81db2cf0-ffffffff81db2d8c: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6b080)
Location: drivers/mmc/core/core.c:626
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_send_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:__mmc_send_op_cond_cb
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:sdio_reset
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff81e6b080-ffffffff81e6b11c: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2cd90)
Location: drivers/mmc/core/core.c:638
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:_mmc_select_card
  - drivers/mmc/core/mmc_ops.c:__mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/mmc/core/block.c:mmc_blk_fix_state
  - drivers/mmc/core/block.c:mmc_sd_num_wr_blocks
```
**Symbols:**

```
ffff800010b2cd90-ffff800010b2ce3c: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c080c4)
Location: drivers/mmc/core/core.c:638
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:_mmc_select_card
  - drivers/mmc/core/mmc_ops.c:__mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/mmc/core/block.c:mmc_blk_fix_state
  - drivers/mmc/core/block.c:mmc_sd_num_wr_blocks
```
**Symbols:**

```
c0c080c4-c0c08184: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c25c00)
Location: drivers/mmc/core/core.c:638
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:_mmc_select_card
  - drivers/mmc/core/mmc_ops.c:__mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
c000000000c25c00-c000000000c25cc4: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000706dc6)
Location: drivers/mmc/core/core.c:638
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:_mmc_select_card
  - drivers/mmc/core/mmc_ops.c:__mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/mmc/core/block.c:mmc_blk_fix_state
  - drivers/mmc/core/block.c:mmc_sd_num_wr_blocks
```
**Symbols:**

```
ffffffe000706dc6-ffffffe000706e3c: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818771d0)
Location: drivers/mmc/core/core.c:638
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:_mmc_select_card
  - drivers/mmc/core/mmc_ops.c:__mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff818771d0-ffffffff81877261: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c8670)
Location: drivers/mmc/core/core.c:638
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:_mmc_select_card
  - drivers/mmc/core/mmc_ops.c:__mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff818c8670-ffffffff818c8701: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host *host, struct mmc_command *cmd, int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e5190)
Location: drivers/mmc/core/core.c:638
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_abort_tuning
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc
  - drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native
  - drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_set_dsr
  - drivers/mmc/core/mmc_ops.c:_mmc_select_card
  - drivers/mmc/core/mmc_ops.c:__mmc_send_status
  - drivers/mmc/core/sd_ops.c:mmc_send_relative_addr
  - drivers/mmc/core/sd_ops.c:mmc_send_if_cond
  - drivers/mmc/core/sd_ops.c:mmc_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
ffffffff818e5190-ffffffff818e5221: mmc_wait_for_cmd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
