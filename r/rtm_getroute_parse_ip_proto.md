# Function: <code>rtm_getroute_parse_ip_proto</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff8193ca90)
Location: net/ipv4/netlink.c:8
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff8193ca90-ffffffff8193cacc: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff8196c810)
Location: net/ipv4/netlink.c:9
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff8196c810-ffffffff8196c85d: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff819d3520)
Location: net/ipv4/netlink.c:10
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff819d3520-ffffffff819d3570: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff81a0a090)
Location: net/ipv4/netlink.c:10
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81a0a090-ffffffff81a0a0e0: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff81afa860)
Location: net/ipv4/netlink.c:10
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81afa860-ffffffff81afa8b0: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff81b08020)
Location: net/ipv4/netlink.c:10
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81b08020-ffffffff81b08070: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff81af3880)
Location: net/ipv4/netlink.c:10
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81af3880-ffffffff81af38e1: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff81bb3da0)
Location: net/ipv4/netlink.c:10
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81bb3da0-ffffffff81bb3e01: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff81d47620)
Location: net/ipv4/netlink.c:10
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81d47620-ffffffff81d476b5: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff81f10ab0)
Location: net/ipv4/netlink.c:10
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81f10ab0-ffffffff81f10b45: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff81f707a0)
Location: net/ipv4/netlink.c:10
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81f707a0-ffffffff81f7083d: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff82036f00)
Location: net/ipv4/netlink.c:10
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff82036f00-ffffffff82036f9d: rtm_getroute_parse_ip_proto (STB_GLOBAL)
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
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffff800010cc3458)
Location: net/ipv4/netlink.c:10
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffff800010cc3458-ffff800010cc350c: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (c0dcec80)
Location: net/ipv4/netlink.c:10
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
c0dcec80-c0dced04: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (c000000000ddf090)
Location: net/ipv4/netlink.c:10
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
c000000000ddf090-c000000000ddf128: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffe0008187aa)
Location: net/ipv4/netlink.c:10
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffe0008187aa-ffffffe000818844: rtm_getroute_parse_ip_proto (STB_GLOBAL)
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
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff819a9e30)
Location: net/ipv4/netlink.c:10
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff819a9e30-ffffffff819a9e80: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff819638f0)
Location: net/ipv4/netlink.c:10
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff819638f0-ffffffff81963940: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff81a146d0)
Location: net/ipv4/netlink.c:10
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81a146d0-ffffffff81a14720: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtm_getroute_parse_ip_proto(struct nlattr *attr, u8 *ip_proto, u8 family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/netlink.c (ffffffff81a1f0e0)
Location: net/ipv4/netlink.c:10
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81a1f0e0-ffffffff81a1f130: rtm_getroute_parse_ip_proto (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 family</code>
</li>
<li>
<b>Param reordered. </b>
<code>attr, ip_proto, extack</code> ➡️ <code>attr, ip_proto, family, extack</code>
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
