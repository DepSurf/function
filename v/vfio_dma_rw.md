# Function: <code>vfio_dma_rw</code>

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
int vfio_dma_rw(struct vfio_group *group, dma_addr_t user_iova, void *data, size_t len, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189aca0)
Location: drivers/vfio/vfio.c:2159
Inline: False
```
**Symbols:**

```
ffffffff8189aca0-ffffffff8189acf4: vfio_dma_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_dma_rw(struct vfio_group *group, dma_addr_t user_iova, void *data, size_t len, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818a9860)
Location: drivers/vfio/vfio.c:2165
Inline: False
```
**Symbols:**

```
ffffffff818a9860-ffffffff818a98b4: vfio_dma_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_dma_rw(struct vfio_group *group, dma_addr_t user_iova, void *data, size_t len, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188cc30)
Location: drivers/vfio/vfio.c:2064
Inline: False
```
**Symbols:**

```
ffffffff8188cc30-ffffffff8188cc88: vfio_dma_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_dma_rw(struct vfio_group *group, dma_addr_t user_iova, void *data, size_t len, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81920110)
Location: drivers/vfio/vfio.c:2171
Inline: False
```
**Symbols:**

```
ffffffff81920110-ffffffff81920168: vfio_dma_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_dma_rw(struct vfio_device *device, dma_addr_t user_iova, void *data, size_t len, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a75f60)
Location: drivers/vfio/vfio.c:2010
Inline: False
```
**Symbols:**

```
ffffffff81a75f60-ffffffff81a76013: vfio_dma_rw (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vfio_device *device</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vfio_group *group</code>
</li>
</ul>
</details>
</li>
</ul>
