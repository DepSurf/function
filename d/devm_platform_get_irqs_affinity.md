# Function: <code>devm_platform_get_irqs_affinity</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int devm_platform_get_irqs_affinity(struct platform_device *dev, struct irq_affinity *affd, unsigned int minvec, unsigned int maxvec, int **irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:351
Inline: False
```
**Symbols:**

```
ffffffff81c0e5ae-ffffffff81c0e5ef: devm_platform_get_irqs_affinity.cold (STB_LOCAL)
ffffffff817d1930-ffffffff817d1b1c: devm_platform_get_irqs_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int devm_platform_get_irqs_affinity(struct platform_device *dev, struct irq_affinity *affd, unsigned int minvec, unsigned int maxvec, int **irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:350
Inline: False
```
**Symbols:**

```
ffffffff81c009c2-ffffffff81c00a02: devm_platform_get_irqs_affinity.cold (STB_LOCAL)
ffffffff817b5360-ffffffff817b554e: devm_platform_get_irqs_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devm_platform_get_irqs_affinity(struct platform_device *dev, struct irq_affinity *affd, unsigned int minvec, unsigned int maxvec, int **irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:330
Inline: False
```
**Symbols:**

```
ffffffff81d0333e-ffffffff81d0337e: devm_platform_get_irqs_affinity.cold (STB_LOCAL)
ffffffff8183e650-ffffffff8183e845: devm_platform_get_irqs_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devm_platform_get_irqs_affinity(struct platform_device *dev, struct irq_affinity *affd, unsigned int minvec, unsigned int maxvec, int **irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:334
Inline: False
```
**Symbols:**

```
ffffffff81ecba99-ffffffff81ecbac1: devm_platform_get_irqs_affinity.cold (STB_LOCAL)
ffffffff819814b0-ffffffff819816d7: devm_platform_get_irqs_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_platform_get_irqs_affinity(struct platform_device *dev, struct irq_affinity *affd, unsigned int minvec, unsigned int maxvec, int **irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aef030)
Location: drivers/base/platform.c:334
Inline: False
```
**Symbols:**

```
ffffffff81aef030-ffffffff81aef27f: devm_platform_get_irqs_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_platform_get_irqs_affinity(struct platform_device *dev, struct irq_affinity *affd, unsigned int minvec, unsigned int maxvec, int **irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3d420)
Location: drivers/base/platform.c:334
Inline: False
```
**Symbols:**

```
ffffffff81b3d420-ffffffff81b3d66f: devm_platform_get_irqs_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_platform_get_irqs_affinity(struct platform_device *dev, struct irq_affinity *affd, unsigned int minvec, unsigned int maxvec, int **irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b94f60)
Location: drivers/base/platform.c:335
Inline: False
```
**Symbols:**

```
ffffffff81b94f60-ffffffff81b951af: devm_platform_get_irqs_affinity (STB_GLOBAL)
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
