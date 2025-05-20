# Function: <code>inet_rtm_valid_getroute_req</code>

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
In net/ipv4/route.c (ffffffff81975e50)
Location: net/ipv4/route.c:2997
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffffffff819ac860)
Location: net/ipv4/route.c:3008
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a91ba0)
Location: net/ipv4/route.c:3095
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81a91ba0-ffffffff81a91d69: inet_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9ba30)
Location: net/ipv4/route.c:3077
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81a9ba30-ffffffff81a9bbf9: inet_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a86f70)
Location: net/ipv4/route.c:3078
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81a86f70-ffffffff81a8715e: inet_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b41730)
Location: net/ipv4/route.c:3196
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81b41730-ffffffff81b4191e: inet_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cce1a0)
Location: net/ipv4/route.c:3220
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81cce1a0-ffffffff81cce3c5: inet_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e8e170)
Location: net/ipv4/route.c:3211
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81e8e170-ffffffff81e8e395: inet_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eec8b0)
Location: net/ipv4/route.c:3207
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81eec8b0-ffffffff81eecab6: inet_rtm_valid_getroute_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_rtm_valid_getroute_req(struct sk_buff *skb, const struct nlmsghdr *nlh, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb0910)
Location: net/ipv4/route.c:3162
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81fb0910-ffffffff81fb0b16: inet_rtm_valid_getroute_req (STB_LOCAL)
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
In net/ipv4/route.c (ffff800010c5c9f0)
Location: net/ipv4/route.c:3008
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (c0d6c0b8)
Location: net/ipv4/route.c:3008
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (c000000000d5ef10)
Location: net/ipv4/route.c:3008
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffffffe0007c5834)
Location: net/ipv4/route.c:3008
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffffffff8194c6d0)
Location: net/ipv4/route.c:3008
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffffffff819061c0)
Location: net/ipv4/route.c:3008
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffffffff819b6ea0)
Location: net/ipv4/route.c:3008
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffffffff819c0720)
Location: net/ipv4/route.c:3008
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
