# Function: <code>_prb_read_valid</code>

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
bool _prb_read_valid(struct printk_ringbuffer *rb, u64 *seq, struct printk_record *r, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c3a0)
Location: kernel/printk/printk_ringbuffer.c:1874
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:prb_first_valid_seq
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
  - kernel/printk/printk_ringbuffer.c:prb_read_valid
```
**Symbols:**

```
ffffffff8111c3a0-ffffffff8111c451: _prb_read_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool _prb_read_valid(struct printk_ringbuffer *rb, u64 *seq, struct printk_record *r, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c5f0)
Location: kernel/printk/printk_ringbuffer.c:1874
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:prb_first_valid_seq
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
  - kernel/printk/printk_ringbuffer.c:prb_read_valid
```
**Symbols:**

```
ffffffff8111c5f0-ffffffff8111c88d: _prb_read_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool _prb_read_valid(struct printk_ringbuffer *rb, u64 *seq, struct printk_record *r, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1874
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:prb_first_valid_seq
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
  - kernel/printk/printk_ringbuffer.c:prb_read_valid
```
**Symbols:**

```
ffffffff8113ccb0-ffffffff8113cf43: _prb_read_valid (STB_LOCAL)
ffffffff81cace04-ffffffff81cace5e: _prb_read_valid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool _prb_read_valid(struct printk_ringbuffer *rb, u64 *seq, struct printk_record *r, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1885
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:prb_first_valid_seq
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
  - kernel/printk/printk_ringbuffer.c:prb_read_valid
```
**Symbols:**

```
ffffffff811601f0-ffffffff811604d5: _prb_read_valid (STB_LOCAL)
ffffffff81e5d457-ffffffff81e5d4b2: _prb_read_valid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool _prb_read_valid(struct printk_ringbuffer *rb, u64 *seq, struct printk_record *r, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811938b0)
Location: kernel/printk/printk_ringbuffer.c:1885
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:prb_first_valid_seq
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
  - kernel/printk/printk_ringbuffer.c:prb_read_valid
```
**Symbols:**

```
ffffffff811938b0-ffffffff81193993: _prb_read_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool _prb_read_valid(struct printk_ringbuffer *rb, u64 *seq, struct printk_record *r, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811a5110)
Location: kernel/printk/printk_ringbuffer.c:1885
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:prb_first_valid_seq
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
  - kernel/printk/printk_ringbuffer.c:prb_read_valid
```
**Symbols:**

```
ffffffff811a5110-ffffffff811a51f3: _prb_read_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool _prb_read_valid(struct printk_ringbuffer *rb, u64 *seq, struct printk_record *r, unsigned int *line_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811b4c00)
Location: kernel/printk/printk_ringbuffer.c:1885
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_next_seq
  - kernel/printk/printk_ringbuffer.c:prb_first_valid_seq
  - kernel/printk/printk_ringbuffer.c:prb_read_valid_info
  - kernel/printk/printk_ringbuffer.c:prb_read_valid
```
**Symbols:**

```
ffffffff811b4c00-ffffffff811b4ce3: _prb_read_valid (STB_LOCAL)
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
