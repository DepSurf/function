# Function: <code>copy_data</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c28e)
Location: kernel/printk/printk_ringbuffer.c:1694
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c71a)
Location: kernel/printk/printk_ringbuffer.c:1694
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8113cdd7)
Location: kernel/printk/printk_ringbuffer.c:1694
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8116033a)
Location: kernel/printk/printk_ringbuffer.c:1705
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool copy_data(struct prb_data_ring *data_ring, struct prb_data_blk_lpos *blk_lpos, u16 len, char *buf, unsigned int buf_size, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811935d0)
Location: kernel/printk/printk_ringbuffer.c:1705
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_read
```
**Symbols:**

```
ffffffff811935d0-ffffffff811936f1: copy_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool copy_data(struct prb_data_ring *data_ring, struct prb_data_blk_lpos *blk_lpos, u16 len, char *buf, unsigned int buf_size, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811a4e30)
Location: kernel/printk/printk_ringbuffer.c:1705
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_read
```
**Symbols:**

```
ffffffff811a4e30-ffffffff811a4f53: copy_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool copy_data(struct prb_data_ring *data_ring, struct prb_data_blk_lpos *blk_lpos, u16 len, char *buf, unsigned int buf_size, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811b4920)
Location: kernel/printk/printk_ringbuffer.c:1705
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_read
```
**Symbols:**

```
ffffffff811b4920-ffffffff811b4a43: copy_data (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
