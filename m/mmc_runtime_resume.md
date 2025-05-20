# Function: <code>mmc_runtime_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff816c1640)
Location: drivers/mmc/core/bus.c:186
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff816c4b40)
Location: drivers/mmc/core/mmc.c:1941
Inline: True
```
**Symbols:**

```
ffffffff816c1640-ffffffff816c1659: mmc_runtime_resume (STB_LOCAL)
ffffffff816c4b40-ffffffff816c4b8e: mmc_runtime_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81724270)
Location: drivers/mmc/core/bus.c:186
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81727a80)
Location: drivers/mmc/core/mmc.c:2034
Inline: False
```
**Symbols:**

```
ffffffff81724270-ffffffff81724289: mmc_runtime_resume (STB_LOCAL)
ffffffff81727a80-ffffffff81727abf: mmc_runtime_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff817571f0)
Location: drivers/mmc/core/bus.c:186
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff8175a870)
Location: drivers/mmc/core/mmc.c:2054
Inline: False
```
**Symbols:**

```
ffffffff817571f0-ffffffff81757209: mmc_runtime_resume (STB_LOCAL)
ffffffff8175a870-ffffffff8175a8af: mmc_runtime_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81775070)
Location: drivers/mmc/core/bus.c:188
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81779100)
Location: drivers/mmc/core/mmc.c:2081
Inline: False
```
**Symbols:**

```
ffffffff81775070-ffffffff81775089: mmc_runtime_resume (STB_LOCAL)
ffffffff81779100-ffffffff8177913f: mmc_runtime_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff817eb320)
Location: drivers/mmc/core/bus.c:191
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff817ef550)
Location: drivers/mmc/core/mmc.c:2096
Inline: False
```
**Symbols:**

```
ffffffff817eb320-ffffffff817eb33f: mmc_runtime_resume (STB_LOCAL)
ffffffff817ef550-ffffffff817ef58f: mmc_runtime_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff818344c0)
Location: drivers/mmc/core/bus.c:191
Inline: False
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2110
Inline: False
```
**Symbols:**

```
ffffffff818344c0-ffffffff818344df: mmc_runtime_resume (STB_LOCAL)
ffffffff81838390-ffffffff818383c2: mmc_runtime_resume (STB_LOCAL)
ffffffff81838bef-ffffffff81838c06: mmc_runtime_resume.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81860450)
Location: drivers/mmc/core/bus.c:191
Inline: False
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2127
Inline: False
```
**Symbols:**

```
ffffffff81860450-ffffffff8186046f: mmc_runtime_resume (STB_LOCAL)
ffffffff81864380-ffffffff818643b2: mmc_runtime_resume (STB_LOCAL)
ffffffff81864c15-ffffffff81864c2c: mmc_runtime_resume.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff818a4180)
Location: drivers/mmc/core/bus.c:188
Inline: False
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2134
Inline: False
```
**Symbols:**

```
ffffffff818a4180-ffffffff818a419f: mmc_runtime_resume (STB_LOCAL)
ffffffff818a8220-ffffffff818a8244: mmc_runtime_resume (STB_LOCAL)
ffffffff818a8ac2-ffffffff818a8ae4: mmc_runtime_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff818d6600)
Location: drivers/mmc/core/bus.c:188
Inline: False
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2137
Inline: False
```
**Symbols:**

```
ffffffff818d6600-ffffffff818d661f: mmc_runtime_resume (STB_LOCAL)
ffffffff818da680-ffffffff818da6a4: mmc_runtime_resume (STB_LOCAL)
ffffffff818daf16-ffffffff818daf38: mmc_runtime_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff819a8f00)
Location: drivers/mmc/core/bus.c:202
Inline: False
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2146
Inline: False
```
**Symbols:**

```
ffffffff819a8f00-ffffffff819a8f1f: mmc_runtime_resume (STB_LOCAL)
ffffffff819ad0e0-ffffffff819ad107: mmc_runtime_resume (STB_LOCAL)
ffffffff819ad97c-ffffffff819ad99e: mmc_runtime_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff819abd70)
Location: drivers/mmc/core/bus.c:214
Inline: False
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2158
Inline: False
```
**Symbols:**

```
ffffffff819abd70-ffffffff819abd8f: mmc_runtime_resume (STB_LOCAL)
ffffffff819afcc0-ffffffff819afce7: mmc_runtime_resume (STB_LOCAL)
ffffffff81c2ab0e-ffffffff81c2ab30: mmc_runtime_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff819901b0)
Location: drivers/mmc/core/bus.c:214
Inline: False
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2160
Inline: False
```
**Symbols:**

```
ffffffff819901b0-ffffffff819901cf: mmc_runtime_resume (STB_LOCAL)
ffffffff81994490-ffffffff819944b7: mmc_runtime_resume (STB_LOCAL)
ffffffff81c1cf11-ffffffff81c1cf33: mmc_runtime_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81a3b9d0)
Location: drivers/mmc/core/bus.c:212
Inline: False
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2183
Inline: False
```
**Symbols:**

```
ffffffff81a3b9d0-ffffffff81a3b9ef: mmc_runtime_resume (STB_LOCAL)
ffffffff81a401c0-ffffffff81a401e7: mmc_runtime_resume (STB_LOCAL)
ffffffff81d2dd12-ffffffff81d2dd34: mmc_runtime_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81ba8960)
Location: drivers/mmc/core/bus.c:203
Inline: False
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2218
Inline: False
```
**Symbols:**

```
ffffffff81ba8960-ffffffff81ba8985: mmc_runtime_resume (STB_LOCAL)
ffffffff81bad570-ffffffff81bad5a1: mmc_runtime_resume (STB_LOCAL)
ffffffff81efa127-ffffffff81efa149: mmc_runtime_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81d4b220)
Location: drivers/mmc/core/bus.c:203
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81d50bd0)
Location: drivers/mmc/core/mmc.c:2218
Inline: False
```
**Symbols:**

```
ffffffff81d4b220-ffffffff81d4b245: mmc_runtime_resume (STB_LOCAL)
ffffffff81d50bd0-ffffffff81d50c1a: mmc_runtime_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81db5ad0)
Location: drivers/mmc/core/bus.c:203
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81dbb590)
Location: drivers/mmc/core/mmc.c:2218
Inline: False
```
**Symbols:**

```
ffffffff81db5ad0-ffffffff81db5af5: mmc_runtime_resume (STB_LOCAL)
ffffffff81dbb590-ffffffff81dbb5da: mmc_runtime_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81e6df20)
Location: drivers/mmc/core/bus.c:203
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81e73b60)
Location: drivers/mmc/core/mmc.c:2243
Inline: False
```
**Symbols:**

```
ffffffff81e6df20-ffffffff81e6df45: mmc_runtime_resume (STB_LOCAL)
ffffffff81e73b60-ffffffff81e73baa: mmc_runtime_resume (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffff800010b30598)
Location: drivers/mmc/core/bus.c:188
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffff800010b34b40)
Location: drivers/mmc/core/mmc.c:2137
Inline: False
```
**Symbols:**

```
ffff800010b30598-ffff800010b305cc: mmc_runtime_resume (STB_LOCAL)
ffff800010b34b40-ffff800010b34ba4: mmc_runtime_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (c0c0b390)
Location: drivers/mmc/core/bus.c:188
Inline: False
```
```
In drivers/mmc/core/mmc.c (c0c0f65c)
Location: drivers/mmc/core/mmc.c:2137
Inline: False
```
**Symbols:**

```
c0c0b390-c0c0b3b8: mmc_runtime_resume (STB_LOCAL)
c0c0f65c-c0c0f6ac: mmc_runtime_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (c000000000c29e70)
Location: drivers/mmc/core/bus.c:188
Inline: False
```
```
In drivers/mmc/core/mmc.c (c000000000c2f670)
Location: drivers/mmc/core/mmc.c:2137
Inline: False
```
**Symbols:**

```
c000000000c29e70-c000000000c29eb8: mmc_runtime_resume (STB_LOCAL)
c000000000c2f670-c000000000c2f6ec: mmc_runtime_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffe000709118)
Location: drivers/mmc/core/bus.c:188
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffe00070d0ca)
Location: drivers/mmc/core/mmc.c:2137
Inline: False
```
**Symbols:**

```
ffffffe000709118-ffffffe000709144: mmc_runtime_resume (STB_LOCAL)
ffffffe00070d0ca-ffffffe00070d11c: mmc_runtime_resume (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81879fc0)
Location: drivers/mmc/core/bus.c:188
Inline: False
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2137
Inline: False
```
**Symbols:**

```
ffffffff81879fc0-ffffffff81879fdf: mmc_runtime_resume (STB_LOCAL)
ffffffff8187e040-ffffffff8187e064: mmc_runtime_resume (STB_LOCAL)
ffffffff8187e8d6-ffffffff8187e8f8: mmc_runtime_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff818cb460)
Location: drivers/mmc/core/bus.c:188
Inline: False
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2137
Inline: False
```
**Symbols:**

```
ffffffff818cb460-ffffffff818cb47f: mmc_runtime_resume (STB_LOCAL)
ffffffff818cf4e0-ffffffff818cf504: mmc_runtime_resume (STB_LOCAL)
ffffffff818cfd76-ffffffff818cfd98: mmc_runtime_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_runtime_resume(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff818e7f80)
Location: drivers/mmc/core/bus.c:188
Inline: False
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2137
Inline: False
```
**Symbols:**

```
ffffffff818e7f80-ffffffff818e7f9f: mmc_runtime_resume (STB_LOCAL)
ffffffff818ec000-ffffffff818ec024: mmc_runtime_resume (STB_LOCAL)
ffffffff818ec896-ffffffff818ec8b8: mmc_runtime_resume.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
