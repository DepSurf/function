# Function: <code>io_sq_thread</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81330a70)
Location: fs/io_uring.c:2304
Inline: False
```
**Symbols:**

```
ffffffff81330a70-ffffffff81330e22: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81344430)
Location: fs/io_uring.c:2731
Inline: False
```
**Symbols:**

```
ffffffff81344430-ffffffff8134475e: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813892e0)
Location: fs/io_uring.c:6139
Inline: False
```
**Symbols:**

```
ffffffff813892e0-ffffffff813896fa: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81399d50)
Location: fs/io_uring.c:7066
Inline: False
```
**Symbols:**

```
ffffffff81399d50-ffffffff8139a2a4: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813a0e50)
Location: fs/io_uring.c:6855
Inline: False
```
**Symbols:**

```
ffffffff813a0e50-ffffffff813a1561: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813f06c0)
Location: fs/io_uring.c:7462
Inline: False
```
**Symbols:**

```
ffffffff813f06c0-ffffffff813f0caf: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:8755
Inline: False
```
**Symbols:**

```
ffffffff816d8f90-ffffffff816d9491: io_sq_thread (STB_LOCAL)
ffffffff81e92c53-ffffffff81e92ce3: io_sq_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff8179a410)
Location: io_uring/sqpoll.c:221
Inline: False
```
**Symbols:**

```
ffffffff8179a410-ffffffff8179a92d: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff817db470)
Location: io_uring/sqpoll.c:221
Inline: False
```
**Symbols:**

```
ffffffff817db470-ffffffff817db9d3: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff8181f7b0)
Location: io_uring/sqpoll.c:222
Inline: False
```
**Symbols:**

```
ffffffff8181f7b0-ffffffff8181fd57: io_sq_thread (STB_LOCAL)
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
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010406030)
Location: fs/io_uring.c:2731
Inline: False
```
**Symbols:**

```
ffff800010406030-ffff8000104063c4: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d5bec)
Location: fs/io_uring.c:2731
Inline: False
```
**Symbols:**

```
c05d5bec-c05d5f9c: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050eea0)
Location: fs/io_uring.c:2731
Inline: False
```
**Symbols:**

```
c00000000050eea0-c00000000050f368: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002afb26)
Location: fs/io_uring.c:2731
Inline: False
```
**Symbols:**

```
ffffffe0002afb26-ffffffe0002afe04: io_sq_thread (STB_LOCAL)
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
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133ca10)
Location: fs/io_uring.c:2731
Inline: False
```
**Symbols:**

```
ffffffff8133ca10-ffffffff8133cd3e: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132d6e0)
Location: fs/io_uring.c:2731
Inline: False
```
**Symbols:**

```
ffffffff8132d6e0-ffffffff8132da0e: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133a4e0)
Location: fs/io_uring.c:2731
Inline: False
```
**Symbols:**

```
ffffffff8133a4e0-ffffffff8133a80e: io_sq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_sq_thread(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134d040)
Location: fs/io_uring.c:2731
Inline: False
```
**Symbols:**

```
ffffffff8134d040-ffffffff8134d36c: io_sq_thread (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
