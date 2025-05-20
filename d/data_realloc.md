# Function: <code>data_realloc</code>

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
char *data_realloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111ca80)
Location: kernel/printk/printk_ringbuffer.c:1102
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff8111ca80-ffffffff8111cbcc: data_realloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *data_realloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111cbd0)
Location: kernel/printk/printk_ringbuffer.c:1102
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff8111cbd0-ffffffff8111cd1d: data_realloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *data_realloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1102
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff8113c9a0-ffffffff8113cb18: data_realloc (STB_LOCAL)
ffffffff81caca70-ffffffff81cacc63: data_realloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *data_realloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1105
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff8115fed0-ffffffff81160069: data_realloc (STB_LOCAL)
ffffffff81e5d0bf-ffffffff81e5d2c3: data_realloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
char *data_realloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1105
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff81193290-ffffffff81193429: data_realloc (STB_LOCAL)
ffffffff820590b9-ffffffff820592bd: data_realloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
char *data_realloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1105
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff811a4af0-ffffffff811a4c96: data_realloc (STB_LOCAL)
ffffffff820d77c4-ffffffff820d7954: data_realloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
char *data_realloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1105
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff811b45e0-ffffffff811b4786: data_realloc (STB_LOCAL)
ffffffff821b2a45-ffffffff821b2bd5: data_realloc.cold (STB_LOCAL)
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
