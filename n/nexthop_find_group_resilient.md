# Function: <code>nexthop_find_group_resilient</code>

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
struct nexthop *nexthop_find_group_resilient(struct net *net, u32 id, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af3bc0)
Location: net/ipv4/nexthop.c:3208
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81af3bc0-ffffffff81af3c76: nexthop_find_group_resilient (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_find_group_resilient(struct net *net, u32 id, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3237
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81bb4360-ffffffff81bb444b: nexthop_find_group_resilient (STB_LOCAL)
ffffffff81d3dc58-ffffffff81d3dc92: nexthop_find_group_resilient.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_find_group_resilient(struct net *net, u32 id, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3237
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81d47d90-ffffffff81d47e89: nexthop_find_group_resilient (STB_LOCAL)
ffffffff81f0a528-ffffffff81f0a562: nexthop_find_group_resilient.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_find_group_resilient(struct net *net, u32 id, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3237
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81f112c0-ffffffff81f113b9: nexthop_find_group_resilient (STB_LOCAL)
ffffffff820b1ddd-ffffffff820b1e17: nexthop_find_group_resilient.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_find_group_resilient(struct net *net, u32 id, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3233
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81f710e0-ffffffff81f711de: nexthop_find_group_resilient (STB_LOCAL)
ffffffff82133014-ffffffff8213304e: nexthop_find_group_resilient.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct nexthop *nexthop_find_group_resilient(struct net *net, u32 id, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3255
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff82037840-ffffffff8203793e: nexthop_find_group_resilient (STB_LOCAL)
ffffffff822149c3-ffffffff822149fd: nexthop_find_group_resilient.cold (STB_LOCAL)
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
