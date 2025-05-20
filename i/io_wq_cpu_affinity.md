# Function: <code>io_wq_cpu_affinity</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_wq_cpu_affinity(struct io_wq *wq, cpumask_var_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f3230)
Location: fs/io-wq.c:1324
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff813f3230-ffffffff813f330b: io_wq_cpu_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_wq_cpu_affinity(struct io_wq *wq, cpumask_var_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816dbdb0)
Location: io_uring/io-wq.c:1350
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff816dbdb0-ffffffff816dbea6: io_wq_cpu_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_wq_cpu_affinity(struct io_wq *wq, cpumask_var_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a7ec0)
Location: io_uring/io-wq.c:1343
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff817a7ec0-ffffffff817a7fa6: io_wq_cpu_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int io_wq_cpu_affinity(struct io_uring_task *tctx, cpumask_var_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:1298
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_register_iowq_aff
  - io_uring/sqpoll.c:io_sqpoll_wq_cpu_affinity
```
**Symbols:**

```
ffffffff820f7c3e-ffffffff820f7c53: io_wq_cpu_affinity.cold (STB_LOCAL)
ffffffff817e8cf0-ffffffff817e8e68: io_wq_cpu_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int io_wq_cpu_affinity(struct io_uring_task *tctx, cpumask_var_t mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:1317
Inline: False
Direct callers:
  - io_uring/sqpoll.c:io_sqpoll_wq_cpu_affinity
  - io_uring/register.c:__io_uring_register
  - io_uring/register.c:io_register_iowq_aff
```
**Symbols:**

```
ffffffff821d560e-ffffffff821d5623: io_wq_cpu_affinity.cold (STB_LOCAL)
ffffffff8182eaa0-ffffffff8182ec18: io_wq_cpu_affinity (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_uring_task *tctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_wq *wq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
