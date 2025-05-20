# Function: <code>rtm_dump_nexthop_bucket_nh</code>

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
int rtm_dump_nexthop_bucket_nh(struct sk_buff *skb, struct netlink_callback *cb, struct nexthop *nh, struct rtm_dump_nexthop_bucket_data *dd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af8a10)
Location: net/ipv4/nexthop.c:3309
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81af8a10-ffffffff81af8b49: rtm_dump_nexthop_bucket_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtm_dump_nexthop_bucket_nh(struct sk_buff *skb, struct netlink_callback *cb, struct nexthop *nh, struct rtm_dump_nexthop_bucket_data *dd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb70d0)
Location: net/ipv4/nexthop.c:3338
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
```
**Symbols:**

```
ffffffff81bb70d0-ffffffff81bb7209: rtm_dump_nexthop_bucket_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtm_dump_nexthop_bucket_nh(struct sk_buff *skb, struct netlink_callback *cb, struct nexthop *nh, struct rtm_dump_nexthop_bucket_data *dd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d4ad90)
Location: net/ipv4/nexthop.c:3338
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_cb
```
**Symbols:**

```
ffffffff81d4ad90-ffffffff81d4aee8: rtm_dump_nexthop_bucket_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtm_dump_nexthop_bucket_nh(struct sk_buff *skb, struct netlink_callback *cb, struct nexthop *nh, struct rtm_dump_nexthop_bucket_data *dd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f14480)
Location: net/ipv4/nexthop.c:3338
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_cb
```
**Symbols:**

```
ffffffff81f14480-ffffffff81f145d8: rtm_dump_nexthop_bucket_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtm_dump_nexthop_bucket_nh(struct sk_buff *skb, struct netlink_callback *cb, struct nexthop *nh, struct rtm_dump_nexthop_bucket_data *dd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f74150)
Location: net/ipv4/nexthop.c:3334
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_cb
```
**Symbols:**

```
ffffffff81f74150-ffffffff81f742a5: rtm_dump_nexthop_bucket_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtm_dump_nexthop_bucket_nh(struct sk_buff *skb, struct netlink_callback *cb, struct nexthop *nh, struct rtm_dump_nexthop_bucket_data *dd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff8203a930)
Location: net/ipv4/nexthop.c:3355
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket_cb
```
**Symbols:**

```
ffffffff8203a930-ffffffff8203aa4f: rtm_dump_nexthop_bucket_nh (STB_LOCAL)
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
