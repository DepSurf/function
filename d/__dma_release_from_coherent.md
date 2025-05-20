# Function: <code>__dma_release_from_coherent</code>

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
int __dma_release_from_coherent(struct dma_coherent_mem *mem, int order, void *vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffff811233e0)
Location: kernel/dma/coherent.c:203
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_release_from_global_coherent
  - kernel/dma/coherent.c:dma_release_from_dev_coherent
```
**Symbols:**

```
ffffffff811233e0-ffffffff81123477: __dma_release_from_coherent (STB_LOCAL)
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
int __dma_release_from_coherent(struct dma_coherent_mem *mem, int order, void *vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffff800010195960)
Location: kernel/dma/coherent.c:193
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_release_from_global_coherent
  - kernel/dma/coherent.c:dma_release_from_dev_coherent
```
**Symbols:**

```
ffff800010195960-ffff800010195a58: __dma_release_from_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __dma_release_from_coherent(struct dma_coherent_mem *mem, int order, void *vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c03e219c)
Location: kernel/dma/coherent.c:193
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_release_from_global_coherent
  - kernel/dma/coherent.c:dma_release_from_dev_coherent
```
**Symbols:**

```
c03e219c-c03e222c: __dma_release_from_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __dma_release_from_coherent(struct dma_coherent_mem *mem, int order, void *vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c0000000001f56c0)
Location: kernel/dma/coherent.c:193
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_release_from_global_coherent
  - kernel/dma/coherent.c:dma_release_from_dev_coherent
```
**Symbols:**

```
c0000000001f56c0-c0000000001f57b0: __dma_release_from_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __dma_release_from_coherent(struct dma_coherent_mem *mem, int order, void *vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffe00012734c)
Location: kernel/dma/coherent.c:193
Inline: False
Direct callers:
  - kernel/dma/coherent.c:dma_release_from_global_coherent
  - kernel/dma/coherent.c:dma_release_from_dev_coherent
```
**Symbols:**

```
ffffffe00012734c-ffffffe0001273d4: __dma_release_from_coherent (STB_LOCAL)
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
