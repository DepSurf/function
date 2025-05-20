# Function: <code>prb_read</code>

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
int prb_read(struct printk_ringbuffer *rb, u64 seq, struct printk_record *r, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c190)
Location: kernel/printk/printk_ringbuffer.c:1785
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
```
**Symbols:**

```
ffffffff8111c190-ffffffff8111c399: prb_read (STB_LOCAL)
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
In kernel/printk/printk_ringbuffer.c (ffffffff8111c62e)
Location: kernel/printk/printk_ringbuffer.c:1785
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
In kernel/printk/printk_ringbuffer.c (ffffffff8113ccee)
Location: kernel/printk/printk_ringbuffer.c:1785
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
In kernel/printk/printk_ringbuffer.c (ffffffff81160231)
Location: kernel/printk/printk_ringbuffer.c:1796
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int prb_read(struct printk_ringbuffer *rb, u64 seq, struct printk_record *r, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1796
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
```
**Symbols:**

```
ffffffff81193710-ffffffff81193894: prb_read (STB_LOCAL)
ffffffff82059451-ffffffff820594a9: prb_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int prb_read(struct printk_ringbuffer *rb, u64 seq, struct printk_record *r, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1796
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
```
**Symbols:**

```
ffffffff811a4f70-ffffffff811a50f4: prb_read (STB_LOCAL)
ffffffff820d7aab-ffffffff820d7af6: prb_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int prb_read(struct printk_ringbuffer *rb, u64 seq, struct printk_record *r, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1796
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
```
**Symbols:**

```
ffffffff811b4a60-ffffffff811b4be4: prb_read (STB_LOCAL)
ffffffff821b2d2c-ffffffff821b2d77: prb_read.cold (STB_LOCAL)
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
