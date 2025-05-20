# Function: <code>__udp6_lib_err_encap</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bc45e)
Location: net/ipv6/udp.c:460
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
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
In net/ipv6/udp.c (ffffffff81a2af8a)
Location: net/ipv6/udp.c:448
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
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
In net/ipv6/udp.c (ffffffff81a61aea)
Location: net/ipv6/udp.c:448
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__udp6_lib_err_encap(struct net *net, const struct ipv6hdr *hdr, int offset, struct udphdr *uh, struct udp_table *udptable, struct sk_buff *skb, struct inet6_skb_parm *opt, u8 type, u8 code, __be32 info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b5a2b0)
Location: net/ipv6/udp.c:451
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
**Symbols:**

```
ffffffff81b5a2b0-ffffffff81b5a429: __udp6_lib_err_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__udp6_lib_err_encap(struct net *net, const struct ipv6hdr *hdr, int offset, struct udphdr *uh, struct udp_table *udptable, struct sk_buff *skb, struct inet6_skb_parm *opt, u8 type, u8 code, __be32 info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b689b0)
Location: net/ipv6/udp.c:502
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
**Symbols:**

```
ffffffff81b689b0-ffffffff81b68b29: __udp6_lib_err_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b572a4)
Location: net/ipv6/udp.c:501
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81c1e87e)
Location: net/ipv6/udp.c:503
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81dbb0d3)
Location: net/ipv6/udp.c:505
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81f8b1a8)
Location: net/ipv6/udp.c:520
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81feb866)
Location: net/ipv6/udp.c:534
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff820b9531)
Location: net/ipv6/udp.c:502
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
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
In net/ipv6/udp.c (ffff800010d26b7c)
Location: net/ipv6/udp.c:448
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
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
In net/ipv6/udp.c (c0e2bd18)
Location: net/ipv6/udp.c:448
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
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
In net/ipv6/udp.c (c000000000e578b0)
Location: net/ipv6/udp.c:448
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
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
In net/ipv6/udp.c (ffffffe000868c5e)
Location: net/ipv6/udp.c:448
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
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
In net/ipv6/udp.c (ffffffff81a0117a)
Location: net/ipv6/udp.c:448
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
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
In net/ipv6/udp.c (ffffffff819bdf3a)
Location: net/ipv6/udp.c:448
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
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
In net/ipv6/udp.c (ffffffff81a6bbfa)
Location: net/ipv6/udp.c:448
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
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
In net/ipv6/udp.c (ffffffff81a7820a)
Location: net/ipv6/udp.c:448
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
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
</ul>
