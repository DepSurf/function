# Function: <code>xa_store</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a19450)
Location: lib/xarray.c:1388
Inline: False
```
**Symbols:**

```
ffffffff81a19450-ffffffff81a19496: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a89160)
Location: lib/xarray.c:1406
Inline: False
```
**Symbols:**

```
ffffffff81a89160-ffffffff81a891a8: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac0400)
Location: lib/xarray.c:1417
Inline: False
```
**Symbols:**

```
ffffffff81ac0400-ffffffff81ac0448: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fc1b0)
Location: lib/xarray.c:1419
Inline: False
Direct callers:
  - drivers/base/memory.c:init_memory_block
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_snapshot_id_decrement
  - net/core/devlink.c:__devlink_snapshot_id_increment
```
**Symbols:**

```
ffffffff815fc1b0-ffffffff815fc1f8: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81620dd0)
Location: lib/xarray.c:1569
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_add_task_file
  - drivers/base/memory.c:init_memory_block
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_snapshot_id_decrement
  - net/core/devlink.c:__devlink_snapshot_id_increment
```
**Symbols:**

```
ffffffff81620dd0-ffffffff81620e18: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816047b0)
Location: lib/xarray.c:1570
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - fs/io_uring.c:__io_uring_add_task_file
  - block/bio.c:bioset_init
  - drivers/base/memory.c:init_memory_block
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
**Symbols:**

```
ffffffff816047b0-ffffffff816047f8: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816730a0)
Location: lib/xarray.c:1570
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - fs/io_uring.c:__io_uring_add_tctx_node
  - block/bio.c:bioset_init
  - drivers/base/memory.c:init_memory_block
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
**Symbols:**

```
ffffffff816730a0-ffffffff816730e8: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178d6a0)
Location: lib/xarray.c:1577
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - block/bio.c:bioset_init
  - io_uring/io_uring.c:io_register_pbuf_ring
  - io_uring/io_uring.c:__io_uring_add_tctx_node
  - io_uring/io_uring.c:io_provide_buffers
  - drivers/base/memory.c:add_memory_block
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
**Symbols:**

```
ffffffff8178d6a0-ffffffff8178d6f0: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8204ad10)
Location: lib/xarray.c:1577
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - block/bio.c:bioset_init
  - io_uring/tctx.c:__io_uring_add_tctx_node
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/base/memory.c:add_memory_block
```
**Symbols:**

```
ffffffff8204ad10-ffffffff8204ad60: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c9610)
Location: lib/xarray.c:1575
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - block/bio.c:bioset_init
  - io_uring/tctx.c:__io_uring_add_tctx_node
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/base/memory.c:add_memory_block
```
**Symbols:**

```
ffffffff820c9610-ffffffff820c9660: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a3f90)
Location: lib/xarray.c:1575
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - fs/libfs.c:simple_offset_rename_exchange
  - fs/libfs.c:simple_offset_rename_exchange
  - block/bio.c:bioset_init
  - io_uring/tctx.c:__io_uring_add_tctx_node
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/base/memory.c:add_memory_block
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff821a3f90-ffffffff821a3fe0: xa_store (STB_GLOBAL)
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
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9b4f0)
Location: lib/xarray.c:1417
Inline: False
```
**Symbols:**

```
ffff800010d9b4f0-ffff800010d9b57c: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e97bec)
Location: lib/xarray.c:1417
Inline: False
```
**Symbols:**

```
c0e97bec-c0e97c3c: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee1790)
Location: lib/xarray.c:1417
Inline: False
```
**Symbols:**

```
c000000000ee1790-c000000000ee1848: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c37e2)
Location: lib/xarray.c:1417
Inline: False
```
**Symbols:**

```
ffffffe0008c37e2-ffffffe0008c3862: xa_store (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5f250)
Location: lib/xarray.c:1417
Inline: False
```
**Symbols:**

```
ffffffff81a5f250-ffffffff81a5f298: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1c320)
Location: lib/xarray.c:1417
Inline: False
```
**Symbols:**

```
ffffffff81a1c320-ffffffff81a1c368: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81acb640)
Location: lib/xarray.c:1417
Inline: False
```
**Symbols:**

```
ffffffff81acb640-ffffffff81acb688: xa_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xa_store(struct xarray *xa, long unsigned int index, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad7450)
Location: lib/xarray.c:1417
Inline: False
```
**Symbols:**

```
ffffffff81ad7450-ffffffff81ad7496: xa_store (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
