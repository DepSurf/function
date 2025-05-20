# Function: <code>inet6_hash_frag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int inet6_hash_frag(__be32 id, const struct in6_addr *saddr, const struct in6_addr *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff817ed9e0)
Location: net/ipv6/reassembly.c:86
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ip6_hashfn
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff817ed9e0-ffffffff817edae4: inet6_hash_frag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int inet6_hash_frag(__be32 id, const struct in6_addr *saddr, const struct in6_addr *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff8185c220)
Location: net/ipv6/reassembly.c:86
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_hashfn
```
**Symbols:**

```
ffffffff8185c220-ffffffff8185c326: inet6_hash_frag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int inet6_hash_frag(__be32 id, const struct in6_addr *saddr, const struct in6_addr *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff8188e130)
Location: net/ipv6/reassembly.c:86
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_hashfn
```
**Symbols:**

```
ffffffff8188e130-ffffffff8188e236: inet6_hash_frag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int inet6_hash_frag(__be32 id, const struct in6_addr *saddr, const struct in6_addr *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff818b47d0)
Location: net/ipv6/reassembly.c:86
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_hashfn
```
**Symbols:**

```
ffffffff818b47d0-ffffffff818b48d6: inet6_hash_frag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int inet6_hash_frag(__be32 id, const struct in6_addr *saddr, const struct in6_addr *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff81937540)
Location: net/ipv6/reassembly.c:86
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_hashfn
```
**Symbols:**

```
ffffffff81937540-ffffffff81937646: inet6_hash_frag (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
