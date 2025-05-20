# Function: <code>desc_read_finalized_seq</code>

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
int desc_read_finalized_seq(struct prb_desc_ring *desc_ring, long unsigned int id, u64 seq, struct prb_desc *desc_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c100)
Location: kernel/printk/printk_ringbuffer.c:1744
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_read
  - kernel/printk/printk_ringbuffer.c:prb_read
```
**Symbols:**

```
ffffffff8111c100-ffffffff8111c18e: desc_read_finalized_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int desc_read_finalized_seq(struct prb_desc_ring *desc_ring, long unsigned int id, u64 seq, struct prb_desc *desc_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c560)
Location: kernel/printk/printk_ringbuffer.c:1744
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
```
**Symbols:**

```
ffffffff8111c560-ffffffff8111c5ee: desc_read_finalized_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int desc_read_finalized_seq(struct prb_desc_ring *desc_ring, long unsigned int id, u64 seq, struct prb_desc *desc_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8113c680)
Location: kernel/printk/printk_ringbuffer.c:1744
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
```
**Symbols:**

```
ffffffff8113c680-ffffffff8113c70e: desc_read_finalized_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int desc_read_finalized_seq(struct prb_desc_ring *desc_ring, long unsigned int id, u64 seq, struct prb_desc *desc_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8115f8e0)
Location: kernel/printk/printk_ringbuffer.c:1755
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
```
**Symbols:**

```
ffffffff8115f8e0-ffffffff8115f985: desc_read_finalized_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int desc_read_finalized_seq(struct prb_desc_ring *desc_ring, long unsigned int id, u64 seq, struct prb_desc *desc_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff81192c60)
Location: kernel/printk/printk_ringbuffer.c:1755
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_read
  - kernel/printk/printk_ringbuffer.c:prb_read
```
**Symbols:**

```
ffffffff81192c60-ffffffff81192d05: desc_read_finalized_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int desc_read_finalized_seq(struct prb_desc_ring *desc_ring, long unsigned int id, u64 seq, struct prb_desc *desc_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811a44c0)
Location: kernel/printk/printk_ringbuffer.c:1755
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_read
  - kernel/printk/printk_ringbuffer.c:prb_read
```
**Symbols:**

```
ffffffff811a44c0-ffffffff811a4565: desc_read_finalized_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int desc_read_finalized_seq(struct prb_desc_ring *desc_ring, long unsigned int id, u64 seq, struct prb_desc *desc_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811b3fb0)
Location: kernel/printk/printk_ringbuffer.c:1755
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_read
  - kernel/printk/printk_ringbuffer.c:prb_read
```
**Symbols:**

```
ffffffff811b3fb0-ffffffff811b4055: desc_read_finalized_seq (STB_LOCAL)
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
