# Function: <code>spi_set_cs_timing</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device *spi, u8 setup, u8 hold, u8 inactive_dly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8178c990)
Location: drivers/spi/spi.c:3118
Inline: False
```
**Symbols:**

```
ffffffff8178c990-ffffffff8178c9be: spi_set_cs_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device *spi, u8 setup, u8 hold, u8 inactive_dly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b05a0)
Location: drivers/spi/spi.c:3122
Inline: False
```
**Symbols:**

```
ffffffff817b05a0-ffffffff817b05ce: spi_set_cs_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int spi_set_cs_timing(struct spi_device *spi, struct spi_delay *setup, struct spi_delay *hold, struct spi_delay *inactive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3353
Inline: False
```
**Symbols:**

```
ffffffff8187d0a0-ffffffff8187d0b6: spi_set_cs_timing.cold (STB_LOCAL)
ffffffff81877ee0-ffffffff81877fa5: spi_set_cs_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int spi_set_cs_timing(struct spi_device *spi, struct spi_delay *setup, struct spi_delay *hold, struct spi_delay *inactive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3449
Inline: False
```
**Symbols:**

```
ffffffff81c18b03-ffffffff81c18b19: spi_set_cs_timing.cold (STB_LOCAL)
ffffffff818867f0-ffffffff818868b5: spi_set_cs_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int spi_set_cs_timing(struct spi_device *spi, struct spi_delay *setup, struct spi_delay *hold, struct spi_delay *inactive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3467
Inline: False
```
**Symbols:**

```
ffffffff81c0a8f7-ffffffff81c0a911: spi_set_cs_timing.cold (STB_LOCAL)
ffffffff81869040-ffffffff81869228: spi_set_cs_timing (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd7717)
Location: drivers/spi/spi.c:3643
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2e163)
Location: drivers/spi/spi.c:3698
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81ce0bb3)
Location: drivers/spi/spi.c:3864
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
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
void spi_set_cs_timing(struct spi_device *spi, u8 setup, u8 hold, u8 inactive_dly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c1b00)
Location: drivers/spi/spi.c:3122
Inline: False
```
**Symbols:**

```
ffff8000109c1b00-ffff8000109c1b58: spi_set_cs_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device *spi, u8 setup, u8 hold, u8 inactive_dly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0aad3f0)
Location: drivers/spi/spi.c:3122
Inline: False
```
**Symbols:**

```
c0aad3f0-c0aad41c: spi_set_cs_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device *spi, u8 setup, u8 hold, u8 inactive_dly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a82d40)
Location: drivers/spi/spi.c:3122
Inline: False
```
**Symbols:**

```
c000000000a82d40-c000000000a82d8c: spi_set_cs_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device *spi, u8 setup, u8 hold, u8 inactive_dly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe0006140c2)
Location: drivers/spi/spi.c:3122
Inline: False
```
**Symbols:**

```
ffffffe0006140c2-ffffffe000614108: spi_set_cs_timing (STB_GLOBAL)
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
void spi_set_cs_timing(struct spi_device *spi, u8 setup, u8 hold, u8 inactive_dly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81775080)
Location: drivers/spi/spi.c:3122
Inline: False
```
**Symbols:**

```
ffffffff81775080-ffffffff817750ae: spi_set_cs_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device *spi, u8 setup, u8 hold, u8 inactive_dly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81754e30)
Location: drivers/spi/spi.c:3122
Inline: False
```
**Symbols:**

```
ffffffff81754e30-ffffffff81754e5e: spi_set_cs_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device *spi, u8 setup, u8 hold, u8 inactive_dly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817a5420)
Location: drivers/spi/spi.c:3122
Inline: False
```
**Symbols:**

```
ffffffff817a5420-ffffffff817a544e: spi_set_cs_timing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device *spi, u8 setup, u8 hold, u8 inactive_dly);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817bf2a0)
Location: drivers/spi/spi.c:3122
Inline: False
```
**Symbols:**

```
ffffffff817bf2a0-ffffffff817bf2ce: spi_set_cs_timing (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct spi_delay *inactive</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 inactive_dly</code>
</li>
<li>
<b>Param type changed. </b>
<code>u8 setup</code> ➡️ <code>struct spi_delay *setup</code>
</li>
<li>
<b>Param type changed. </b>
<code>u8 hold</code> ➡️ <code>struct spi_delay *hold</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
