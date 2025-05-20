# Function: <code>icmp_build_probe</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool icmp_build_probe(struct sk_buff *skb, struct icmphdr *icmphdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81b92fc0)
Location: net/ipv4/icmp.c:1026
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
**Symbols:**

```
ffffffff81b92fc0-ffffffff81b93366: icmp_build_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool icmp_build_probe(struct sk_buff *skb, struct icmphdr *icmphdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81d25620)
Location: net/ipv4/icmp.c:1022
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
**Symbols:**

```
ffffffff81d25620-ffffffff81d25a06: icmp_build_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool icmp_build_probe(struct sk_buff *skb, struct icmphdr *icmphdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81eeceb0)
Location: net/ipv4/icmp.c:1022
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
**Symbols:**

```
ffffffff81eeceb0-ffffffff81eed296: icmp_build_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool icmp_build_probe(struct sk_buff *skb, struct icmphdr *icmphdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81f4c850)
Location: net/ipv4/icmp.c:1030
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
**Symbols:**

```
ffffffff81f4c850-ffffffff81f4cc36: icmp_build_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool icmp_build_probe(struct sk_buff *skb, struct icmphdr *icmphdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff82012960)
Location: net/ipv4/icmp.c:1030
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
**Symbols:**

```
ffffffff82012960-ffffffff82012d46: icmp_build_probe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
