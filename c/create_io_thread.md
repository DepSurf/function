# Function: <code>create_io_thread</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *create_io_thread(int (*fn)(void *), void *arg, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3a70)
Location: kernel/fork.c:2447
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_offload_create
  - fs/io-wq.c:create_io_worker
```
**Symbols:**

```
ffffffff810a3a70-ffffffff810a3ad6: create_io_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *create_io_thread(int (*fn)(void *), void *arg, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b5290)
Location: kernel/fork.c:2540
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_offload_create
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff810b5290-ffffffff810b52f6: create_io_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *create_io_thread(int (*fn)(void *), void *arg, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cb5a0)
Location: kernel/fork.c:2600
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff810cb5a0-ffffffff810cb61e: create_io_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *create_io_thread(int (*fn)(void *), void *arg, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e8b50)
Location: kernel/fork.c:2625
Inline: False
Direct callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff810e8b50-ffffffff810e8bce: create_io_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *create_io_thread(int (*fn)(void *), void *arg, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f4760)
Location: kernel/fork.c:2855
Inline: False
Direct callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff810f4760-ffffffff810f47db: create_io_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *create_io_thread(int (*fn)(void *), void *arg, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fdb00)
Location: kernel/fork.c:2845
Inline: False
Direct callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff810fdb00-ffffffff810fdb7b: create_io_thread (STB_GLOBAL)
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
