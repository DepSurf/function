# Function: <code>unsolicited_report_interval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81795430)
Location: net/ipv4/igmp.c:147
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff817e91be)
Location: net/ipv6/mcast.c:123
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:igmp6_group_added
```
**Symbols:**

```
ffffffff81795430-ffffffff817954b0: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81802e10)
Location: net/ipv4/igmp.c:141
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81857a0e)
Location: net/ipv6/mcast.c:123
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:igmp6_group_added
```
**Symbols:**

```
ffffffff81802e10-ffffffff81802e90: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81833db0)
Location: net/ipv4/igmp.c:141
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff818897fe)
Location: net/ipv6/mcast.c:123
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:igmp6_group_added
```
**Symbols:**

```
ffffffff81833db0-ffffffff81833e30: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81855360)
Location: net/ipv4/igmp.c:141
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff818afe7e)
Location: net/ipv6/mcast.c:123
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
```
**Symbols:**

```
ffffffff81855360-ffffffff818553e0: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818d5200)
Location: net/ipv4/igmp.c:142
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81932b9e)
Location: net/ipv6/mcast.c:123
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
```
**Symbols:**

```
ffffffff818d5200-ffffffff818d5280: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8192bb60)
Location: net/ipv4/igmp.c:142
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff8198b64e)
Location: net/ipv6/mcast.c:125
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff8192bb60-ffffffff8192bbe0: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8195aff0)
Location: net/ipv4/igmp.c:139
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff819c1f6e)
Location: net/ipv6/mcast.c:125
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff8195aff0-ffffffff8195b070: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819bfcf0)
Location: net/ipv4/igmp.c:135
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81a30d7e)
Location: net/ipv6/mcast.c:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff819bfcf0-ffffffff819bfd70: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819f6890)
Location: net/ipv4/igmp.c:135
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81a678ce)
Location: net/ipv6/mcast.c:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff819f6890-ffffffff819f6910: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae4bf0)
Location: net/ipv4/igmp.c:133
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81b65441)
Location: net/ipv6/mcast.c:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff81ae4bf0-ffffffff81ae4c70: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af1ac0)
Location: net/ipv4/igmp.c:133
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81b73be1)
Location: net/ipv6/mcast.c:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff81af1ac0-ffffffff81af1b40: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81add2b0)
Location: net/ipv4/igmp.c:133
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81b62524)
Location: net/ipv6/mcast.c:157
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff81add2b0-ffffffff81add330: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81b9c720)
Location: net/ipv4/igmp.c:133
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81c29fb4)
Location: net/ipv6/mcast.c:157
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff81b9c720-ffffffff81b9c7a0: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d2e730)
Location: net/ipv4/igmp.c:133
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81dc7414)
Location: net/ipv6/mcast.c:157
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff81d2e730-ffffffff81d2e7d0: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ef6700)
Location: net/ipv4/igmp.c:133
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81f980e4)
Location: net/ipv6/mcast.c:157
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff81ef6700-ffffffff81ef67a0: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f56170)
Location: net/ipv4/igmp.c:133
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81ff8ad4)
Location: net/ipv6/mcast.c:157
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff81f56170-ffffffff81f56210: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8201c5e0)
Location: net/ipv4/igmp.c:133
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff820c6744)
Location: net/ipv6/mcast.c:157
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff8201c5e0-ffffffff8201c680: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010cad358)
Location: net/ipv4/igmp.c:135
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffff800010d2da20)
Location: net/ipv6/mcast.c:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffff800010cad358-ffff800010cad408: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0db9c54)
Location: net/ipv4/igmp.c:135
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (c0e31f04)
Location: net/ipv6/mcast.c:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
c0db9c54-c0db9cfc: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc3850)
Location: net/ipv4/igmp.c:135
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (c000000000e5fee8)
Location: net/ipv6/mcast.c:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
c000000000dc3850-c000000000dc3944: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe00080739e)
Location: net/ipv4/igmp.c:135
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffe00086e04e)
Location: net/ipv6/mcast.c:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffe00080739e-ffffffe000807446: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81996630)
Location: net/ipv4/igmp.c:135
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81a06f5e)
Location: net/ipv6/mcast.c:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff81996630-ffffffff819966b0: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819500f0)
Location: net/ipv4/igmp.c:135
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff819c3d1e)
Location: net/ipv6/mcast.c:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff819500f0-ffffffff81950170: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a00ed0)
Location: net/ipv4/igmp.c:135
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81a719de)
Location: net/ipv6/mcast.c:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff81a00ed0-ffffffff81a00f50: unsolicited_report_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int unsolicited_report_interval(struct in_device *in_dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0b3c0)
Location: net/ipv4/igmp.c:135
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff81a7dffe)
Location: net/ipv6/mcast.c:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_reset
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
```
**Symbols:**

```
ffffffff81a0b3c0-ffffffff81a0b440: unsolicited_report_interval (STB_LOCAL)
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
