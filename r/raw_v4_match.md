# Function: <code>raw_v4_match</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool raw_v4_match(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81d17891)
Location: net/ipv4/raw.c:119
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_v4_input
```
**Symbols:**

```
ffffffff81d163b0-ffffffff81d1644f: raw_v4_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool raw_v4_match(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81ede151)
Location: net/ipv4/raw.c:119
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_v4_input
```
**Symbols:**

```
ffffffff81edc690-ffffffff81edc72f: raw_v4_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool raw_v4_match(struct net *net, const struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81f3d46c)
Location: net/ipv4/raw.c:119
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_v4_input
```
**Symbols:**

```
ffffffff81f3b7f0-ffffffff81f3b88f: raw_v4_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool raw_v4_match(struct net *net, const struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff820035cc)
Location: net/ipv4/raw.c:119
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_v4_input
```
**Symbols:**

```
ffffffff82001910-ffffffff820019af: raw_v4_match (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sock *sk</code> ➡️ <code>const struct sock *sk</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
