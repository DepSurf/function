# Function: <code>bpf_skb_generic_pop</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179d6e0)
Location: net/core/filter.c:1794
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
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
In net/core/filter.c (ffffffff817cc140)
Location: net/core/filter.c:1916
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_skb_generic_pop(struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817eb050)
Location: net/core/filter.c:1960
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
**Symbols:**

```
ffffffff817eb050-ffffffff817eb140: bpf_skb_generic_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_skb_generic_pop(struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81866ea0)
Location: net/core/filter.c:2025
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
**Symbols:**

```
ffffffff81866ea0-ffffffff81866f90: bpf_skb_generic_pop (STB_LOCAL)
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
In net/core/filter.c (ffffffff818b5d8d)
Location: net/core/filter.c:2542
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
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
In net/core/filter.c (ffffffff818dae27)
Location: net/core/filter.c:2734
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
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
In net/core/filter.c (ffffffff81927bd7)
Location: net/core/filter.c:2780
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
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
In net/core/filter.c (ffffffff81959f77)
Location: net/core/filter.c:2782
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_skb_generic_pop(struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2d9c0)
Location: net/core/filter.c:2820
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_proto_6_to_4
```
**Symbols:**

```
ffffffff81a2d9c0-ffffffff81a2daaf: bpf_skb_generic_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_skb_generic_pop(struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2f450)
Location: net/core/filter.c:3189
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_net_shrink
  - net/core/filter.c:bpf_skb_proto_6_to_4
```
**Symbols:**

```
ffffffff81a2f450-ffffffff81a2f53f: bpf_skb_generic_pop (STB_LOCAL)
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
In net/core/filter.c (ffffffff81a16c97)
Location: net/core/filter.c:3186
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
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
In net/core/filter.c (ffffffff81ac8127)
Location: net/core/filter.c:3173
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
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
In net/core/filter.c (ffffffff81c45967)
Location: net/core/filter.c:3174
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_skb_generic_pop(struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df9be0)
Location: net/core/filter.c:3181
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
**Symbols:**

```
ffffffff81df9be0-ffffffff81df9cd1: bpf_skb_generic_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_skb_generic_pop(struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6b420)
Location: net/core/filter.c:3197
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
**Symbols:**

```
ffffffff81e6b420-ffffffff81e6b511: bpf_skb_generic_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_skb_generic_pop(struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2a500)
Location: net/core/filter.c:3231
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
**Symbols:**

```
ffffffff81f2a500-ffffffff81f2a5f1: bpf_skb_generic_pop (STB_LOCAL)
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
In net/core/filter.c (ffff800010bfbb4c)
Location: net/core/filter.c:2782
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
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
In net/core/filter.c (c0d16604)
Location: net/core/filter.c:2782
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
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
In net/core/filter.c (c000000000ce6904)
Location: net/core/filter.c:2782
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
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
In net/core/filter.c (ffffffe00077e176)
Location: net/core/filter.c:2782
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
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
In net/core/filter.c (ffffffff818f9f47)
Location: net/core/filter.c:2782
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
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
In net/core/filter.c (ffffffff818b3d77)
Location: net/core/filter.c:2782
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
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
In net/core/filter.c (ffffffff8194af77)
Location: net/core/filter.c:2782
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
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
In net/core/filter.c (ffffffff8196c887)
Location: net/core/filter.c:2782
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_pop
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
