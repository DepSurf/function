# Function: <code>valid_fdb_dump_strict</code>

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
int valid_fdb_dump_strict(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818caa00)
Location: net/core/rtnetlink.c:3836
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff818caa00-ffffffff818cab67: valid_fdb_dump_strict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int valid_fdb_dump_strict(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81917fc0)
Location: net/core/rtnetlink.c:3903
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81917fc0-ffffffff8191812e: valid_fdb_dump_strict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int valid_fdb_dump_strict(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8194a5e0)
Location: net/core/rtnetlink.c:3934
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff8194a5e0-ffffffff8194a74e: valid_fdb_dump_strict (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81a1a380)
Location: net/core/rtnetlink.c:4137
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81a1a380-ffffffff81a1a4f7: valid_fdb_dump_strict.constprop.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81a1a600)
Location: net/core/rtnetlink.c:4229
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81a1a600-ffffffff81a1a777: valid_fdb_dump_strict.constprop.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81a01d40)
Location: net/core/rtnetlink.c:4227
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81a01d40-ffffffff81a01ef3: valid_fdb_dump_strict.constprop.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81ab41d0)
Location: net/core/rtnetlink.c:4248
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81ab41d0-ffffffff81ab43b6: valid_fdb_dump_strict.constprop.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81c2d150)
Location: net/core/rtnetlink.c:4369
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81c2d150-ffffffff81c2d341: valid_fdb_dump_strict.constprop.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81de02c0)
Location: net/core/rtnetlink.c:4420
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81de02c0-ffffffff81de04b1: valid_fdb_dump_strict.constprop.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81e51a50)
Location: net/core/rtnetlink.c:4509
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81e51a50-ffffffff81e51c41: valid_fdb_dump_strict.constprop.0 (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81f10b20)
Location: net/core/rtnetlink.c:4542
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff81f10b20-ffffffff81f10d11: valid_fdb_dump_strict.constprop.0 (STB_LOCAL)
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
int valid_fdb_dump_strict(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bec7e8)
Location: net/core/rtnetlink.c:3934
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffff800010bec7e8-ffff800010bec9a0: valid_fdb_dump_strict (STB_LOCAL)
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
In net/core/rtnetlink.c (c0d07168)
Location: net/core/rtnetlink.c:3934
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int valid_fdb_dump_strict(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccfa60)
Location: net/core/rtnetlink.c:3934
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
c000000000ccfa60-c000000000ccfcb4: valid_fdb_dump_strict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int valid_fdb_dump_strict(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe0007700c4)
Location: net/core/rtnetlink.c:3934
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffe0007700c4-ffffffe00077020c: valid_fdb_dump_strict (STB_LOCAL)
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
int valid_fdb_dump_strict(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ea5b0)
Location: net/core/rtnetlink.c:3934
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff818ea5b0-ffffffff818ea71e: valid_fdb_dump_strict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int valid_fdb_dump_strict(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a43f0)
Location: net/core/rtnetlink.c:3934
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff818a43f0-ffffffff818a455e: valid_fdb_dump_strict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int valid_fdb_dump_strict(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193b5e0)
Location: net/core/rtnetlink.c:3934
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff8193b5e0-ffffffff8193b74e: valid_fdb_dump_strict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int valid_fdb_dump_strict(const struct nlmsghdr *nlh, int *br_idx, int *brport_idx, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195ce60)
Location: net/core/rtnetlink.c:3934
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
**Symbols:**

```
ffffffff8195ce60-ffffffff8195cfce: valid_fdb_dump_strict (STB_LOCAL)
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
