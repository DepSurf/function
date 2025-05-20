# Function: <code>inet6_set_iftoken</code>

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
In net/ipv6/addrconf.c (ffffffff817d2181)
Location: net/ipv6/addrconf.c:4832
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
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
In net/ipv6/addrconf.c (ffffffff8183fb51)
Location: net/ipv6/addrconf.c:5087
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
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
In net/ipv6/addrconf.c (ffffffff81871781)
Location: net/ipv6/addrconf.c:5137
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
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
In net/ipv6/addrconf.c (ffffffff818964fa)
Location: net/ipv6/addrconf.c:5227
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
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
In net/ipv6/addrconf.c (ffffffff819178ca)
Location: net/ipv6/addrconf.c:5233
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
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
In net/ipv6/addrconf.c (ffffffff8196f007)
Location: net/ipv6/addrconf.c:5352
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
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
In net/ipv6/addrconf.c (ffffffff819a4bb7)
Location: net/ipv6/addrconf.c:5511
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
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
In net/ipv6/addrconf.c (ffffffff81a10f19)
Location: net/ipv6/addrconf.c:5592
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81a47c62)
Location: net/ipv6/addrconf.c:5621
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet6_set_iftoken(struct inet6_dev *idev, struct in6_addr *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3e670)
Location: net/ipv6/addrconf.c:5638
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
**Symbols:**

```
ffffffff81b3e670-ffffffff81b3e8ff: inet6_set_iftoken (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet6_set_iftoken(struct inet6_dev *idev, struct in6_addr *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b4d200)
Location: net/ipv6/addrconf.c:5669
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
**Symbols:**

```
ffffffff81b4d200-ffffffff81b4d48f: inet6_set_iftoken (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet6_set_iftoken(struct inet6_dev *idev, struct in6_addr *token, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3b000)
Location: net/ipv6/addrconf.c:5677
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
**Symbols:**

```
ffffffff81b3b000-ffffffff81b3b323: inet6_set_iftoken (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int inet6_set_iftoken(struct inet6_dev *idev, struct in6_addr *token, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5720
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
**Symbols:**

```
ffffffff81c017f0-ffffffff81c01b30: inet6_set_iftoken (STB_LOCAL)
ffffffff81d3fb41-ffffffff81d3fb73: inet6_set_iftoken.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inet6_set_iftoken(struct inet6_dev *idev, struct in6_addr *token, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5739
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
**Symbols:**

```
ffffffff81d9b4d0-ffffffff81d9b84d: inet6_set_iftoken (STB_LOCAL)
ffffffff81f0c4b6-ffffffff81f0c4e8: inet6_set_iftoken.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int inet6_set_iftoken(struct inet6_dev *idev, struct in6_addr *token, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5752
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
**Symbols:**

```
ffffffff81f6a110-ffffffff81f6a48d: inet6_set_iftoken (STB_LOCAL)
ffffffff820b3b76-ffffffff820b3ba8: inet6_set_iftoken.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int inet6_set_iftoken(struct inet6_dev *idev, struct in6_addr *token, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5758
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
**Symbols:**

```
ffffffff81fca150-ffffffff81fca4ca: inet6_set_iftoken (STB_LOCAL)
ffffffff82134c67-ffffffff82134c99: inet6_set_iftoken.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int inet6_set_iftoken(struct inet6_dev *idev, struct in6_addr *token, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5815
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
```
**Symbols:**

```
ffffffff820978f0-ffffffff82097c6a: inet6_set_iftoken (STB_LOCAL)
ffffffff8221672b-ffffffff8221675d: inet6_set_iftoken.cold (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffff800010d0a734)
Location: net/ipv6/addrconf.c:5621
Inline: True
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
In net/ipv6/addrconf.c (c0e10ec4)
Location: net/ipv6/addrconf.c:5621
Inline: True
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
In net/ipv6/addrconf.c (c000000000e35460)
Location: net/ipv6/addrconf.c:5621
Inline: True
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
In net/ipv6/addrconf.c (ffffffe0008521f4)
Location: net/ipv6/addrconf.c:5621
Inline: True
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
In net/ipv6/addrconf.c (ffffffff819e72f2)
Location: net/ipv6/addrconf.c:5621
Inline: True
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
In net/ipv6/addrconf.c (ffffffff819a40b2)
Location: net/ipv6/addrconf.c:5621
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81a51d72)
Location: net/ipv6/addrconf.c:5621
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81a5dcd2)
Location: net/ipv6/addrconf.c:5621
Inline: True
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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
