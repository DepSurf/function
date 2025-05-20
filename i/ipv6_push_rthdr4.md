# Function: <code>ipv6_push_rthdr4</code>

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
In net/ipv6/exthdrs.c (ffffffff818940e3)
Location: net/ipv6/exthdrs.c:867
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff818bb5c5)
Location: net/ipv6/exthdrs.c:867
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff8193e602)
Location: net/ipv6/exthdrs.c:908
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff8199753d)
Location: net/ipv6/exthdrs.c:895
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff819cde0d)
Location: net/ipv6/exthdrs.c:895
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff81a3ca2b)
Location: net/ipv6/exthdrs.c:891
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff81a736ab)
Location: net/ipv6/exthdrs.c:891
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipv6_push_rthdr4(struct sk_buff *skb, u8 *proto, struct ipv6_rt_hdr *opt, struct in6_addr **addr_p, struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b6be60)
Location: net/ipv6/exthdrs.c:1088
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81b6be60-ffffffff81b6bffa: ipv6_push_rthdr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipv6_push_rthdr4(struct sk_buff *skb, u8 *proto, struct ipv6_rt_hdr *opt, struct in6_addr **addr_p, struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b7a8d0)
Location: net/ipv6/exthdrs.c:1083
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81b7a8d0-ffffffff81b7aa6a: ipv6_push_rthdr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipv6_push_rthdr4(struct sk_buff *skb, u8 *proto, struct ipv6_rt_hdr *opt, struct in6_addr **addr_p, struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b69320)
Location: net/ipv6/exthdrs.c:1083
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81b69320-ffffffff81b694b4: ipv6_push_rthdr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipv6_push_rthdr4(struct sk_buff *skb, u8 *proto, struct ipv6_rt_hdr *opt, struct in6_addr **addr_p, struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81c30d50)
Location: net/ipv6/exthdrs.c:1131
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81c30d50-ffffffff81c30ee4: ipv6_push_rthdr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipv6_push_rthdr4(struct sk_buff *skb, u8 *proto, struct ipv6_rt_hdr *opt, struct in6_addr **addr_p, struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81dceba0)
Location: net/ipv6/exthdrs.c:1132
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81dceba0-ffffffff81dced03: ipv6_push_rthdr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipv6_push_rthdr4(struct sk_buff *skb, u8 *proto, struct ipv6_rt_hdr *opt, struct in6_addr **addr_p, struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81f9fed0)
Location: net/ipv6/exthdrs.c:1132
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81f9fed0-ffffffff81fa0033: ipv6_push_rthdr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipv6_push_rthdr4(struct sk_buff *skb, u8 *proto, struct ipv6_rt_hdr *opt, struct in6_addr **addr_p, struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff820009b0)
Location: net/ipv6/exthdrs.c:1099
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff820009b0-ffffffff82000b13: ipv6_push_rthdr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipv6_push_rthdr4(struct sk_buff *skb, u8 *proto, struct ipv6_rt_hdr *opt, struct in6_addr **addr_p, struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff820cf7f0)
Location: net/ipv6/exthdrs.c:1104
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff820cf7f0-ffffffff820cf953: ipv6_push_rthdr4 (STB_LOCAL)
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
In net/ipv6/exthdrs.c (ffff800010d3c17c)
Location: net/ipv6/exthdrs.c:891
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (c0e3f384)
Location: net/ipv6/exthdrs.c:891
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (c000000000e6fd20)
Location: net/ipv6/exthdrs.c:891
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffe000878b7a)
Location: net/ipv6/exthdrs.c:891
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff81a12d3b)
Location: net/ipv6/exthdrs.c:891
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff819cfafb)
Location: net/ipv6/exthdrs.c:891
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff81a7d7bb)
Location: net/ipv6/exthdrs.c:891
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff81a8a00b)
Location: net/ipv6/exthdrs.c:891
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
