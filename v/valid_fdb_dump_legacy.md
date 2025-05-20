# Function: <code>valid_fdb_dump_legacy</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int valid_fdb_dump_legacy(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818cb500)
Location: net/core/rtnetlink.c:3890
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff818cb500-ffffffff818cb5b9: valid_fdb_dump_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int valid_fdb_dump_legacy(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81918130)
Location: net/core/rtnetlink.c:3957
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81918130-ffffffff819181f5: valid_fdb_dump_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int valid_fdb_dump_legacy(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8194a750)
Location: net/core/rtnetlink.c:3988
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff8194a750-ffffffff8194a815: valid_fdb_dump_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1abe0)
Location: net/core/rtnetlink.c:4191
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81a1abe0-ffffffff81a1aca3: valid_fdb_dump_legacy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1ae00)
Location: net/core/rtnetlink.c:4283
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81a1ae00-ffffffff81a1aec3: valid_fdb_dump_legacy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a02670)
Location: net/core/rtnetlink.c:4281
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81a02670-ffffffff81a02751: valid_fdb_dump_legacy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab4c50)
Location: net/core/rtnetlink.c:4302
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81ab4c50-ffffffff81ab4d31: valid_fdb_dump_legacy.constprop.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81c2d960)
Location: net/core/rtnetlink.c:4423
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81c2d960-ffffffff81c2da57: valid_fdb_dump_legacy.constprop.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81de0b10)
Location: net/core/rtnetlink.c:4474
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81de0b10-ffffffff81de0c07: valid_fdb_dump_legacy.constprop.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81e52200)
Location: net/core/rtnetlink.c:4563
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81e52200-ffffffff81e522f7: valid_fdb_dump_legacy.constprop.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81f117e0)
Location: net/core/rtnetlink.c:4596
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81f117e0-ffffffff81f118d7: valid_fdb_dump_legacy.constprop.0 (STB_LOCAL)
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
int valid_fdb_dump_legacy(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bed680)
Location: net/core/rtnetlink.c:3988
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffff800010bed680-ffff800010bed778: valid_fdb_dump_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int valid_fdb_dump_legacy(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d05c08)
Location: net/core/rtnetlink.c:3988
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
c0d05c08-c0d05cf4: valid_fdb_dump_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int valid_fdb_dump_legacy(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccfdb0)
Location: net/core/rtnetlink.c:3988
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
c000000000ccfdb0-c000000000ccfee8: valid_fdb_dump_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int valid_fdb_dump_legacy(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe000770408)
Location: net/core/rtnetlink.c:3988
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffe000770408-ffffffe00077049e: valid_fdb_dump_legacy (STB_LOCAL)
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
int valid_fdb_dump_legacy(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ea720)
Location: net/core/rtnetlink.c:3988
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff818ea720-ffffffff818ea7e5: valid_fdb_dump_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int valid_fdb_dump_legacy(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a4560)
Location: net/core/rtnetlink.c:3988
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff818a4560-ffffffff818a4625: valid_fdb_dump_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int valid_fdb_dump_legacy(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193b750)
Location: net/core/rtnetlink.c:3988
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff8193b750-ffffffff8193b815: valid_fdb_dump_legacy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int valid_fdb_dump_legacy(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195cfd0)
Location: net/core/rtnetlink.c:3988
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff8195cfd0-ffffffff8195d095: valid_fdb_dump_legacy (STB_LOCAL)
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
