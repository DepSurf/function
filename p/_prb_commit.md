# Function: <code>_prb_commit</code>

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
void _prb_commit(struct prb_reserved_entry *e, long unsigned int state_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c4b0)
Location: kernel/printk/printk_ringbuffer.c:1570
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
```
**Symbols:**

```
ffffffff8111c4b0-ffffffff8111c4fb: _prb_commit (STB_LOCAL)
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
In kernel/printk/printk_ringbuffer.c (ffffffff8111d465)
Location: kernel/printk/printk_ringbuffer.c:1570
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
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
In kernel/printk/printk_ringbuffer.c (ffffffff8113d795)
Location: kernel/printk/printk_ringbuffer.c:1570
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void _prb_commit(struct prb_reserved_entry *e, long unsigned int state_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1576
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
```
**Symbols:**

```
ffffffff8115f750-ffffffff8115f7d8: _prb_commit (STB_LOCAL)
ffffffff81e5ce08-ffffffff81e5ce2b: _prb_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void _prb_commit(struct prb_reserved_entry *e, long unsigned int state_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1576
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
```
**Symbols:**

```
ffffffff81192ab0-ffffffff81192b38: _prb_commit (STB_LOCAL)
ffffffff82058e02-ffffffff82058e25: _prb_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void _prb_commit(struct prb_reserved_entry *e, long unsigned int state_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1576
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
```
**Symbols:**

```
ffffffff811a4310-ffffffff811a4398: _prb_commit (STB_LOCAL)
ffffffff820d759d-ffffffff820d75c0: _prb_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void _prb_commit(struct prb_reserved_entry *e, long unsigned int state_val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1576
Inline: False
Direct callers:
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
```
**Symbols:**

```
ffffffff811b3e00-ffffffff811b3e88: _prb_commit (STB_LOCAL)
ffffffff821b281e-ffffffff821b2841: _prb_commit.cold (STB_LOCAL)
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
