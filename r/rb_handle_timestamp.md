# Function: <code>rb_handle_timestamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81147400)
Location: kernel/trace/ring_buffer.c:2671
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
```
**Symbols:**

```
ffffffff81147400-ffffffff81147483: rb_handle_timestamp.isra.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114fc10)
Location: kernel/trace/ring_buffer.c:2665
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
```
**Symbols:**

```
ffffffff8114fc10-ffffffff8114fc93: rb_handle_timestamp.isra.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81159e10)
Location: kernel/trace/ring_buffer.c:2634
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81159e10-ffffffff81159e93: rb_handle_timestamp.isra.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115cca0)
Location: kernel/trace/ring_buffer.c:2636
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff8115cca0-ffffffff8115cd15: rb_handle_timestamp.isra.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81169c40)
Location: kernel/trace/ring_buffer.c:2629
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81169c40-ffffffff81169cb5: rb_handle_timestamp.isra.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81178ba0)
Location: kernel/trace/ring_buffer.c:2758
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81178ba0-ffffffff81178c15: rb_handle_timestamp.isra.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81186060)
Location: kernel/trace/ring_buffer.c:2821
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81186060-ffffffff811860d5: rb_handle_timestamp.isra.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811933e0)
Location: kernel/trace/ring_buffer.c:2798
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff811933e0-ffffffff81193455: rb_handle_timestamp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119f010)
Location: kernel/trace/ring_buffer.c:2799
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff8119f010-ffffffff8119f085: rb_handle_timestamp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rb_handle_timestamp(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4da0)
Location: kernel/trace/ring_buffer.c:2868
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff811b4da0-ffffffff811b4e18: rb_handle_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff8000102175f8)
Location: kernel/trace/ring_buffer.c:2799
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffff8000102175f8-ffff800010217664: rb_handle_timestamp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rb_handle_timestamp(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0456580)
Location: kernel/trace/ring_buffer.c:2799
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
c0456580-c0456610: rb_handle_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rb_handle_timestamp(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c000000000299e50)
Location: kernel/trace/ring_buffer.c:2799
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
c000000000299e50-c000000000299ee4: rb_handle_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rb_handle_timestamp(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000177242)
Location: kernel/trace/ring_buffer.c:2799
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffe000177242-ffffffe00017729a: rb_handle_timestamp (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197630)
Location: kernel/trace/ring_buffer.c:2799
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81197630-ffffffff811976a5: rb_handle_timestamp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118aa90)
Location: kernel/trace/ring_buffer.c:2799
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff8118aa90-ffffffff8118ab05: rb_handle_timestamp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195400)
Location: kernel/trace/ring_buffer.c:2799
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81195400-ffffffff81195475: rb_handle_timestamp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a3290)
Location: kernel/trace/ring_buffer.c:2799
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff811a3290-ffffffff811a3305: rb_handle_timestamp.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
