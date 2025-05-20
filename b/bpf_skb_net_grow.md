# Function: <code>bpf_skb_net_grow</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817eb585)
Location: net/core/filter.c:2169
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
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
In net/core/filter.c (ffffffff81867455)
Location: net/core/filter.c:2234
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
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
In net/core/filter.c (ffffffff818b644f)
Location: net/core/filter.c:2763
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
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
In net/core/filter.c (ffffffff818db4ec)
Location: net/core/filter.c:2953
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
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
In net/core/filter.c (ffffffff8192800f)
Location: net/core/filter.c:3009
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
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
In net/core/filter.c (ffffffff8195a63f)
Location: net/core/filter.c:3011
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_skb_net_grow(struct sk_buff *skb, u32 off, u32 len_diff, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2c1a0)
Location: net/core/filter.c:3049
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
**Symbols:**

```
ffffffff81a2c1a0-ffffffff81a2c4c6: bpf_skb_net_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_skb_net_grow(struct sk_buff *skb, u32 off, u32 len_diff, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2d720)
Location: net/core/filter.c:3418
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
**Symbols:**

```
ffffffff81a2d720-ffffffff81a2da46: bpf_skb_net_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_skb_net_grow(struct sk_buff *skb, u32 off, u32 len_diff, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a14f90)
Location: net/core/filter.c:3412
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
**Symbols:**

```
ffffffff81a14f90-ffffffff81a15305: bpf_skb_net_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_skb_net_grow(struct sk_buff *skb, u32 off, u32 len_diff, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac6540)
Location: net/core/filter.c:3381
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
**Symbols:**

```
ffffffff81ac6540-ffffffff81ac68b3: bpf_skb_net_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_skb_net_grow(struct sk_buff *skb, u32 off, u32 len_diff, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c41dd0)
Location: net/core/filter.c:3382
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
**Symbols:**

```
ffffffff81c41dd0-ffffffff81c4214c: bpf_skb_net_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_skb_net_grow(struct sk_buff *skb, u32 off, u32 len_diff, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df92d0)
Location: net/core/filter.c:3392
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
**Symbols:**

```
ffffffff81df92d0-ffffffff81df96a2: bpf_skb_net_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_skb_net_grow(struct sk_buff *skb, u32 off, u32 len_diff, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6abe0)
Location: net/core/filter.c:3412
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
**Symbols:**

```
ffffffff81e6abe0-ffffffff81e6afb0: bpf_skb_net_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_skb_net_grow(struct sk_buff *skb, u32 off, u32 len_diff, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f29b70)
Location: net/core/filter.c:3446
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
**Symbols:**

```
ffffffff81f29b70-ffffffff81f29f40: bpf_skb_net_grow (STB_LOCAL)
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
In net/core/filter.c (ffff800010bfbd78)
Location: net/core/filter.c:3011
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
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
In net/core/filter.c (c0d16cf8)
Location: net/core/filter.c:3011
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
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
In net/core/filter.c (c000000000ce7220)
Location: net/core/filter.c:3011
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
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
In net/core/filter.c (ffffffe00077e70a)
Location: net/core/filter.c:3011
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
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
In net/core/filter.c (ffffffff818fa60f)
Location: net/core/filter.c:3011
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
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
In net/core/filter.c (ffffffff818b443f)
Location: net/core/filter.c:3011
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
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
In net/core/filter.c (ffffffff8194b63f)
Location: net/core/filter.c:3011
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
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
In net/core/filter.c (ffffffff8196cf4f)
Location: net/core/filter.c:3011
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
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
