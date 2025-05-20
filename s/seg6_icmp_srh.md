# Function: <code>seg6_icmp_srh</code>

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
void seg6_icmp_srh(struct sk_buff *skb, struct inet6_skb_parm *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81c381e0)
Location: net/ipv6/seg6.c:111
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81c381e0-ffffffff81c38256: seg6_icmp_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void seg6_icmp_srh(struct sk_buff *skb, struct inet6_skb_parm *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81dd5e10)
Location: net/ipv6/seg6.c:111
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81dd5e10-ffffffff81dd5e9a: seg6_icmp_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void seg6_icmp_srh(struct sk_buff *skb, struct inet6_skb_parm *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81fa7620)
Location: net/ipv6/seg6.c:111
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff81fa7620-ffffffff81fa76aa: seg6_icmp_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void seg6_icmp_srh(struct sk_buff *skb, struct inet6_skb_parm *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff82007e80)
Location: net/ipv6/seg6.c:111
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff82007e80-ffffffff82007f0a: seg6_icmp_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void seg6_icmp_srh(struct sk_buff *skb, struct inet6_skb_parm *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff820d6da0)
Location: net/ipv6/seg6.c:111
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_notify
```
**Symbols:**

```
ffffffff820d6da0-ffffffff820d6e2a: seg6_icmp_srh (STB_GLOBAL)
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
