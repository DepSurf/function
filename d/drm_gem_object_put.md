# Function: <code>drm_gem_object_put</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_client.c (ffffffff81c81c43)
Location: include/drm/drm_gem.h:510
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client.c:drm_client_buffer_delete
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c4c4)
Location: include/drm/drm_gem.h:510
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan
  - drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap_obj
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap_obj
  - drivers/gpu/drm/drm_gem.c:drm_gem_vm_close
  - drivers/gpu/drm/drm_gem.c:drm_gem_vm_close
  - drivers/gpu/drm/drm_gem.c:drm_gem_open_ioctl
  - drivers/gpu/drm/drm_gem.c:drm_gem_open_ioctl
  - drivers/gpu/drm/drm_gem.c:drm_gem_flink_ioctl
  - drivers/gpu/drm/drm_gem.c:drm_gem_flink_ioctl
  - drivers/gpu/drm/drm_gem.c:drm_gem_dma_resv_wait
  - drivers/gpu/drm/drm_gem.c:drm_gem_dma_resv_wait
  - drivers/gpu/drm/drm_gem.c:drm_gem_dumb_map_offset
  - drivers/gpu/drm/drm_gem.c:drm_gem_dumb_map_offset
  - drivers/gpu/drm/drm_gem.c:drm_gem_object_handle_put_unlocked
  - drivers/gpu/drm/drm_gem.c:drm_gem_object_handle_put_unlocked
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81caca30)
Location: include/drm/drm_gem.h:510
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_mmap
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_mmap
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_fd_to_handle
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_fd_to_handle
  - drivers/gpu/drm/drm_prime.c:drm_gem_dmabuf_release
  - drivers/gpu/drm/drm_prime.c:drm_gem_dmabuf_release
```
```
In drivers/gpu/drm/drm_gem_shmem_helper.c (ffffffff81cbe36f)
Location: include/drm/drm_gem.h:510
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_dumb_create
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_dumb_create
```
```
In drivers/gpu/drm/drm_gem_framebuffer_helper.c (ffffffff81ccc097)
Location: include/drm/drm_gem.h:510
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_init_with_funcs
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_destroy
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_destroy
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
