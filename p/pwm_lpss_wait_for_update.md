# Function: <code>pwm_lpss_wait_for_update</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81512610)
Location: drivers/pwm/pwm-lpss.c:63
Inline: True
```
**Symbols:**

```
ffffffff81512610-ffffffff81512695: pwm_lpss_wait_for_update.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81527e90)
Location: drivers/pwm/pwm-lpss.c:54
Inline: True
```
**Symbols:**

```
ffffffff81527e90-ffffffff81527f15: pwm_lpss_wait_for_update.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff8155733f)
Location: drivers/pwm/pwm-lpss.c:51
Inline: True
```
**Symbols:**

```
ffffffff815570f0-ffffffff81557160: pwm_lpss_wait_for_update.isra.0 (STB_LOCAL)
ffffffff8155733f-ffffffff8155735c: pwm_lpss_wait_for_update.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81578965)
Location: drivers/pwm/pwm-lpss.c:51
Inline: True
```
**Symbols:**

```
ffffffff81578730-ffffffff815787a0: pwm_lpss_wait_for_update.isra.0 (STB_LOCAL)
ffffffff81578965-ffffffff81578982: pwm_lpss_wait_for_update.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pwm_lpss_wait_for_update(struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:51
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
**Symbols:**

```
ffffffff8161d4e0-ffffffff8161d552: pwm_lpss_wait_for_update (STB_LOCAL)
ffffffff8161d95b-ffffffff8161d979: pwm_lpss_wait_for_update.cold (STB_LOCAL)
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
In drivers/pwm/pwm-lpss.c (ffffffff8164406f)
Location: drivers/pwm/pwm-lpss.c:51
Inline: True
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
In drivers/pwm/pwm-lpss.c (ffffffff81626dc4)
Location: drivers/pwm/pwm-lpss.c:51
Inline: True
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
In drivers/pwm/pwm-lpss.c (ffffffff81696640)
Location: drivers/pwm/pwm-lpss.c:51
Inline: True
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
In drivers/pwm/pwm-lpss.c (ffffffff817b74e0)
Location: drivers/pwm/pwm-lpss.c:51
Inline: True
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
In drivers/pwm/pwm-lpss.c (ffffffff818d1ba5)
Location: drivers/pwm/pwm-lpss.c:88
Inline: True
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
In drivers/pwm/pwm-lpss.c (ffffffff81914b95)
Location: drivers/pwm/pwm-lpss.c:88
Inline: True
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
In drivers/pwm/pwm-lpss.c (ffffffff8195cb05)
Location: drivers/pwm/pwm-lpss.c:88
Inline: True
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
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff8156c6b5)
Location: drivers/pwm/pwm-lpss.c:51
Inline: True
```
**Symbols:**

```
ffffffff8156c480-ffffffff8156c4f0: pwm_lpss_wait_for_update.isra.0 (STB_LOCAL)
ffffffff8156c6b5-ffffffff8156c6d2: pwm_lpss_wait_for_update.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81586bb5)
Location: drivers/pwm/pwm-lpss.c:51
Inline: True
```
**Symbols:**

```
ffffffff81586980-ffffffff815869eb: pwm_lpss_wait_for_update.isra.0 (STB_LOCAL)
ffffffff81586bb5-ffffffff81586bd2: pwm_lpss_wait_for_update.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
