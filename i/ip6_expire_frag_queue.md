# Function: <code>ip6_expire_frag_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip6_expire_frag_queue(struct net *net, struct frag_queue *fq, struct inet_frags *frags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff817eeaa0)
Location: net/ipv6/reassembly.c:131
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff817eeaa0-ffffffff817eeba5: ip6_expire_frag_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip6_expire_frag_queue(struct net *net, struct frag_queue *fq, struct inet_frags *frags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff8185d350)
Location: net/ipv6/reassembly.c:131
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff8185d350-ffffffff8185d44d: ip6_expire_frag_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip6_expire_frag_queue(struct net *net, struct frag_queue *fq, struct inet_frags *frags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff8188f2c0)
Location: net/ipv6/reassembly.c:131
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff8188f2c0-ffffffff8188f3bd: ip6_expire_frag_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip6_expire_frag_queue(struct net *net, struct frag_queue *fq, struct inet_frags *frags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff818b5840)
Location: net/ipv6/reassembly.c:131
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff818b5840-ffffffff818b5935: ip6_expire_frag_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip6_expire_frag_queue(struct net *net, struct frag_queue *fq, struct inet_frags *frags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff819385b0)
Location: net/ipv6/reassembly.c:131
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff819385b0-ffffffff819386ab: ip6_expire_frag_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip6_expire_frag_queue(struct net *net, struct frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/reassembly.c (ffffffff819904d0)
Location: net/ipv6/reassembly.c:85
Inline: False
Direct callers:
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff819904d0-ffffffff819905ef: ip6_expire_frag_queue (STB_GLOBAL)
```
</details>
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
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct inet_frags *frags</code>
</li>
</ul>
</details>
</li>
</ul>
