# Function: <code>pwm_lpss_prepare</code>

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
In drivers/pwm/pwm-lpss.c (ffffffff81512570)
Location: drivers/pwm/pwm-lpss.c:94
Inline: True
```
**Symbols:**

```
ffffffff81512570-ffffffff8151260c: pwm_lpss_prepare.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip *lpwm, struct pwm_device *pwm, int duty_ns, int period_ns);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81527d10)
Location: drivers/pwm/pwm-lpss.c:85
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff815281a0)
Location: drivers/pwm/pwm-lpss-platform.c:79
Inline: False
```
**Symbols:**

```
ffffffff81527d10-ffffffff81527dc8: pwm_lpss_prepare.isra.4 (STB_LOCAL)
ffffffff815281a0-ffffffff815281c0: pwm_lpss_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip *lpwm, struct pwm_device *pwm, int duty_ns, int period_ns);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81556f70)
Location: drivers/pwm/pwm-lpss.c:82
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81557430)
Location: drivers/pwm/pwm-lpss-platform.c:76
Inline: False
```
**Symbols:**

```
ffffffff81556f70-ffffffff81557028: pwm_lpss_prepare.isra.0 (STB_LOCAL)
ffffffff81557430-ffffffff8155744d: pwm_lpss_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip *lpwm, struct pwm_device *pwm, int duty_ns, int period_ns);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff815785b0)
Location: drivers/pwm/pwm-lpss.c:82
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81578a60)
Location: drivers/pwm/pwm-lpss-platform.c:76
Inline: False
```
**Symbols:**

```
ffffffff815785b0-ffffffff81578668: pwm_lpss_prepare.isra.0 (STB_LOCAL)
ffffffff81578a60-ffffffff81578a7d: pwm_lpss_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip *lpwm, struct pwm_device *pwm, int duty_ns, int period_ns);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff8161d6f0)
Location: drivers/pwm/pwm-lpss.c:82
Inline: True
Direct callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8161da70)
Location: drivers/pwm/pwm-lpss-platform.c:76
Inline: False
```
**Symbols:**

```
ffffffff8161d6f0-ffffffff8161d7ad: pwm_lpss_prepare.isra.0 (STB_LOCAL)
ffffffff8161da70-ffffffff8161da8d: pwm_lpss_prepare (STB_LOCAL)
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
In drivers/pwm/pwm-lpss.c (ffffffff81643f8b)
Location: drivers/pwm/pwm-lpss.c:87
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
In drivers/pwm/pwm-lpss.c (ffffffff81626cdb)
Location: drivers/pwm/pwm-lpss.c:87
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
In drivers/pwm/pwm-lpss.c (ffffffff81696540)
Location: drivers/pwm/pwm-lpss.c:87
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
In drivers/pwm/pwm-lpss.c (ffffffff817b73e0)
Location: drivers/pwm/pwm-lpss.c:87
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
In drivers/pwm/pwm-lpss.c (ffffffff818d1ac0)
Location: drivers/pwm/pwm-lpss.c:124
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
In drivers/pwm/pwm-lpss.c (ffffffff81914ab0)
Location: drivers/pwm/pwm-lpss.c:124
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
In drivers/pwm/pwm-lpss.c (ffffffff8195ca20)
Location: drivers/pwm/pwm-lpss.c:124
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
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip *lpwm, struct pwm_device *pwm, int duty_ns, int period_ns);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff8156c300)
Location: drivers/pwm/pwm-lpss.c:82
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8156c7b0)
Location: drivers/pwm/pwm-lpss-platform.c:76
Inline: False
```
**Symbols:**

```
ffffffff8156c300-ffffffff8156c3b8: pwm_lpss_prepare.isra.0 (STB_LOCAL)
ffffffff8156c7b0-ffffffff8156c7cd: pwm_lpss_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void pwm_lpss_prepare(struct pwm_lpss_chip *lpwm, struct pwm_device *pwm, int duty_ns, int period_ns);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81586800)
Location: drivers/pwm/pwm-lpss.c:82
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81586cb0)
Location: drivers/pwm/pwm-lpss-platform.c:76
Inline: False
```
**Symbols:**

```
ffffffff81586800-ffffffff815868b8: pwm_lpss_prepare.isra.0 (STB_LOCAL)
ffffffff81586cb0-ffffffff81586ccd: pwm_lpss_prepare (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
