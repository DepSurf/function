# Function: <code>perf_event_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct perf_event *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81184c90)
Location: kernel/events/core.c:8967
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81184c90-ffffffff81184ce3: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81196ac0)
Location: kernel/events/core.c:10152
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81196ac0-ffffffff81196af2: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a6590)
Location: kernel/events/core.c:10423
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811a6590-ffffffff811a65c2: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811adce0)
Location: kernel/events/core.c:10660
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811adce0-ffffffff811add12: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811c1860)
Location: kernel/events/core.c:10692
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811c1860-ffffffff811c1892: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e1bb0)
Location: kernel/events/core.c:11222
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811e1bb0-ffffffff811e1be4: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f2020)
Location: kernel/events/core.c:11265
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811f2020-ffffffff811f2054: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81209c60)
Location: kernel/events/core.c:11632
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81209c60-ffffffff81209c94: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81216fd0)
Location: kernel/events/core.c:11745
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81216fd0-ffffffff81217004: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242c20)
Location: kernel/events/core.c:12348
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81242c20-ffffffff81242c54: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124d370)
Location: kernel/events/core.c:12632
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8124d370-ffffffff8124d3a4: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81251c30)
Location: kernel/events/core.c:12818
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff81251c30-ffffffff81251c64: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128d450)
Location: kernel/events/core.c:12939
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8128d450-ffffffff8128d484: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e2180)
Location: kernel/events/core.c:12909
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff812e2180-ffffffff812e21bc: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8134a6f0)
Location: kernel/events/core.c:13147
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8134a6f0-ffffffff8134a72c: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8137b730)
Location: kernel/events/core.c:13189
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8137b730-ffffffff8137b76f: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a4930)
Location: kernel/events/core.c:13285
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff813a4930-ffffffff813a496f: perf_event_get (STB_GLOBAL)
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
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102a1248)
Location: kernel/events/core.c:11745
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffff8000102a1248-ffff8000102a1298: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04d13f0)
Location: kernel/events/core.c:11745
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
c04d13f0-c04d1430: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003534c0)
Location: kernel/events/core.c:11745
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
c0000000003534c0-c000000000353538: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001d05ba)
Location: kernel/events/core.c:11745
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffe0001d05ba-ffffffe0001d05fc: perf_event_get (STB_GLOBAL)
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
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120f620)
Location: kernel/events/core.c:11745
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8120f620-ffffffff8120f654: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812023b0)
Location: kernel/events/core.c:11745
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff812023b0-ffffffff812023e4: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120d3c0)
Location: kernel/events/core.c:11745
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8120d3c0-ffffffff8120d3f4: perf_event_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *perf_event_get(unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8121c260)
Location: kernel/events/core.c:11745
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8121c260-ffffffff8121c294: perf_event_get (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>struct perf_event *</code> ➡️ <code>struct file *</code>
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
