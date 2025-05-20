# Function: <code>wq_worker_sleeping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *wq_worker_sleeping(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b380)
Location: kernel/workqueue.c:855
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8109b380-ffffffff8109b406: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109e980)
Location: kernel/workqueue.c:874
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8109e980-ffffffff8109e9fe: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a36b0)
Location: kernel/workqueue.c:876
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810a36b0-ffffffff810a372e: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0990)
Location: kernel/workqueue.c:876
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810a0990-ffffffff810a09ef: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a7220)
Location: kernel/workqueue.c:878
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810a7220-ffffffff810a727f: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810adde0)
Location: kernel/workqueue.c:876
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810adde0-ffffffff810ade3f: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b6ed0)
Location: kernel/workqueue.c:876
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810b6ed0-ffffffff810b6f2f: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd920)
Location: kernel/workqueue.c:868
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff810bd920-ffffffff810bd9a8: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2fb0)
Location: kernel/workqueue.c:869
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff810c2fb0-ffffffff810c3038: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810caa20)
Location: kernel/workqueue.c:865
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff810caa20-ffffffff810caaac: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5b50)
Location: kernel/workqueue.c:865
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff810c5b50-ffffffff810c5bdc: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7480)
Location: kernel/workqueue.c:866
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff810c7480-ffffffff810c750c: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810da1a0)
Location: kernel/workqueue.c:892
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff810da1a0-ffffffff810da22c: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f38a0)
Location: kernel/workqueue.c:892
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff810f38a0-ffffffff810f393f: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81115a10)
Location: kernel/workqueue.c:892
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff81115a10-ffffffff81115aaf: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81122630)
Location: kernel/workqueue.c:1090
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff81122630-ffffffff811226db: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112c670)
Location: kernel/workqueue.c:1284
Inline: False
Direct callers:
  - kernel/sched/core.c:rt_mutex_pre_schedule
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff8112c670-ffffffff8112c6f0: wq_worker_sleeping (STB_GLOBAL)
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
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010120ca8)
Location: kernel/workqueue.c:869
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffff800010120ca8-ffff800010120dc0: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0374c38)
Location: kernel/workqueue.c:869
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
c0374c38-c0374d34: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016a0e0)
Location: kernel/workqueue.c:869
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
c00000000016a0e0-c00000000016a210: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d9c6a)
Location: kernel/workqueue.c:869
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffe0000d9c6a-ffffffe0000d9d2e: wq_worker_sleeping (STB_GLOBAL)
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
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd320)
Location: kernel/workqueue.c:869
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff810bd320-ffffffff810bd3a8: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810abb50)
Location: kernel/workqueue.c:869
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff810abb50-ffffffff810abbd2: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bc880)
Location: kernel/workqueue.c:869
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff810bc880-ffffffff810bc908: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wq_worker_sleeping(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4c10)
Location: kernel/workqueue.c:869
Inline: False
Direct callers:
  - kernel/sched/core.c:schedule
```
**Symbols:**

```
ffffffff810c4c10-ffffffff810c4c8f: wq_worker_sleeping (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
</ul>
</details>
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct task_struct *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
