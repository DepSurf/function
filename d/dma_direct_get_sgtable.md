# Function: <code>dma_direct_get_sgtable</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dma_direct_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113e2c0)
Location: kernel/dma/direct.c:477
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffff8113e2c0-ffffffff8113e378: dma_direct_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dma_direct_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81139620)
Location: kernel/dma/direct.c:433
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffff81139620-ffffffff811396fb: dma_direct_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dma_direct_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113a6f0)
Location: kernel/dma/direct.c:433
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffff8113a6f0-ffffffff8113a7cb: dma_direct_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dma_direct_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8115d620)
Location: kernel/dma/direct.c:473
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffff8115d620-ffffffff8115d6ed: dma_direct_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dma_direct_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81187530)
Location: kernel/dma/direct.c:505
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffff81187530-ffffffff8118760f: dma_direct_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dma_direct_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c3100)
Location: kernel/dma/direct.c:536
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffff811c3100-ffffffff811c31df: dma_direct_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dma_direct_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d5c40)
Location: kernel/dma/direct.c:535
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffff811d5c40-ffffffff811d5d1f: dma_direct_get_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dma_direct_get_sgtable(struct device *dev, struct sg_table *sgt, void *cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811eabc0)
Location: kernel/dma/direct.c:524
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_sgtable_attrs
```
**Symbols:**

```
ffffffff811eabc0-ffffffff811eaca1: dma_direct_get_sgtable (STB_GLOBAL)
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
