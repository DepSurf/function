# Function: <code>raw_v6_match</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
bool raw_v6_match(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81dbc0f0)
Location: net/ipv6/raw.c:67
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
**Symbols:**

```
ffffffff81dbc0f0-ffffffff81dbc1cd: raw_v6_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool raw_v6_match(struct net *net, struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81f8c310)
Location: net/ipv6/raw.c:67
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
**Symbols:**

```
ffffffff81f8c310-ffffffff81f8c3ed: raw_v6_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool raw_v6_match(struct net *net, const struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81fecae0)
Location: net/ipv6/raw.c:67
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
**Symbols:**

```
ffffffff81fecae0-ffffffff81fecbbd: raw_v6_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool raw_v6_match(struct net *net, const struct sock *sk, short unsigned int num, const struct in6_addr *loc_addr, const struct in6_addr *rmt_addr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff820ba6e0)
Location: net/ipv6/raw.c:67
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:ipv6_raw_deliver
```
**Symbols:**

```
ffffffff820ba6e0-ffffffff820ba7bd: raw_v6_match (STB_GLOBAL)
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
