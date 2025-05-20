# Function: <code>dma_fence_is_chain</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff819ef59b)
Location: include/linux/dma-fence.h:610
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819ef9f9)
Location: include/linux/dma-fence.h:610
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f0ec9)
Location: include/linux/dma-fence.h:610
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff819f3df8)
Location: include/linux/dma-fence.h:610
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff81b6cb4b)
Location: include/linux/dma-fence.h:610
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d019)
Location: include/linux/dma-fence.h:610
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81b6dc94)
Location: include/linux/dma-fence.h:610
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6eb99)
Location: include/linux/dma-fence.h:610
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bc028b)
Location: include/linux/dma-fence.h:632
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0749)
Location: include/linux/dma-fence.h:632
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81bc1454)
Location: include/linux/dma-fence.h:632
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc2489)
Location: include/linux/dma-fence.h:632
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c14a0b)
Location: include/linux/dma-fence.h:667
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c14ec9)
Location: include/linux/dma-fence.h:667
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81c15bd4)
Location: include/linux/dma-fence.h:667
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16c19)
Location: include/linux/dma-fence.h:667
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb225f)
Location: include/linux/dma-fence.h:667
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
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
