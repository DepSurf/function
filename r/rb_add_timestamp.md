# Function: <code>rb_add_timestamp</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void rb_add_timestamp(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event **event, struct rb_event_info *info, u64 *delta, unsigned int *length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:2668
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff811b2630-ffffffff811b2766: rb_add_timestamp (STB_LOCAL)
ffffffff81be5487-ffffffff81be54a2: rb_add_timestamp.cold (STB_LOCAL)
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
In kernel/trace/ring_buffer.c (ffffffff811b475f)
Location: kernel/trace/ring_buffer.c:2747
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
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
In kernel/trace/ring_buffer.c (ffffffff811de99f)
Location: kernel/trace/ring_buffer.c:2747
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
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
In kernel/trace/ring_buffer.c (ffffffff812159bf)
Location: kernel/trace/ring_buffer.c:2783
Inline: True
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
In kernel/trace/ring_buffer.c (ffffffff8125f01f)
Location: kernel/trace/ring_buffer.c:2871
Inline: True
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
In kernel/trace/ring_buffer.c (ffffffff8127621f)
Location: kernel/trace/ring_buffer.c:2869
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rb_add_timestamp(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event **event, struct rb_event_info *info, u64 *delta, unsigned int *length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:2717
Inline: False
```
**Symbols:**

```
ffffffff8128e500-ffffffff8128e6e2: rb_add_timestamp (STB_LOCAL)
ffffffff821b772f-ffffffff821b7772: rb_add_timestamp.cold (STB_LOCAL)
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
</ul>
