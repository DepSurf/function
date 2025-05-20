# Function: <code>netlink_getsockbyportid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *netlink_getsockbyportid(struct sock *ssk, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174bf20)
Location: net/netlink/af_netlink.c:1653
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_alloc_skb
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff8174bf20-ffffffff8174bf8d: netlink_getsockbyportid (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffffffff817ba704)
Location: net/netlink/af_netlink.c:1044
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff817ea0a4)
Location: net/netlink/af_netlink.c:1061
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff81809d74)
Location: net/netlink/af_netlink.c:1095
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff81888cd4)
Location: net/netlink/af_netlink.c:1108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff818dc724)
Location: net/netlink/af_netlink.c:1147
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff81909104)
Location: net/netlink/af_netlink.c:1140
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff8196a45c)
Location: net/netlink/af_netlink.c:1132
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff819a0ecc)
Location: net/netlink/af_netlink.c:1133
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7a6df)
Location: net/netlink/af_netlink.c:1133
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a8354f)
Location: net/netlink/af_netlink.c:1134
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff81a6c61f)
Location: net/netlink/af_netlink.c:1144
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff81b25c6f)
Location: net/netlink/af_netlink.c:1149
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff81cae85d)
Location: net/netlink/af_netlink.c:1149
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff81e6be9d)
Location: net/netlink/af_netlink.c:1168
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff81ec7efd)
Location: net/netlink/af_netlink.c:1168
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff81f8b30e)
Location: net/netlink/af_netlink.c:1171
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffff800010c4f5d0)
Location: net/netlink/af_netlink.c:1133
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (c0d5f73c)
Location: net/netlink/af_netlink.c:1133
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (c000000000d4de60)
Location: net/netlink/af_netlink.c:1133
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffe0007bb1e8)
Location: net/netlink/af_netlink.c:1133
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff81940d3c)
Location: net/netlink/af_netlink.c:1133
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff818fa82c)
Location: net/netlink/af_netlink.c:1133
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff81991ecc)
Location: net/netlink/af_netlink.c:1133
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
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
In net/netlink/af_netlink.c (ffffffff819b49bc)
Location: net/netlink/af_netlink.c:1133
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
