# Function: <code>inet_fill_ifaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81790980)
Location: net/ipv4/devinet.c:1503
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
**Symbols:**

```
ffffffff81790980-ffffffff81790c64: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817fdcb0)
Location: net/ipv4/devinet.c:1529
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
**Symbols:**

```
ffffffff817fdcb0-ffffffff817fdf94: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8182ec10)
Location: net/ipv4/devinet.c:1529
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
**Symbols:**

```
ffffffff8182ec10-ffffffff8182eef4: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818500e0)
Location: net/ipv4/devinet.c:1569
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
**Symbols:**

```
ffffffff818500e0-ffffffff818503ad: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818cfd10)
Location: net/ipv4/devinet.c:1578
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
**Symbols:**

```
ffffffff818cfd10-ffffffff818cffdd: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, u32 portid, u32 seq, int event, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819261e0)
Location: net/ipv4/devinet.c:1586
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
**Symbols:**

```
ffffffff819261e0-ffffffff819264db: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81955210)
Location: net/ipv4/devinet.c:1598
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff81955210-ffffffff81955545: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1648
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff819b9ba0-ffffffff819b9ee3: inet_fill_ifaddr (STB_LOCAL)
ffffffff819bcc78-ffffffff819bcc93: inet_fill_ifaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819f0730)
Location: net/ipv4/devinet.c:1643
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff819f0730-ffffffff819f0a7a: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ade6a0)
Location: net/ipv4/devinet.c:1649
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff81ade6a0-ffffffff81ade9f6: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1648
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff81aeb480-ffffffff81aeb7f3: inet_fill_ifaddr (STB_LOCAL)
ffffffff81c32897-ffffffff81c328af: inet_fill_ifaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1648
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff81ad6af0-ffffffff81ad6e5b: inet_fill_ifaddr (STB_LOCAL)
ffffffff81c24b6b-ffffffff81c24b83: inet_fill_ifaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1648
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff81b95530-ffffffff81b9589b: inet_fill_ifaddr (STB_LOCAL)
ffffffff81d3c1b9-ffffffff81d3c1d1: inet_fill_ifaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1653
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff81d27200-ffffffff81d27598: inet_fill_ifaddr (STB_LOCAL)
ffffffff81f08a06-ffffffff81f08a1e: inet_fill_ifaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81eeeb50)
Location: net/ipv4/devinet.c:1654
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff81eeeb50-ffffffff81eeef15: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81f4e510)
Location: net/ipv4/devinet.c:1657
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff81f4e510-ffffffff81f4e8d5: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff82014650)
Location: net/ipv4/devinet.c:1674
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff82014650-ffffffff82014a18: inet_fill_ifaddr (STB_LOCAL)
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
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca6998)
Location: net/ipv4/devinet.c:1643
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffff800010ca6998-ffff800010ca6ca4: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db308c)
Location: net/ipv4/devinet.c:1643
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:in_dev_dump_addr
```
**Symbols:**

```
c0db308c-c0db33b8: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000dbae00)
Location: net/ipv4/devinet.c:1643
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:in_dev_dump_addr
```
**Symbols:**

```
c000000000dbae00-c000000000dbb254: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe000801d52)
Location: net/ipv4/devinet.c:1643
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:in_dev_dump_addr
```
**Symbols:**

```
ffffffe000801d52-ffffffe000801fc4: inet_fill_ifaddr (STB_LOCAL)
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
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819904d0)
Location: net/ipv4/devinet.c:1643
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff819904d0-ffffffff8199081a: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81949f90)
Location: net/ipv4/devinet.c:1643
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff81949f90-ffffffff8194a2da: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819fad70)
Location: net/ipv4/devinet.c:1643
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff819fad70-ffffffff819fb0ba: inet_fill_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet_fill_ifaddr(struct sk_buff *skb, struct in_ifaddr *ifa, struct inet_fill_args *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a050c0)
Location: net/ipv4/devinet.c:1643
Inline: False
Direct callers:
  - net/ipv4/devinet.c:rtmsg_ifa
```
**Symbols:**

```
ffffffff81a050c0-ffffffff81a0540d: inet_fill_ifaddr (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inet_fill_args *args</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 portid</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 seq</code>
</li>
<li>
<b>Param removed. </b>
<code>int event</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
