# Function: <code>seg6_hmac_validate_skb</code>

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
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff818a4e20)
Location: net/ipv6/seg6_hmac.c:241
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff818a4e20-ffffffff818a4f45: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff818cb860)
Location: net/ipv6/seg6_hmac.c:241
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff818cb860-ffffffff818cb9a2: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81950600)
Location: net/ipv6/seg6_hmac.c:242
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff81950600-ffffffff81950742: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff819a9b00)
Location: net/ipv6/seg6_hmac.c:242
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff819a9b00-ffffffff819a9c3b: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff819e0620)
Location: net/ipv6/seg6_hmac.c:243
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff819e0620-ffffffff819e075b: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a4f280)
Location: net/ipv6/seg6_hmac.c:238
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff81a4f280-ffffffff81a4f3bf: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a85f10)
Location: net/ipv6/seg6_hmac.c:238
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff81a85f10-ffffffff81a8604f: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81b80f30)
Location: net/ipv6/seg6_hmac.c:237
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81b80f30-ffffffff81b81075: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81b90750)
Location: net/ipv6/seg6_hmac.c:236
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81b90750-ffffffff81b90895: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81b7f980)
Location: net/ipv6/seg6_hmac.c:236
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81b7f980-ffffffff81b7fabf: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81c4b220)
Location: net/ipv6/seg6_hmac.c:236
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81c4b220-ffffffff81c4b35f: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81deab50)
Location: net/ipv6/seg6_hmac.c:236
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81deab50-ffffffff81deacbc: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81fbe710)
Location: net/ipv6/seg6_hmac.c:236
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81fbe710-ffffffff81fbe87c: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff8201f5b0)
Location: net/ipv6/seg6_hmac.c:236
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff8201f5b0-ffffffff8201f71c: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff820ee6e0)
Location: net/ipv6/seg6_hmac.c:236
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:input_action_end_x_core
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff820ee6e0-ffffffff820ee84c: seg6_hmac_validate_skb (STB_GLOBAL)
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
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffff800010d527e0)
Location: net/ipv6/seg6_hmac.c:238
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffff800010d527e0-ffff800010d52958: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (c0e52ca0)
Location: net/ipv6/seg6_hmac.c:238
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
c0e52ca0-c0e52de0: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (c000000000e8aec0)
Location: net/ipv6/seg6_hmac.c:238
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
c000000000e8aec0-c000000000e8b04c: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffe00088a806)
Location: net/ipv6/seg6_hmac.c:238
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffe00088a806-ffffffe00088a8e0: seg6_hmac_validate_skb (STB_GLOBAL)
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
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a255a0)
Location: net/ipv6/seg6_hmac.c:238
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff81a255a0-ffffffff81a256df: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff819e2360)
Location: net/ipv6/seg6_hmac.c:238
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff819e2360-ffffffff819e249f: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a90020)
Location: net/ipv6/seg6_hmac.c:238
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff81a90020-ffffffff81a9015f: seg6_hmac_validate_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool seg6_hmac_validate_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a9d180)
Location: net/ipv6/seg6_hmac.c:238
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff81a9d180-ffffffff81a9d427: seg6_hmac_validate_skb (STB_GLOBAL)
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
