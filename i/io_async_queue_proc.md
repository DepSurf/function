# Function: <code>io_async_queue_proc</code>

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
void io_async_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81380310)
Location: fs/io_uring.c:4376
Inline: False
```
**Symbols:**

```
ffffffff81380310-ffffffff81380414: io_async_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_async_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138fd90)
Location: fs/io_uring.c:5350
Inline: False
```
**Symbols:**

```
ffffffff8138fd90-ffffffff8138fdb8: io_async_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_async_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81396fe0)
Location: fs/io_uring.c:5083
Inline: False
```
**Symbols:**

```
ffffffff81396fe0-ffffffff81397008: io_async_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_async_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813de190)
Location: fs/io_uring.c:5555
Inline: False
```
**Symbols:**

```
ffffffff813de190-ffffffff813de1b8: io_async_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_async_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c8610)
Location: io_uring/io_uring.c:6968
Inline: False
```
**Symbols:**

```
ffffffff816c8610-ffffffff816c8646: io_async_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_async_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff8179c780)
Location: io_uring/poll.c:644
Inline: False
```
**Symbols:**

```
ffffffff8179c780-ffffffff8179c7b6: io_async_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_async_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff817ddad0)
Location: io_uring/poll.c:646
Inline: False
```
**Symbols:**

```
ffffffff817ddad0-ffffffff817ddb06: io_async_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_async_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff81821e70)
Location: io_uring/poll.c:667
Inline: False
```
**Symbols:**

```
ffffffff81821e70-ffffffff81821ea6: io_async_queue_proc (STB_LOCAL)
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
