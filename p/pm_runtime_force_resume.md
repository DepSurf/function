# Function: <code>pm_runtime_force_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81557730)
Location: drivers/base/power/runtime.c:1483
Inline: False
```
**Symbols:**

```
ffffffff81557730-ffffffff8155778a: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a97c0)
Location: drivers/base/power/runtime.c:1501
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_restore_noirq
  - drivers/base/power/domain.c:pm_genpd_thaw_noirq
  - drivers/base/power/domain.c:pm_genpd_resume_noirq
```
**Symbols:**

```
ffffffff815a97c0-ffffffff815a9846: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d8560)
Location: drivers/base/power/runtime.c:1691
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_restore_noirq
  - drivers/base/power/domain.c:pm_genpd_thaw_noirq
  - drivers/base/power/domain.c:pm_genpd_resume_noirq
```
**Symbols:**

```
ffffffff815d8560-ffffffff815d8640: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ecb30)
Location: drivers/base/power/runtime.c:1691
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_restore_noirq
  - drivers/base/power/domain.c:pm_genpd_thaw_noirq
  - drivers/base/power/domain.c:pm_genpd_resume_noirq
```
**Symbols:**

```
ffffffff815ecb30-ffffffff815ecc00: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81653ee0)
Location: drivers/base/power/runtime.c:1682
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
```
**Symbols:**

```
ffffffff81653ee0-ffffffff81653fb2: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168ed60)
Location: drivers/base/power/runtime.c:1688
Inline: False
```
**Symbols:**

```
ffffffff8168ed60-ffffffff8168ee27: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816af090)
Location: drivers/base/power/runtime.c:1696
Inline: False
```
**Symbols:**

```
ffffffff816af090-ffffffff816af155: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e9a30)
Location: drivers/base/power/runtime.c:1781
Inline: False
```
**Symbols:**

```
ffffffff816e9a30-ffffffff816e9ae0: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170da90)
Location: drivers/base/power/runtime.c:1786
Inline: False
```
**Symbols:**

```
ffffffff8170da90-ffffffff8170db40: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c97c0)
Location: drivers/base/power/runtime.c:1811
Inline: False
```
**Symbols:**

```
ffffffff817c97c0-ffffffff817c98b1: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817de2c0)
Location: drivers/base/power/runtime.c:1832
Inline: False
```
**Symbols:**

```
ffffffff817de2c0-ffffffff817de3b1: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c26c0)
Location: drivers/base/power/runtime.c:1835
Inline: False
```
**Symbols:**

```
ffffffff817c26c0-ffffffff817c2794: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184c280)
Location: drivers/base/power/runtime.c:1869
Inline: False
```
**Symbols:**

```
ffffffff8184c280-ffffffff8184c354: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81991c50)
Location: drivers/base/power/runtime.c:1902
Inline: False
```
**Symbols:**

```
ffffffff81991c50-ffffffff81991d1d: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b020c0)
Location: drivers/base/power/runtime.c:1920
Inline: False
```
**Symbols:**

```
ffffffff81b020c0-ffffffff81b021a5: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b501b0)
Location: drivers/base/power/runtime.c:1924
Inline: False
```
**Symbols:**

```
ffffffff81b501b0-ffffffff81b50295: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba8730)
Location: drivers/base/power/runtime.c:1925
Inline: False
```
**Symbols:**

```
ffffffff81ba8730-ffffffff81ba8815: pm_runtime_force_resume (STB_GLOBAL)
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
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fd0b0)
Location: drivers/base/power/runtime.c:1786
Inline: False
Direct callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_resume
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_resume_noirq
```
**Symbols:**

```
ffff8000108fd0b0-ffff8000108fd16c: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e8750)
Location: drivers/base/power/runtime.c:1786
Inline: False
Direct callers:
  - drivers/bus/ti-sysc.c:sysc_noirq_resume
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_resume
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_resume
```
**Symbols:**

```
c09e8750-c09e8814: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c000000000999910)
Location: drivers/base/power/runtime.c:1786
Inline: False
```
**Symbols:**

```
c000000000999910-c000000000999a10: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058bf14)
Location: drivers/base/power/runtime.c:1786
Inline: False
```
**Symbols:**

```
ffffffe00058bf14-ffffffe00058bfbe: pm_runtime_force_resume (STB_GLOBAL)
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
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d31e0)
Location: drivers/base/power/runtime.c:1786
Inline: False
```
**Symbols:**

```
ffffffff816d31e0-ffffffff816d3290: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ae4d0)
Location: drivers/base/power/runtime.c:1786
Inline: False
```
**Symbols:**

```
ffffffff816ae4d0-ffffffff816ae580: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81701750)
Location: drivers/base/power/runtime.c:1786
Inline: False
```
**Symbols:**

```
ffffffff81701750-ffffffff81701800: pm_runtime_force_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pm_runtime_force_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171c510)
Location: drivers/base/power/runtime.c:1786
Inline: False
```
**Symbols:**

```
ffffffff8171c510-ffffffff8171c5c0: pm_runtime_force_resume (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
