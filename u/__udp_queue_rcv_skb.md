# Function: <code>__udp_queue_rcv_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81786f20)
Location: net/ipv4/udp.c:1463
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
**Symbols:**

```
ffffffff81786f20-ffffffff8178704d: __udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f41f0)
Location: net/ipv4/udp.c:1454
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
**Symbols:**

```
ffffffff817f41f0-ffffffff817f4326: __udp_queue_rcv_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81827cf0)
Location: net/ipv4/udp.c:1626
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
**Symbols:**

```
ffffffff81827cf0-ffffffff81827e3e: __udp_queue_rcv_skb (STB_GLOBAL)
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
In net/ipv4/udp.c (ffffffff81848982)
Location: net/ipv4/udp.c:1777
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
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
In net/ipv4/udp.c (ffffffff818c83aa)
Location: net/ipv4/udp.c:1784
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
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
In net/ipv4/udp.c (ffffffff8191e28e)
Location: net/ipv4/udp.c:1867
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
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
In net/ipv4/udp.c (ffffffff8194cee0)
Location: net/ipv4/udp.c:1939
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffffffff819b1698)
Location: net/ipv4/udp.c:1925
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffffffff819e83fc)
Location: net/ipv4/udp.c:1961
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffffffff81ad6341)
Location: net/ipv4/udp.c:1970
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __udp_queue_rcv_skb(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ae2680)
Location: net/ipv4/udp.c:2020
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
**Symbols:**

```
ffffffff81ae2680-ffffffff81ae27f3: __udp_queue_rcv_skb (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff81acd848)
Location: net/ipv4/udp.c:2069
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffffffff81b8c225)
Location: net/ipv4/udp.c:2081
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffffffff81d1c81c)
Location: net/ipv4/udp.c:2080
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffffffff81ee3825)
Location: net/ipv4/udp.c:2082
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffffffff81f43096)
Location: net/ipv4/udp.c:2054
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffffffff82008fff)
Location: net/ipv4/udp.c:2025
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffff800010c9d844)
Location: net/ipv4/udp.c:1961
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (c0dab170)
Location: net/ipv4/udp.c:1961
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (c000000000daf114)
Location: net/ipv4/udp.c:1961
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffffffe0007fa842)
Location: net/ipv4/udp.c:1961
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffffffff8198826c)
Location: net/ipv4/udp.c:1961
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffffffff81941d2c)
Location: net/ipv4/udp.c:1961
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffffffff819f2a3c)
Location: net/ipv4/udp.c:1961
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
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
In net/ipv4/udp.c (ffffffff819fcf3c)
Location: net/ipv4/udp.c:1961
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
