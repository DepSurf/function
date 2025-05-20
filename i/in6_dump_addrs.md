# Function: <code>in6_dump_addrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817cc767)
Location: net/ipv6/addrconf.c:4415
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff818391c5)
Location: net/ipv6/addrconf.c:4667
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186abe5)
Location: net/ipv6/addrconf.c:4710
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
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
In net/ipv6/addrconf.c (ffffffff8188f17b)
Location: net/ipv6/addrconf.c:4788
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
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
In net/ipv6/addrconf.c (ffffffff819107cb)
Location: net/ipv6/addrconf.c:4792
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
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
In net/ipv6/addrconf.c (ffffffff81968439)
Location: net/ipv6/addrconf.c:4919
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199d1e0)
Location: net/ipv6/addrconf.c:4966
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff8199d1e0-ffffffff8199d63c: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5002
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81a093b0-ffffffff81a0988a: in6_dump_addrs (STB_LOCAL)
ffffffff81a11298-ffffffff81a112cd: in6_dump_addrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a400a0)
Location: net/ipv6/addrconf.c:5031
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81a400a0-ffffffff81a40574: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b35e00)
Location: net/ipv6/addrconf.c:5048
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81b35e00-ffffffff81b35fbf: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b452e0)
Location: net/ipv6/addrconf.c:5079
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81b452e0-ffffffff81b4549f: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b32df0)
Location: net/ipv6/addrconf.c:5083
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81b32df0-ffffffff81b331a5: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bf9090)
Location: net/ipv6/addrconf.c:5121
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81bf9090-ffffffff81bf9445: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d92470)
Location: net/ipv6/addrconf.c:5138
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81d92470-ffffffff81d9282f: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f60ba0)
Location: net/ipv6/addrconf.c:5151
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81f60ba0-ffffffff81f60f5f: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc09d0)
Location: net/ipv6/addrconf.c:5157
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81fc09d0-ffffffff81fc0d8f: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208de90)
Location: net/ipv6/addrconf.c:5212
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff8208de90-ffffffff8208e251: in6_dump_addrs (STB_LOCAL)
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
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d01318)
Location: net/ipv6/addrconf.c:5031
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffff800010d01318-ffff800010d017cc: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e08e98)
Location: net/ipv6/addrconf.c:5031
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
c0e08e98-c0e09310: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e2b290)
Location: net/ipv6/addrconf.c:5031
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
c000000000e2b290-c000000000e2b820: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084b23e)
Location: net/ipv6/addrconf.c:5031
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffe00084b23e-ffffffe00084b578: in6_dump_addrs (STB_LOCAL)
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
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819df730)
Location: net/ipv6/addrconf.c:5031
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff819df730-ffffffff819dfc04: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199c4f0)
Location: net/ipv6/addrconf.c:5031
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff8199c4f0-ffffffff8199c9c4: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4a1b0)
Location: net/ipv6/addrconf.c:5031
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81a4a1b0-ffffffff81a4a684: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int in6_dump_addrs(struct inet6_dev *idev, struct sk_buff *skb, struct netlink_callback *cb, int s_ip_idx, struct inet6_fill_args *fillargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a560f0)
Location: net/ipv6/addrconf.c:5031
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_dump_addr
```
**Symbols:**

```
ffffffff81a560f0-ffffffff81a565c4: in6_dump_addrs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
