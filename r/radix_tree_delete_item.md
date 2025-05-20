# Function: <code>radix_tree_delete_item</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct radix_tree_root *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813ef290)
Location: lib/radix-tree.c:1376
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff813ef290-ffffffff813ef372: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct radix_tree_root *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81435a40)
Location: lib/radix-tree.c:1533
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff81435a40-ffffffff81435b79: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct radix_tree_root *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff814520a0)
Location: lib/radix-tree.c:1856
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff814520a0-ffffffff81452169: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct radix_tree_root *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f1e80)
Location: lib/radix-tree.c:2037
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_free_swap
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - ipc/util.c:ipc_rmid
  - block/bsg.c:bsg_register_queue
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/md/dm.c:free_minor
  - net/core/net_namespace.c:cleanup_net
  - net/netlink/genetlink.c:genl_unregister_family
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff818f1e80-ffffffff818f1f28: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct radix_tree_root *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81978330)
Location: lib/radix-tree.c:2034
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_free_swap
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/md/dm.c:free_minor
  - net/core/net_namespace.c:cleanup_net
  - net/netlink/genetlink.c:genl_unregister_family
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff81978330-ffffffff819783d8: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct radix_tree_root *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d4a40)
Location: lib/radix-tree.c:2033
Inline: False
Direct callers:
  - mm/shmem.c:shmem_free_swap
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff819d4a40-ffffffff819d4af7: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d6a0)
Location: lib/radix-tree.c:1435
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff81a0d6a0-ffffffff81a0d75b: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7cfd0)
Location: lib/radix-tree.c:1422
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff81a7cfd0-ffffffff81a7d091: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab4300)
Location: lib/radix-tree.c:1422
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff81ab4300-ffffffff81ab43c1: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eeca0)
Location: lib/radix-tree.c:1414
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff815eeca0-ffffffff815eed64: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff816133f0)
Location: lib/radix-tree.c:1414
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff816133f0-ffffffff816134b4: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f6a50)
Location: lib/radix-tree.c:1415
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff815f6a50-ffffffff815f6b11: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81664150)
Location: lib/radix-tree.c:1415
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff81664150-ffffffff81664211: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177e3e0)
Location: lib/radix-tree.c:1415
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff8177e3e0-ffffffff8177e4af: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8203afe0)
Location: lib/radix-tree.c:1415
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff8203afe0-ffffffff8203b0af: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b94c0)
Location: lib/radix-tree.c:1413
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff820b94c0-ffffffff820b958f: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82193dd0)
Location: lib/radix-tree.c:1413
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff82193dd0-ffffffff82193e9f: radix_tree_delete_item (STB_GLOBAL)
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
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8e820)
Location: lib/radix-tree.c:1422
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffff800010d8e820-ffff800010d8e8f8: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e88f24)
Location: lib/radix-tree.c:1422
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
c0e88f24-c0e89020: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed1480)
Location: lib/radix-tree.c:1422
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
c000000000ed1480-c000000000ed15b0: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b725c)
Location: lib/radix-tree.c:1422
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffe0008b725c-ffffffe0008b7322: radix_tree_delete_item (STB_GLOBAL)
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
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a53150)
Location: lib/radix-tree.c:1422
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff81a53150-ffffffff81a53211: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a10250)
Location: lib/radix-tree.c:1422
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff81a10250-ffffffff81a10311: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf540)
Location: lib/radix-tree.c:1422
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff81abf540-ffffffff81abf601: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *radix_tree_delete_item(struct xarray *root, long unsigned int index, void *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acba10)
Location: lib/radix-tree.c:1422
Inline: False
Direct callers:
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_delete
```
**Symbols:**

```
ffffffff81acba10-ffffffff81acbad1: radix_tree_delete_item (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root *root</code> ➡️ <code>struct xarray *root</code>
</li>
</ul>
</details>
</li>
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
