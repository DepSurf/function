# Function: <code>rb_reserve_next_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ring_buffer_event *rb_reserve_next_event(struct ring_buffer *buffer, struct ring_buffer_per_cpu *cpu_buffer, long unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81147860)
Location: kernel/trace/ring_buffer.c:2742
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_write
```
**Symbols:**

```
ffffffff81147860-ffffffff81147cb9: rb_reserve_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ring_buffer_event *rb_reserve_next_event(struct ring_buffer *buffer, struct ring_buffer_per_cpu *cpu_buffer, long unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81151b00)
Location: kernel/trace/ring_buffer.c:2737
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81151b00-ffffffff81151f71: rb_reserve_next_event (STB_LOCAL)
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
In kernel/trace/ring_buffer.c (ffffffff8115a995)
Location: kernel/trace/ring_buffer.c:2706
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffffffff8115d9d3)
Location: kernel/trace/ring_buffer.c:2708
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffffffff8116ac03)
Location: kernel/trace/ring_buffer.c:2700
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffffffff81179978)
Location: kernel/trace/ring_buffer.c:2830
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffffffff81189298)
Location: kernel/trace/ring_buffer.c:2893
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffffffff81196886)
Location: kernel/trace/ring_buffer.c:2870
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffffffff811a2256)
Location: kernel/trace/ring_buffer.c:2871
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b8bba)
Location: kernel/trace/ring_buffer.c:2940
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b65f6)
Location: kernel/trace/ring_buffer.c:3501
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffffffff811b5916)
Location: kernel/trace/ring_buffer.c:3588
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffffffff811df97f)
Location: kernel/trace/ring_buffer.c:3588
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81216ccc)
Location: kernel/trace/ring_buffer.c:3626
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81261e3c)
Location: kernel/trace/ring_buffer.c:3705
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81278eac)
Location: kernel/trace/ring_buffer.c:3708
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81293a9e)
Location: kernel/trace/ring_buffer.c:3604
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffff80001021c690)
Location: kernel/trace/ring_buffer.c:2871
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (c045b12c)
Location: kernel/trace/ring_buffer.c:2871
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (c00000000029fe0c)
Location: kernel/trace/ring_buffer.c:2871
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffffffe00017a16c)
Location: kernel/trace/ring_buffer.c:2871
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffffffff8119a876)
Location: kernel/trace/ring_buffer.c:2871
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffffffff8118d8f6)
Location: kernel/trace/ring_buffer.c:2871
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffffffff81198646)
Location: kernel/trace/ring_buffer.c:2871
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
In kernel/trace/ring_buffer.c (ffffffff811a629d)
Location: kernel/trace/ring_buffer.c:2871
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
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
</ul>
