# Function: <code>seg6_do_srh_inline</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff818a42e1)
Location: net/ipv6/seg6_iptunnel.c:151
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca917)
Location: net/ipv6/seg6_iptunnel.c:147
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e120)
Location: net/ipv6/seg6_iptunnel.c:156
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff8194e120-ffffffff8194e3d3: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff819a70b0)
Location: net/ipv6/seg6_iptunnel.c:176
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff819a70b0-ffffffff819a736a: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff819ddc10)
Location: net/ipv6/seg6_iptunnel.c:178
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff819ddc10-ffffffff819ddec1: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c790)
Location: net/ipv6/seg6_iptunnel.c:173
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81a4c790-ffffffff81a4ca35: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83360)
Location: net/ipv6/seg6_iptunnel.c:173
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81a83360-ffffffff81a83605: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e180)
Location: net/ipv6/seg6_iptunnel.c:173
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81b7e180-ffffffff81b7e406: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d190)
Location: net/ipv6/seg6_iptunnel.c:190
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81b8d190-ffffffff81b8d41d: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c040)
Location: net/ipv6/seg6_iptunnel.c:190
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81b7c040-ffffffff81b7c2c4: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81c46f40)
Location: net/ipv6/seg6_iptunnel.c:199
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81c46f40-ffffffff81c471c4: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6270)
Location: net/ipv6/seg6_iptunnel.c:201
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81de6270-ffffffff81de6536: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb8f70)
Location: net/ipv6/seg6_iptunnel.c:321
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81fb8f70-ffffffff81fb9210: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff820196d0)
Location: net/ipv6/seg6_iptunnel.c:321
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff820196d0-ffffffff82019970: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff820e86a0)
Location: net/ipv6/seg6_iptunnel.c:321
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff820e86a0-ffffffff820e8940: seg6_do_srh_inline (STB_GLOBAL)
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
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f170)
Location: net/ipv6/seg6_iptunnel.c:173
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffff800010d4f170-ffff800010d4f3e0: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (c0e4fec8)
Location: net/ipv6/seg6_iptunnel.c:173
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
c0e4fec8-c0e50138: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (c000000000e86990)
Location: net/ipv6/seg6_iptunnel.c:173
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
c000000000e86990-c000000000e86d24: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffe000887c94)
Location: net/ipv6/seg6_iptunnel.c:173
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffe000887c94-ffffffe000887ee2: seg6_do_srh_inline (STB_GLOBAL)
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
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81a229f0)
Location: net/ipv6/seg6_iptunnel.c:173
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81a229f0-ffffffff81a22c95: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff819df7b0)
Location: net/ipv6/seg6_iptunnel.c:173
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff819df7b0-ffffffff819dfa55: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d470)
Location: net/ipv6/seg6_iptunnel.c:173
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81a8d470-ffffffff81a8d715: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int seg6_do_srh_inline(struct sk_buff *skb, struct ipv6_sr_hdr *osrh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a160)
Location: net/ipv6/seg6_iptunnel.c:173
Inline: False
Direct callers:
  - net/core/filter.c:bpf_push_seg6_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
**Symbols:**

```
ffffffff81a9a160-ffffffff81a9a405: seg6_do_srh_inline (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
