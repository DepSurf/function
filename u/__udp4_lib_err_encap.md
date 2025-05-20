# Function: <code>__udp4_lib_err_encap</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194da9f)
Location: net/ipv4/udp.c:595
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (ffffffff819b22b9)
Location: net/ipv4/udp.c:582
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (ffffffff819e9059)
Location: net/ipv4/udp.c:582
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__udp4_lib_err_encap(struct net *net, const struct iphdr *iph, struct udphdr *uh, struct udp_table *udptable, struct sk_buff *skb, u32 info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad3b40)
Location: net/ipv4/udp.c:588
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
**Symbols:**

```
ffffffff81ad3b40-ffffffff81ad3c6b: __udp4_lib_err_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__udp4_lib_err_encap(struct net *net, const struct iphdr *iph, struct udphdr *uh, struct udp_table *udptable, struct sk_buff *skb, u32 info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81adfc50)
Location: net/ipv4/udp.c:638
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_err
```
**Symbols:**

```
ffffffff81adfc50-ffffffff81adfd7b: __udp4_lib_err_encap (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff81ace8fe)
Location: net/ipv4/udp.c:644
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (ffffffff81b8d2cb)
Location: net/ipv4/udp.c:645
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (ffffffff81d1e47b)
Location: net/ipv4/udp.c:645
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (ffffffff81ee551b)
Location: net/ipv4/udp.c:653
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (ffffffff81f44cf1)
Location: net/ipv4/udp.c:668
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (ffffffff8200ad43)
Location: net/ipv4/udp.c:638
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (ffff800010c9e9a4)
Location: net/ipv4/udp.c:582
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (c0dabc60)
Location: net/ipv4/udp.c:582
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (c000000000db1140)
Location: net/ipv4/udp.c:582
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (ffffffe0007fb562)
Location: net/ipv4/udp.c:582
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (ffffffff81988ec9)
Location: net/ipv4/udp.c:582
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (ffffffff81942989)
Location: net/ipv4/udp.c:582
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (ffffffff819f3699)
Location: net/ipv4/udp.c:582
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
In net/ipv4/udp.c (ffffffff819fd859)
Location: net/ipv4/udp.c:582
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_err
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
