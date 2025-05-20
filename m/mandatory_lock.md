# Function: <code>mandatory_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c76c9)
Location: include/linux/fs.h:2075
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff8120996a)
Location: include/linux/fs.h:2075
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff8120c6a5)
Location: include/linux/fs.h:2075
Inline: True
Inline callers:
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff8121ab98)
Location: include/linux/fs.h:2075
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/locks.c (ffffffff8125fe06)
Location: include/linux/fs.h:2075
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e3d62)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff8122f778)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff81231cfc)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff812423d5)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/locks.c (ffffffff8128bfc6)
Location: include/linux/fs.h:2165
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffff811f3d4a)
Location: include/linux/fs.h:2146
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff81241d0b)
Location: include/linux/fs.h:2146
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff812442ac)
Location: include/linux/fs.h:2146
Inline: True
Inline callers:
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff812552ae)
Location: include/linux/fs.h:2146
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/locks.c (ffffffff812a0d46)
Location: include/linux/fs.h:2146
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffff811fed27)
Location: include/linux/fs.h:2199
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff8124d327)
Location: include/linux/fs.h:2199
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff8124fa3d)
Location: include/linux/fs.h:2199
Inline: True
Inline callers:
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff812612f2)
Location: include/linux/fs.h:2199
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/locks.c (ffffffff812afae5)
Location: include/linux/fs.h:2199
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffff8121736a)
Location: include/linux/fs.h:2244
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff8126f29a)
Location: include/linux/fs.h:2244
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff8127198d)
Location: include/linux/fs.h:2244
Inline: True
Inline callers:
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff81283a29)
Location: include/linux/fs.h:2244
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/locks.c (ffffffff812d394e)
Location: include/linux/fs.h:2244
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffff8123842f)
Location: include/linux/fs.h:2260
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff81295d84)
Location: include/linux/fs.h:2260
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff812977fc)
Location: include/linux/fs.h:2260
Inline: True
Inline callers:
  - fs/read_write.c:clone_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff812aabb6)
Location: include/linux/fs.h:2260
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/locks.c (ffffffff812fddfe)
Location: include/linux/fs.h:2260
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffff8124be05)
Location: include/linux/fs.h:2346
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff812aab74)
Location: include/linux/fs.h:2346
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff812ac4d2)
Location: include/linux/fs.h:2346
Inline: True
Inline callers:
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff812bf986)
Location: include/linux/fs.h:2346
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/locks.c (ffffffff8131385f)
Location: include/linux/fs.h:2346
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffff8125e293)
Location: include/linux/fs.h:2340
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff812c7351)
Location: include/linux/fs.h:2340
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff812c8c2f)
Location: include/linux/fs.h:2340
Inline: True
Inline callers:
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff812dcb0e)
Location: include/linux/fs.h:2340
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/locks.c (ffffffff8133b068)
Location: include/linux/fs.h:2340
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffff8126ca87)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff812d8d61)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff812da63f)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff812ee65d)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/locks.c (ffffffff813535c8)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffff8129c753)
Location: include/linux/fs.h:2408
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff8130eba1)
Location: include/linux/fs.h:2408
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff81310b3f)
Location: include/linux/fs.h:2408
Inline: True
Inline callers:
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff8132140a)
Location: include/linux/fs.h:2408
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
```
In fs/locks.c (ffffffff813999be)
Location: include/linux/fs.h:2408
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffff812a7a83)
Location: include/linux/fs.h:2362
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff8131ae83)
Location: include/linux/fs.h:2362
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff8131d730)
Location: include/linux/fs.h:2362
Inline: True
Inline callers:
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff8132c9aa)
Location: include/linux/fs.h:2362
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
```
In fs/remap_range.c (ffffffff8136603f)
Location: include/linux/fs.h:2362
Inline: True
Inline callers:
  - fs/remap_range.c:remap_verify_area
```
```
In fs/locks.c (ffffffff813ab4ae)
Location: include/linux/fs.h:2362
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
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
In fs/read_write.c (0)
Location: include/linux/fs.h:2639
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/fs.h:2639
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/fs.h:2639
Inline: True
```
</details>
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
In <code>6.8</code>: Absent ⚠️
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
In mm/mmap.c (ffff800010303b88)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffff80001037e0e0)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffff80001037fc7c)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffff8000103982e4)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/locks.c (ffff800010415118)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (c05224ac)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (c0568a64)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (c056a2a0)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (c057e8e4)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/locks.c (c05e22ec)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk64
  - fs/locks.c:fcntl_setlk64
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (c0000000003d08d8)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (c000000000473afc)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (c000000000475ba0)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (c000000000492204)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/locks.c (c000000000524b94)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffe000210596)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffe000253e66)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffe00025561e)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffe000265efe)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/locks.c (ffffffe0002bcd00)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffff812650d7)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff812d1341)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff812d2c1f)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff812e6c3d)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/locks.c (ffffffff8134bba8)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffff812574f7)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff812c1fc1)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff812c389f)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff812d787d)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/locks.c (ffffffff8133c888)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffff81262e77)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff812cf151)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff812d0a2f)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff812e4a4d)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/locks.c (ffffffff81349678)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
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
In mm/mmap.c (ffffffff81272837)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/open.c (ffffffff812dff61)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/read_write.c (ffffffff812e185f)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:remap_verify_area
  - fs/read_write.c:rw_verify_area
  - fs/read_write.c:rw_verify_area
```
```
In fs/namei.c (ffffffff812f59cd)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/locks.c (ffffffff8135cf28)
Location: include/linux/fs.h:2375
Inline: True
Inline callers:
  - fs/locks.c:lock_get_status
  - fs/locks.c:lock_get_status
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
```
</details>
</li>
</ul>

## Differences
