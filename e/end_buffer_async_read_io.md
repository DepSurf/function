# Function: <code>end_buffer_async_read_io</code>

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
void end_buffer_async_read_io(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135b590)
Location: fs/buffer.c:320
Inline: False
```
**Symbols:**

```
ffffffff8135b590-ffffffff8135b61c: end_buffer_async_read_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void end_buffer_async_read_io(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81369700)
Location: fs/buffer.c:320
Inline: False
```
**Symbols:**

```
ffffffff81369700-ffffffff813697a3: end_buffer_async_read_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void end_buffer_async_read_io(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136f860)
Location: fs/buffer.c:320
Inline: False
```
**Symbols:**

```
ffffffff8136f860-ffffffff8136f903: end_buffer_async_read_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void end_buffer_async_read_io(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813be300)
Location: fs/buffer.c:320
Inline: False
```
**Symbols:**

```
ffffffff813be300-ffffffff813be3a3: end_buffer_async_read_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void end_buffer_async_read_io(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81445ee0)
Location: fs/buffer.c:320
Inline: False
```
**Symbols:**

```
ffffffff81445ee0-ffffffff81445f98: end_buffer_async_read_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void end_buffer_async_read_io(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d4620)
Location: fs/buffer.c:320
Inline: False
```
**Symbols:**

```
ffffffff814d4620-ffffffff814d46d8: end_buffer_async_read_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void end_buffer_async_read_io(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150ad90)
Location: fs/buffer.c:352
Inline: False
```
**Symbols:**

```
ffffffff8150ad90-ffffffff8150aed4: end_buffer_async_read_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void end_buffer_async_read_io(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153fc50)
Location: fs/buffer.c:347
Inline: False
```
**Symbols:**

```
ffffffff8153fc50-ffffffff8153fe05: end_buffer_async_read_io (STB_LOCAL)
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
