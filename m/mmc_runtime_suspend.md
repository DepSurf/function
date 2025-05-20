# Function: <code>mmc_runtime_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff816c1620)
Location: drivers/mmc/core/bus.c:178
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff816c4bf0)
Location: drivers/mmc/core/mmc.c:1923
Inline: True
```
**Symbols:**

```
ffffffff816c1620-ffffffff816c1639: mmc_runtime_suspend (STB_LOCAL)
ffffffff816c4bf0-ffffffff816c4c46: mmc_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81724250)
Location: drivers/mmc/core/bus.c:178
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81727bb0)
Location: drivers/mmc/core/mmc.c:2016
Inline: True
```
**Symbols:**

```
ffffffff81724250-ffffffff81724269: mmc_runtime_suspend (STB_LOCAL)
ffffffff81727bb0-ffffffff81727c04: mmc_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff817571d0)
Location: drivers/mmc/core/bus.c:178
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff8175ac20)
Location: drivers/mmc/core/mmc.c:2036
Inline: True
```
**Symbols:**

```
ffffffff817571d0-ffffffff817571e9: mmc_runtime_suspend (STB_LOCAL)
ffffffff8175ac20-ffffffff8175ac74: mmc_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81775050)
Location: drivers/mmc/core/bus.c:180
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81776fd0)
Location: drivers/mmc/core/mmc.c:2063
Inline: True
```
**Symbols:**

```
ffffffff81775050-ffffffff81775069: mmc_runtime_suspend (STB_LOCAL)
ffffffff81776fd0-ffffffff81777024: mmc_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff817eb300)
Location: drivers/mmc/core/bus.c:183
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff817ed3e0)
Location: drivers/mmc/core/mmc.c:2078
Inline: True
```
**Symbols:**

```
ffffffff817eb300-ffffffff817eb31f: mmc_runtime_suspend (STB_LOCAL)
ffffffff817ed3e0-ffffffff817ed434: mmc_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff818344a0)
Location: drivers/mmc/core/bus.c:183
Inline: False
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2092
Inline: True
```
**Symbols:**

```
ffffffff818344a0-ffffffff818344bf: mmc_runtime_suspend (STB_LOCAL)
ffffffff81836510-ffffffff8183654a: mmc_runtime_suspend (STB_LOCAL)
ffffffff818387e3-ffffffff81838806: mmc_runtime_suspend.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81860430)
Location: drivers/mmc/core/bus.c:183
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81862528)
Location: drivers/mmc/core/mmc.c:2109
Inline: True
```
**Symbols:**

```
ffffffff81860430-ffffffff8186044f: mmc_runtime_suspend (STB_LOCAL)
ffffffff81862500-ffffffff8186253a: mmc_runtime_suspend (STB_LOCAL)
ffffffff818647e3-ffffffff81864806: mmc_runtime_suspend.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff818a4160)
Location: drivers/mmc/core/bus.c:180
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff818a6678)
Location: drivers/mmc/core/mmc.c:2116
Inline: True
```
**Symbols:**

```
ffffffff818a4160-ffffffff818a417f: mmc_runtime_suspend (STB_LOCAL)
ffffffff818a6650-ffffffff818a668a: mmc_runtime_suspend (STB_LOCAL)
ffffffff818a87d3-ffffffff818a87f6: mmc_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff818d65e0)
Location: drivers/mmc/core/bus.c:180
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff818d8ad8)
Location: drivers/mmc/core/mmc.c:2119
Inline: True
```
**Symbols:**

```
ffffffff818d65e0-ffffffff818d65ff: mmc_runtime_suspend (STB_LOCAL)
ffffffff818d8ab0-ffffffff818d8aea: mmc_runtime_suspend (STB_LOCAL)
ffffffff818dac2e-ffffffff818dac51: mmc_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff819a8ee0)
Location: drivers/mmc/core/bus.c:194
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff819ab7a8)
Location: drivers/mmc/core/mmc.c:2128
Inline: True
```
**Symbols:**

```
ffffffff819a8ee0-ffffffff819a8eff: mmc_runtime_suspend (STB_LOCAL)
ffffffff819ab780-ffffffff819ab7ba: mmc_runtime_suspend (STB_LOCAL)
ffffffff819ad6eb-ffffffff819ad70e: mmc_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff819abd50)
Location: drivers/mmc/core/bus.c:206
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff819ae358)
Location: drivers/mmc/core/mmc.c:2140
Inline: True
```
**Symbols:**

```
ffffffff819abd50-ffffffff819abd6f: mmc_runtime_suspend (STB_LOCAL)
ffffffff819ae330-ffffffff819ae36a: mmc_runtime_suspend (STB_LOCAL)
ffffffff81c2a880-ffffffff81c2a8a3: mmc_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81990190)
Location: drivers/mmc/core/bus.c:206
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81992988)
Location: drivers/mmc/core/mmc.c:2142
Inline: True
```
**Symbols:**

```
ffffffff81990190-ffffffff819901af: mmc_runtime_suspend (STB_LOCAL)
ffffffff81992960-ffffffff8199299a: mmc_runtime_suspend (STB_LOCAL)
ffffffff81c1cc38-ffffffff81c1cc5b: mmc_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81a3b9b0)
Location: drivers/mmc/core/bus.c:204
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81a3e488)
Location: drivers/mmc/core/mmc.c:2165
Inline: True
```
**Symbols:**

```
ffffffff81a3b9b0-ffffffff81a3b9cf: mmc_runtime_suspend (STB_LOCAL)
ffffffff81a3e460-ffffffff81a3e49a: mmc_runtime_suspend (STB_LOCAL)
ffffffff81d2d93c-ffffffff81d2d95f: mmc_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81ba8930)
Location: drivers/mmc/core/bus.c:195
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81bab7a2)
Location: drivers/mmc/core/mmc.c:2200
Inline: True
```
**Symbols:**

```
ffffffff81ba8930-ffffffff81ba8955: mmc_runtime_suspend (STB_LOCAL)
ffffffff81bab770-ffffffff81bab7b4: mmc_runtime_suspend (STB_LOCAL)
ffffffff81ef9d4e-ffffffff81ef9d71: mmc_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81d4b1e0)
Location: drivers/mmc/core/bus.c:195
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81d4eb10)
Location: drivers/mmc/core/mmc.c:2200
Inline: True
```
**Symbols:**

```
ffffffff81d4b1e0-ffffffff81d4b205: mmc_runtime_suspend (STB_LOCAL)
ffffffff81d4eb10-ffffffff81d4eb8d: mmc_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81db5a90)
Location: drivers/mmc/core/bus.c:195
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81db9420)
Location: drivers/mmc/core/mmc.c:2200
Inline: True
```
**Symbols:**

```
ffffffff81db5a90-ffffffff81db5ab5: mmc_runtime_suspend (STB_LOCAL)
ffffffff81db9420-ffffffff81db949d: mmc_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81e6dee0)
Location: drivers/mmc/core/bus.c:195
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff81e71a20)
Location: drivers/mmc/core/mmc.c:2225
Inline: True
```
**Symbols:**

```
ffffffff81e6dee0-ffffffff81e6df05: mmc_runtime_suspend (STB_LOCAL)
ffffffff81e71a20-ffffffff81e71a9d: mmc_runtime_suspend (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffff800010b30560)
Location: drivers/mmc/core/bus.c:180
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffff800010b33148)
Location: drivers/mmc/core/mmc.c:2119
Inline: True
```
**Symbols:**

```
ffff800010b30560-ffff800010b30594: mmc_runtime_suspend (STB_LOCAL)
ffff800010b33148-ffff800010b331b4: mmc_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (c0c0b368)
Location: drivers/mmc/core/bus.c:180
Inline: False
```
```
In drivers/mmc/core/mmc.c (c0c0dbac)
Location: drivers/mmc/core/mmc.c:2119
Inline: True
```
**Symbols:**

```
c0c0b368-c0c0b390: mmc_runtime_suspend (STB_LOCAL)
c0c0dbac-c0c0dc0c: mmc_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (c000000000c29e20)
Location: drivers/mmc/core/bus.c:180
Inline: False
```
```
In drivers/mmc/core/mmc.c (c000000000c2d5b0)
Location: drivers/mmc/core/mmc.c:2119
Inline: True
```
**Symbols:**

```
c000000000c29e20-c000000000c29e68: mmc_runtime_suspend (STB_LOCAL)
c000000000c2d5b0-c000000000c2d658: mmc_runtime_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffe0007090ec)
Location: drivers/mmc/core/bus.c:180
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffe00070b878)
Location: drivers/mmc/core/mmc.c:2119
Inline: True
```
**Symbols:**

```
ffffffe0007090ec-ffffffe000709118: mmc_runtime_suspend (STB_LOCAL)
ffffffe00070b878-ffffffe00070b8d6: mmc_runtime_suspend (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81879fa0)
Location: drivers/mmc/core/bus.c:180
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff8187c498)
Location: drivers/mmc/core/mmc.c:2119
Inline: True
```
**Symbols:**

```
ffffffff81879fa0-ffffffff81879fbf: mmc_runtime_suspend (STB_LOCAL)
ffffffff8187c470-ffffffff8187c4aa: mmc_runtime_suspend (STB_LOCAL)
ffffffff8187e5ee-ffffffff8187e611: mmc_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff818cb440)
Location: drivers/mmc/core/bus.c:180
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff818cd938)
Location: drivers/mmc/core/mmc.c:2119
Inline: True
```
**Symbols:**

```
ffffffff818cb440-ffffffff818cb45f: mmc_runtime_suspend (STB_LOCAL)
ffffffff818cd910-ffffffff818cd94a: mmc_runtime_suspend (STB_LOCAL)
ffffffff818cfa8e-ffffffff818cfab1: mmc_runtime_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int mmc_runtime_suspend(struct device *dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff818e7f60)
Location: drivers/mmc/core/bus.c:180
Inline: False
```
```
In drivers/mmc/core/mmc.c (ffffffff818ea458)
Location: drivers/mmc/core/mmc.c:2119
Inline: True
```
**Symbols:**

```
ffffffff818e7f60-ffffffff818e7f7f: mmc_runtime_suspend (STB_LOCAL)
ffffffff818ea430-ffffffff818ea46a: mmc_runtime_suspend (STB_LOCAL)
ffffffff818ec5ae-ffffffff818ec5d1: mmc_runtime_suspend.cold (STB_LOCAL)
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
