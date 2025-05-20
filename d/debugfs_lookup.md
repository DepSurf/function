# Function: <code>debugfs_lookup</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8137c4c0)
Location: fs/debugfs/inode.c:261
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff8137c4c0-ffffffff8137c550: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813a1370)
Location: fs/debugfs/inode.c:263
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff813a1370-ffffffff813a1400: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813d0750)
Location: fs/debugfs/inode.c:288
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff813d0750-ffffffff813d07b7: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813eade0)
Location: fs/debugfs/inode.c:288
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff813eade0-ffffffff813eae47: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81416ee0)
Location: fs/debugfs/inode.c:290
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff81416ee0-ffffffff81416f4b: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81430dc0)
Location: fs/debugfs/inode.c:292
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff81430dc0-ffffffff81430e2b: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81480bd0)
Location: fs/debugfs/inode.c:292
Inline: False
```
**Symbols:**

```
ffffffff81480bd0-ffffffff81480c2c: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8149e5a0)
Location: fs/debugfs/inode.c:296
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_remove
```
**Symbols:**

```
ffffffff8149e5a0-ffffffff8149e613: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814a4570)
Location: fs/debugfs/inode.c:300
Inline: True
Direct callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - drivers/base/component.c:free_master
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_remove
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff814a4570-ffffffff814a45e2: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814fccc0)
Location: fs/debugfs/inode.c:300
Inline: True
Direct callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/slub.c:debugfs_slab_release
  - drivers/base/component.c:free_master
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_remove
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff81cd24b3-ffffffff81cd24c7: debugfs_lookup.cold (STB_LOCAL)
ffffffff814fcc80-ffffffff814fccfe: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:300
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - mm/slub.c:debugfs_slab_release
  - drivers/base/component.c:free_aggregate_device
  - drivers/base/dd.c:deferred_probe_exit
  - drivers/base/power/domain.c:genpd_remove
  - drivers/usb/core/usb.c:usb_debugfs_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff81e855f8-ffffffff81e8560d: debugfs_lookup.cold (STB_LOCAL)
ffffffff8158d490-ffffffff8158d525: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:323
Inline: False
Direct callers:
  - mm/slub.c:debugfs_slab_release
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
```
**Symbols:**

```
ffffffff82072a09-ffffffff82072a1e: debugfs_lookup.cold (STB_LOCAL)
ffffffff81633f30-ffffffff81633fc5: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:323
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
```
**Symbols:**

```
ffffffff820f266d-ffffffff820f2682: debugfs_lookup.cold (STB_LOCAL)
ffffffff8166c240-ffffffff8166c2d5: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:330
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_remove_files
```
**Symbols:**

```
ffffffff821cf908-ffffffff821cf91d: debugfs_lookup.cold (STB_LOCAL)
ffffffff816a66e0-ffffffff816a6775: debugfs_lookup (STB_GLOBAL)
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
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffff800010515968)
Location: fs/debugfs/inode.c:292
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffff800010515968-ffff8000105159f4: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c06d0750)
Location: fs/debugfs/inode.c:292
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
c06d0750-c06d07d4: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c00000000065e2a0)
Location: fs/debugfs/inode.c:292
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
c00000000065e2a0-c00000000065e38c: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffe00037f182)
Location: fs/debugfs/inode.c:292
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffe00037f182-ffffffe00037f1fc: debugfs_lookup (STB_GLOBAL)
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
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814293a0)
Location: fs/debugfs/inode.c:292
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff814293a0-ffffffff8142940b: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81419e20)
Location: fs/debugfs/inode.c:292
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff81419e20-ffffffff81419e8b: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81425540)
Location: fs/debugfs/inode.c:292
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff81425540-ffffffff814255ab: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *debugfs_lookup(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8143c400)
Location: fs/debugfs/inode.c:292
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
**Symbols:**

```
ffffffff8143c400-ffffffff8143c46b: debugfs_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
