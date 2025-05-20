# Function: <code>kthread_create_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a0c90)
Location: kernel/kthread.c:395
Inline: False
```
**Symbols:**

```
ffffffff810a0c90-ffffffff810a0cee: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a4380)
Location: kernel/kthread.c:395
Inline: False
```
**Symbols:**

```
ffffffff810a4380-ffffffff810a43de: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a9bf0)
Location: kernel/kthread.c:425
Inline: False
```
**Symbols:**

```
ffffffff810a9bf0-ffffffff810a9ca6: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6830)
Location: kernel/kthread.c:429
Inline: False
```
**Symbols:**

```
ffffffff810a6830-ffffffff810a68c8: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810acfa0)
Location: kernel/kthread.c:436
Inline: False
```
**Symbols:**

```
ffffffff810acfa0-ffffffff810ad038: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3d00)
Location: kernel/kthread.c:450
Inline: False
```
**Symbols:**

```
ffffffff810b3d00-ffffffff810b3da2: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bce50)
Location: kernel/kthread.c:450
Inline: False
```
**Symbols:**

```
ffffffff810bce50-ffffffff810bcef2: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (0)
Location: kernel/kthread.c:459
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff810c33c8-ffffffff810c33ee: kthread_create_on_cpu.cold (STB_LOCAL)
ffffffff810c2d30-ffffffff810c2dcb: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c9300)
Location: kernel/kthread.c:459
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff810c9300-ffffffff810c939b: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d16f0)
Location: kernel/kthread.c:495
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_offload_start
```
**Symbols:**

```
ffffffff810d16f0-ffffffff810d178b: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cc120)
Location: kernel/kthread.c:496
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_offload_create
```
**Symbols:**

```
ffffffff810cc120-ffffffff810cc1a3: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cdc00)
Location: kernel/kthread.c:523
Inline: False
```
**Symbols:**

```
ffffffff810cdc00-ffffffff810cdc83: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0e30)
Location: kernel/kthread.c:523
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:start_cpu_kthread
```
**Symbols:**

```
ffffffff810e0e30-ffffffff810e0ed8: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810f9fa0)
Location: kernel/kthread.c:582
Inline: False
Direct callers:
  - kernel/smpboot.c:__smpboot_create_thread
  - kernel/trace/trace_hwlat.c:start_cpu_kthread
```
**Symbols:**

```
ffffffff810f9fa0-ffffffff810fa059: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111cd10)
Location: kernel/kthread.c:582
Inline: False
Direct callers:
  - kernel/smpboot.c:__smpboot_create_thread
  - kernel/trace/trace_hwlat.c:start_cpu_kthread
```
**Symbols:**

```
ffffffff8111cd10-ffffffff8111cdc9: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81129e30)
Location: kernel/kthread.c:583
Inline: False
Direct callers:
  - kernel/smpboot.c:__smpboot_create_thread
  - kernel/trace/trace_hwlat.c:start_cpu_kthread
  - kernel/trace/trace_osnoise.c:start_kthread
```
**Symbols:**

```
ffffffff81129e30-ffffffff81129ee9: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff811344a0)
Location: kernel/kthread.c:582
Inline: False
Direct callers:
  - kernel/smpboot.c:__smpboot_create_thread
  - kernel/trace/trace_hwlat.c:start_cpu_kthread
  - kernel/trace/trace_osnoise.c:start_kthread
```
**Symbols:**

```
ffffffff811344a0-ffffffff81134559: kthread_create_on_cpu (STB_GLOBAL)
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
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128f80)
Location: kernel/kthread.c:459
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffff800010128f80-ffff80001012905c: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037b500)
Location: kernel/kthread.c:459
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
c037b500-c037b5bc: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000173770)
Location: kernel/kthread.c:459
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
c000000000173770-c000000000173850: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000dfe44)
Location: kernel/kthread.c:459
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffe0000dfe44-ffffffe0000dfee2: kthread_create_on_cpu (STB_GLOBAL)
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
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c3680)
Location: kernel/kthread.c:459
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff810c3680-ffffffff810c371b: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1eb0)
Location: kernel/kthread.c:459
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff810b1eb0-ffffffff810b1f4b: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2bd0)
Location: kernel/kthread.c:459
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff810c2bd0-ffffffff810c2c6b: kthread_create_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *kthread_create_on_cpu(int (*threadfn)(void *), void *data, unsigned int cpu, const char *namefmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb010)
Location: kernel/kthread.c:459
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff810cb010-ffffffff810cb0ab: kthread_create_on_cpu (STB_GLOBAL)
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
