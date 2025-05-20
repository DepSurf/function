# Function: <code>inet_rtm_getroute_build_skb</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e6afe)
Location: net/ipv4/route.c:2711
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffffffff819139c4)
Location: net/ipv4/route.c:2713
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffffffff8197607b)
Location: net/ipv4/route.c:2936
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
In net/ipv4/route.c (ffffffff819aca8b)
Location: net/ipv4/route.c:2947
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
struct sk_buff *inet_rtm_getroute_build_skb(__be32 src, __be32 dst, u8 ip_proto, __be16 sport, __be16 dport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a922d0)
Location: net/ipv4/route.c:3034
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81a922d0-ffffffff81a9245c: inet_rtm_getroute_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *inet_rtm_getroute_build_skb(__be32 src, __be32 dst, u8 ip_proto, __be16 sport, __be16 dport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9c170)
Location: net/ipv4/route.c:3016
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81a9c170-ffffffff81a9c2fc: inet_rtm_getroute_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *inet_rtm_getroute_build_skb(__be32 src, __be32 dst, u8 ip_proto, __be16 sport, __be16 dport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a87160)
Location: net/ipv4/route.c:3017
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81a87160-ffffffff81a872eb: inet_rtm_getroute_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *inet_rtm_getroute_build_skb(__be32 src, __be32 dst, u8 ip_proto, __be16 sport, __be16 dport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b41920)
Location: net/ipv4/route.c:3135
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81b41920-ffffffff81b41aab: inet_rtm_getroute_build_skb (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81cd33a4)
Location: net/ipv4/route.c:3159
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffffffff81e93594)
Location: net/ipv4/route.c:3150
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffffffff81ef1d34)
Location: net/ipv4/route.c:3146
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffffffff81fb5e84)
Location: net/ipv4/route.c:3101
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
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
In net/ipv4/route.c (ffff800010c5cbd4)
Location: net/ipv4/route.c:2947
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
In net/ipv4/route.c (c0d6c32c)
Location: net/ipv4/route.c:2947
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
In net/ipv4/route.c (c000000000d5f1a4)
Location: net/ipv4/route.c:2947
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
In net/ipv4/route.c (ffffffe0007c59fc)
Location: net/ipv4/route.c:2947
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
In net/ipv4/route.c (ffffffff8194c8fb)
Location: net/ipv4/route.c:2947
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
In net/ipv4/route.c (ffffffff819063eb)
Location: net/ipv4/route.c:2947
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
In net/ipv4/route.c (ffffffff819b70cb)
Location: net/ipv4/route.c:2947
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
In net/ipv4/route.c (ffffffff819c094b)
Location: net/ipv4/route.c:2947
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
</ul>
