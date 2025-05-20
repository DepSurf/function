# Function: <code>sd_parse_ext_reg</code>

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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81a435c4)
Location: drivers/mmc/core/sd.c:1180
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:sd_read_ext_regs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sd_parse_ext_reg(struct mmc_card *card, u8 *gen_info_buf, u16 *next_ext_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1187
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:sd_read_ext_regs
```
**Symbols:**

```
ffffffff81bb0f20-ffffffff81bb11ac: sd_parse_ext_reg (STB_LOCAL)
ffffffff81efa6cc-ffffffff81efa728: sd_parse_ext_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sd_parse_ext_reg(struct mmc_card *card, u8 *gen_info_buf, u16 *next_ext_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81d54db0)
Location: drivers/mmc/core/sd.c:1189
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:sd_read_ext_regs
```
**Symbols:**

```
ffffffff81d54db0-ffffffff81d55085: sd_parse_ext_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sd_parse_ext_reg(struct mmc_card *card, u8 *gen_info_buf, u16 *next_ext_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81dbf730)
Location: drivers/mmc/core/sd.c:1189
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:sd_read_ext_regs
```
**Symbols:**

```
ffffffff81dbf730-ffffffff81dbf9e2: sd_parse_ext_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sd_parse_ext_reg(struct mmc_card *card, u8 *gen_info_buf, u16 *next_ext_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81e77e40)
Location: drivers/mmc/core/sd.c:1189
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:sd_read_ext_regs
```
**Symbols:**

```
ffffffff81e77e40-ffffffff81e78150: sd_parse_ext_reg (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
