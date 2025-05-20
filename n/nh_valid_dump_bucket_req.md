# Function: <code>nh_valid_dump_bucket_req</code>

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
int nh_valid_dump_bucket_req(const struct nlmsghdr *nlh, struct nh_dump_filter *filter, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af4f50)
Location: net/ipv4/nexthop.c:3251
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81af4f50-ffffffff81af510d: nh_valid_dump_bucket_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nh_valid_dump_bucket_req(const struct nlmsghdr *nlh, struct nh_dump_filter *filter, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb5850)
Location: net/ipv4/nexthop.c:3280
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81bb5850-ffffffff81bb5a0d: nh_valid_dump_bucket_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nh_valid_dump_bucket_req(const struct nlmsghdr *nlh, struct nh_dump_filter *filter, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d49bd0)
Location: net/ipv4/nexthop.c:3280
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81d49bd0-ffffffff81d49dd1: nh_valid_dump_bucket_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nh_valid_dump_bucket_req(const struct nlmsghdr *nlh, struct nh_dump_filter *filter, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f13230)
Location: net/ipv4/nexthop.c:3280
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81f13230-ffffffff81f13431: nh_valid_dump_bucket_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nh_valid_dump_bucket_req(const struct nlmsghdr *nlh, struct nh_dump_filter *filter, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f72f00)
Location: net/ipv4/nexthop.c:3276
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81f72f00-ffffffff81f73101: nh_valid_dump_bucket_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nh_valid_dump_bucket_req(const struct nlmsghdr *nlh, struct nh_dump_filter *filter, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff82038f00)
Location: net/ipv4/nexthop.c:3298
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff82038f00-ffffffff82039104: nh_valid_dump_bucket_req (STB_LOCAL)
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
