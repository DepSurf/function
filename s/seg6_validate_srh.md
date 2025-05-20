# Function: <code>seg6_validate_srh</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81899d60)
Location: net/ipv6/seg6.c:32
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
**Symbols:**

```
ffffffff81899d60-ffffffff81899dc6: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff818bff40)
Location: net/ipv6/seg6.c:32
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
**Symbols:**

```
ffffffff818bff40-ffffffff818bffab: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81943010)
Location: net/ipv6/seg6.c:32
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81943010-ffffffff8194307b: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff8199be20)
Location: net/ipv6/seg6.c:32
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff8199be20-ffffffff8199be90: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff819d2770)
Location: net/ipv6/seg6.c:33
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff819d2770-ffffffff819d27e0: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81a415a0)
Location: net/ipv6/seg6.c:28
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81a415a0-ffffffff81a41616: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81a78220)
Location: net/ipv6/seg6.c:28
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81a78220-ffffffff81a78296: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len, bool reduced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81b72560)
Location: net/ipv6/seg6.c:28
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81b72560-ffffffff81b725f6: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len, bool reduced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81b812d0)
Location: net/ipv6/seg6.c:28
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81b812d0-ffffffff81b81366: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len, bool reduced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81b6fee0)
Location: net/ipv6/seg6.c:28
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81b6fee0-ffffffff81b6ff7e: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len, bool reduced);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81c38149)
Location: net/ipv6/seg6.c:28
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
```
**Symbols:**

```
ffffffff81c37a40-ffffffff81c37ad4: seg6_validate_srh.part.0 (STB_LOCAL)
ffffffff81c38030-ffffffff81c380ce: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len, bool reduced);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81dd5d6d)
Location: net/ipv6/seg6.c:28
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
```
**Symbols:**

```
ffffffff81dd55f0-ffffffff81dd5693: seg6_validate_srh.part.0 (STB_LOCAL)
ffffffff81dd5c40-ffffffff81dd5cf0: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len, bool reduced);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81fa756d)
Location: net/ipv6/seg6.c:28
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
```
**Symbols:**

```
ffffffff81fa6d70-ffffffff81fa6e13: seg6_validate_srh.part.0 (STB_LOCAL)
ffffffff81fa7430-ffffffff81fa74e0: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len, bool reduced);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6.c (ffffffff82007dcd)
Location: net/ipv6/seg6.c:28
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
```
**Symbols:**

```
ffffffff820075e0-ffffffff8200767e: seg6_validate_srh.part.0 (STB_LOCAL)
ffffffff82007c90-ffffffff82007d38: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len, bool reduced);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6.c (ffffffff820d6ced)
Location: net/ipv6/seg6.c:28
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_get_srh
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/seg6.c:seg6_get_srh
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
```
**Symbols:**

```
ffffffff820d6470-ffffffff820d650e: seg6_validate_srh.part.0 (STB_LOCAL)
ffffffff820d6bb0-ffffffff820d6c58: seg6_validate_srh (STB_GLOBAL)
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
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffff800010d417a8)
Location: net/ipv6/seg6.c:28
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffff800010d417a8-ffff800010d41874: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (c0e441bc)
Location: net/ipv6/seg6.c:28
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
c0e441bc-c0e44270: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (c000000000e76360)
Location: net/ipv6/seg6.c:28
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
c000000000e76360-c000000000e76448: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffe00087ce56)
Location: net/ipv6/seg6.c:28
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffe00087ce56-ffffffe00087cf16: seg6_validate_srh (STB_GLOBAL)
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
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81a178b0)
Location: net/ipv6/seg6.c:28
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81a178b0-ffffffff81a17926: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff819d4670)
Location: net/ipv6/seg6.c:28
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff819d4670-ffffffff819d46e6: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81a82330)
Location: net/ipv6/seg6.c:28
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81a82330-ffffffff81a823a6: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr *srh, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81a8ec40)
Location: net/ipv6/seg6.c:28
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
  - net/ipv6/seg6_local.c:get_srh
```
**Symbols:**

```
ffffffff81a8ec40-ffffffff81a8ecb6: seg6_validate_srh (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reduced</code>
</li>
</ul>
</details>
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
