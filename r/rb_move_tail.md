# Function: <code>rb_move_tail</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81147490)
Location: kernel/trace/ring_buffer.c:2142
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
```
**Symbols:**

```
ffffffff81147490-ffffffff81147855: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811515a0)
Location: kernel/trace/ring_buffer.c:2138
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
```
**Symbols:**

```
ffffffff811515a0-ffffffff81151aff: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81159ea0)
Location: kernel/trace/ring_buffer.c:2107
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff81159ea0-ffffffff8115a3db: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115cff0)
Location: kernel/trace/ring_buffer.c:2109
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff8115cff0-ffffffff8115d47e: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116a220)
Location: kernel/trace/ring_buffer.c:2105
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff8116a220-ffffffff8116a6ae: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81178ef0)
Location: kernel/trace/ring_buffer.c:2178
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff81178ef0-ffffffff81179379: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811865b0)
Location: kernel/trace/ring_buffer.c:2226
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff811865b0-ffffffff81186a47: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811936f0)
Location: kernel/trace/ring_buffer.c:2203
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff811936f0-ffffffff81193c30: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119f2c0)
Location: kernel/trace/ring_buffer.c:2204
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff8119f2c0-ffffffff8119f741: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5d90)
Location: kernel/trace/ring_buffer.c:2273
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff811b5d90-ffffffff811b6136: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b3670)
Location: kernel/trace/ring_buffer.c:2518
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff811b3670-ffffffff811b39fb: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b41c0)
Location: kernel/trace/ring_buffer.c:2597
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff811b41c0-ffffffff811b4541: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811de390)
Location: kernel/trace/ring_buffer.c:2597
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff811de390-ffffffff811de711: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81215370)
Location: kernel/trace/ring_buffer.c:2633
Inline: False
```
**Symbols:**

```
ffffffff81215370-ffffffff8121571d: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125e9c0)
Location: kernel/trace/ring_buffer.c:2721
Inline: False
```
**Symbols:**

```
ffffffff8125e9c0-ffffffff8125ed6d: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81275ba0)
Location: kernel/trace/ring_buffer.c:2719
Inline: False
```
**Symbols:**

```
ffffffff81275ba0-ffffffff81275f66: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81290820)
Location: kernel/trace/ring_buffer.c:2566
Inline: False
```
**Symbols:**

```
ffffffff81290820-ffffffff81290bdd: rb_move_tail (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021b028)
Location: kernel/trace/ring_buffer.c:2204
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffff80001021b028-ffff80001021b7a8: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0459abc)
Location: kernel/trace/ring_buffer.c:2204
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
c0459abc-c045a1fc: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029c300)
Location: kernel/trace/ring_buffer.c:2204
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
c00000000029c300-c00000000029cbf8: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe0001780b6)
Location: kernel/trace/ring_buffer.c:2204
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffe0001780b6-ffffffe000178482: rb_move_tail (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811978e0)
Location: kernel/trace/ring_buffer.c:2204
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff811978e0-ffffffff81197d61: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118b090)
Location: kernel/trace/ring_buffer.c:2204
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff8118b090-ffffffff8118b511: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811956b0)
Location: kernel/trace/ring_buffer.c:2204
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff811956b0-ffffffff81195b31: rb_move_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ring_buffer_event *rb_move_tail(struct ring_buffer_per_cpu *cpu_buffer, long unsigned int tail, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a3540)
Location: kernel/trace/ring_buffer.c:2204
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff811a3540-ffffffff811a39c1: rb_move_tail (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
