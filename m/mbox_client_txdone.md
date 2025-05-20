# Function: <code>mbox_client_txdone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff816eb770)
Location: drivers/mailbox/mailbox.c:190
Inline: True
```
**Symbols:**

```
ffffffff816eb770-ffffffff816eb79a: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81750250)
Location: drivers/mailbox/mailbox.c:190
Inline: True
```
**Symbols:**

```
ffffffff81750250-ffffffff8175027a: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8177be10)
Location: drivers/mailbox/mailbox.c:189
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff8177be10-ffffffff8177be3a: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8179a8d0)
Location: drivers/mailbox/mailbox.c:192
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff8179a8d0-ffffffff8179a8fa: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81810c90)
Location: drivers/mailbox/mailbox.c:192
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81810c90-ffffffff81810cba: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8185ab30)
Location: drivers/mailbox/mailbox.c:192
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff8185ab30-ffffffff8185ab5a: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81879f30)
Location: drivers/mailbox/mailbox.c:192
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81879f30-ffffffff81879f5a: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff818bf89c)
Location: drivers/mailbox/mailbox.c:189
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff818bf89c-ffffffff818bf8b3: mbox_client_txdone.cold (STB_LOCAL)
ffffffff818bf4f0-ffffffff818bf50a: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff818f23d6)
Location: drivers/mailbox/mailbox.c:189
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff818f23d6-ffffffff818f23ed: mbox_client_txdone.cold (STB_LOCAL)
ffffffff818f2040-ffffffff818f205a: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff819c7c41)
Location: drivers/mailbox/mailbox.c:189
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff819c7c41-ffffffff819c7c58: mbox_client_txdone.cold (STB_LOCAL)
ffffffff819c7ae0-ffffffff819c7afa: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81c2d97a)
Location: drivers/mailbox/mailbox.c:191
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81c2d97a-ffffffff81c2d991: mbox_client_txdone.cold (STB_LOCAL)
ffffffff819c7a30-ffffffff819c7a4a: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81c1fbe0)
Location: drivers/mailbox/mailbox.c:191
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81c1fbe0-ffffffff81c1fbf7: mbox_client_txdone.cold (STB_LOCAL)
ffffffff819ac970-ffffffff819ac98a: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81d3152e)
Location: drivers/mailbox/mailbox.c:191
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81d3152e-ffffffff81d31545: mbox_client_txdone.cold (STB_LOCAL)
ffffffff81a5ae80-ffffffff81a5ae9a: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81efd988)
Location: drivers/mailbox/mailbox.c:197
Inline: True
Direct callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81efd988-ffffffff81efd99f: mbox_client_txdone.cold (STB_LOCAL)
ffffffff81bca6c0-ffffffff81bca6e4: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81d73d20)
Location: drivers/mailbox/mailbox.c:197
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81d73d20-ffffffff81d73d5e: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81de19c0)
Location: drivers/mailbox/mailbox.c:197
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81de19c0-ffffffff81de19fe: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81e97980)
Location: drivers/mailbox/mailbox.c:198
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81e97980-ffffffff81e979be: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffff800010b7a400)
Location: drivers/mailbox/mailbox.c:189
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_set_rate
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_get_status
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_get_status
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_control
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_control
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_config
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_config
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_handover
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_handover
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_release
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_release
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_request
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_request
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_flow_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_flow_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_ch_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_ch_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_tx_ch_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_tx_ch_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_unpair
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_unpair
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_pair
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_pair
  - drivers/firmware/ti_sci.c:ti_sci_cmd_ring_get_config
  - drivers/firmware/ti_sci.c:ti_sci_cmd_ring_get_config
  - drivers/firmware/ti_sci.c:ti_sci_cmd_ring_config
  - drivers/firmware/ti_sci.c:ti_sci_cmd_ring_config
  - drivers/firmware/ti_sci.c:ti_sci_get_resource_range
  - drivers/firmware/ti_sci.c:ti_sci_get_resource_range
  - drivers/firmware/ti_sci.c:ti_sci_cmd_core_reboot
  - drivers/firmware/ti_sci.c:ti_sci_cmd_core_reboot
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_match_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_match_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_num_parents
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_num_parents
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_parent
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_parent
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_parent
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_parent
  - drivers/firmware/ti_sci.c:ti_sci_cmd_get_clock_state
  - drivers/firmware/ti_sci.c:ti_sci_cmd_get_clock_state
  - drivers/firmware/ti_sci.c:ti_sci_set_clock_state
  - drivers/firmware/ti_sci.c:ti_sci_set_clock_state
  - drivers/firmware/ti_sci.c:ti_sci_cmd_set_device_resets
  - drivers/firmware/ti_sci.c:ti_sci_cmd_set_device_resets
  - drivers/firmware/ti_sci.c:ti_sci_get_device_state
  - drivers/firmware/ti_sci.c:ti_sci_get_device_state
  - drivers/firmware/ti_sci.c:ti_sci_set_device_state
  - drivers/firmware/ti_sci.c:ti_sci_set_device_state
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
```
**Symbols:**

```
ffff800010b7a400-ffff800010b7a454: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (c0c5fb64)
Location: drivers/mailbox/mailbox.c:189
Inline: True
Direct callers:
  - drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_set_rate
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
```
**Symbols:**

```
c0c5fb64-c0c5fba4: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (c000000000c59390)
Location: drivers/mailbox/mailbox.c:189
Inline: True
```
**Symbols:**

```
c000000000c59390-c000000000c593e4: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffe00072bf7a)
Location: drivers/mailbox/mailbox.c:189
Inline: True
```
**Symbols:**

```
ffffffe00072bf7a-ffffffe00072bfc8: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81893706)
Location: drivers/mailbox/mailbox.c:189
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81893706-ffffffff8189371d: mbox_client_txdone.cold (STB_LOCAL)
ffffffff81893370-ffffffff8189338a: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8184bc06)
Location: drivers/mailbox/mailbox.c:189
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff8184bc06-ffffffff8184bc1d: mbox_client_txdone.cold (STB_LOCAL)
ffffffff8184b870-ffffffff8184b88a: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff818e7206)
Location: drivers/mailbox/mailbox.c:189
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff818e7206-ffffffff818e721d: mbox_client_txdone.cold (STB_LOCAL)
ffffffff818e6e70-ffffffff818e6e8a: mbox_client_txdone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mbox_client_txdone(struct mbox_chan *chan, int r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81903e86)
Location: drivers/mailbox/mailbox.c:189
Inline: True
Direct callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81903e86-ffffffff81903e9d: mbox_client_txdone.cold (STB_LOCAL)
ffffffff81903af0-ffffffff81903b0a: mbox_client_txdone (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
