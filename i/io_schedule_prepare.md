# Function: <code>io_schedule_prepare</code>

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
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b30f0)
Location: kernel/sched/core.c:4961
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff810b30f0-ffffffff810b3135: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba4f0)
Location: kernel/sched/core.c:5006
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff810ba4f0-ffffffff810ba535: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1b80)
Location: kernel/sched/core.c:5131
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff810c1b80-ffffffff810c1bc5: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810caeb0)
Location: kernel/sched/core.c:5114
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810caeb0-ffffffff810caef5: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2b80)
Location: kernel/sched/core.c:5567
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810d2b80-ffffffff810d2bcb: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dcff0)
Location: kernel/sched/core.c:5758
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810dcff0-ffffffff810dd03b: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81bc8945)
Location: kernel/sched/core.c:5991
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
```
**Symbols:**

```
ffffffff810e5bd0-ffffffff810e5c1d: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81c41715)
Location: kernel/sched/core.c:6811
Inline: True
Inline callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
Direct callers:
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
```
**Symbols:**

```
ffffffff810e37f0-ffffffff810e383e: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81c33685)
Location: kernel/sched/core.c:7162
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
ffffffff810e5980-ffffffff810e59ce: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81d51f85)
Location: kernel/sched/core.c:8360
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
ffffffff810fca60-ffffffff810fcaae: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81f22565)
Location: kernel/sched/core.c:8652
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
ffffffff81119380-ffffffff811193d3: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff820cce05)
Location: kernel/sched/core.c:8836
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
ffffffff81140c20-ffffffff81140c73: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82151215)
Location: kernel/sched/core.c:8993
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
ffffffff8114c940-ffffffff8114c993: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82233fc5)
Location: kernel/sched/core.c:8988
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
ffffffff81158600-ffffffff81158653: io_schedule_prepare (STB_GLOBAL)
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
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013caa8)
Location: kernel/sched/core.c:5758
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffff80001013caa8-ffff80001013caf0: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038cdd0)
Location: kernel/sched/core.c:5758
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
c038cdd0-c038ce24: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018b160)
Location: kernel/sched/core.c:5758
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
c00000000018b160-c00000000018b1c8: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ec0e4)
Location: kernel/sched/core.c:5758
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffe0000ec0e4-ffffffe0000ec128: io_schedule_prepare (STB_GLOBAL)
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
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7200)
Location: kernel/sched/core.c:5758
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810d7200-ffffffff810d724b: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c5af0)
Location: kernel/sched/core.c:5758
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810c5af0-ffffffff810c5b3b: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3e40)
Location: kernel/sched/core.c:5758
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810d3e40-ffffffff810d3e8b: io_schedule_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_schedule_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dede0)
Location: kernel/sched/core.c:5758
Inline: False
Direct callers:
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/locking/mutex.c:mutex_lock_io
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810dede0-ffffffff810dee2b: io_schedule_prepare (STB_GLOBAL)
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
