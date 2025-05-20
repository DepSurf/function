# Function: <code>xen_grant_setup_dma_ops</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_grant_setup_dma_ops(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-dma-ops.c (0)
Location: drivers/xen/grant-dma-ops.c:300
Inline: False
```
**Symbols:**

```
ffffffff81ebf501-ffffffff81ebf565: xen_grant_setup_dma_ops.cold (STB_LOCAL)
ffffffff818e0610-ffffffff818e0679: xen_grant_setup_dma_ops (STB_GLOBAL)
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
In drivers/xen/grant-dma-ops.c (ffffffff81a35486)
Location: drivers/xen/grant-dma-ops.c:372
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
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
In drivers/xen/grant-dma-ops.c (ffffffff81a7eedd)
Location: drivers/xen/grant-dma-ops.c:374
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
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
In drivers/xen/grant-dma-ops.c (ffffffff81ad144d)
Location: drivers/xen/grant-dma-ops.c:374
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
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
</ul>
