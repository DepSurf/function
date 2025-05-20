# Function: <code>ip6_pkt_drop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d3a90)
Location: net/ipv6/route.c:2442
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_discard
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_prohibit_out
```
**Symbols:**

```
ffffffff817d3a90-ffffffff817d3b71: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81841490)
Location: net/ipv6/route.c:2513
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81841490-ffffffff81841576: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818732f0)
Location: net/ipv6/route.c:2562
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff818732f0-ffffffff818733d6: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81897cc0)
Location: net/ipv6/route.c:2646
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81897cc0-ffffffff81897da4: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81919040)
Location: net/ipv6/route.c:3347
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81919040-ffffffff81919124: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819707e0)
Location: net/ipv6/route.c:3691
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff819707e0-ffffffff819708bd: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a6410)
Location: net/ipv6/route.c:3671
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff819a6410-ffffffff819a64ed: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a12af0)
Location: net/ipv6/route.c:4322
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81a12af0-ffffffff81a12c85: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a496e0)
Location: net/ipv6/route.c:4335
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81a496e0-ffffffff81a49875: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b40130)
Location: net/ipv6/route.c:4376
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81b40130-ffffffff81b402b1: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4eb10)
Location: net/ipv6/route.c:4360
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81b4eb10-ffffffff81b4ec9c: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3c940)
Location: net/ipv6/route.c:4375
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81b3c940-ffffffff81b3cacc: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c03260)
Location: net/ipv6/route.c:4505
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81c03260-ffffffff81c03462: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9d1b0)
Location: net/ipv6/route.c:4481
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81d9d1b0-ffffffff81d9d3f9: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6c0e0)
Location: net/ipv6/route.c:4481
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81f6c0e0-ffffffff81f6c329: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcc210)
Location: net/ipv6/route.c:4479
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81fcc210-ffffffff81fcc464: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820999f0)
Location: net/ipv6/route.c:4481
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff820999f0-ffffffff82099c47: ip6_pkt_drop (STB_LOCAL)
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
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d11dd8)
Location: net/ipv6/route.c:4335
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffff800010d11dd8-ffff800010d11fb8: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e12b28)
Location: net/ipv6/route.c:4335
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
c0e12b28-c0e12e70: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e37db0)
Location: net/ipv6/route.c:4335
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
c000000000e37db0-c000000000e38024: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000853ddc)
Location: net/ipv6/route.c:4335
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffe000853ddc-ffffffe000853fbe: ip6_pkt_drop (STB_LOCAL)
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
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e8d70)
Location: net/ipv6/route.c:4335
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff819e8d70-ffffffff819e8f05: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a5b30)
Location: net/ipv6/route.c:4335
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff819a5b30-ffffffff819a5cc5: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a537f0)
Location: net/ipv6/route.c:4335
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81a537f0-ffffffff81a53985: ip6_pkt_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_pkt_drop(struct sk_buff *skb, u8 code, int ipstats_mib_noroutes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5f7e0)
Location: net/ipv6/route.c:4335
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pkt_prohibit_out
  - net/ipv6/route.c:ip6_pkt_prohibit
  - net/ipv6/route.c:ip6_pkt_discard_out
  - net/ipv6/route.c:ip6_pkt_discard
```
**Symbols:**

```
ffffffff81a5f7e0-ffffffff81a5f975: ip6_pkt_drop (STB_LOCAL)
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
