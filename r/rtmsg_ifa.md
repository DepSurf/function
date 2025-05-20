# Function: <code>rtmsg_ifa</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81790c70)
Location: net/ipv4/devinet.c:1620
Inline: False
Direct callers:
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff81790c70-ffffffff81790d6e: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817fdfa0)
Location: net/ipv4/devinet.c:1646
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff817fdfa0-ffffffff817fe09e: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8182ef00)
Location: net/ipv4/devinet.c:1646
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff8182ef00-ffffffff8182effe: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818503b0)
Location: net/ipv4/devinet.c:1686
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff818503b0-ffffffff81850490: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818cffe0)
Location: net/ipv4/devinet.c:1695
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff818cffe0-ffffffff818d00c0: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819264e0)
Location: net/ipv4/devinet.c:1705
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff819264e0-ffffffff819265c6: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81955550)
Location: net/ipv4/devinet.c:1832
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff81955550-ffffffff81955651: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1884
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff819b9ef0-ffffffff819b9ff2: rtmsg_ifa (STB_LOCAL)
ffffffff819bcc93-ffffffff819bcca6: rtmsg_ifa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819f0a80)
Location: net/ipv4/devinet.c:1879
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff819f0a80-ffffffff819f0b82: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81adea00)
Location: net/ipv4/devinet.c:1885
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff81adea00-ffffffff81adeb02: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aeb800)
Location: net/ipv4/devinet.c:1884
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff81aeb800-ffffffff81aeb902: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad6e60)
Location: net/ipv4/devinet.c:1884
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff81ad6e60-ffffffff81ad6f62: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81b958a0)
Location: net/ipv4/devinet.c:1884
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff81b958a0-ffffffff81b959a2: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81d275a0)
Location: net/ipv4/devinet.c:1891
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff81d275a0-ffffffff81d276be: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81eeef30)
Location: net/ipv4/devinet.c:1892
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff81eeef30-ffffffff81eef04e: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81f4e8f0)
Location: net/ipv4/devinet.c:1895
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff81f4e8f0-ffffffff81f4ea0e: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff82014a30)
Location: net/ipv4/devinet.c:1926
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff82014a30-ffffffff82014b4e: rtmsg_ifa (STB_LOCAL)
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
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca6ca8)
Location: net/ipv4/devinet.c:1879
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffff800010ca6ca8-ffff800010ca6db8: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db33b8)
Location: net/ipv4/devinet.c:1879
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
c0db33b8-c0db34dc: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000dbb260)
Location: net/ipv4/devinet.c:1879
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
c000000000dbb260-c000000000dbb3c0: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe000801fc4)
Location: net/ipv4/devinet.c:1879
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffe000801fc4-ffffffe000802098: rtmsg_ifa (STB_LOCAL)
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
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81990820)
Location: net/ipv4/devinet.c:1879
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff81990820-ffffffff81990922: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8194a2e0)
Location: net/ipv4/devinet.c:1879
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff8194a2e0-ffffffff8194a3e2: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819fb0c0)
Location: net/ipv4/devinet.c:1879
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff819fb0c0-ffffffff819fb1c2: rtmsg_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rtmsg_ifa(int event, struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a05410)
Location: net/ipv4/devinet.c:1879
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
```
**Symbols:**

```
ffffffff81a05410-ffffffff81a05512: rtmsg_ifa (STB_LOCAL)
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
