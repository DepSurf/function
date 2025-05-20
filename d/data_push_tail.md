# Function: <code>data_push_tail</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111cb05)
Location: kernel/printk/printk_ringbuffer.c:629
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_push_tail
Direct callers:
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_push_tail
```
**Symbols:**

```
ffffffff8111c660-ffffffff8111c711: data_push_tail.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d3a9)
Location: kernel/printk/printk_ringbuffer.c:629
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
```
**Symbols:**

```
ffffffff8111c8e0-ffffffff8111cab1: data_push_tail.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d6d3)
Location: kernel/printk/printk_ringbuffer.c:629
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
```
**Symbols:**

```
ffffffff8113c710-ffffffff8113c865: data_push_tail.part.0 (STB_LOCAL)
ffffffff81cac8fa-ffffffff81cac98d: data_push_tail.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool data_push_tail(struct printk_ringbuffer *rb, long unsigned int lpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:632
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
```
**Symbols:**

```
ffffffff8115f990-ffffffff8115fb26: data_push_tail (STB_LOCAL)
ffffffff81e5ce9e-ffffffff81e5cf31: data_push_tail.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool data_push_tail(struct printk_ringbuffer *rb, long unsigned int lpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:632
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
```
**Symbols:**

```
ffffffff81192d20-ffffffff81192eb6: data_push_tail (STB_LOCAL)
ffffffff82058e98-ffffffff82058f2b: data_push_tail.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool data_push_tail(struct printk_ringbuffer *rb, long unsigned int lpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:632
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
```
**Symbols:**

```
ffffffff811a4580-ffffffff811a472d: data_push_tail (STB_LOCAL)
ffffffff820d7620-ffffffff820d76a0: data_push_tail.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool data_push_tail(struct printk_ringbuffer *rb, long unsigned int lpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:632
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
```
**Symbols:**

```
ffffffff811b4070-ffffffff811b421d: data_push_tail (STB_LOCAL)
ffffffff821b28a1-ffffffff821b2921: data_push_tail.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
