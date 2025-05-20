# Function: <code>dma_init_coherent_memory</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffff81123555)
Location: kernel/dma/coherent.c:40
Inline: True
Inline callers:
  - kernel/dma/coherent.c:dma_declare_coherent_memory
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
int dma_init_coherent_memory(phys_addr_t phys_addr, dma_addr_t device_addr, size_t size, struct dma_coherent_mem **mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffff800010195790)
Location: kernel/dma/coherent.c:40
Inline: False
Direct callers:
  - kernel/dma/coherent.c:rmem_dma_device_init
  - kernel/dma/coherent.c:dma_declare_coherent_memory
```
**Symbols:**

```
ffff800010195790-ffff800010195890: dma_init_coherent_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_init_coherent_memory(phys_addr_t phys_addr, dma_addr_t device_addr, size_t size, struct dma_coherent_mem **mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c03e22fc)
Location: kernel/dma/coherent.c:40
Inline: False
Direct callers:
  - kernel/dma/coherent.c:rmem_dma_device_init
  - kernel/dma/coherent.c:dma_declare_coherent_memory
```
**Symbols:**

```
c03e22fc-c03e23cc: dma_init_coherent_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_init_coherent_memory(phys_addr_t phys_addr, dma_addr_t device_addr, size_t size, struct dma_coherent_mem **mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c0000000001f58c0)
Location: kernel/dma/coherent.c:40
Inline: False
Direct callers:
  - kernel/dma/coherent.c:rmem_dma_device_init
  - kernel/dma/coherent.c:dma_declare_coherent_memory
```
**Symbols:**

```
c0000000001f58c0-c0000000001f5a24: dma_init_coherent_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_init_coherent_memory(phys_addr_t phys_addr, dma_addr_t device_addr, size_t size, struct dma_coherent_mem **mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffe0001275b6)
Location: kernel/dma/coherent.c:40
Inline: False
Direct callers:
  - kernel/dma/coherent.c:rmem_dma_device_init
  - kernel/dma/coherent.c:dma_declare_coherent_memory
```
**Symbols:**

```
ffffffe0001275b6-ffffffe000127688: dma_init_coherent_memory (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
