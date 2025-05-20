# Function: <code>rtnl_valid_stats_req</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819175c0)
Location: net/core/rtnetlink.c:4977
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff819175c0-ffffffff81917649: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81949c00)
Location: net/core/rtnetlink.c:5008
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81949c00-ffffffff81949c89: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a18240)
Location: net/core/rtnetlink.c:5215
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81a18240-ffffffff81a182c9: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a18310)
Location: net/core/rtnetlink.c:5307
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81a18310-ffffffff81a18399: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819ff760)
Location: net/core/rtnetlink.c:5309
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff819ff760-ffffffff819ff841: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab1a30)
Location: net/core/rtnetlink.c:5330
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81ab1a30-ffffffff81ab1b11: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2ad30)
Location: net/core/rtnetlink.c:5730
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81c2ad30-ffffffff81c2adea: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81dddbd0)
Location: net/core/rtnetlink.c:5781
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81dddbd0-ffffffff81dddc8a: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e4e990)
Location: net/core/rtnetlink.c:5874
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81e4e990-ffffffff81e4ea4a: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f0d850)
Location: net/core/rtnetlink.c:5904
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81f0d850-ffffffff81f0d90a: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010beb728)
Location: net/core/rtnetlink.c:5008
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffff800010beb728-ffff800010beb818: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d042d8)
Location: net/core/rtnetlink.c:5008
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
c0d042d8-c0d043b4: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccea90)
Location: net/core/rtnetlink.c:5008
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
c000000000ccea90-c000000000cceb7c: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076ee56)
Location: net/core/rtnetlink.c:5008
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffe00076ee56-ffffffe00076ef06: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e9bd0)
Location: net/core/rtnetlink.c:5008
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff818e9bd0-ffffffff818e9c59: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a3a10)
Location: net/core/rtnetlink.c:5008
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff818a3a10-ffffffff818a3a99: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193ac00)
Location: net/core/rtnetlink.c:5008
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff8193ac00-ffffffff8193ac89: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr *nlh, bool strict_check, bool is_dump, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195c440)
Location: net/core/rtnetlink.c:5008
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff8195c440-ffffffff8195c4c9: rtnl_valid_stats_req (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
