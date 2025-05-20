# Function: <code>ipv6_srh_rcv</code>

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
In net/ipv6/exthdrs.c (ffffffff81894aa8)
Location: net/ipv6/exthdrs.c:323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
In net/ipv6/exthdrs.c (ffffffff818bad97)
Location: net/ipv6/exthdrs.c:323
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
In net/ipv6/exthdrs.c (ffffffff8193dda7)
Location: net/ipv6/exthdrs.c:356
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
In net/ipv6/exthdrs.c (ffffffff81996cb3)
Location: net/ipv6/exthdrs.c:356
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
In net/ipv6/exthdrs.c (ffffffff819cd5aa)
Location: net/ipv6/exthdrs.c:356
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a3bcd0)
Location: net/ipv6/exthdrs.c:352
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff81a3bcd0-ffffffff81a3c2b7: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a72950)
Location: net/ipv6/exthdrs.c:352
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff81a72950-ffffffff81a72f37: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b6c5a0)
Location: net/ipv6/exthdrs.c:353
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff81b6c5a0-ffffffff81b6ca9d: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b7b010)
Location: net/ipv6/exthdrs.c:353
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff81b7b010-ffffffff81b7b513: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b699a0)
Location: net/ipv6/exthdrs.c:352
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff81b699a0-ffffffff81b69fd8: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81c31800)
Location: net/ipv6/exthdrs.c:363
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff81c31800-ffffffff81c31e38: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81dcf050)
Location: net/ipv6/exthdrs.c:369
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff81dcf050-ffffffff81dcf637: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81fa03c0)
Location: net/ipv6/exthdrs.c:369
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff81fa03c0-ffffffff81fa09a7: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff82000e80)
Location: net/ipv6/exthdrs.c:366
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff82000e80-ffffffff820013eb: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff820cfcc0)
Location: net/ipv6/exthdrs.c:368
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff820cfcc0-ffffffff820d022b: ipv6_srh_rcv (STB_LOCAL)
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
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffff800010d3b488)
Location: net/ipv6/exthdrs.c:352
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffff800010d3b488-ffff800010d3ba20: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (c0e3d9f8)
Location: net/ipv6/exthdrs.c:352
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
c0e3d9f8-c0e3e198: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (c000000000e6ebc0)
Location: net/ipv6/exthdrs.c:352
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
c000000000e6ebc0-c000000000e6f2f0: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffe000877dde)
Location: net/ipv6/exthdrs.c:352
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffe000877dde-ffffffe000878302: ipv6_srh_rcv (STB_LOCAL)
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
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a11fe0)
Location: net/ipv6/exthdrs.c:352
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff81a11fe0-ffffffff81a125c7: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff819ceda0)
Location: net/ipv6/exthdrs.c:352
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff819ceda0-ffffffff819cf387: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a7ca60)
Location: net/ipv6/exthdrs.c:352
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff81a7ca60-ffffffff81a7d047: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a892b0)
Location: net/ipv6/exthdrs.c:352
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
**Symbols:**

```
ffffffff81a892b0-ffffffff81a89897: ipv6_srh_rcv (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
