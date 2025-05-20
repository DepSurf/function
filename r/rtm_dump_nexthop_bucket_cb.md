# Function: <code>rtm_dump_nexthop_bucket_cb</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af8bfe)
Location: net/ipv4/nexthop.c:3362
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int rtm_dump_nexthop_bucket_cb(struct sk_buff *skb, struct netlink_callback *cb, struct nexthop *nh, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb723a)
Location: net/ipv4/nexthop.c:3391
Inline: True
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81bb7210-ffffffff81bb7276: rtm_dump_nexthop_bucket_cb (STB_LOCAL)
ffffffff81d3e1f8-ffffffff81d3e240: rtm_dump_nexthop_bucket_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rtm_dump_nexthop_bucket_cb(struct sk_buff *skb, struct netlink_callback *cb, struct nexthop *nh, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3391
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81d4aef0-ffffffff81d4af6e: rtm_dump_nexthop_bucket_cb (STB_LOCAL)
ffffffff81f0aad6-ffffffff81f0ab1e: rtm_dump_nexthop_bucket_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rtm_dump_nexthop_bucket_cb(struct sk_buff *skb, struct netlink_callback *cb, struct nexthop *nh, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3391
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81f145f0-ffffffff81f1466e: rtm_dump_nexthop_bucket_cb (STB_LOCAL)
ffffffff820b238b-ffffffff820b23d3: rtm_dump_nexthop_bucket_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rtm_dump_nexthop_bucket_cb(struct sk_buff *skb, struct netlink_callback *cb, struct nexthop *nh, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3381
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81f742c0-ffffffff81f7433e: rtm_dump_nexthop_bucket_cb (STB_LOCAL)
ffffffff8213353b-ffffffff82133583: rtm_dump_nexthop_bucket_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rtm_dump_nexthop_bucket_cb(struct sk_buff *skb, struct netlink_callback *cb, struct nexthop *nh, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3398
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff8203aa60-ffffffff8203aade: rtm_dump_nexthop_bucket_cb (STB_LOCAL)
ffffffff82214f47-ffffffff82214f8f: rtm_dump_nexthop_bucket_cb.cold (STB_LOCAL)
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
