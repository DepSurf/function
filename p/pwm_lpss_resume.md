# Function: <code>pwm_lpss_resume</code>

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
int pwm_lpss_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81512440)
Location: drivers/pwm/pwm-lpss.c:233
Inline: False
```
**Symbols:**

```
ffffffff81512440-ffffffff81512484: pwm_lpss_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pwm_lpss_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81527b90)
Location: drivers/pwm/pwm-lpss.c:266
Inline: False
```
**Symbols:**

```
ffffffff81527b90-ffffffff81527bd4: pwm_lpss_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pwm_lpss_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81556e00)
Location: drivers/pwm/pwm-lpss.c:263
Inline: False
```
**Symbols:**

```
ffffffff81556e00-ffffffff81556e3e: pwm_lpss_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pwm_lpss_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81578420)
Location: drivers/pwm/pwm-lpss.c:263
Inline: False
```
**Symbols:**

```
ffffffff81578420-ffffffff8157845e: pwm_lpss_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pwm_lpss_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff8161d3c0)
Location: drivers/pwm/pwm-lpss.c:270
Inline: False
```
**Symbols:**

```
ffffffff8161d3c0-ffffffff8161d3fe: pwm_lpss_resume (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>gcp</code>: ✅</summary>

```c
int pwm_lpss_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff8156c170)
Location: drivers/pwm/pwm-lpss.c:263
Inline: False
```
**Symbols:**

```
ffffffff8156c170-ffffffff8156c1ae: pwm_lpss_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pwm_lpss_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81586670)
Location: drivers/pwm/pwm-lpss.c:263
Inline: False
```
**Symbols:**

```
ffffffff81586670-ffffffff815866ae: pwm_lpss_resume (STB_GLOBAL)
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
