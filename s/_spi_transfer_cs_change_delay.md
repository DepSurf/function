# Function: <code>_spi_transfer_cs_change_delay</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817917df)
Location: drivers/spi/spi.c:1109
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b53df)
Location: drivers/spi/spi.c:1110
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8187c34e)
Location: drivers/spi/spi.c:1191
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8188a5eb)
Location: drivers/spi/spi.c:1215
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8186d00c)
Location: drivers/spi/spi.c:1227
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818fcfb6)
Location: drivers/spi/spi.c:1305
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81a4e5b1)
Location: drivers/spi/spi.c:1348
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd5f43)
Location: drivers/spi/spi.c:1463
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _spi_transfer_cs_change_delay(struct spi_message *msg, struct spi_transfer *xfer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2d205)
Location: drivers/spi/spi.c:1463
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_cs_change_delay_exec
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81c2c7a0-ffffffff81c2c83c: _spi_transfer_cs_change_delay (STB_LOCAL)
ffffffff8211e054-ffffffff8211e069: _spi_transfer_cs_change_delay.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _spi_transfer_cs_change_delay(struct spi_message *msg, struct spi_transfer *xfer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cdfc05)
Location: drivers/spi/spi.c:1536
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_cs_change_delay_exec
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81cdf0c0-ffffffff81cdf15c: _spi_transfer_cs_change_delay (STB_LOCAL)
ffffffff821ff5f2-ffffffff821ff607: _spi_transfer_cs_change_delay.cold (STB_LOCAL)
```
</details>
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
In drivers/spi/spi.c (ffff8000109c8c70)
Location: drivers/spi/spi.c:1110
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
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
In drivers/spi/spi.c (c0ab2790)
Location: drivers/spi/spi.c:1110
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a8a6c8)
Location: drivers/spi/spi.c:1110
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000618ec4)
Location: drivers/spi/spi.c:1110
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81779ebf)
Location: drivers/spi/spi.c:1110
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81759c6f)
Location: drivers/spi/spi.c:1110
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817aa25f)
Location: drivers/spi/spi.c:1110
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817c40ff)
Location: drivers/spi/spi.c:1110
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
