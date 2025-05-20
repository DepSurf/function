# Function: <code>nh_valid_get_bucket_req</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nh_valid_get_bucket_req(const struct nlmsghdr *nlh, u32 *id, u16 *bucket_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af5900)
Location: net/ipv4/nexthop.c:3441
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
```
**Symbols:**

```
ffffffff81af5900-ffffffff81af5ab2: nh_valid_get_bucket_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nh_valid_get_bucket_req(const struct nlmsghdr *nlh, u32 *id, u16 *bucket_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb6200)
Location: net/ipv4/nexthop.c:3470
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
```
**Symbols:**

```
ffffffff81bb6200-ffffffff81bb63b2: nh_valid_get_bucket_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nh_valid_get_bucket_req(const struct nlmsghdr *nlh, u32 *id, u16 *bucket_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d49de0)
Location: net/ipv4/nexthop.c:3470
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
```
**Symbols:**

```
ffffffff81d49de0-ffffffff81d49fc2: nh_valid_get_bucket_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nh_valid_get_bucket_req(const struct nlmsghdr *nlh, u32 *id, u16 *bucket_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f13450)
Location: net/ipv4/nexthop.c:3470
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
```
**Symbols:**

```
ffffffff81f13450-ffffffff81f13632: nh_valid_get_bucket_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nh_valid_get_bucket_req(const struct nlmsghdr *nlh, u32 *id, u16 *bucket_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f73120)
Location: net/ipv4/nexthop.c:3456
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
```
**Symbols:**

```
ffffffff81f73120-ffffffff81f73302: nh_valid_get_bucket_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nh_valid_get_bucket_req(const struct nlmsghdr *nlh, u32 *id, u16 *bucket_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff820391e0)
Location: net/ipv4/nexthop.c:3473
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
```
**Symbols:**

```
ffffffff820391e0-ffffffff820393c5: nh_valid_get_bucket_req (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
