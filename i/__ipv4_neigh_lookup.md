# Function: <code>__ipv4_neigh_lookup</code>

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
In net/ipv4/route.c (ffffffff817542ba)
Location: include/net/arp.h:25
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
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
In net/ipv4/route.c (ffffffff817c0384)
Location: include/net/arp.h:25
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
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
In net/ipv4/route.c (ffffffff817f0224)
Location: include/net/arp.h:25
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
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
In net/ipv4/route.c (ffffffff818102ba)
Location: include/net/arp.h:25
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct neighbour *__ipv4_neigh_lookup(struct net_device *dev, u32 key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81890169)
Location: include/net/arp.h:29
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
Direct callers:
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff8188ed90-ffffffff8188ee5f: __ipv4_neigh_lookup (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff818e36ef)
Location: include/net/arp.h:29
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
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
In net/ipv4/route.c (ffffffff8191059f)
Location: include/net/arp.h:29
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
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
In net/ipv4/route.c (ffffffff81973003)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffff819a9976)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffff81a92da9)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffff81a9cc5a)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffff81a87d1f)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffff81b42250)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffff81ccec58)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffff81e8eec3)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffff81eed5d2)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffff81fb1642)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffff800010c5954c)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (c0d69100)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (c000000000d5b2f0)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffe0007c31f8)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffff819497e6)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffff819032d6)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffff819b3fb6)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/ipv4/route.c (ffffffff819bd6a6)
Location: include/net/arp.h:37
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
