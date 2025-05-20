# Function: <code>dma_declare_coherent_memory</code>

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
int dma_declare_coherent_memory(struct device *dev, phys_addr_t phys_addr, dma_addr_t device_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffff81123550)
Location: kernel/dma/coherent.c:110
Inline: False
```
**Symbols:**

```
ffffffff81123550-ffffffff81123690: dma_declare_coherent_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/dma-mapping.h:764
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/dma-mapping.h:850
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/dma-map-ops.h:181
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/dma-map-ops.h:181
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/dma-map-ops.h:175
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
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/dma-map-ops.h:175
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
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/dma-map-ops.h:187
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
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/dma-map-ops.h:188
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
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/dma-map-ops.h:183
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
int dma_declare_coherent_memory(struct device *dev, phys_addr_t phys_addr, dma_addr_t device_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffff800010195bc8)
Location: kernel/dma/coherent.c:110
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffff800010195bc8-ffff800010195c90: dma_declare_coherent_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_declare_coherent_memory(struct device *dev, phys_addr_t phys_addr, dma_addr_t device_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c03e257c)
Location: kernel/dma/coherent.c:110
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
c03e257c-c03e2640: dma_declare_coherent_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_declare_coherent_memory(struct device *dev, phys_addr_t phys_addr, dma_addr_t device_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c0000000001f5ce0)
Location: kernel/dma/coherent.c:110
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
c0000000001f5ce0-c0000000001f5de4: dma_declare_coherent_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_declare_coherent_memory(struct device *dev, phys_addr_t phys_addr, dma_addr_t device_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffe000127716)
Location: kernel/dma/coherent.c:110
Inline: False
```
**Symbols:**

```
ffffffe000127716-ffffffe0001277a0: dma_declare_coherent_memory (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/dma-mapping.h:764
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/dma-mapping.h:764
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
