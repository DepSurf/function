# Function: <code>rtmsg_ifinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172fb40)
Location: net/core/rtnetlink.c:2548
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
Direct callers:
  - net/core/dev.c:dev_close_many
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:register_netdevice
  - net/core/rtnetlink.c:rtnetlink_event
```
**Symbols:**

```
ffffffff8172fb40-ffffffff8172fb84: rtmsg_ifinfo.part.20 (STB_LOCAL)
ffffffff8172fb90-ffffffff8172fbaa: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8179a31f)
Location: net/core/rtnetlink.c:2742
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/rtnetlink.c:rtnetlink_event
```
**Symbols:**

```
ffffffff8179a290-ffffffff8179a2d4: rtmsg_ifinfo.part.23 (STB_LOCAL)
ffffffff8179a2e0-ffffffff8179a2fa: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c80bf)
Location: net/core/rtnetlink.c:2815
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
  - net/core/rtnetlink.c:rtnetlink_event
```
**Symbols:**

```
ffffffff817c8030-ffffffff817c8074: rtmsg_ifinfo.part.25 (STB_LOCAL)
ffffffff817c8080-ffffffff817c809a: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e6960)
Location: net/core/rtnetlink.c:2918
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff817e6960-ffffffff817e6980: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81861910)
Location: net/core/rtnetlink.c:3149
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff81861910-ffffffff81861933: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ad4d0)
Location: net/core/rtnetlink.c:3306
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff818ad4d0-ffffffff818ad4f5: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818d1730)
Location: net/core/rtnetlink.c:3449
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff818d1730-ffffffff818d1755: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8191e600)
Location: net/core/rtnetlink.c:3510
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff8191e600-ffffffff8191e625: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81950c30)
Location: net/core/rtnetlink.c:3541
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff81950c30-ffffffff81950c55: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a21a60)
Location: net/core/rtnetlink.c:3744
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff81a21a60-ffffffff81a21abd: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a21ea0)
Location: net/core/rtnetlink.c:3836
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff81a21ea0-ffffffff81a21efd: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a091d0)
Location: net/core/rtnetlink.c:3834
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff81a091d0-ffffffff81a0922d: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81abb6a0)
Location: net/core/rtnetlink.c:3855
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff81abb6a0-ffffffff81abb6fd: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c35f20)
Location: net/core/rtnetlink.c:3946
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff81c35f20-ffffffff81c35fa5: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags, u32 portid, const struct nlmsghdr *nlh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de9530)
Location: net/core/rtnetlink.c:3992
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff81de9530-ffffffff81de9619: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags, u32 portid, const struct nlmsghdr *nlh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e5ad80)
Location: net/core/rtnetlink.c:4081
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff81e5ad80-ffffffff81e5ae2f: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags, u32 portid, const struct nlmsghdr *nlh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f1a140)
Location: net/core/rtnetlink.c:4121
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff81f1a140-ffffffff81f1a1ef: rtmsg_ifinfo (STB_GLOBAL)
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
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bf27c0)
Location: net/core/rtnetlink.c:3541
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffff800010bf27c0-ffff800010bf2834: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d0b094)
Location: net/core/rtnetlink.c:3541
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
c0d0b094-c0d0b0e0: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd7790)
Location: net/core/rtnetlink.c:3541
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
c000000000cd7790-c000000000cd77c0: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe000774290)
Location: net/core/rtnetlink.c:3541
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffe000774290-ffffffe0007742f2: rtmsg_ifinfo (STB_GLOBAL)
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
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818f0c00)
Location: net/core/rtnetlink.c:3541
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff818f0c00-ffffffff818f0c25: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818aaa40)
Location: net/core/rtnetlink.c:3541
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff818aaa40-ffffffff818aaa65: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81941c30)
Location: net/core/rtnetlink.c:3541
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff81941c30-ffffffff81941c55: rtmsg_ifinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rtmsg_ifinfo(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81963530)
Location: net/core/rtnetlink.c:3541
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_notify_flags
  - net/core/dev.c:dev_close_many
```
**Symbols:**

```
ffffffff81963530-ffffffff81963555: rtmsg_ifinfo (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 portid</code>
</li>
<li>
<b>Param added. </b>
<code>const struct nlmsghdr *nlh</code>
</li>
</ul>
</details>
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
