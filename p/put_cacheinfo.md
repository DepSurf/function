# Function: <code>put_cacheinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81790ac5)
Location: net/ipv4/devinet.c:1490
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff817c92b0)
Location: net/ipv6/addrconf.c:4265
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff817c92b0-ffffffff817c934b: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817fddf5)
Location: net/ipv4/devinet.c:1516
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81836490)
Location: net/ipv6/addrconf.c:4517
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffffffff81836490-ffffffff8183652b: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8182ed55)
Location: net/ipv4/devinet.c:1516
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81867fa0)
Location: net/ipv6/addrconf.c:4560
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffffffff81867fa0-ffffffff8186803b: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81850221)
Location: net/ipv4/devinet.c:1556
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8188c700)
Location: net/ipv6/addrconf.c:4638
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffffffff8188c700-ffffffff8188c79b: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818cfe51)
Location: net/ipv4/devinet.c:1565
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8190da90)
Location: net/ipv6/addrconf.c:4642
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffffffff8190da90-ffffffff8190db2b: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81926339)
Location: net/ipv4/devinet.c:1573
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81964d40)
Location: net/ipv6/addrconf.c:4763
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffffffff81964d40-ffffffff81964ddb: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8195537d)
Location: net/ipv4/devinet.c:1585
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8199a1c0)
Location: net/ipv6/addrconf.c:4785
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffffffff8199a1c0-ffffffff8199a25b: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819b9d08)
Location: net/ipv4/devinet.c:1635
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81a06150)
Location: net/ipv6/addrconf.c:4821
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffffffff81a06150-ffffffff81a061ef: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819f0898)
Location: net/ipv4/devinet.c:1630
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81a3ccc0)
Location: net/ipv6/addrconf.c:4850
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffffffff81a3ccc0-ffffffff81a3cd5f: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ade808)
Location: net/ipv4/devinet.c:1636
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81b34457)
Location: net/ipv6/addrconf.c:4867
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aeb5e8)
Location: net/ipv4/devinet.c:1635
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81b44ca7)
Location: net/ipv6/addrconf.c:4894
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad6c58)
Location: net/ipv4/devinet.c:1635
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81b32f79)
Location: net/ipv6/addrconf.c:4898
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81b95698)
Location: net/ipv4/devinet.c:1635
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81bf9219)
Location: net/ipv6/addrconf.c:4934
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81d273ec)
Location: net/ipv4/devinet.c:1640
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81d92609)
Location: net/ipv6/addrconf.c:4946
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81eeecf6)
Location: net/ipv4/devinet.c:1641
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81f60d39)
Location: net/ipv6/addrconf.c:4959
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81f4e6b6)
Location: net/ipv4/devinet.c:1644
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81fc0bb6)
Location: net/ipv6/addrconf.c:4965
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff820147f7)
Location: net/ipv4/devinet.c:1661
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8208e076)
Location: net/ipv6/addrconf.c:5020
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca6ae4)
Location: net/ipv4/devinet.c:1630
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffff800010cfe0c0)
Location: net/ipv6/addrconf.c:4850
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffff800010cfe0c0-ffff800010cfe194: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db320c)
Location: net/ipv4/devinet.c:1630
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (c0e05c8c)
Location: net/ipv6/addrconf.c:4850
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
c0e05c8c-c0e05d2c: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000dbafa0)
Location: net/ipv4/devinet.c:1630
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (c000000000e26510)
Location: net/ipv6/addrconf.c:4850
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
c000000000e26510-c000000000e265dc: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe000801e66)
Location: net/ipv4/devinet.c:1630
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffe00084859c)
Location: net/ipv6/addrconf.c:4850
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffffffe00084859c-ffffffe00084861a: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81990638)
Location: net/ipv4/devinet.c:1630
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff819dc350)
Location: net/ipv6/addrconf.c:4850
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffffffff819dc350-ffffffff819dc3ef: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8194a0f8)
Location: net/ipv4/devinet.c:1630
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81999110)
Location: net/ipv6/addrconf.c:4850
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffffffff81999110-ffffffff819991af: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819faed8)
Location: net/ipv4/devinet.c:1630
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81a46dd0)
Location: net/ipv6/addrconf.c:4850
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffffffff81a46dd0-ffffffff81a46e6f: put_cacheinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int put_cacheinfo(struct sk_buff *skb, long unsigned int cstamp, long unsigned int tstamp, u32 preferred, u32 valid);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a05229)
Location: net/ipv4/devinet.c:1630
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff81a52b50)
Location: net/ipv6/addrconf.c:4850
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
**Symbols:**

```
ffffffff81a52b50-ffffffff81a52bf1: put_cacheinfo (STB_LOCAL)
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
