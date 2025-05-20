# Function: <code>rtnl_stats_get_parse</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtnl_stats_get_parse(const struct nlmsghdr *nlh, u32 filter_mask, struct rtnl_stats_dump_filters *filters, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2cf30)
Location: net/core/rtnetlink.c:5702
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81c2cf30-ffffffff81c2d143: rtnl_stats_get_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtnl_stats_get_parse(const struct nlmsghdr *nlh, u32 filter_mask, struct rtnl_stats_dump_filters *filters, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de0090)
Location: net/core/rtnetlink.c:5753
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81de0090-ffffffff81de02a3: rtnl_stats_get_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtnl_stats_get_parse(const struct nlmsghdr *nlh, u32 filter_mask, struct rtnl_stats_dump_filters *filters, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e51760)
Location: net/core/rtnetlink.c:5846
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81e51760-ffffffff81e51996: rtnl_stats_get_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtnl_stats_get_parse(const struct nlmsghdr *nlh, u32 filter_mask, struct rtnl_stats_dump_filters *filters, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f108d0)
Location: net/core/rtnetlink.c:5876
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_stats_get
```
**Symbols:**

```
ffffffff81f108d0-ffffffff81f10b09: rtnl_stats_get_parse (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
