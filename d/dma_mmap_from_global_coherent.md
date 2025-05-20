# Function: <code>dma_mmap_from_global_coherent</code>

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
int dma_mmap_from_global_coherent(struct vm_area_struct *vma, void *vaddr, size_t size, int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffff81123860)
Location: kernel/dma/coherent.c:293
Inline: False
```
**Symbols:**

```
ffffffff81123860-ffffffff8112388e: dma_mmap_from_global_coherent (STB_GLOBAL)
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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:202
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:202
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:216
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:217
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:212
Inline: True
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
int dma_mmap_from_global_coherent(struct vm_area_struct *vma, void *vaddr, size_t size, int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffff800010195e68)
Location: kernel/dma/coherent.c:282
Inline: False
```
**Symbols:**

```
ffff800010195e68-ffff800010195ed4: dma_mmap_from_global_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_mmap_from_global_coherent(struct vm_area_struct *vma, void *vaddr, size_t size, int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c03e277c)
Location: kernel/dma/coherent.c:282
Inline: False
```
**Symbols:**

```
c03e277c-c03e27cc: dma_mmap_from_global_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_mmap_from_global_coherent(struct vm_area_struct *vma, void *vaddr, size_t size, int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c0000000001f5f30)
Location: kernel/dma/coherent.c:282
Inline: False
```
**Symbols:**

```
c0000000001f5f30-c0000000001f5f78: dma_mmap_from_global_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_mmap_from_global_coherent(struct vm_area_struct *vma, void *vaddr, size_t size, int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffe000127922)
Location: kernel/dma/coherent.c:282
Inline: False
```
**Symbols:**

```
ffffffe000127922-ffffffe000127980: dma_mmap_from_global_coherent (STB_GLOBAL)
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
