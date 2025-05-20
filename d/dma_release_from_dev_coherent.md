# Function: <code>dma_release_from_dev_coherent</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dma_release_from_dev_coherent(struct device *dev, int order, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffff81123810)
Location: kernel/dma/coherent.c:231
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
ffffffff81123810-ffffffff8112382c: dma_release_from_dev_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int dma_release_from_dev_coherent(struct device *dev, int order, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffff800010195d60)
Location: kernel/dma/coherent.c:221
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
ffff800010195d60-ffff800010195dac: dma_release_from_dev_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_release_from_dev_coherent(struct device *dev, int order, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c03e26e0)
Location: kernel/dma/coherent.c:221
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
c03e26e0-c03e2704: dma_release_from_dev_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_release_from_dev_coherent(struct device *dev, int order, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c0000000001f5eb0)
Location: kernel/dma/coherent.c:221
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
c0000000001f5eb0-c0000000001f5ed0: dma_release_from_dev_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_release_from_dev_coherent(struct device *dev, int order, void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffe000127848)
Location: kernel/dma/coherent.c:221
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
ffffffe000127848-ffffffe000127888: dma_release_from_dev_coherent (STB_GLOBAL)
```
</details>
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
</ul>
<b>Arch</b>
<ul>
</ul>
