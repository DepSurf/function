# Function: <code>desc_reserve</code>

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
bool desc_reserve(struct printk_ringbuffer *rb, long unsigned int *id_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c860)
Location: kernel/printk/printk_ringbuffer.c:872
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
**Symbols:**

```
ffffffff8111c860-ffffffff8111c94b: desc_reserve (STB_LOCAL)
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
In kernel/printk/printk_ringbuffer.c (ffffffff8111d0f6)
Location: kernel/printk/printk_ringbuffer.c:872
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
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
In kernel/printk/printk_ringbuffer.c (ffffffff8113d3af)
Location: kernel/printk/printk_ringbuffer.c:872
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool desc_reserve(struct printk_ringbuffer *rb, long unsigned int *id_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:875
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
**Symbols:**

```
ffffffff8115fb30-ffffffff8115fd87: desc_reserve (STB_LOCAL)
ffffffff81e5cf31-ffffffff81e5cfd1: desc_reserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool desc_reserve(struct printk_ringbuffer *rb, long unsigned int *id_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:875
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
**Symbols:**

```
ffffffff81192ed0-ffffffff81193127: desc_reserve (STB_LOCAL)
ffffffff82058f2b-ffffffff82058fcb: desc_reserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool desc_reserve(struct printk_ringbuffer *rb, long unsigned int *id_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:875
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
**Symbols:**

```
ffffffff811a4740-ffffffff811a499c: desc_reserve (STB_LOCAL)
ffffffff820d76a0-ffffffff820d7740: desc_reserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool desc_reserve(struct printk_ringbuffer *rb, long unsigned int *id_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:875
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
**Symbols:**

```
ffffffff811b4230-ffffffff811b448c: desc_reserve (STB_LOCAL)
ffffffff821b2921-ffffffff821b29c1: desc_reserve.cold (STB_LOCAL)
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
