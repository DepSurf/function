# Function: <code>nh_valid_dump_req</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d4640)
Location: net/ipv4/nexthop.c:1632
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffff81a0b1b0)
Location: net/ipv4/nexthop.c:1634
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffff81afbb40)
Location: net/ipv4/nexthop.c:1770
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff81afbb40-ffffffff81afbcd4: nh_valid_dump_req.constprop.0.isra.0 (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81b093d0)
Location: net/ipv4/nexthop.c:1993
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff81b093d0-ffffffff81b09564: nh_valid_dump_req.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nh_valid_dump_req(const struct nlmsghdr *nlh, struct nh_dump_filter *filter, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af4d80)
Location: net/ipv4/nexthop.c:3104
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff81af4d80-ffffffff81af4e39: nh_valid_dump_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nh_valid_dump_req(const struct nlmsghdr *nlh, struct nh_dump_filter *filter, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb5600)
Location: net/ipv4/nexthop.c:3133
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff81bb5600-ffffffff81bb56b9: nh_valid_dump_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nh_valid_dump_req(const struct nlmsghdr *nlh, struct nh_dump_filter *filter, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d49170)
Location: net/ipv4/nexthop.c:3133
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff81d49170-ffffffff81d49249: nh_valid_dump_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nh_valid_dump_req(const struct nlmsghdr *nlh, struct nh_dump_filter *filter, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f127a0)
Location: net/ipv4/nexthop.c:3133
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff81f127a0-ffffffff81f12879: nh_valid_dump_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nh_valid_dump_req(const struct nlmsghdr *nlh, struct nh_dump_filter *filter, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f72460)
Location: net/ipv4/nexthop.c:3133
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff81f72460-ffffffff81f72539: nh_valid_dump_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nh_valid_dump_req(const struct nlmsghdr *nlh, struct nh_dump_filter *filter, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff82038600)
Location: net/ipv4/nexthop.c:3156
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
**Symbols:**

```
ffffffff82038600-ffffffff820386d9: nh_valid_dump_req (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffff800010cc4794)
Location: net/ipv4/nexthop.c:1634
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (c0dd01d0)
Location: net/ipv4/nexthop.c:1634
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (c000000000de07c8)
Location: net/ipv4/nexthop.c:1634
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffe000819c18)
Location: net/ipv4/nexthop.c:1634
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffff819aaf50)
Location: net/ipv4/nexthop.c:1634
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffff81964a10)
Location: net/ipv4/nexthop.c:1634
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffff81a157f0)
Location: net/ipv4/nexthop.c:1634
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
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
In net/ipv4/nexthop.c (ffffffff81a20230)
Location: net/ipv4/nexthop.c:1634
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
