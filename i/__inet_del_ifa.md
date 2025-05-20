# Function: <code>__inet_del_ifa</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81790d70)
Location: net/ipv4/devinet.c:326
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
```
**Symbols:**

```
ffffffff81790d70-ffffffff81791011: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817fe0a0)
Location: net/ipv4/devinet.c:326
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff817fe0a0-ffffffff817fe356: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8182f000)
Location: net/ipv4/devinet.c:326
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff8182f000-ffffffff8182f2b6: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81850490)
Location: net/ipv4/devinet.c:326
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff81850490-ffffffff8185074d: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818d00c0)
Location: net/ipv4/devinet.c:332
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff818d00c0-ffffffff818d037d: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819265d0)
Location: net/ipv4/devinet.c:333
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff819265d0-ffffffff819268b5: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81955660)
Location: net/ipv4/devinet.c:343
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff81955660-ffffffff81955945: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819ba000)
Location: net/ipv4/devinet.c:347
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff819ba000-ffffffff819ba2fd: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819f0b90)
Location: net/ipv4/devinet.c:347
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff819f0b90-ffffffff819f0e8d: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81adeb10)
Location: net/ipv4/devinet.c:348
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inetdev_destroy
```
**Symbols:**

```
ffffffff81adeb10-ffffffff81adee0d: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aeb910)
Location: net/ipv4/devinet.c:348
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inetdev_destroy
```
**Symbols:**

```
ffffffff81aeb910-ffffffff81aebc0d: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad6f70)
Location: net/ipv4/devinet.c:348
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff81ad6f70-ffffffff81ad7261: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:348
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff81b959b0-ffffffff81b95cb0: __inet_del_ifa (STB_LOCAL)
ffffffff81d3c1d1-ffffffff81d3c1e6: __inet_del_ifa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:351
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff81d276c0-ffffffff81d279c8: __inet_del_ifa (STB_LOCAL)
ffffffff81f08a1e-ffffffff81f08a32: __inet_del_ifa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:352
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inetdev_destroy
```
**Symbols:**

```
ffffffff81eef060-ffffffff81eef368: __inet_del_ifa (STB_LOCAL)
ffffffff820b045d-ffffffff820b0471: __inet_del_ifa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:352
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inetdev_destroy
```
**Symbols:**

```
ffffffff81f4ea20-ffffffff81f4ed28: __inet_del_ifa (STB_LOCAL)
ffffffff82131708-ffffffff8213171c: __inet_del_ifa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:352
Inline: False
Direct callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
  - net/ipv4/devinet.c:inetdev_destroy
```
**Symbols:**

```
ffffffff82014b60-ffffffff82014e89: __inet_del_ifa (STB_LOCAL)
ffffffff822130bd-ffffffff822130d1: __inet_del_ifa.cold (STB_LOCAL)
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
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca6db8)
Location: net/ipv4/devinet.c:347
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffff800010ca6db8-ffff800010ca710c: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db34dc)
Location: net/ipv4/devinet.c:347
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
c0db34dc-c0db380c: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000dbb3c0)
Location: net/ipv4/devinet.c:347
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
c000000000dbb3c0-c000000000dbb830: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe000802098)
Location: net/ipv4/devinet.c:347
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffe000802098-ffffffe000802332: __inet_del_ifa (STB_LOCAL)
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
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81990930)
Location: net/ipv4/devinet.c:347
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff81990930-ffffffff81990c2d: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8194a3f0)
Location: net/ipv4/devinet.c:347
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff8194a3f0-ffffffff8194a6ed: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819fb1d0)
Location: net/ipv4/devinet.c:347
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff819fb1d0-ffffffff819fb4cd: __inet_del_ifa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __inet_del_ifa(struct in_device *in_dev, struct in_ifaddr **ifap, int destroy, struct nlmsghdr *nlh, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a05520)
Location: net/ipv4/devinet.c:347
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff81a05520-ffffffff81a0581d: __inet_del_ifa (STB_LOCAL)
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
