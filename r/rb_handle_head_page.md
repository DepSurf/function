# Function: <code>rb_handle_head_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81147677)
Location: kernel/trace/ring_buffer.c:1917
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115184b)
Location: kernel/trace/ring_buffer.c:1908
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115a1bb)
Location: kernel/trace/ring_buffer.c:1877
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115d16a)
Location: kernel/trace/ring_buffer.c:1879
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116a39a)
Location: kernel/trace/ring_buffer.c:1876
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811790f0)
Location: kernel/trace/ring_buffer.c:1949
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811867b7)
Location: kernel/trace/ring_buffer.c:1997
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119390a)
Location: kernel/trace/ring_buffer.c:1974
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119f4c7)
Location: kernel/trace/ring_buffer.c:1975
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rb_handle_head_page(struct ring_buffer_per_cpu *cpu_buffer, struct buffer_page *tail_page, struct buffer_page *next_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5c90)
Location: kernel/trace/ring_buffer.c:2044
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
**Symbols:**

```
ffffffff811b5c90-ffffffff811b5d8e: rb_handle_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rb_handle_head_page(struct ring_buffer_per_cpu *cpu_buffer, struct buffer_page *tail_page, struct buffer_page *next_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b3570)
Location: kernel/trace/ring_buffer.c:2289
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
**Symbols:**

```
ffffffff811b3570-ffffffff811b366e: rb_handle_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rb_handle_head_page(struct ring_buffer_per_cpu *cpu_buffer, struct buffer_page *tail_page, struct buffer_page *next_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b40c0)
Location: kernel/trace/ring_buffer.c:2368
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
**Symbols:**

```
ffffffff811b40c0-ffffffff811b41be: rb_handle_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rb_handle_head_page(struct ring_buffer_per_cpu *cpu_buffer, struct buffer_page *tail_page, struct buffer_page *next_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811de290)
Location: kernel/trace/ring_buffer.c:2368
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
**Symbols:**

```
ffffffff811de290-ffffffff811de38e: rb_handle_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rb_handle_head_page(struct ring_buffer_per_cpu *cpu_buffer, struct buffer_page *tail_page, struct buffer_page *next_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81215250)
Location: kernel/trace/ring_buffer.c:2404
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
**Symbols:**

```
ffffffff81215250-ffffffff81215361: rb_handle_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rb_handle_head_page(struct ring_buffer_per_cpu *cpu_buffer, struct buffer_page *tail_page, struct buffer_page *next_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125e890)
Location: kernel/trace/ring_buffer.c:2485
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
**Symbols:**

```
ffffffff8125e890-ffffffff8125e9a8: rb_handle_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rb_handle_head_page(struct ring_buffer_per_cpu *cpu_buffer, struct buffer_page *tail_page, struct buffer_page *next_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81275a70)
Location: kernel/trace/ring_buffer.c:2483
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
**Symbols:**

```
ffffffff81275a70-ffffffff81275b82: rb_handle_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rb_handle_head_page(struct ring_buffer_per_cpu *cpu_buffer, struct buffer_page *tail_page, struct buffer_page *next_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812906f0)
Location: kernel/trace/ring_buffer.c:2328
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
**Symbols:**

```
ffffffff812906f0-ffffffff8129080c: rb_handle_head_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021b2c8)
Location: kernel/trace/ring_buffer.c:1975
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0459e18)
Location: kernel/trace/ring_buffer.c:1975
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029c6c0)
Location: kernel/trace/ring_buffer.c:1975
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017828c)
Location: kernel/trace/ring_buffer.c:1975
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197ae7)
Location: kernel/trace/ring_buffer.c:1975
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118b297)
Location: kernel/trace/ring_buffer.c:1975
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811958b7)
Location: kernel/trace/ring_buffer.c:1975
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a3747)
Location: kernel/trace/ring_buffer.c:1975
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
