# Function: <code>dma_resv_unlock</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81825729)
Location: include/linux/dma-resv.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff81836109)
Location: include/linux/dma-resv.h:216
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff81818658)
Location: include/linux/dma-resv.h:216
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
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
In drivers/dma-buf/dma-buf.c (ffffffff818a2b58)
Location: include/linux/dma-resv.h:208
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff819ec472)
Location: include/linux/dma-resv.h:451
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
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
In drivers/dma-buf/dma-buf.c (ffffffff81b6a8fd)
Location: include/linux/dma-resv.h:461
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In drivers/dma-buf/dma-buf.c (ffffffff81bbdd4d)
Location: include/linux/dma-resv.h:461
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap_internal
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
In drivers/dma-buf/dma-buf.c (ffffffff81c1249d)
Location: include/linux/dma-resv.h:461
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_detach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
  - drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c4bb)
Location: include/linux/dma-resv.h:461
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan
  - drivers/gpu/drm/drm_gem.c:drm_gem_unlock_reservations
  - drivers/gpu/drm/drm_gem.c:drm_gem_lock_reservations
  - drivers/gpu/drm/drm_gem.c:drm_gem_lock_reservations
  - drivers/gpu/drm/drm_gem.c:drm_gem_vunmap_unlocked
  - drivers/gpu/drm/drm_gem.c:drm_gem_vmap_unlocked
```
```
In drivers/gpu/drm/drm_gem_shmem_helper.c (ffffffff81cbd87d)
Location: include/linux/dma-resv.h:461
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vm_close
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vm_open
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_fault
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_unpin
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_free
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_object_pin
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
