# Function: <code>data_alloc</code>

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
char *data_alloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c950)
Location: kernel/printk/printk_ringbuffer.c:1021
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff8111c950-ffffffff8111ca75: data_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *data_alloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111cac0)
Location: kernel/printk/printk_ringbuffer.c:1021
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff8111cac0-ffffffff8111cbcd: data_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *data_alloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1021
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff8113c870-ffffffff8113c99f: data_alloc (STB_LOCAL)
ffffffff81cac98d-ffffffff81caca70: data_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *data_alloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1024
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff8115fd90-ffffffff8115fece: data_alloc (STB_LOCAL)
ffffffff81e5cfd1-ffffffff81e5d0bf: data_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
char *data_alloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1024
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff81193140-ffffffff8119327e: data_alloc (STB_LOCAL)
ffffffff82058fcb-ffffffff820590b9: data_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
char *data_alloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1024
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff811a49b0-ffffffff811a4ada: data_alloc (STB_LOCAL)
ffffffff820d7740-ffffffff820d77c4: data_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
char *data_alloc(struct printk_ringbuffer *rb, unsigned int size, struct prb_data_blk_lpos *blk_lpos, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1024
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
```
**Symbols:**

```
ffffffff811b44a0-ffffffff811b45ca: data_alloc (STB_LOCAL)
ffffffff821b29c1-ffffffff821b2a45: data_alloc.cold (STB_LOCAL)
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
