# Function: <code>io_uring_cancel_generic</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void io_uring_cancel_generic(bool cancel_all, struct io_sq_data *sqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:9806
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_cancel
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff813f05e0-ffffffff813f06b1: io_uring_cancel_generic (STB_LOCAL)
ffffffff81cc5d6c-ffffffff81cc5f44: io_uring_cancel_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_uring_cancel_generic(bool cancel_all, struct io_sq_data *sqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e929c0)
Location: io_uring/io_uring.c:11196
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_cancel
  - io_uring/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff81e929c0-ffffffff81e92c53: io_uring_cancel_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_uring_cancel_generic(bool cancel_all, struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817924f0)
Location: io_uring/io_uring.c:3089
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_cancel
  - io_uring/sqpoll.c:io_sq_thread
```
**Symbols:**

```
ffffffff817924f0-ffffffff817927bb: io_uring_cancel_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_uring_cancel_generic(bool cancel_all, struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d31f0)
Location: io_uring/io_uring.c:3311
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_cancel
  - io_uring/sqpoll.c:io_sq_thread
```
**Symbols:**

```
ffffffff817d31f0-ffffffff817d352f: io_uring_cancel_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_uring_cancel_generic(bool cancel_all, struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81817000)
Location: io_uring/io_uring.c:3332
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_cancel
  - io_uring/sqpoll.c:io_sq_thread
```
**Symbols:**

```
ffffffff81817000-ffffffff8181733f: io_uring_cancel_generic (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
