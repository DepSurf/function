# Function: <code>sdio_release_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff816cc9a0)
Location: drivers/mmc/core/sdio_irq.c:302
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff816cc9a0-ffffffff816ccb47: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff8172f8d0)
Location: drivers/mmc/core/sdio_irq.c:302
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff8172f8d0-ffffffff8172fa6c: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff817628c0)
Location: drivers/mmc/core/sdio_irq.c:304
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff817628c0-ffffffff81762a4d: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff81781080)
Location: drivers/mmc/core/sdio_irq.c:325
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff81781080-ffffffff817811df: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff817f7650)
Location: drivers/mmc/core/sdio_irq.c:326
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff817f7650-ffffffff817f77b5: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff81840b30)
Location: drivers/mmc/core/sdio_irq.c:326
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff81840b30-ffffffff81840c93: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff8186cae0)
Location: drivers/mmc/core/sdio_irq.c:326
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff8186cae0-ffffffff8186cc43: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:325
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff818b0b76-ffffffff818b0b89: sdio_release_irq.cold (STB_LOCAL)
ffffffff818b0940-ffffffff818b0aab: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff818e2df0)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff818e2df0-ffffffff818e2f59: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff819b5d40)
Location: drivers/mmc/core/sdio_irq.c:343
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff819b5d40-ffffffff819b5e35: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff819b82c0)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff819b82c0-ffffffff819b83b5: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff8199c990)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff8199c990-ffffffff8199caef: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff81d2e80e-ffffffff81d2e82d: sdio_release_irq.cold (STB_LOCAL)
ffffffff81a49370-ffffffff81a494e0: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff81efac7f-ffffffff81efac9e: sdio_release_irq.cold (STB_LOCAL)
ffffffff81bb7650-ffffffff81bb77d7: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff820a9b85-ffffffff820a9ba4: sdio_release_irq.cold (STB_LOCAL)
ffffffff81d5c200-ffffffff81d5c387: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff8212af5e-ffffffff8212af7d: sdio_release_irq.cold (STB_LOCAL)
ffffffff81dc6c70-ffffffff81dc6df2: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff8220cd1b-ffffffff8220cd3a: sdio_release_irq.cold (STB_LOCAL)
ffffffff81e7f5b0-ffffffff81e7f732: sdio_release_irq (STB_GLOBAL)
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
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffff800010b3d680)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffff800010b3d680-ffff800010b3d7ec: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (c0c17c88)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
c0c17c88-c0c17e28: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (c000000000c3ab50)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
c000000000c3ab50-c000000000c3ad40: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffe0007147a2)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffe0007147a2-ffffffe0007148b2: sdio_release_irq (STB_GLOBAL)
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
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff818867b0)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff818867b0-ffffffff81886919: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff818d7c50)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff818d7c50-ffffffff818d7db9: sdio_release_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sdio_release_irq(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff818f4770)
Location: drivers/mmc/core/sdio_irq.c:342
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
**Symbols:**

```
ffffffff818f4770-ffffffff818f48d9: sdio_release_irq (STB_GLOBAL)
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
