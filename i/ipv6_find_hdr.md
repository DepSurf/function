# Function: <code>ipv6_find_hdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff817ffd00)
Location: net/ipv6/exthdrs_core.c:185
Inline: False
```
**Symbols:**

```
ffffffff817ffd00-ffffffff818000ae: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff818713a0)
Location: net/ipv6/exthdrs_core.c:185
Inline: False
```
**Symbols:**

```
ffffffff818713a0-ffffffff8187176a: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff818a58f0)
Location: net/ipv6/exthdrs_core.c:185
Inline: False
```
**Symbols:**

```
ffffffff818a58f0-ffffffff818a5cc1: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff818cc370)
Location: net/ipv6/exthdrs_core.c:185
Inline: False
```
**Symbols:**

```
ffffffff818cc370-ffffffff818cc721: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81951120)
Location: net/ipv6/exthdrs_core.c:185
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81951120-ffffffff819514d1: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff819aa6a0)
Location: net/ipv6/exthdrs_core.c:185
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff819aa6a0-ffffffff819aaa7e: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff819e11a0)
Location: net/ipv6/exthdrs_core.c:185
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff819e11a0-ffffffff819e1563: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/exthdrs_core.c (0)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81a50317-ffffffff81a5032f: ipv6_find_hdr.cold (STB_LOCAL)
ffffffff81a4ff70-ffffffff81a50317: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a86bc0)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81a86bc0-ffffffff81a86f41: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81b81e70)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81b81e70-ffffffff81b821f1: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81b91560)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81b91560-ffffffff81b918e1: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81b80760)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81b80760-ffffffff81b80b3a: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81c4c780)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6_local.c:input_action_end_dt46
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81c4c780-ffffffff81c4cb5a: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81decb60)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6_local.c:input_action_end_dt46
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81decb60-ffffffff81decfa8: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81fc0950)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6_local.c:input_action_end_dt46
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81fc0950-ffffffff81fc0d98: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff820218d0)
Location: net/ipv6/exthdrs_core.c:188
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6_local.c:input_action_end_dt46
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff820218d0-ffffffff82021d2e: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff820f09f0)
Location: net/ipv6/exthdrs_core.c:188
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6_local.c:input_action_end_dt46
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff820f09f0-ffffffff820f0e4a: ipv6_find_hdr (STB_GLOBAL)
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
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffff800010d53250)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffff800010d53250-ffff800010d535b0: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (c0e53bc0)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
c0e53bc0-c0e53f58: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (c000000000e8b940)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
c000000000e8b940-c000000000e8be24: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffe00088afba)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffe00088afba-ffffffe00088b28a: ipv6_find_hdr (STB_GLOBAL)
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
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a26250)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81a26250-ffffffff81a265d1: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff819e3010)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff819e3010-ffffffff819e3391: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a91e00)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81a91e00-ffffffff81a92181: ipv6_find_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff *skb, unsigned int *offset, int target, short unsigned int *fragoff, int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs_core.c (ffffffff81a9deb0)
Location: net/ipv6/exthdrs_core.c:186
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81a9deb0-ffffffff81a9e231: ipv6_find_hdr (STB_GLOBAL)
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
