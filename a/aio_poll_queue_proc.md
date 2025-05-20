# Function: <code>aio_poll_queue_proc</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81306b80)
Location: fs/aio.c:1706
Inline: False
```
**Symbols:**

```
ffffffff81306b80-ffffffff81306bb9: aio_poll_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81328130)
Location: fs/aio.c:1701
Inline: False
```
**Symbols:**

```
ffffffff81328130-ffffffff81328169: aio_poll_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133aed0)
Location: fs/aio.c:1717
Inline: False
```
**Symbols:**

```
ffffffff8133aed0-ffffffff8133af09: aio_poll_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81375170)
Location: fs/aio.c:1724
Inline: False
```
**Symbols:**

```
ffffffff81375170-ffffffff813751a9: aio_poll_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81383020)
Location: fs/aio.c:1722
Inline: False
```
**Symbols:**

```
ffffffff81383020-ffffffff81383059: aio_poll_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138a090)
Location: fs/aio.c:1719
Inline: False
```
**Symbols:**

```
ffffffff8138a090-ffffffff8138a0c9: aio_poll_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1822
Inline: False
```
**Symbols:**

```
ffffffff813d7370-ffffffff813d73d1: aio_poll_queue_proc (STB_LOCAL)
ffffffff81cc5714-ffffffff81cc5730: aio_poll_queue_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1846
Inline: False
```
**Symbols:**

```
ffffffff81460f60-ffffffff81460fdc: aio_poll_queue_proc (STB_LOCAL)
ffffffff81e780fa-ffffffff81e78117: aio_poll_queue_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1847
Inline: False
```
**Symbols:**

```
ffffffff814f0ed0-ffffffff814f0f4c: aio_poll_queue_proc (STB_LOCAL)
ffffffff8206a030-ffffffff8206a04d: aio_poll_queue_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1839
Inline: False
```
**Symbols:**

```
ffffffff81527ff0-ffffffff8152806c: aio_poll_queue_proc (STB_LOCAL)
ffffffff820e9fcc-ffffffff820e9fe9: aio_poll_queue_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:1882
Inline: False
```
**Symbols:**

```
ffffffff8155d030-ffffffff8155d0ac: aio_poll_queue_proc (STB_LOCAL)
ffffffff821c6aae-ffffffff821c6acb: aio_poll_queue_proc.cold (STB_LOCAL)
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
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fa030)
Location: fs/aio.c:1717
Inline: False
```
**Symbols:**

```
ffff8000103fa030-ffff8000103fa090: aio_poll_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05ce49c)
Location: fs/aio.c:1717
Inline: False
```
**Symbols:**

```
c05ce49c-c05ce4e8: aio_poll_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000502fe0)
Location: fs/aio.c:1717
Inline: False
```
**Symbols:**

```
c000000000502fe0-c00000000050304c: aio_poll_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002a93da)
Location: fs/aio.c:1717
Inline: False
```
**Symbols:**

```
ffffffe0002a93da-ffffffe0002a942c: aio_poll_queue_proc (STB_LOCAL)
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
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813334b0)
Location: fs/aio.c:1717
Inline: False
```
**Symbols:**

```
ffffffff813334b0-ffffffff813334e9: aio_poll_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81324120)
Location: fs/aio.c:1717
Inline: False
```
**Symbols:**

```
ffffffff81324120-ffffffff81324159: aio_poll_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81330f80)
Location: fs/aio.c:1717
Inline: False
```
**Symbols:**

```
ffffffff81330f80-ffffffff81330fb9: aio_poll_queue_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aio_poll_queue_proc(struct file *file, struct wait_queue_head *head, struct poll_table_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81343b60)
Location: fs/aio.c:1717
Inline: False
```
**Symbols:**

```
ffffffff81343b60-ffffffff81343b99: aio_poll_queue_proc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
