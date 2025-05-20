# Function: <code>rtm_get_nexthop_bucket</code>

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
int rtm_get_nexthop_bucket(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af88a0)
Location: net/ipv4/nexthop.c:3472
Inline: False
```
**Symbols:**

```
ffffffff81af88a0-ffffffff81af8a09: rtm_get_nexthop_bucket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtm_get_nexthop_bucket(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb73d0)
Location: net/ipv4/nexthop.c:3501
Inline: False
```
**Symbols:**

```
ffffffff81bb73d0-ffffffff81bb7539: rtm_get_nexthop_bucket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtm_get_nexthop_bucket(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d4b0e0)
Location: net/ipv4/nexthop.c:3501
Inline: False
```
**Symbols:**

```
ffffffff81d4b0e0-ffffffff81d4b269: rtm_get_nexthop_bucket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtm_get_nexthop_bucket(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f14800)
Location: net/ipv4/nexthop.c:3501
Inline: False
```
**Symbols:**

```
ffffffff81f14800-ffffffff81f14989: rtm_get_nexthop_bucket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtm_get_nexthop_bucket(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f744d0)
Location: net/ipv4/nexthop.c:3487
Inline: False
```
**Symbols:**

```
ffffffff81f744d0-ffffffff81f74659: rtm_get_nexthop_bucket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtm_get_nexthop_bucket(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff8203ac70)
Location: net/ipv4/nexthop.c:3504
Inline: False
```
**Symbols:**

```
ffffffff8203ac70-ffffffff8203adf9: rtm_get_nexthop_bucket (STB_LOCAL)
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
