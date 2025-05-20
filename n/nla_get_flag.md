# Function: <code>nla_get_flag</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1352
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1610
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81986cd3)
Location: include/net/netlink.h:1610
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1610
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a52c40)
Location: include/net/netlink.h:1677
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:1677
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1677
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a59260)
Location: include/net/netlink.h:1690
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:1690
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1690
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3c1c0)
Location: include/net/netlink.h:1690
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af3b17)
Location: include/net/netlink.h:1690
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1690
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af2b60)
Location: include/net/netlink.h:1690
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb4037)
Location: include/net/netlink.h:1690
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1690
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c76b4f)
Location: include/net/netlink.h:1690
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d47927)
Location: include/net/netlink.h:1690
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1690
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2f36b)
Location: include/net/netlink.h:1739
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f10df7)
Location: include/net/netlink.h:1739
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1739
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f70ba7)
Location: include/net/netlink.h:1740
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
```
```
In net/devlink/leftover.c (ffffffff8203128b)
Location: include/net/netlink.h:1740
Inline: True
```
```
In net/devlink/dev.c (0)
Location: include/net/netlink.h:1740
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1740
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff82037307)
Location: include/net/netlink.h:1838
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:__nh_valid_dump_req
  - net/ipv4/nexthop.c:__nh_valid_dump_req
```
```
In net/devlink/dev.c (0)
Location: include/net/netlink.h:1838
Inline: True
```
```
In net/devlink/param.c (ffffffff8210da6e)
Location: include/net/netlink.h:1838
Inline: True
```
```
In net/devlink/region.c (0)
Location: include/net/netlink.h:1838
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1838
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2f158)
Location: include/net/netlink.h:1610
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1610
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d4639c)
Location: include/net/netlink.h:1610
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1610
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d27348)
Location: include/net/netlink.h:1610
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1610
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a58b0)
Location: include/net/netlink.h:1610
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1610
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81926b43)
Location: include/net/netlink.h:1610
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1610
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e08f3)
Location: include/net/netlink.h:1610
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1610
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81977cd3)
Location: include/net/netlink.h:1610
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1610
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199a1c3)
Location: include/net/netlink.h:1610
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_nl_cmd_param_set_doit
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/net/netlink.h:1610
Inline: True
```
</details>
</li>
</ul>

## Differences
