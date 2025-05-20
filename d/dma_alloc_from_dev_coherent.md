# Function: <code>dma_alloc_from_dev_coherent</code>

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
int dma_alloc_from_dev_coherent(struct device *dev, ssize_t size, dma_addr_t *dma_handle, void **ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffff811237a0)
Location: kernel/dma/coherent.c:182
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffff811237a0-ffffffff811237d4: dma_alloc_from_dev_coherent (STB_GLOBAL)
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
int dma_alloc_from_dev_coherent(struct device *dev, ssize_t size, dma_addr_t *dma_handle, void **ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffff800010195c90)
Location: kernel/dma/coherent.c:171
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffff800010195c90-ffff800010195d08: dma_alloc_from_dev_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_alloc_from_dev_coherent(struct device *dev, ssize_t size, dma_addr_t *dma_handle, void **ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c03e2640)
Location: kernel/dma/coherent.c:171
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
c03e2640-c03e269c: dma_alloc_from_dev_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_alloc_from_dev_coherent(struct device *dev, ssize_t size, dma_addr_t *dma_handle, void **ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c0000000001f5df0)
Location: kernel/dma/coherent.c:171
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
c0000000001f5df0-c0000000001f5e6c: dma_alloc_from_dev_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_alloc_from_dev_coherent(struct device *dev, ssize_t size, dma_addr_t *dma_handle, void **ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffe0001277a0)
Location: kernel/dma/coherent.c:171
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_attrs
```
**Symbols:**

```
ffffffe0001277a0-ffffffe000127802: dma_alloc_from_dev_coherent (STB_GLOBAL)
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
