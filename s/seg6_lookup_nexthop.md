# Function: <code>seg6_lookup_nexthop</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff819a8c80)
Location: net/ipv6/seg6_local.c:152
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
**Symbols:**

```
ffffffff819a8c80-ffffffff819a8e6d: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff819df7a0)
Location: net/ipv6/seg6_local.c:152
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
**Symbols:**

```
ffffffff819df7a0-ffffffff819df98d: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:147
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
**Symbols:**

```
ffffffff81a4ec8c-ffffffff81a4ec9f: seg6_lookup_nexthop.cold (STB_LOCAL)
ffffffff81a4e350-ffffffff81a4e50f: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a84fb0)
Location: net/ipv6/seg6_local.c:154
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
**Symbols:**

```
ffffffff81a84fb0-ffffffff81a85172: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b807a8)
Location: net/ipv6/seg6_local.c:212
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
**Symbols:**

```
ffffffff81b805d0-ffffffff81b805e2: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b9003d)
Location: net/ipv6/seg6_local.c:265
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
**Symbols:**

```
ffffffff81b8fe50-ffffffff81b8fe62: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b7f1f6)
Location: net/ipv6/seg6_local.c:294
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
**Symbols:**

```
ffffffff81b7ef70-ffffffff81b7ef82: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81c4aa55)
Location: net/ipv6/seg6_local.c:266
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
**Symbols:**

```
ffffffff81c4a7b0-ffffffff81c4a7c2: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81dea326)
Location: net/ipv6/seg6_local.c:268
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
**Symbols:**

```
ffffffff81dea0c0-ffffffff81dea0de: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81fbdbe6)
Location: net/ipv6/seg6_local.c:319
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
**Symbols:**

```
ffffffff81fbd960-ffffffff81fbd97e: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff8201ec06)
Location: net/ipv6/seg6_local.c:326
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:end_flv8986_core
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
**Symbols:**

```
ffffffff8201e980-ffffffff8201e99e: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff820edd36)
Location: net/ipv6/seg6_local.c:330
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:input_action_end_x_core
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
```
**Symbols:**

```
ffffffff820edab0-ffffffff820edace: seg6_lookup_nexthop (STB_GLOBAL)
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
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffff800010d51040)
Location: net/ipv6/seg6_local.c:154
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
**Symbols:**

```
ffff800010d51040-ffff800010d51208: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (c0e51bac)
Location: net/ipv6/seg6_local.c:154
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
**Symbols:**

```
c0e51bac-c0e51dc8: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (c000000000e88fc0)
Location: net/ipv6/seg6_local.c:154
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
**Symbols:**

```
c000000000e88fc0-c000000000e891e8: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffe0008892da)
Location: net/ipv6/seg6_local.c:154
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
**Symbols:**

```
ffffffe0008892da-ffffffe00088947a: seg6_lookup_nexthop (STB_GLOBAL)
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
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a24640)
Location: net/ipv6/seg6_local.c:154
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
**Symbols:**

```
ffffffff81a24640-ffffffff81a24802: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff819e1400)
Location: net/ipv6/seg6_local.c:154
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
**Symbols:**

```
ffffffff819e1400-ffffffff819e15c2: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a8f0c0)
Location: net/ipv6/seg6_local.c:154
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
**Symbols:**

```
ffffffff81a8f0c0-ffffffff81a8f282: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int seg6_lookup_nexthop(struct sk_buff *skb, struct in6_addr *nhaddr, u32 tbl_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a9be40)
Location: net/ipv6/seg6_local.c:154
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
**Symbols:**

```
ffffffff81a9be40-ffffffff81a9c002: seg6_lookup_nexthop (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
