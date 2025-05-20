# Function: <code>ipmr_rtm_valid_getroute_req</code>

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
In net/ipv4/ipmr.c (ffffffff819db516)
Location: net/ipv4/ipmr.c:2482
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
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
In net/ipv4/ipmr.c (ffffffff81a123e6)
Location: net/ipv4/ipmr.c:2483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipmr_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b01350)
Location: net/ipv4/ipmr.c:2451
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
**Symbols:**

```
ffffffff81b01350-ffffffff81b014fa: ipmr_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipmr_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b0f430)
Location: net/ipv4/ipmr.c:2460
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
**Symbols:**

```
ffffffff81b0f430-ffffffff81b0f5da: ipmr_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipmr_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81afd130)
Location: net/ipv4/ipmr.c:2460
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
**Symbols:**

```
ffffffff81afd130-ffffffff81afd303: ipmr_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipmr_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81bbe920)
Location: net/ipv4/ipmr.c:2462
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
**Symbols:**

```
ffffffff81bbe920-ffffffff81bbeaf3: ipmr_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipmr_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81d52d30)
Location: net/ipv4/ipmr.c:2456
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
**Symbols:**

```
ffffffff81d52d30-ffffffff81d52f39: ipmr_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipmr_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f1d6c0)
Location: net/ipv4/ipmr.c:2463
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
**Symbols:**

```
ffffffff81f1d6c0-ffffffff81f1d8c9: ipmr_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipmr_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f7d1c0)
Location: net/ipv4/ipmr.c:2478
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
**Symbols:**

```
ffffffff81f7d1c0-ffffffff81f7d3be: ipmr_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipmr_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff820438c0)
Location: net/ipv4/ipmr.c:2476
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
**Symbols:**

```
ffffffff820438c0-ffffffff82043abe: ipmr_rtm_valid_getroute_req (STB_LOCAL)
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
In net/ipv4/ipmr.c (ffff800010ccb0cc)
Location: net/ipv4/ipmr.c:2483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
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
In net/ipv4/ipmr.c (c0dd6a08)
Location: net/ipv4/ipmr.c:2483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
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
In net/ipv4/ipmr.c (c000000000dec200)
Location: net/ipv4/ipmr.c:2483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
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
In net/ipv4/ipmr.c (ffffffe0008212de)
Location: net/ipv4/ipmr.c:2483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
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
In net/ipv4/ipmr.c (ffffffff819b1d06)
Location: net/ipv4/ipmr.c:2483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
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
In net/ipv4/ipmr.c (ffffffff8196e336)
Location: net/ipv4/ipmr.c:2483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
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
In net/ipv4/ipmr.c (ffffffff81a1c5a6)
Location: net/ipv4/ipmr.c:2483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
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
In net/ipv4/ipmr.c (ffffffff81a274f6)
Location: net/ipv4/ipmr.c:2483
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
