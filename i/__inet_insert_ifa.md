# Function: <code>__inet_insert_ifa</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817911c0)
Location: net/ipv4/devinet.c:436
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
```
**Symbols:**

```
ffffffff817911c0-ffffffff817913e5: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817fe500)
Location: net/ipv4/devinet.c:440
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff817fe500-ffffffff817fe725: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8182f460)
Location: net/ipv4/devinet.c:440
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff8182f460-ffffffff8182f685: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81850910)
Location: net/ipv4/devinet.c:440
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81850910-ffffffff81850ba8: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818d0540)
Location: net/ipv4/devinet.c:446
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff818d0540-ffffffff818d07e0: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81926aa0)
Location: net/ipv4/devinet.c:447
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81926aa0-ffffffff81926d5e: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81955b50)
Location: net/ipv4/devinet.c:457
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81955b50-ffffffff81955e0e: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819ba520)
Location: net/ipv4/devinet.c:471
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff819ba520-ffffffff819ba7fb: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819f10b0)
Location: net/ipv4/devinet.c:471
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff819f10b0-ffffffff819f138e: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81adf020)
Location: net/ipv4/devinet.c:472
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81adf020-ffffffff81adf2fe: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aebe20)
Location: net/ipv4/devinet.c:472
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81aebe20-ffffffff81aec0fe: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad7490)
Location: net/ipv4/devinet.c:472
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81ad7490-ffffffff81ad776e: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:472
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81b95f40-ffffffff81b96237: __inet_insert_ifa (STB_LOCAL)
ffffffff81d3c1e6-ffffffff81d3c216: __inet_insert_ifa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:475
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81d27c70-ffffffff81d27f66: __inet_insert_ifa (STB_LOCAL)
ffffffff81f08a32-ffffffff81f08a5c: __inet_insert_ifa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:476
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81eef630-ffffffff81eef926: __inet_insert_ifa (STB_LOCAL)
ffffffff820b0471-ffffffff820b049b: __inet_insert_ifa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:476
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81f4eff0-ffffffff81f4f2e6: __inet_insert_ifa (STB_LOCAL)
ffffffff8213171c-ffffffff82131746: __inet_insert_ifa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:476
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff82015150-ffffffff8201545e: __inet_insert_ifa (STB_LOCAL)
ffffffff822130d1-ffffffff822130fb: __inet_insert_ifa.cold (STB_LOCAL)
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
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca7308)
Location: net/ipv4/devinet.c:471
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffff800010ca7308-ffff800010ca7614: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db3a24)
Location: net/ipv4/devinet.c:471
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
c0db3a24-c0db3d40: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000dbbab0)
Location: net/ipv4/devinet.c:471
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
c000000000dbbab0-c000000000dbbe64: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe0008024a0)
Location: net/ipv4/devinet.c:471
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffe0008024a0-ffffffe000802748: __inet_insert_ifa (STB_LOCAL)
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
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81990e50)
Location: net/ipv4/devinet.c:471
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81990e50-ffffffff8199112e: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8194a910)
Location: net/ipv4/devinet.c:471
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff8194a910-ffffffff8194abee: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819fb6f0)
Location: net/ipv4/devinet.c:471
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff819fb6f0-ffffffff819fb9ce: __inet_insert_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __inet_insert_ifa(struct in_ifaddr *ifa, struct nlmsghdr *nlh, u32 portid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a05a20)
Location: net/ipv4/devinet.c:471
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
**Symbols:**

```
ffffffff81a05a20-ffffffff81a05cfe: __inet_insert_ifa (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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
