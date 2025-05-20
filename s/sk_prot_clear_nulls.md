# Function: <code>sk_prot_clear_nulls</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81700b6c)
Location: include/net/sock.h:946
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f03d9)
Location: include/net/sock.h:946
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_clear_sk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81767533)
Location: include/net/sock.h:959
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f229)
Location: include/net/sock.h:959
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_clear_sk
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
In net/core/sock.c (ffffffff8179452d)
Location: include/net/sock.h:995
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff817b292d)
Location: include/net/sock.h:1013
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff8182ab3d)
Location: include/net/sock.h:1013
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff81874c59)
Location: include/net/sock.h:1020
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff8189551b)
Location: include/net/sock.h:1048
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff818e0977)
Location: include/net/sock.h:1051
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff81912bb7)
Location: include/net/sock.h:1061
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff819e3b97)
Location: include/net/sock.h:1107
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff819e353f)
Location: include/net/sock.h:1122
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff819c9542)
Location: include/net/sock.h:1127
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff81a788c2)
Location: include/net/sock.h:1139
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff81bec2f7)
Location: include/net/sock.h:1185
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff81d98d57)
Location: include/net/sock.h:1223
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff81e070d7)
Location: include/net/sock.h:1235
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff81ec3947)
Location: include/net/sock.h:1210
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffff800010baa324)
Location: include/net/sock.h:1061
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (c0cc8e20)
Location: include/net/sock.h:1061
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (c000000000c804e4)
Location: include/net/sock.h:1061
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffe00073dca4)
Location: include/net/sock.h:1061
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff818b2bb7)
Location: include/net/sock.h:1061
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff8186cb07)
Location: include/net/sock.h:1061
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff81903bb7)
Location: include/net/sock.h:1061
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
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
In net/core/sock.c (ffffffff81924bb7)
Location: include/net/sock.h:1061
Inline: True
Inline callers:
  - net/core/sock.c:sk_prot_alloc
```
</details>
</li>
</ul>

## Differences
