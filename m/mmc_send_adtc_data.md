# Function: <code>mmc_send_adtc_data</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmc_send_adtc_data(struct mmc_card *card, struct mmc_host *host, u32 opcode, u32 args, void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81a414e0)
Location: drivers/mmc/core/mmc_ops.c:254
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_spi_send_cxd
  - drivers/mmc/core/sd.c:sd_busy_poweroff_notify_cb
  - drivers/mmc/core/sd.c:sd_flush_cache
  - drivers/mmc/core/sd.c:sd_read_ext_regs
  - drivers/mmc/core/sd.c:sd_read_ext_regs
  - drivers/mmc/core/sd.c:sd_read_ext_regs
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
```
**Symbols:**

```
ffffffff81a414e0-ffffffff81a41608: mmc_send_adtc_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmc_send_adtc_data(struct mmc_card *card, struct mmc_host *host, u32 opcode, u32 args, void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81baea80)
Location: drivers/mmc/core/mmc_ops.c:283
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_spi_send_cxd
  - drivers/mmc/core/sd.c:sd_busy_poweroff_notify_cb
  - drivers/mmc/core/sd.c:sd_flush_cache
  - drivers/mmc/core/sd.c:sd_read_ext_regs
  - drivers/mmc/core/sd.c:sd_parse_ext_reg
  - drivers/mmc/core/sd.c:sd_parse_ext_reg
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
```
**Symbols:**

```
ffffffff81baea80-ffffffff81baebea: mmc_send_adtc_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_send_adtc_data(struct mmc_card *card, struct mmc_host *host, u32 opcode, u32 args, void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d523a0)
Location: drivers/mmc/core/mmc_ops.c:283
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_spi_send_cxd
  - drivers/mmc/core/sd.c:sd_busy_poweroff_notify_cb
  - drivers/mmc/core/sd.c:sd_flush_cache
  - drivers/mmc/core/sd.c:sd_read_ext_regs
  - drivers/mmc/core/sd.c:sd_parse_ext_reg
  - drivers/mmc/core/sd.c:sd_parse_ext_reg
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
```
**Symbols:**

```
ffffffff81d523a0-ffffffff81d5250a: mmc_send_adtc_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_send_adtc_data(struct mmc_card *card, struct mmc_host *host, u32 opcode, u32 args, void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbcdb0)
Location: drivers/mmc/core/mmc_ops.c:283
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_spi_send_cxd
  - drivers/mmc/core/sd.c:sd_busy_poweroff_notify_cb
  - drivers/mmc/core/sd.c:sd_flush_cache
  - drivers/mmc/core/sd.c:sd_read_ext_regs
  - drivers/mmc/core/sd.c:sd_parse_ext_reg
  - drivers/mmc/core/sd.c:sd_parse_ext_reg
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
```
**Symbols:**

```
ffffffff81dbcdb0-ffffffff81dbcf1a: mmc_send_adtc_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_send_adtc_data(struct mmc_card *card, struct mmc_host *host, u32 opcode, u32 args, void *buf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e75380)
Location: drivers/mmc/core/mmc_ops.c:283
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_spi_send_cxd
  - drivers/mmc/core/sd.c:sd_busy_poweroff_notify_cb
  - drivers/mmc/core/sd.c:sd_flush_cache
  - drivers/mmc/core/sd.c:sd_read_ext_regs
  - drivers/mmc/core/sd.c:sd_parse_ext_reg
  - drivers/mmc/core/sd.c:sd_parse_ext_reg
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
```
**Symbols:**

```
ffffffff81e75380-ffffffff81e754ea: mmc_send_adtc_data (STB_GLOBAL)
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
