# Function: <code>d_lookup_done</code>

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
In fs/namei.c (ffffffff81242a70)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/proc/base.c (ffffffff812aaec2)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff812b2177)
Location: include/linux/dcache.h:360
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81347f9b)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
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
In fs/namei.c (ffffffff812559d1)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/proc/base.c (ffffffff812c0792)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff812c79f7)
Location: include/linux/dcache.h:360
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8135d8e2)
Location: include/linux/dcache.h:360
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
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
In fs/namei.c (ffffffff812616f0)
Location: include/linux/dcache.h:366
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/proc/base.c (ffffffff812cdb00)
Location: include/linux/dcache.h:366
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff812d4ea7)
Location: include/linux/dcache.h:366
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81372338)
Location: include/linux/dcache.h:366
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
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
In fs/namei.c (ffffffff81283e3f)
Location: include/linux/dcache.h:367
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
```
```
In fs/proc/base.c (ffffffff812f2338)
Location: include/linux/dcache.h:367
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff812f96dc)
Location: include/linux/dcache.h:367
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81397046)
Location: include/linux/dcache.h:367
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
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
Location: include/linux/dcache.h:368
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
```
```
In fs/proc/base.c (ffffffff8131f188)
Location: include/linux/dcache.h:368
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff81326d18)
Location: include/linux/dcache.h:368
Inline: True
```
```
In fs/fuse/dir.c (ffffffff813c62b9)
Location: include/linux/dcache.h:368
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
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
In fs/namei.c (ffffffff812bff8d)
Location: include/linux/dcache.h:365
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
In fs/proc/base.c (ffffffff813362b8)
Location: include/linux/dcache.h:365
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff8133debe)
Location: include/linux/dcache.h:365
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff813eac50)
Location: include/linux/dcache.h:365
Inline: True
Inline callers:
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
In fs/proc/base.c (ffffffff8135e384)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff81365ddc)
Location: include/linux/dcache.h:363
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff81416272)
Location: include/linux/dcache.h:363
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
In fs/proc/base.c (ffffffff813765e4)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff8137e06c)
Location: include/linux/dcache.h:363
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff81430158)
Location: include/linux/dcache.h:363
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
Location: include/linux/dcache.h:365
Inline: True
Inline callers:
  - fs/namei.c:atomic_open
  - fs/namei.c:atomic_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/proc/base.c (ffffffff813bf304)
Location: include/linux/dcache.h:365
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff813c87bc)
Location: include/linux/dcache.h:365
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff814800f8)
Location: include/linux/dcache.h:365
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
Location: include/linux/dcache.h:366
Inline: True
Inline callers:
  - fs/namei.c:atomic_open
  - fs/namei.c:atomic_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/proc/base.c (ffffffff813d1114)
Location: include/linux/dcache.h:366
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff813da7ac)
Location: include/linux/dcache.h:366
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff8149b7d2)
Location: include/linux/dcache.h:366
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
In fs/namei.c (ffffffff81333fa7)
Location: include/linux/dcache.h:369
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/proc/base.c (ffffffff813d8014)
Location: include/linux/dcache.h:369
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff813e138b)
Location: include/linux/dcache.h:369
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff814a0a0d)
Location: include/linux/dcache.h:369
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
In fs/namei.c (ffffffff813818f7)
Location: include/linux/dcache.h:369
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/proc/base.c (ffffffff81429754)
Location: include/linux/dcache.h:369
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff81432e3b)
Location: include/linux/dcache.h:369
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff814f88dd)
Location: include/linux/dcache.h:369
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
In fs/namei.c (ffffffff8140093c)
Location: include/linux/dcache.h:359
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
```
```
In fs/proc/base.c (ffffffff814a2b9b)
Location: include/linux/dcache.h:359
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff814ab685)
Location: include/linux/dcache.h:359
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff815886cd)
Location: include/linux/dcache.h:359
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
In fs/namei.c (ffffffff8148a7a8)
Location: include/linux/dcache.h:362
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff814a0c34)
Location: include/linux/dcache.h:362
Inline: True
```
```
In fs/proc/base.c (ffffffff81537d70)
Location: include/linux/dcache.h:362
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff81541700)
Location: include/linux/dcache.h:362
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff8162eb8d)
Location: include/linux/dcache.h:362
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
In fs/namei.c (ffffffff814c0658)
Location: include/linux/dcache.h:362
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff814d5f44)
Location: include/linux/dcache.h:362
Inline: True
```
```
In fs/proc/base.c (ffffffff8156ff73)
Location: include/linux/dcache.h:362
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff81579c60)
Location: include/linux/dcache.h:362
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff81666ded)
Location: include/linux/dcache.h:362
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
In fs/namei.c (ffffffff814f2b38)
Location: include/linux/dcache.h:369
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
```
```
In fs/dcache.c (ffffffff815082e0)
Location: include/linux/dcache.h:369
Inline: True
```
```
In fs/proc/base.c (ffffffff815a8903)
Location: include/linux/dcache.h:369
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff815b2375)
Location: include/linux/dcache.h:369
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff816a1102)
Location: include/linux/dcache.h:369
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
In fs/proc/base.c (ffff800010441bc8)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffff80001044b50c)
Location: include/linux/dcache.h:363
Inline: True
```
```
In fs/fuse/readdir.c (ffff800010514cbc)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
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
In fs/proc/base.c (c06073a4)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (c060fd84)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
```
```
In fs/fuse/readdir.c (c06cfa98)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
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
In fs/proc/base.c (c000000000556f60)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (c000000000562528)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
```
```
In fs/fuse/readdir.c (c00000000065d230)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
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
In fs/proc/base.c (ffffffe0002d89ec)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffe0002e097e)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
```
```
In fs/fuse/readdir.c (ffffffe00037e6c8)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
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
In fs/proc/base.c (ffffffff8136ebc4)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff8137664c)
Location: include/linux/dcache.h:363
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff81428738)
Location: include/linux/dcache.h:363
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
In fs/proc/base.c (ffffffff8135f654)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff8136711c)
Location: include/linux/dcache.h:363
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff814191b8)
Location: include/linux/dcache.h:363
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
In fs/proc/base.c (ffffffff8136c694)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff8137411c)
Location: include/linux/dcache.h:363
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff814248d8)
Location: include/linux/dcache.h:363
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
In fs/proc/base.c (ffffffff8137ff74)
Location: include/linux/dcache.h:363
Inline: True
Inline callers:
  - fs/proc/base.c:proc_fill_cache
```
```
In fs/proc/proc_sysctl.c (ffffffff81387b2c)
Location: include/linux/dcache.h:363
Inline: True
```
```
In fs/fuse/readdir.c (ffffffff8143b446)
Location: include/linux/dcache.h:363
Inline: True
```
</details>
</li>
</ul>

## Differences
