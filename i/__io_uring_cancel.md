# Function: <code>__io_uring_cancel</code>

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
void __io_uring_cancel(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813a1c90)
Location: fs/io_uring.c:9162
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff813a1c90-ffffffff813a1ea6: __io_uring_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __io_uring_cancel(bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813f0cb0)
Location: fs/io_uring.c:9871
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff813f0cb0-ffffffff813f0cc6: __io_uring_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __io_uring_cancel(bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e92ce3)
Location: io_uring/io_uring.c:11262
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff81e92ce3-ffffffff81e92d01: __io_uring_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __io_uring_cancel(bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817927d0)
Location: io_uring/io_uring.c:3162
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff817927d0-ffffffff817927ee: __io_uring_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __io_uring_cancel(bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d3540)
Location: io_uring/io_uring.c:3390
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff817d3540-ffffffff817d355e: __io_uring_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __io_uring_cancel(bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81817350)
Location: io_uring/io_uring.c:3411
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff81817350-ffffffff8181736e: __io_uring_cancel (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool cancel_all</code>
</li>
<li>
<b>Param removed. </b>
<code>struct files_struct *files</code>
</li>
</ul>
</details>
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
