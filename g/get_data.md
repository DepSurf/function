# Function: <code>get_data</code>

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
const char *get_data(struct prb_data_ring *data_ring, struct prb_data_blk_lpos *blk_lpos, unsigned int *data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111bf50)
Location: kernel/printk/printk_ringbuffer.c:1202
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_read
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff8111bf50-ffffffff8111c03f: get_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *get_data(struct prb_data_ring *data_ring, struct prb_data_blk_lpos *blk_lpos, unsigned int *data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c3b0)
Location: kernel/printk/printk_ringbuffer.c:1202
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff8111c3b0-ffffffff8111c499: get_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
const char *get_data(struct prb_data_ring *data_ring, struct prb_data_blk_lpos *blk_lpos, unsigned int *data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1202
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff8113cb20-ffffffff8113ccaf: get_data (STB_LOCAL)
ffffffff81cacc63-ffffffff81cace04: get_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const char *get_data(struct prb_data_ring *data_ring, struct prb_data_blk_lpos *blk_lpos, unsigned int *data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1205
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff81160070-ffffffff811601e8: get_data (STB_LOCAL)
ffffffff81e5d2c3-ffffffff81e5d457: get_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
const char *get_data(struct prb_data_ring *data_ring, struct prb_data_blk_lpos *blk_lpos, unsigned int *data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1205
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:copy_data
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff81193440-ffffffff811935b8: get_data (STB_LOCAL)
ffffffff820592bd-ffffffff82059451: get_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
const char *get_data(struct prb_data_ring *data_ring, struct prb_data_blk_lpos *blk_lpos, unsigned int *data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1205
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:copy_data
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff811a4cb0-ffffffff811a4e1c: get_data (STB_LOCAL)
ffffffff820d7954-ffffffff820d7aab: get_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
const char *get_data(struct prb_data_ring *data_ring, struct prb_data_blk_lpos *blk_lpos, unsigned int *data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1205
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:copy_data
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff811b47a0-ffffffff811b490c: get_data (STB_LOCAL)
ffffffff821b2bd5-ffffffff821b2d2c: get_data.cold (STB_LOCAL)
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
