# Function: <code>rtm_to_ifaddr</code>

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
In net/ipv4/devinet.c (ffffffff817918da)
Location: net/ipv4/devinet.c:742
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (ffffffff817fe9ca)
Location: net/ipv4/devinet.c:746
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (ffffffff8182f92a)
Location: net/ipv4/devinet.c:746
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (ffffffff8185103f)
Location: net/ipv4/devinet.c:767
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (ffffffff818d0c72)
Location: net/ipv4/devinet.c:774
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (ffffffff81926fd8)
Location: net/ipv4/devinet.c:775
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (ffffffff81956088)
Location: net/ipv4/devinet.c:785
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (ffffffff819baa89)
Location: net/ipv4/devinet.c:816
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (ffffffff819f1909)
Location: net/ipv4/devinet.c:816
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct in_ifaddr *rtm_to_ifaddr(struct net *net, struct nlmsghdr *nlh, __u32 *pvalid_lft, __u32 *pprefered_lft, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81adfb80)
Location: net/ipv4/devinet.c:823
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81adfb80-ffffffff81adfe65: rtm_to_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct in_ifaddr *rtm_to_ifaddr(struct net *net, struct nlmsghdr *nlh, __u32 *pvalid_lft, __u32 *pprefered_lft, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aeca00)
Location: net/ipv4/devinet.c:822
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81aeca00-ffffffff81aecce5: rtm_to_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct in_ifaddr *rtm_to_ifaddr(struct net *net, struct nlmsghdr *nlh, __u32 *pvalid_lft, __u32 *pprefered_lft, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad81d0)
Location: net/ipv4/devinet.c:822
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81ad81d0-ffffffff81ad84cb: rtm_to_ifaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct in_ifaddr *rtm_to_ifaddr(struct net *net, struct nlmsghdr *nlh, __u32 *pvalid_lft, __u32 *pprefered_lft, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:822
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81b97030-ffffffff81b97343: rtm_to_ifaddr (STB_LOCAL)
ffffffff81d3c288-ffffffff81d3c2bb: rtm_to_ifaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:823
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81d28e60-ffffffff81d29174: rtm_to_ifaddr.constprop.0 (STB_LOCAL)
ffffffff81f08acd-ffffffff81f08b00: rtm_to_ifaddr.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:824
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81ef07a0-ffffffff81ef0ab4: rtm_to_ifaddr.constprop.0 (STB_LOCAL)
ffffffff820b04d3-ffffffff820b0506: rtm_to_ifaddr.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:824
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81f50200-ffffffff81f50514: rtm_to_ifaddr.constprop.0 (STB_LOCAL)
ffffffff8213177e-ffffffff821317b1: rtm_to_ifaddr.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:827
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff820163b0-ffffffff8201675f: rtm_to_ifaddr.constprop.0 (STB_LOCAL)
ffffffff82213133-ffffffff82213174: rtm_to_ifaddr.constprop.0.cold (STB_LOCAL)
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
In net/ipv4/devinet.c (ffff800010ca78a4)
Location: net/ipv4/devinet.c:816
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (c0db445c)
Location: net/ipv4/devinet.c:816
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (c000000000dbc600)
Location: net/ipv4/devinet.c:816
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (ffffffe00080296e)
Location: net/ipv4/devinet.c:816
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (ffffffff819916a9)
Location: net/ipv4/devinet.c:816
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (ffffffff8194b169)
Location: net/ipv4/devinet.c:816
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (ffffffff819fbf49)
Location: net/ipv4/devinet.c:816
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
In net/ipv4/devinet.c (ffffffff81a062b9)
Location: net/ipv4/devinet.c:816
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
</ul>
