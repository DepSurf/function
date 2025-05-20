# Function: <code>inet6_rtm_valid_getroute_req</code>

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
In net/ipv6/route.c (ffffffff81a1519f)
Location: net/ipv6/route.c:5688
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/ipv6/route.c (ffffffff81a4bd6f)
Location: net/ipv6/route.c:5702
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet6_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b412c0)
Location: net/ipv6/route.c:5790
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81b412c0-ffffffff81b41489: inet6_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet6_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4fd80)
Location: net/ipv6/route.c:5779
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81b4fd80-ffffffff81b4ff49: inet6_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet6_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3e3a0)
Location: net/ipv6/route.c:5798
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81b3e3a0-ffffffff81b3e58e: inet6_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet6_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c04c80)
Location: net/ipv6/route.c:5957
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81c04c80-ffffffff81c04e6e: inet6_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet6_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9e9b0)
Location: net/ipv6/route.c:5950
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81d9e9b0-ffffffff81d9ebd5: inet6_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet6_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6d970)
Location: net/ipv6/route.c:5951
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81f6d970-ffffffff81f6db95: inet6_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet6_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcda40)
Location: net/ipv6/route.c:5949
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81fcda40-ffffffff81fcdc46: inet6_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet6_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209b290)
Location: net/ipv6/route.c:5942
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff8209b290-ffffffff8209b496: inet6_rtm_valid_getroute_req (STB_LOCAL)
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
In net/ipv6/route.c (ffff800010d11300)
Location: net/ipv6/route.c:5702
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/ipv6/route.c (c0e1565c)
Location: net/ipv6/route.c:5702
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/ipv6/route.c (c000000000e3a6a4)
Location: net/ipv6/route.c:5702
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/ipv6/route.c (ffffffe000855fac)
Location: net/ipv6/route.c:5702
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/ipv6/route.c (ffffffff819eb3ff)
Location: net/ipv6/route.c:5702
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/ipv6/route.c (ffffffff819a81bf)
Location: net/ipv6/route.c:5702
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/ipv6/route.c (ffffffff81a55e7f)
Location: net/ipv6/route.c:5702
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/ipv6/route.c (ffffffff81a61eaf)
Location: net/ipv6/route.c:5702
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
