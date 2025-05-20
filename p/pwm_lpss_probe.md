# Function: <code>pwm_lpss_probe</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pwm_lpss_chip *pwm_lpss_probe(struct device *dev, struct resource *r, const struct pwm_lpss_boardinfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81512490)
Location: drivers/pwm/pwm-lpss.c:176
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
**Symbols:**

```
ffffffff81512490-ffffffff81512559: pwm_lpss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pwm_lpss_chip *pwm_lpss_probe(struct device *dev, struct resource *r, const struct pwm_lpss_boardinfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81527be0)
Location: drivers/pwm/pwm-lpss.c:203
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
**Symbols:**

```
ffffffff81527be0-ffffffff81527ca9: pwm_lpss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pwm_lpss_chip *pwm_lpss_probe(struct device *dev, struct resource *r, const struct pwm_lpss_boardinfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:200
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
**Symbols:**

```
ffffffff81557308-ffffffff8155733f: pwm_lpss_probe.cold (STB_LOCAL)
ffffffff81556e40-ffffffff81556f04: pwm_lpss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct pwm_lpss_chip *pwm_lpss_probe(struct device *dev, struct resource *r, const struct pwm_lpss_boardinfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:200
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
**Symbols:**

```
ffffffff81578948-ffffffff81578965: pwm_lpss_probe.cold (STB_LOCAL)
ffffffff81578460-ffffffff81578541: pwm_lpss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct pwm_lpss_chip *pwm_lpss_probe(struct device *dev, struct resource *r, const struct pwm_lpss_boardinfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:200
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
**Symbols:**

```
ffffffff8161d979-ffffffff8161d992: pwm_lpss_probe.cold (STB_LOCAL)
ffffffff8161d560-ffffffff8161d67f: pwm_lpss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct pwm_lpss_chip *pwm_lpss_probe(struct device *dev, struct resource *r, const struct pwm_lpss_boardinfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:210
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
**Symbols:**

```
ffffffff81bf6de2-ffffffff81bf6dfb: pwm_lpss_probe.cold (STB_LOCAL)
ffffffff81643da0-ffffffff81643ec3: pwm_lpss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct pwm_lpss_chip *pwm_lpss_probe(struct device *dev, struct resource *r, const struct pwm_lpss_boardinfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:210
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
**Symbols:**

```
ffffffff81be8c51-ffffffff81be8c6a: pwm_lpss_probe.cold (STB_LOCAL)
ffffffff81626b60-ffffffff81626c7a: pwm_lpss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct pwm_lpss_chip *pwm_lpss_probe(struct device *dev, struct resource *r, const struct pwm_lpss_boardinfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:210
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
**Symbols:**

```
ffffffff81ce2f5a-ffffffff81ce2f73: pwm_lpss_probe.cold (STB_LOCAL)
ffffffff816963f0-ffffffff8169650d: pwm_lpss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct pwm_lpss_chip *pwm_lpss_probe(struct device *dev, struct resource *r, const struct pwm_lpss_boardinfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:210
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
**Symbols:**

```
ffffffff81ea9a46-ffffffff81ea9a5f: pwm_lpss_probe.cold (STB_LOCAL)
ffffffff817b7270-ffffffff817b73a6: pwm_lpss_probe (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct pwm_lpss_chip *pwm_lpss_probe(struct device *dev, struct resource *r, const struct pwm_lpss_boardinfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:200
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
**Symbols:**

```
ffffffff8156c698-ffffffff8156c6b5: pwm_lpss_probe.cold (STB_LOCAL)
ffffffff8156c1b0-ffffffff8156c291: pwm_lpss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct pwm_lpss_chip *pwm_lpss_probe(struct device *dev, struct resource *r, const struct pwm_lpss_boardinfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:200
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
**Symbols:**

```
ffffffff81586b98-ffffffff81586bb5: pwm_lpss_probe.cold (STB_LOCAL)
ffffffff815866b0-ffffffff81586791: pwm_lpss_probe (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
