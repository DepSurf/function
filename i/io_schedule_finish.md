# Function: <code>io_schedule_finish</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3156)
Location: kernel/sched/core.c:4971
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff810b3180-ffffffff810b31ad: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba556)
Location: kernel/sched/core.c:5016
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff810ba580-ffffffff810ba5ad: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1be6)
Location: kernel/sched/core.c:5141
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff810c1c10-ffffffff810c1c3d: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810caf16)
Location: kernel/sched/core.c:5124
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810caf40-ffffffff810caf6d: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a989b6)
Location: kernel/sched/core.c:5577
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810d2bd0-ffffffff810d2bfd: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81ad0306)
Location: kernel/sched/core.c:5768
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810dd040-ffffffff810dd06d: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81bc8985)
Location: kernel/sched/core.c:6001
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
```
**Symbols:**

```
ffffffff810e5c20-ffffffff810e5c4d: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81c41756)
Location: kernel/sched/core.c:6821
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
```
**Symbols:**

```
ffffffff810e3840-ffffffff810e3871: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81c336c6)
Location: kernel/sched/core.c:7172
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810e59d0-ffffffff810e5a01: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81d51fc6)
Location: kernel/sched/core.c:8370
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810fcab0-ffffffff810fcae1: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81f225a6)
Location: kernel/sched/core.c:8661
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff811193e0-ffffffff8111941b: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff820cce46)
Location: kernel/sched/core.c:8845
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff81140c90-ffffffff81140ccb: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82151256)
Location: kernel/sched/core.c:9002
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff8114c9b0-ffffffff8114c9eb: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82234006)
Location: kernel/sched/core.c:8997
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff81158670-ffffffff811586ab: io_schedule_finish (STB_GLOBAL)
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
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010da20a8)
Location: kernel/sched/core.c:5768
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffff80001013caf0-ffff80001013cb24: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0e9a214)
Location: kernel/sched/core.c:5768
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
c038ce24-c038ce58: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000ee352c)
Location: kernel/sched/core.c:5768
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
c00000000018b1d0-c00000000018b1ec: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0008c57b0)
Location: kernel/sched/core.c:5768
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffe0000ec128-ffffffe0000ec158: io_schedule_finish (STB_GLOBAL)
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
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a6f176)
Location: kernel/sched/core.c:5768
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810d7250-ffffffff810d727d: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a2b5a6)
Location: kernel/sched/core.c:5768
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810c5b40-ffffffff810c5b6d: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81adb586)
Location: kernel/sched/core.c:5768
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810d3e90-ffffffff810d3ebd: io_schedule_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void io_schedule_finish(int token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81ae7b26)
Location: kernel/sched/core.c:5768
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810dee30-ffffffff810dee5d: io_schedule_finish (STB_GLOBAL)
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
