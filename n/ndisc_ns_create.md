# Function: <code>ndisc_ns_create</code>

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
struct sk_buff *ndisc_ns_create(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81db3aa0)
Location: net/ipv6/ndisc.c:601
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_ns
```
**Symbols:**

```
ffffffff81db3aa0-ffffffff81db3c45: ndisc_ns_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *ndisc_ns_create(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81f83450)
Location: net/ipv6/ndisc.c:602
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_ns
```
**Symbols:**

```
ffffffff81f83450-ffffffff81f835f5: ndisc_ns_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *ndisc_ns_create(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81fe37a0)
Location: net/ipv6/ndisc.c:603
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_ns
```
**Symbols:**

```
ffffffff81fe37a0-ffffffff81fe3943: ndisc_ns_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *ndisc_ns_create(struct net_device *dev, const struct in6_addr *solicit, const struct in6_addr *saddr, u64 nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff820b16b0)
Location: net/ipv6/ndisc.c:603
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_ns
```
**Symbols:**

```
ffffffff820b16b0-ffffffff820b1853: ndisc_ns_create (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
