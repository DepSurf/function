# Function: <code>rb_add_time_stamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81146220)
Location: kernel/trace/ring_buffer.c:2250
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
```
**Symbols:**

```
ffffffff81146220-ffffffff81146266: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114ea70)
Location: kernel/trace/ring_buffer.c:2242
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
```
**Symbols:**

```
ffffffff8114ea70-ffffffff8114eab6: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811589b0)
Location: kernel/trace/ring_buffer.c:2211
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff811589b0-ffffffff811589f6: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115bce0)
Location: kernel/trace/ring_buffer.c:2213
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff8115bce0-ffffffff8115bd26: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81168da0)
Location: kernel/trace/ring_buffer.c:2209
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff81168da0-ffffffff81168de6: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta, bool abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81177ce0)
Location: kernel/trace/ring_buffer.c:2282
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff81177ce0-ffffffff81177d21: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta, bool abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81185280)
Location: kernel/trace/ring_buffer.c:2330
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff81185280-ffffffff811852c1: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta, bool abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81192480)
Location: kernel/trace/ring_buffer.c:2307
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff81192480-ffffffff811924c1: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta, bool abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119e130)
Location: kernel/trace/ring_buffer.c:2308
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff8119e130-ffffffff8119e171: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta, bool abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b49e0)
Location: kernel/trace/ring_buffer.c:2377
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff811b49e0-ffffffff811b4a21: rb_add_time_stamp (STB_LOCAL)
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
In kernel/trace/ring_buffer.c (ffffffff811b266b)
Location: kernel/trace/ring_buffer.c:2622
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_add_timestamp
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
In kernel/trace/ring_buffer.c (ffffffff811b477d)
Location: kernel/trace/ring_buffer.c:2701
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
In kernel/trace/ring_buffer.c (ffffffff811de9bd)
Location: kernel/trace/ring_buffer.c:2701
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
In kernel/trace/ring_buffer.c (ffffffff812159dc)
Location: kernel/trace/ring_buffer.c:2737
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
In kernel/trace/ring_buffer.c (ffffffff8125f03c)
Location: kernel/trace/ring_buffer.c:2825
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
In kernel/trace/ring_buffer.c (ffffffff8127623c)
Location: kernel/trace/ring_buffer.c:2823
Inline: True
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
In kernel/trace/ring_buffer.c (ffffffff8128e53b)
Location: kernel/trace/ring_buffer.c:2670
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_add_timestamp
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
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta, bool abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010216f98)
Location: kernel/trace/ring_buffer.c:2308
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffff800010216f98-ffff800010216ff0: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta, bool abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0455d24)
Location: kernel/trace/ring_buffer.c:2308
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
c0455d24-c0455d9c: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta, bool abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0000000002992d0)
Location: kernel/trace/ring_buffer.c:2308
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
c0000000002992d0-c00000000029932c: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta, bool abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe0001768d4)
Location: kernel/trace/ring_buffer.c:2308
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffe0001768d4-ffffffe000176920: rb_add_time_stamp (STB_LOCAL)
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
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta, bool abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196750)
Location: kernel/trace/ring_buffer.c:2308
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff81196750-ffffffff81196791: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta, bool abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81189860)
Location: kernel/trace/ring_buffer.c:2308
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff81189860-ffffffff811898a1: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta, bool abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81194520)
Location: kernel/trace/ring_buffer.c:2308
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff81194520-ffffffff81194561: rb_add_time_stamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ring_buffer_event *rb_add_time_stamp(struct ring_buffer_event *event, u64 delta, bool abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2100)
Location: kernel/trace/ring_buffer.c:2308
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:__rb_reserve_next
```
**Symbols:**

```
ffffffff811a2100-ffffffff811a2141: rb_add_time_stamp (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool abs</code>
</li>
</ul>
</details>
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
