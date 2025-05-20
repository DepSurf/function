# Function: <code>scaled_ppm_to_ppb</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff817decc7)
Location: drivers/ptp/ptp_clock.c:79
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8180a107)
Location: drivers/ptp/ptp_clock.c:79
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8184be8e)
Location: drivers/ptp/ptp_clock.c:66
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
**Symbols:**

```
ffffffff8184bce0-ffffffff8184bd01: scaled_ppm_to_ppb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8187d6be)
Location: drivers/ptp/ptp_clock.c:66
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
**Symbols:**

```
ffffffff8187d4f0-ffffffff8187d511: scaled_ppm_to_ppb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8194baeb)
Location: drivers/ptp/ptp_clock.c:66
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
**Symbols:**

```
ffffffff8194b8c0-ffffffff8194b8e1: scaled_ppm_to_ppb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff819514fb)
Location: drivers/ptp/ptp_clock.c:66
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
**Symbols:**

```
ffffffff819512d0-ffffffff819512f1: scaled_ppm_to_ppb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int scaled_ppm_to_ppb(long int ppm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8193537b)
Location: drivers/ptp/ptp_clock.c:66
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
**Symbols:**

```
ffffffff81935150-ffffffff81935171: scaled_ppm_to_ppb (STB_GLOBAL)
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
In drivers/ptp/ptp_clock.c (ffffffff819d8a14)
Location: include/linux/ptp_clock_kernel.h:197
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In drivers/ptp/ptp_clock.c (ffffffff81b3bed0)
Location: include/linux/ptp_clock_kernel.h:228
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In drivers/ptp/ptp_clock.c (ffffffff81cd1e24)
Location: include/linux/ptp_clock_kernel.h:223
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In drivers/ptp/ptp_clock.c (ffffffff81d3986c)
Location: include/linux/ptp_clock_kernel.h:230
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In drivers/ptp/ptp_clock.c (ffffffff81defc2c)
Location: include/linux/ptp_clock_kernel.h:230
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
s32 scaled_ppm_to_ppb(long int ppm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffff800010ac6f68)
Location: drivers/ptp/ptp_clock.c:66
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
**Symbols:**

```
ffff800010ac6d10-ffff800010ac6d48: scaled_ppm_to_ppb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (c0ba69dc)
Location: drivers/ptp/ptp_clock.c:66
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
**Symbols:**

```
c0ba67e0-c0ba680c: scaled_ppm_to_ppb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (c000000000ba869c)
Location: drivers/ptp/ptp_clock.c:66
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
**Symbols:**

```
c000000000ba83c0-c000000000ba83dc: scaled_ppm_to_ppb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffe0006c59c0)
Location: drivers/ptp/ptp_clock.c:66
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
**Symbols:**

```
ffffffe0006c57b4-ffffffe0006c57e6: scaled_ppm_to_ppb (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81825c2e)
Location: drivers/ptp/ptp_clock.c:66
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
**Symbols:**

```
ffffffff81825a60-ffffffff81825a81: scaled_ppm_to_ppb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff817ed2be)
Location: drivers/ptp/ptp_clock.c:66
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
**Symbols:**

```
ffffffff817ed0f0-ffffffff817ed111: scaled_ppm_to_ppb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81872b6e)
Location: drivers/ptp/ptp_clock.c:66
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
**Symbols:**

```
ffffffff818729a0-ffffffff818729c1: scaled_ppm_to_ppb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8188e51e)
Location: drivers/ptp/ptp_clock.c:66
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
**Symbols:**

```
ffffffff8188e350-ffffffff8188e371: scaled_ppm_to_ppb (STB_GLOBAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>s32</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
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
