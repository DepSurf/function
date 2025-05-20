# Function: <code>l3mdev_l3_rcv</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff817c4a33)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff8183563f)
Location: include/net/l3mdev.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff817f4553)
Location: include/net/l3mdev.h:139
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff8186716f)
Location: include/net/l3mdev.h:139
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81814982)
Location: include/net/l3mdev.h:139
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff8188b8ef)
Location: include/net/l3mdev.h:139
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81893b1b)
Location: include/net/l3mdev.h:139
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff8190cbbf)
Location: include/net/l3mdev.h:139
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff818e7dcb)
Location: include/net/l3mdev.h:139
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81963f85)
Location: include/net/l3mdev.h:139
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81915518)
Location: include/net/l3mdev.h:150
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff819996c4)
Location: include/net/l3mdev.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81977a50)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81a055fd)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819ae3e0)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c1e3)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a97d96)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81b319b1)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81aa1cf9)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81b405b1)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a8d588)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e687)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81b4875d)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81bf49a2)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81cd5b17)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d783)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81e95fa7)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b893)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81ef47ea)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb651)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81fb8775)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff820889da)
Location: include/net/l3mdev.h:165
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffff800010c5e82c)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffff800010cfcf44)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (c0d6dfb0)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (c0e04d48)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (c000000000d61204)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (c000000000e25484)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffe0007c6f10)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffe000847a7c)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff8194e250)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff819db873)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81907d40)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81998633)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819b8a20)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81a462f3)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819c2294)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv6/ip6_input.c (ffffffff81a51ff0)
Location: include/net/l3mdev.h:146
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
</details>
</li>
</ul>

## Differences
