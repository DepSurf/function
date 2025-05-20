# Function: <code>io_poll_rewait</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool io_poll_rewait(struct io_kiocb *req, struct io_poll_iocb *poll);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137ba40)
Location: fs/io_uring.c:4205
Inline: False
Direct callers:
  - fs/io_uring.c:io_async_task_func
```
**Symbols:**

```
ffffffff8137ba40-ffffffff8137bb19: io_poll_rewait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool io_poll_rewait(struct io_kiocb *req, struct io_poll_iocb *poll);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81389a00)
Location: fs/io_uring.c:5180
Inline: False
Direct callers:
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
**Symbols:**

```
ffffffff81389a00-ffffffff81389ad0: io_poll_rewait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_poll_rewait(struct io_kiocb *req, struct io_poll_iocb *poll);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390ac0)
Location: fs/io_uring.c:4878
Inline: False
Direct callers:
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
**Symbols:**

```
ffffffff81390ac0-ffffffff81390b8e: io_poll_rewait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool io_poll_rewait(struct io_kiocb *req, struct io_poll_iocb *poll);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:5329
Inline: False
Direct callers:
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
**Symbols:**

```
ffffffff813de410-ffffffff813de513: io_poll_rewait (STB_LOCAL)
ffffffff81cc5843-ffffffff81cc586c: io_poll_rewait.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
