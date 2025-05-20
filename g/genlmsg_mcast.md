# Function: <code>genlmsg_mcast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8174fa35)
Location: net/netlink/genetlink.c:1104
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff817bba05)
Location: net/netlink/genetlink.c:1099
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff817eb345)
Location: net/netlink/genetlink.c:1075
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8180b358)
Location: net/netlink/genetlink.c:1078
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8188a2b2)
Location: net/netlink/genetlink.c:1079
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff818dd8f8)
Location: net/netlink/genetlink.c:1081
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8190a2b8)
Location: net/netlink/genetlink.c:1082
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8196b6b9)
Location: net/netlink/genetlink.c:1110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
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
In net/netlink/genetlink.c (ffffffff819a2069)
Location: net/netlink/genetlink.c:1110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int genlmsg_mcast(struct sk_buff *skb, u32 portid, long unsigned int group, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a7ba10)
Location: net/netlink/genetlink.c:1197
Inline: False
```
**Symbols:**

```
ffffffff81a7ba10-ffffffff81a7bb31: genlmsg_mcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genlmsg_mcast(struct sk_buff *skb, u32 portid, long unsigned int group, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a848d0)
Location: net/netlink/genetlink.c:1413
Inline: False
```
**Symbols:**

```
ffffffff81a848d0-ffffffff81a849f1: genlmsg_mcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a6da09)
Location: net/netlink/genetlink.c:1445
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81b27119)
Location: net/netlink/genetlink.c:1437
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81cb005b)
Location: net/netlink/genetlink.c:1441
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81e6ddeb)
Location: net/netlink/genetlink.c:1753
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81ec9f0b)
Location: net/netlink/genetlink.c:1755
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81f8d6de)
Location: net/netlink/genetlink.c:1898
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
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
In net/netlink/genetlink.c (ffff800010c50d20)
Location: net/netlink/genetlink.c:1110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
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
In net/netlink/genetlink.c (c0d609a4)
Location: net/netlink/genetlink.c:1110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
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
In net/netlink/genetlink.c (c000000000d4fa38)
Location: net/netlink/genetlink.c:1110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
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
In net/netlink/genetlink.c (ffffffe0007bc16e)
Location: net/netlink/genetlink.c:1110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
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
In net/netlink/genetlink.c (ffffffff81941ed9)
Location: net/netlink/genetlink.c:1110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
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
In net/netlink/genetlink.c (ffffffff818fb9c9)
Location: net/netlink/genetlink.c:1110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
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
In net/netlink/genetlink.c (ffffffff81993069)
Location: net/netlink/genetlink.c:1110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
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
In net/netlink/genetlink.c (ffffffff819b5b59)
Location: net/netlink/genetlink.c:1110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genlmsg_multicast_allns
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
</ul>
