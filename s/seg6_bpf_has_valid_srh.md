# Function: <code>seg6_bpf_has_valid_srh</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff819dfdd0)
Location: net/ipv6/seg6_local.c:462
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff819dfdd0-ffffffff819dfe29: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a4e9d0)
Location: net/ipv6/seg6_local.c:457
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff81a4e9d0-ffffffff81a4ea29: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a85670)
Location: net/ipv6/seg6_local.c:470
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff81a85670-ffffffff81a856c9: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b805f0)
Location: net/ipv6/seg6_local.c:484
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff81b805f0-ffffffff81b80654: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b8fe70)
Location: net/ipv6/seg6_local.c:801
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff81b8fe70-ffffffff81b8fed4: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b7ef90)
Location: net/ipv6/seg6_local.c:830
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff81b7ef90-ffffffff81b7eff4: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:873
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff81d41664-ffffffff81d4167f: seg6_bpf_has_valid_srh.cold (STB_LOCAL)
ffffffff81c4a7d0-ffffffff81c4a84e: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:873
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff81f0dfd9-ffffffff81f0dfee: seg6_bpf_has_valid_srh.cold (STB_LOCAL)
ffffffff81dea0e0-ffffffff81dea174: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:998
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff820b5369-ffffffff820b537e: seg6_bpf_has_valid_srh.cold (STB_LOCAL)
ffffffff81fbd990-ffffffff81fbda24: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:1325
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff82136249-ffffffff8213625e: seg6_bpf_has_valid_srh.cold (STB_LOCAL)
ffffffff8201e9b0-ffffffff8201ea44: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:1385
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff82217e19-ffffffff82217e2e: seg6_bpf_has_valid_srh.cold (STB_LOCAL)
ffffffff820edae0-ffffffff820edb74: seg6_bpf_has_valid_srh (STB_GLOBAL)
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
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffff800010d516f0)
Location: net/ipv6/seg6_local.c:470
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffff800010d516f0-ffff800010d51778: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (c0e522a0)
Location: net/ipv6/seg6_local.c:470
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
c0e522a0-c0e5231c: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (c000000000e89900)
Location: net/ipv6/seg6_local.c:470
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
c000000000e89900-c000000000e899bc: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffe0008898ee)
Location: net/ipv6/seg6_local.c:470
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffe0008898ee-ffffffe000889970: seg6_bpf_has_valid_srh (STB_GLOBAL)
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
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a24d00)
Location: net/ipv6/seg6_local.c:470
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff81a24d00-ffffffff81a24d59: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff819e1ac0)
Location: net/ipv6/seg6_local.c:470
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff819e1ac0-ffffffff819e1b19: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a8f780)
Location: net/ipv6/seg6_local.c:470
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff81a8f780-ffffffff81a8f7d9: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool seg6_bpf_has_valid_srh(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a9c500)
Location: net/ipv6/seg6_local.c:470
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
**Symbols:**

```
ffffffff81a9c500-ffffffff81a9c559: seg6_bpf_has_valid_srh (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
