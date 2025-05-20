# Function: <code>udp6_csum_zero_error</code>

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
In net/ipv6/udp.c (0)
Location: net/ipv6/udp.c:773
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void udp6_csum_zero_error(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff8184fef0)
Location: net/ipv6/udp.c:678
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff8184fef0-ffffffff8184ff66: udp6_csum_zero_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void udp6_csum_zero_error(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81881cf0)
Location: net/ipv6/udp.c:664
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff81881cf0-ffffffff81881d66: udp6_csum_zero_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void udp6_csum_zero_error(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff818a84d0)
Location: net/ipv6/udp.c:690
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff818a84d0-ffffffff818a8542: udp6_csum_zero_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void udp6_csum_zero_error(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff8192af80)
Location: net/ipv6/udp.c:693
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
**Symbols:**

```
ffffffff8192af80-ffffffff8192aff2: udp6_csum_zero_error (STB_LOCAL)
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
In net/ipv6/udp.c (ffffffff819863b3)
Location: net/ipv6/udp.c:661
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff819bcca3)
Location: net/ipv6/udp.c:741
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81a2b7f9)
Location: net/ipv6/udp.c:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81a6235c)
Location: net/ipv6/udp.c:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81b5ac61)
Location: net/ipv6/udp.c:731
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81b693f5)
Location: net/ipv6/udp.c:785
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81b576f5)
Location: net/ipv6/udp.c:798
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81c1ed12)
Location: net/ipv6/udp.c:800
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81dbb572)
Location: net/ipv6/udp.c:802
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81f8b6b2)
Location: net/ipv6/udp.c:832
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81febd96)
Location: net/ipv6/udp.c:848
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff820b9bb7)
Location: net/ipv6/udp.c:818
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffff800010d2738c)
Location: net/ipv6/udp.c:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (c0e2c2a8)
Location: net/ipv6/udp.c:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (c000000000e582e0)
Location: net/ipv6/udp.c:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffe000868e82)
Location: net/ipv6/udp.c:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81a019ec)
Location: net/ipv6/udp.c:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff819be7ac)
Location: net/ipv6/udp.c:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81a6c46c)
Location: net/ipv6/udp.c:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
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
In net/ipv6/udp.c (ffffffff81a78a7c)
Location: net/ipv6/udp.c:729
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
