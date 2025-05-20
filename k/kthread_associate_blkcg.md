# Function: <code>kthread_associate_blkcg</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ac900)
Location: kernel/kthread.c:1186
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
**Symbols:**

```
ffffffff810ac900-ffffffff810ac992: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3910)
Location: kernel/kthread.c:1204
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
**Symbols:**

```
ffffffff810b3910-ffffffff810b39a9: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bcc10)
Location: kernel/kthread.c:1206
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
**Symbols:**

```
ffffffff810bcc10-ffffffff810bcca9: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2a00)
Location: kernel/kthread.c:1216
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
**Symbols:**

```
ffffffff810c2a00-ffffffff810c2a95: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8f70)
Location: kernel/kthread.c:1216
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
**Symbols:**

```
ffffffff810c8f70-ffffffff810c9005: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (ffffffff810d0960)
Location: kernel/kthread.c:1312
Inline: True
```
**Symbols:**

```
ffffffff810d0960-ffffffff810d09f8: kthread_associate_blkcg.part.0 (STB_LOCAL)
ffffffff810d0a00-ffffffff810d0a20: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (ffffffff810cb540)
Location: kernel/kthread.c:1386
Inline: True
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io-wq.c:io_impersonate_work
  - fs/io-wq.c:__io_worker_unuse
```
**Symbols:**

```
ffffffff810cb540-ffffffff810cb5ec: kthread_associate_blkcg.part.0 (STB_LOCAL)
ffffffff810cb5f0-ffffffff810cb610: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cce80)
Location: kernel/kthread.c:1444
Inline: True
```
**Symbols:**

```
ffffffff810cce80-ffffffff810ccf29: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810df8d0)
Location: kernel/kthread.c:1444
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
```
**Symbols:**

```
ffffffff810df8d0-ffffffff810df979: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810f9c30)
Location: kernel/kthread.c:1500
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
```
**Symbols:**

```
ffffffff810f9c30-ffffffff810f9cf7: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111c970)
Location: kernel/kthread.c:1500
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
```
**Symbols:**

```
ffffffff8111c970-ffffffff8111ca37: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81129b00)
Location: kernel/kthread.c:1510
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
```
**Symbols:**

```
ffffffff81129b00-ffffffff81129bc7: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81134140)
Location: kernel/kthread.c:1526
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
```
**Symbols:**

```
ffffffff81134140-ffffffff81134207: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128838)
Location: kernel/kthread.c:1216
Inline: True
```
**Symbols:**

```
ffff800010128838-ffff800010128954: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037ac60)
Location: kernel/kthread.c:1216
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
**Symbols:**

```
c037ac60-c037ad94: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000173430)
Location: kernel/kthread.c:1216
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
**Symbols:**

```
c000000000173430-c0000000001735e8: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df4ea)
Location: kernel/kthread.c:1216
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
**Symbols:**

```
ffffffe0000df4ea-ffffffe0000df5ca: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c32f0)
Location: kernel/kthread.c:1216
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
**Symbols:**

```
ffffffff810c32f0-ffffffff810c3385: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1b30)
Location: kernel/kthread.c:1216
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
**Symbols:**

```
ffffffff810b1b30-ffffffff810b1bc5: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2840)
Location: kernel/kthread.c:1216
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
**Symbols:**

```
ffffffff810c2840-ffffffff810c28d5: kthread_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kthread_associate_blkcg(struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cae30)
Location: kernel/kthread.c:1216
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
**Symbols:**

```
ffffffff810cae30-ffffffff810caeef: kthread_associate_blkcg (STB_GLOBAL)
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
