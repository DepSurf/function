# Function: <code>igmp6_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff817eabc0)
Location: net/ipv6/mcast.c:1931
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/mcast.c:igmp6_timer_handler
```
**Symbols:**

```
ffffffff817eabc0-ffffffff817eaf47: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81859490)
Location: net/ipv6/mcast.c:1930
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
**Symbols:**

```
ffffffff81859490-ffffffff818597a2: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff8188b2c0)
Location: net/ipv6/mcast.c:1954
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
**Symbols:**

```
ffffffff8188b2c0-ffffffff8188b5d2: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff818b1020)
Location: net/ipv6/mcast.c:1954
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff818b1020-ffffffff818b1369: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81933670)
Location: net/ipv6/mcast.c:1959
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff81933670-ffffffff819339b9: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff8198c010)
Location: net/ipv6/mcast.c:1982
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff8198c010-ffffffff8198c320: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff819c2a90)
Location: net/ipv6/mcast.c:1982
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff819c2a90-ffffffff819c2dc8: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a318b0)
Location: net/ipv6/mcast.c:1981
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff81a318b0-ffffffff81a31c01: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a68400)
Location: net/ipv6/mcast.c:1981
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff81a68400-ffffffff81a68751: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b616d0)
Location: net/ipv6/mcast.c:1978
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff81b616d0-ffffffff81b61a85: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b6fe50)
Location: net/ipv6/mcast.c:1978
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff81b6fe50-ffffffff81b7022d: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b5e110)
Location: net/ipv6/mcast.c:2124
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_mca_work
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff81b5e110-ffffffff81b5e43e: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81c255c0)
Location: net/ipv6/mcast.c:2122
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_mca_work
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff81c255c0-ffffffff81c25918: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81dc2d30)
Location: net/ipv6/mcast.c:2124
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_mca_work
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff81dc2d30-ffffffff81dc3185: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81f93780)
Location: net/ipv6/mcast.c:2124
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_mca_work
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff81f93780-ffffffff81f93bd3: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81ff40d0)
Location: net/ipv6/mcast.c:2124
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_mca_work
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff81ff40d0-ffffffff81ff456e: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff820c1030)
Location: net/ipv6/mcast.c:2122
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_mca_work
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff820c1030-ffffffff820c13f5: igmp6_send (STB_LOCAL)
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
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffff800010d2fdd8)
Location: net/ipv6/mcast.c:1981
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffff800010d2fdd8-ffff800010d30208: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (c0e335e0)
Location: net/ipv6/mcast.c:1981
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
c0e335e0-c0e33c00: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (c000000000e61080)
Location: net/ipv6/mcast.c:1981
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
c000000000e61080-c000000000e61500: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffe00086f55c)
Location: net/ipv6/mcast.c:1981
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffe00086f55c-ffffffe00086f9a4: igmp6_send (STB_LOCAL)
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
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a07a90)
Location: net/ipv6/mcast.c:1981
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff81a07a90-ffffffff81a07de1: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff819c4850)
Location: net/ipv6/mcast.c:1981
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff819c4850-ffffffff819c4ba1: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a72510)
Location: net/ipv6/mcast.c:1981
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff81a72510-ffffffff81a72861: igmp6_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void igmp6_send(struct in6_addr *addr, struct net_device *dev, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a7eb90)
Location: net/ipv6/mcast.c:1981
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:igmp6_group_dropped
```
**Symbols:**

```
ffffffff81a7eb90-ffffffff81a7eee6: igmp6_send (STB_LOCAL)
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
