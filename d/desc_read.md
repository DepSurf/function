# Function: <code>desc_read</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
enum desc_state desc_read(struct prb_desc_ring *desc_ring, long unsigned int id, struct prb_desc *desc_out, u64 *seq_out, u32 *caller_id_out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c575)
Location: kernel/printk/printk_ringbuffer.c:432
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:data_make_reusable
Direct callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:desc_push_tail
  - kernel/printk/printk_ringbuffer.c:desc_push_tail
```
**Symbols:**

```
ffffffff8111c040-ffffffff8111c0f1: desc_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum desc_state desc_read(struct prb_desc_ring *desc_ring, long unsigned int id, struct prb_desc *desc_out, u64 *seq_out, u32 *caller_id_out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c4a0)
Location: kernel/printk/printk_ringbuffer.c:432
Inline: True
Direct callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff8111c4a0-ffffffff8111c551: desc_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum desc_state desc_read(struct prb_desc_ring *desc_ring, long unsigned int id, struct prb_desc *desc_out, u64 *seq_out, u32 *caller_id_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:432
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff8113c590-ffffffff8113c671: desc_read (STB_LOCAL)
ffffffff81cac885-ffffffff81cac8fa: desc_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum desc_state desc_read(struct prb_desc_ring *desc_ring, long unsigned int id, struct prb_desc *desc_out, u64 *seq_out, u32 *caller_id_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:432
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
**Symbols:**

```
ffffffff8115f7e0-ffffffff8115f8d9: desc_read (STB_LOCAL)
ffffffff81e5ce2b-ffffffff81e5ce9e: desc_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum desc_state desc_read(struct prb_desc_ring *desc_ring, long unsigned int id, struct prb_desc *desc_out, u64 *seq_out, u32 *caller_id_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:432
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
**Symbols:**

```
ffffffff81192b50-ffffffff81192c49: desc_read (STB_LOCAL)
ffffffff82058e25-ffffffff82058e98: desc_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum desc_state desc_read(struct prb_desc_ring *desc_ring, long unsigned int id, struct prb_desc *desc_out, u64 *seq_out, u32 *caller_id_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:432
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
**Symbols:**

```
ffffffff811a43b0-ffffffff811a44a9: desc_read (STB_LOCAL)
ffffffff820d75c0-ffffffff820d7620: desc_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum desc_state desc_read(struct prb_desc_ring *desc_ring, long unsigned int id, struct prb_desc *desc_out, u64 *seq_out, u32 *caller_id_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:432
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
**Symbols:**

```
ffffffff811b3ea0-ffffffff811b3f99: desc_read (STB_LOCAL)
ffffffff821b2841-ffffffff821b28a1: desc_read.cold (STB_LOCAL)
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
