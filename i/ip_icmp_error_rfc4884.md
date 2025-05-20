# Function: <code>ip_icmp_error_rfc4884</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip_icmp_error_rfc4884(const struct sk_buff *skb, struct sock_ee_data_rfc4884 *out, int thlen, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81ae8c90)
Location: net/ipv4/icmp.c:1176
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81ae8c90-ffffffff81ae8cef: ip_icmp_error_rfc4884 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip_icmp_error_rfc4884(const struct sk_buff *skb, struct sock_ee_data_rfc4884 *out, int thlen, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81ad4140)
Location: net/ipv4/icmp.c:1295
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81ad4140-ffffffff81ad42c6: ip_icmp_error_rfc4884 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip_icmp_error_rfc4884(const struct sk_buff *skb, struct sock_ee_data_rfc4884 *out, int thlen, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81b92e30)
Location: net/ipv4/icmp.c:1312
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81b92e30-ffffffff81b92fb6: ip_icmp_error_rfc4884 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip_icmp_error_rfc4884(const struct sk_buff *skb, struct sock_ee_data_rfc4884 *out, int thlen, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81d25040)
Location: net/ipv4/icmp.c:1318
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81d25040-ffffffff81d251d7: ip_icmp_error_rfc4884 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip_icmp_error_rfc4884(const struct sk_buff *skb, struct sock_ee_data_rfc4884 *out, int thlen, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81eec620)
Location: net/ipv4/icmp.c:1318
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81eec620-ffffffff81eec7b7: ip_icmp_error_rfc4884 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip_icmp_error_rfc4884(const struct sk_buff *skb, struct sock_ee_data_rfc4884 *out, int thlen, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81f4c410)
Location: net/ipv4/icmp.c:1326
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff81f4c410-ffffffff81f4c5a7: ip_icmp_error_rfc4884 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip_icmp_error_rfc4884(const struct sk_buff *skb, struct sock_ee_data_rfc4884 *out, int thlen, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff82012520)
Location: net/ipv4/icmp.c:1326
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_icmp_error
  - net/ipv6/datagram.c:ipv6_icmp_error
```
**Symbols:**

```
ffffffff82012520-ffffffff820126b7: ip_icmp_error_rfc4884 (STB_GLOBAL)
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
