# Function: <code>skb_vlan_push</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81708e60)
Location: net/core/skbuff.c:4470
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff81708e60-ffffffff81709096: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81770980)
Location: net/core/skbuff.c:4544
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff81770980-ffffffff81770bd3: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179da70)
Location: net/core/skbuff.c:4596
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff8179da70-ffffffff8179dc76: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bb930)
Location: net/core/skbuff.c:4690
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff817bb930-ffffffff817bbb17: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818349e0)
Location: net/core/skbuff.c:5121
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff818349e0-ffffffff81834bcb: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187f820)
Location: net/core/skbuff.c:5201
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff8187f820-ffffffff8187f9cc: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189fa80)
Location: net/core/skbuff.c:5229
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff8189fa80-ffffffff8189fc25: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ea4a0)
Location: net/core/skbuff.c:5422
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff818ea4a0-ffffffff818ea647: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191c610)
Location: net/core/skbuff.c:5434
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff8191c610-ffffffff8191c7b7: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5536
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff819f4a6d-ffffffff819f4a85: skb_vlan_push.cold (STB_LOCAL)
ffffffff819f02c0-ffffffff819f04a8: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5604
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff81c30a16-ffffffff81c30a2e: skb_vlan_push.cold (STB_LOCAL)
ffffffff819f0520-ffffffff819f0708: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5692
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff81c22ceb-ffffffff81c22d03: skb_vlan_push.cold (STB_LOCAL)
ffffffff819d4e60-ffffffff819d504b: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5767
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff81d35273-ffffffff81d352a6: skb_vlan_push.cold (STB_LOCAL)
ffffffff81a84bf0-ffffffff81a84def: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5688
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff81f01853-ffffffff81f01886: skb_vlan_push.cold (STB_LOCAL)
ffffffff81bfabd0-ffffffff81bfada2: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5890
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff820aad42-ffffffff820aad56: skb_vlan_push.cold (STB_LOCAL)
ffffffff81da96e0-ffffffff81da97e1: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5941
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff8212c297-ffffffff8212c2ab: skb_vlan_push.cold (STB_LOCAL)
ffffffff81e186a0-ffffffff81e187a1: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6094
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff8220df77-ffffffff8220df8b: skb_vlan_push.cold (STB_LOCAL)
ffffffff81ed5b40-ffffffff81ed5c41: skb_vlan_push (STB_GLOBAL)
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
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb6bf0)
Location: net/core/skbuff.c:5434
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffff800010bb6bf0-ffff800010bb6d90: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd3a44)
Location: net/core/skbuff.c:5434
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
c0cd3a44-c0cd3bec: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8e540)
Location: net/core/skbuff.c:5434
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
c000000000c8e540-c000000000c8e764: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000746864)
Location: net/core/skbuff.c:5434
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffe000746864-ffffffe0007469e4: skb_vlan_push (STB_GLOBAL)
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
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bc610)
Location: net/core/skbuff.c:5434
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff818bc610-ffffffff818bc7b7: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81876550)
Location: net/core/skbuff.c:5434
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff81876550-ffffffff818766f7: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190d610)
Location: net/core/skbuff.c:5434
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff8190d610-ffffffff8190d7b7: skb_vlan_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skb_vlan_push(struct sk_buff *skb, __be16 vlan_proto, u16 vlan_tci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192e740)
Location: net/core/skbuff.c:5434
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_vlan_push
```
**Symbols:**

```
ffffffff8192e740-ffffffff8192e8e7: skb_vlan_push (STB_GLOBAL)
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
