# Function: <code>__call_nexthop_res_bucket_notifiers</code>

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
int __call_nexthop_res_bucket_notifiers(struct net *net, u32 nhg_id, u16 bucket_index, bool force, struct nh_info *oldi, struct nh_info *newi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af6620)
Location: net/ipv4/nexthop.c:324
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
**Symbols:**

```
ffffffff81af6620-ffffffff81af687d: __call_nexthop_res_bucket_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __call_nexthop_res_bucket_notifiers(struct net *net, u32 nhg_id, u16 bucket_index, bool force, struct nh_info *oldi, struct nh_info *newi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb56c0)
Location: net/ipv4/nexthop.c:324
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
**Symbols:**

```
ffffffff81bb56c0-ffffffff81bb5847: __call_nexthop_res_bucket_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __call_nexthop_res_bucket_notifiers(struct net *net, u32 nhg_id, u16 bucket_index, bool force, struct nh_info *oldi, struct nh_info *newi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d49a30)
Location: net/ipv4/nexthop.c:325
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
**Symbols:**

```
ffffffff81d49a30-ffffffff81d49bd0: __call_nexthop_res_bucket_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __call_nexthop_res_bucket_notifiers(struct net *net, u32 nhg_id, u16 bucket_index, bool force, struct nh_info *oldi, struct nh_info *newi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f13080)
Location: net/ipv4/nexthop.c:325
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
**Symbols:**

```
ffffffff81f13080-ffffffff81f13220: __call_nexthop_res_bucket_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __call_nexthop_res_bucket_notifiers(struct net *net, u32 nhg_id, u16 bucket_index, bool force, struct nh_info *oldi, struct nh_info *newi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f72d50)
Location: net/ipv4/nexthop.c:325
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
**Symbols:**

```
ffffffff81f72d50-ffffffff81f72ef0: __call_nexthop_res_bucket_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __call_nexthop_res_bucket_notifiers(struct net *net, u32 nhg_id, u16 bucket_index, bool force, struct nh_info *oldi, struct nh_info *newi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff82039ac0)
Location: net/ipv4/nexthop.c:325
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:replace_nexthop_single_notify
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
**Symbols:**

```
ffffffff82039ac0-ffffffff82039c8f: __call_nexthop_res_bucket_notifiers (STB_LOCAL)
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
