# Function: <code>d_in_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (0)
Location: include/linux/dcache.h:355
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/dcache.h:355
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/dcache.h:355
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/dcache.h:355
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:355
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (0)
Location: include/linux/dcache.h:355
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/dcache.h:355
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/dcache.h:355
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/dcache.h:355
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:355
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (0)
Location: include/linux/dcache.h:361
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/dcache.h:361
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/dcache.h:361
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/dcache.h:361
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:361
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (0)
Location: include/linux/dcache.h:362
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/dcache.h:362
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/dcache.h:362
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/dcache.h:362
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/dcache.h:362
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a9f78)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff812b56bf)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dentry_kill
```
```
In fs/proc/base.c (ffffffff8131f188)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff81326cd8)
Location: include/linux/dcache.h:363
Inline: True
```
```
In fs/fuse/dir.c (ffffffff813c609b)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_atomic_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bfbd9)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff812ca9df)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dentry_kill
```
```
In fs/proc/base.c (ffffffff813362b8)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff8133de98)
Location: include/linux/dcache.h:360
Inline: True
```
```
In fs/fuse/dir.c (ffffffff813dfac0)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff813ea5d1)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dc44d)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff812e8368)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/proc/base.c (ffffffff8135e384)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff81365d99)
Location: include/linux/dcache.h:358
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8140b6bf)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff81416170)
Location: include/linux/dcache.h:358
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812edf5d)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff812f9ef8)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/proc/base.c (ffffffff813765e4)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff8137e029)
Location: include/linux/dcache.h:358
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8142516f)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff81430054)
Location: include/linux/dcache.h:358
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813227b8)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/namei.c:atomic_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff81331f2e)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dentry_kill
```
```
In fs/proc/base.c (ffffffff813bf304)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff813c8779)
Location: include/linux/dcache.h:360
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8147487f)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff8147fff4)
Location: include/linux/dcache.h:360
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132dd58)
Location: include/linux/dcache.h:361
Inline: True
Inline callers:
  - fs/namei.c:atomic_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff8133d94e)
Location: include/linux/dcache.h:361
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dentry_kill
```
```
In fs/proc/base.c (ffffffff813d1114)
Location: include/linux/dcache.h:361
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff813da769)
Location: include/linux/dcache.h:361
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8148f23b)
Location: include/linux/dcache.h:361
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff8149b6d7)
Location: include/linux/dcache.h:361
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333f86)
Location: include/linux/dcache.h:364
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff81343c4d)
Location: include/linux/dcache.h:364
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dentry_kill
```
```
In fs/proc/base.c (ffffffff813d8014)
Location: include/linux/dcache.h:364
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff813e1348)
Location: include/linux/dcache.h:364
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81494c6b)
Location: include/linux/dcache.h:364
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff814a08e3)
Location: include/linux/dcache.h:364
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813818d6)
Location: include/linux/dcache.h:364
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff8139157d)
Location: include/linux/dcache.h:364
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dentry_kill
```
```
In fs/proc/base.c (ffffffff81429754)
Location: include/linux/dcache.h:364
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff81432df8)
Location: include/linux/dcache.h:364
Inline: True
```
```
In fs/fuse/dir.c (ffffffff814ebf2b)
Location: include/linux/dcache.h:364
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff814f87b3)
Location: include/linux/dcache.h:364
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8140091b)
Location: include/linux/dcache.h:354
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff8141351d)
Location: include/linux/dcache.h:354
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/proc/base.c (ffffffff814a2b9b)
Location: include/linux/dcache.h:354
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff814ab642)
Location: include/linux/dcache.h:354
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8157abbc)
Location: include/linux/dcache.h:354
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff81588594)
Location: include/linux/dcache.h:354
Inline: True
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
In fs/namei.c (ffffffff8148a787)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff8149e94e)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/proc/base.c (ffffffff81537d70)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff815416bd)
Location: include/linux/dcache.h:357
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8162037c)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff8162ea54)
Location: include/linux/dcache.h:357
Inline: True
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
In fs/namei.c (ffffffff814c0637)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff814d3c6e)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/proc/base.c (ffffffff8156ff73)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff81579c1d)
Location: include/linux/dcache.h:357
Inline: True
```
```
In fs/fuse/dir.c (ffffffff816587d0)
Location: include/linux/dcache.h:357
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff81666cb4)
Location: include/linux/dcache.h:357
Inline: True
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
In fs/namei.c (ffffffff814f2b17)
Location: include/linux/dcache.h:364
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff81506320)
Location: include/linux/dcache.h:364
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
```
```
In fs/proc/base.c (ffffffff815a8903)
Location: include/linux/dcache.h:364
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff815b233d)
Location: include/linux/dcache.h:364
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81692500)
Location: include/linux/dcache.h:364
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff816a0fc4)
Location: include/linux/dcache.h:364
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff8000103977d8)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffff8000103a8a98)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/proc/base.c (ffff800010441bc8)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffff80001044b4c4)
Location: include/linux/dcache.h:358
Inline: True
```
```
In fs/fuse/dir.c (ffff80001050884c)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffff800010514ad8)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057dd00)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (c058a0e8)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/proc/base.c (c06073a4)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (c060fd84)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
```
```
In fs/fuse/dir.c (c06c4804)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (c06cf838)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000491640)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (c0000000004a35bc)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/proc/base.c (c000000000556f60)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (c000000000562528)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
```
```
In fs/fuse/dir.c (c00000000064e220)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (c00000000065d0c4)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000265800)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffe00026edf6)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/proc/base.c (ffffffe0002d89ec)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffe0002e097e)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
```
```
In fs/fuse/dir.c (ffffffe00037444e)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffe00037e97a)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e653d)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff812f24d8)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/proc/base.c (ffffffff8136ebc4)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff81376609)
Location: include/linux/dcache.h:358
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8141d74f)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff81428634)
Location: include/linux/dcache.h:358
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d717d)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff812e3108)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/proc/base.c (ffffffff8135f654)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff813670d9)
Location: include/linux/dcache.h:358
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8140e1cf)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff814190b4)
Location: include/linux/dcache.h:358
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e434d)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff812f02e8)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/proc/base.c (ffffffff8136c694)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff813740d9)
Location: include/linux/dcache.h:358
Inline: True
```
```
In fs/fuse/dir.c (ffffffff814198ef)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff814247d4)
Location: include/linux/dcache.h:358
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f52cd)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff813013dd)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
```
```
In fs/proc/base.c (ffffffff8137ff74)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff81387ae9)
Location: include/linux/dcache.h:358
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8143065f)
Location: include/linux/dcache.h:358
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_atomic_open
```
```
In fs/fuse/readdir.c (ffffffff8143b344)
Location: include/linux/dcache.h:358
Inline: True
```
</details>
</li>
</ul>

## Differences
