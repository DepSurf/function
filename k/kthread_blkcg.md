# Function: <code>kthread_blkcg</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810abd90)
Location: kernel/kthread.c:1212
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
  - block/blk-mq.c:blk_mq_bio_to_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_get_queue
```
**Symbols:**

```
ffffffff810abd90-ffffffff810abdbe: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3690)
Location: kernel/kthread.c:1230
Inline: True
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
  - block/blk-mq.c:blk_mq_bio_to_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_get_queue
```
**Symbols:**

```
ffffffff810b3690-ffffffff810b36bc: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bca00)
Location: kernel/kthread.c:1232
Inline: True
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/bio.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810bca00-ffffffff810bca2c: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c29d0)
Location: kernel/kthread.c:1242
Inline: True
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/bio.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810c29d0-ffffffff810c29fe: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c7e00)
Location: kernel/kthread.c:1242
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/bio.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810c7e00-ffffffff810c7e2c: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0880)
Location: kernel/kthread.c:1338
Inline: True
Direct callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
  - block/bio.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810d0880-ffffffff810d08ac: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb460)
Location: kernel/kthread.c:1412
Inline: True
Direct callers:
  - mm/readahead.c:page_cache_sync_ra
  - mm/swapfile.c:cgroup_throttle_swaprate
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_grab_identity
  - fs/io_uring.c:io_init_identity
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810cb460-ffffffff810cb48c: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ccc10)
Location: kernel/kthread.c:1470
Inline: True
Direct callers:
  - mm/readahead.c:page_cache_sync_ra
  - mm/swapfile.c:cgroup_throttle_swaprate
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810ccc10-ffffffff810ccc3c: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810df6b0)
Location: kernel/kthread.c:1470
Inline: False
Direct callers:
  - mm/readahead.c:page_cache_sync_ra
  - mm/swapfile.c:__cgroup_throttle_swaprate
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810df6b0-ffffffff810df6dc: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fb4d0)
Location: kernel/kthread.c:1526
Inline: False
Direct callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810fb4d0-ffffffff810fb502: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111e410)
Location: kernel/kthread.c:1526
Inline: False
Direct callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff8111e410-ffffffff8111e442: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112b680)
Location: kernel/kthread.c:1536
Inline: False
Direct callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff8112b680-ffffffff8112b6b2: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81135dd0)
Location: kernel/kthread.c:1552
Inline: False
Direct callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff81135dd0-ffffffff81135e02: kthread_blkcg (STB_GLOBAL)
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
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff8000101271a0)
Location: kernel/kthread.c:1242
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/bio.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffff8000101271a0-ffff8000101271dc: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0379a08)
Location: kernel/kthread.c:1242
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/bio.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
c0379a08-c0379a48: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0000000001733f0)
Location: kernel/kthread.c:1242
Inline: True
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/bio.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
c0000000001733f0-c00000000017342c: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000de9da)
Location: kernel/kthread.c:1242
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/bio.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffe0000de9da-ffffffe0000dea0a: kthread_blkcg (STB_GLOBAL)
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
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2180)
Location: kernel/kthread.c:1242
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/bio.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810c2180-ffffffff810c21ac: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b09d0)
Location: kernel/kthread.c:1242
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/bio.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810b09d0-ffffffff810b09fc: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c16d0)
Location: kernel/kthread.c:1242
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/bio.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810c16d0-ffffffff810c16fc: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cgroup_subsys_state *kthread_blkcg();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c9b00)
Location: kernel/kthread.c:1242
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/bio.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810c9b00-ffffffff810c9b2c: kthread_blkcg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
