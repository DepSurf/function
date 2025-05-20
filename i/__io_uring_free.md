# Function: <code>__io_uring_free</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __io_uring_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139a950)
Location: fs/io_uring.c:8165
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff8139a950-ffffffff8139a9c5: __io_uring_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __io_uring_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813a1c30)
Location: fs/io_uring.c:7961
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
  - fs/io_uring.c:__io_uring_cancel
```
**Symbols:**

```
ffffffff813a1c30-ffffffff813a1c86: __io_uring_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __io_uring_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813f0570)
Location: fs/io_uring.c:8673
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
  - fs/io_uring.c:io_uring_cancel_generic
```
**Symbols:**

```
ffffffff813f0570-ffffffff813f05d8: __io_uring_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __io_uring_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d8f10)
Location: io_uring/io_uring.c:9958
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
  - io_uring/io_uring.c:io_uring_cancel_generic
```
**Symbols:**

```
ffffffff816d8f10-ffffffff816d8f85: __io_uring_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __io_uring_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/tctx.c (ffffffff8179b9c0)
Location: io_uring/tctx.c:47
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
  - io_uring/io_uring.c:io_uring_cancel_generic
```
**Symbols:**

```
ffffffff8179b9c0-ffffffff8179ba2f: __io_uring_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __io_uring_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/tctx.c (ffffffff817dcaf0)
Location: io_uring/tctx.c:47
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
  - io_uring/io_uring.c:io_uring_cancel_generic
```
**Symbols:**

```
ffffffff817dcaf0-ffffffff817dcb5f: __io_uring_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __io_uring_free(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/tctx.c (ffffffff81820d90)
Location: io_uring/tctx.c:47
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
  - io_uring/io_uring.c:io_uring_cancel_generic
```
**Symbols:**

```
ffffffff81820d90-ffffffff81820e06: __io_uring_free (STB_GLOBAL)
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
