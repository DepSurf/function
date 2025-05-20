# Function: <code>bpf_skb_generic_push</code>

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
In net/core/filter.c (ffffffff8179d8d5)
Location: net/core/filter.c:1777
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
In net/core/filter.c (ffffffff817cc335)
Location: net/core/filter.c:1899
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
int bpf_skb_generic_push(struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9390)
Location: net/core/filter.c:1943
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
**Symbols:**

```
ffffffff817e9390-ffffffff817e93de: bpf_skb_generic_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_skb_generic_push(struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81864810)
Location: net/core/filter.c:2008
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
```
**Symbols:**

```
ffffffff81864810-ffffffff8186485e: bpf_skb_generic_push (STB_LOCAL)
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
In net/core/filter.c (ffffffff818b1965)
Location: net/core/filter.c:2525
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (ffffffff818d6395)
Location: net/core/filter.c:2717
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (ffffffff81923b75)
Location: net/core/filter.c:2763
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (ffffffff81955e75)
Location: net/core/filter.c:2765
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (ffffffff81a298e5)
Location: net/core/filter.c:2803
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (ffffffff81a2a271)
Location: net/core/filter.c:3172
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (ffffffff81a114d1)
Location: net/core/filter.c:3169
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (ffffffff81ac2931)
Location: net/core/filter.c:3156
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (ffffffff81c3d521)
Location: net/core/filter.c:3157
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_skb_generic_push(struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df51f0)
Location: net/core/filter.c:3164
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
```
**Symbols:**

```
ffffffff81df51f0-ffffffff81df5248: bpf_skb_generic_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_skb_generic_push(struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e66be0)
Location: net/core/filter.c:3180
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
```
**Symbols:**

```
ffffffff81e66be0-ffffffff81e66c38: bpf_skb_generic_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_skb_generic_push(struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f25d90)
Location: net/core/filter.c:3214
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_change_proto
```
**Symbols:**

```
ffffffff81f25d90-ffffffff81f25de8: bpf_skb_generic_push (STB_LOCAL)
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
In net/core/filter.c (ffff800010bf7bec)
Location: net/core/filter.c:2765
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (c0d113d0)
Location: net/core/filter.c:2765
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (c000000000cddc08)
Location: net/core/filter.c:2765
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (ffffffe00077959e)
Location: net/core/filter.c:2765
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (ffffffff818f5e45)
Location: net/core/filter.c:2765
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (ffffffff818afc75)
Location: net/core/filter.c:2765
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (ffffffff81946e75)
Location: net/core/filter.c:2765
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
In net/core/filter.c (ffffffff81968785)
Location: net/core/filter.c:2765
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_hdr_push
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
