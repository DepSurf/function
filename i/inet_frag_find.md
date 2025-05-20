# Function: <code>inet_frag_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inet_frag_queue *inet_frag_find(struct netns_frags *nf, struct inet_frags *f, void *key, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff817a1ee0)
Location: net/ipv4/inet_fragment.c:399
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff817a1ee0-ffffffff817a21a1: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inet_frag_queue *inet_frag_find(struct netns_frags *nf, struct inet_frags *f, void *key, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff8180fba0)
Location: net/ipv4/inet_fragment.c:391
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff8180fba0-ffffffff8180fe5b: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inet_frag_queue *inet_frag_find(struct netns_frags *nf, struct inet_frags *f, void *key, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff818410f0)
Location: net/ipv4/inet_fragment.c:391
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff818410f0-ffffffff818413ab: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inet_frag_queue *inet_frag_find(struct netns_frags *nf, struct inet_frags *f, void *key, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81862970)
Location: net/ipv4/inet_fragment.c:389
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81862970-ffffffff81862c12: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inet_frag_queue *inet_frag_find(struct netns_frags *nf, struct inet_frags *f, void *key, unsigned int hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff818e2aa0)
Location: net/ipv4/inet_fragment.c:392
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff818e2aa0-ffffffff818e2d46: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct netns_frags *nf, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81939290)
Location: net/ipv4/inet_fragment.c:200
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81939290-ffffffff819396a4: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct netns_frags *nf, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81968e50)
Location: net/ipv4/inet_fragment.c:206
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81968e50-ffffffff81969340: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819cfd30)
Location: net/ipv4/inet_fragment.c:322
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff819cfd30-ffffffff819cff4f: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a068c0)
Location: net/ipv4/inet_fragment.c:322
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81a068c0-ffffffff81a06adf: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81af6300)
Location: net/ipv4/inet_fragment.c:322
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81af6300-ffffffff81af650e: inet_frag_find.part.0 (STB_LOCAL)
ffffffff81af6510-ffffffff81af653a: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81b03170)
Location: net/ipv4/inet_fragment.c:353
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81b03170-ffffffff81b0338b: inet_frag_find.part.0 (STB_LOCAL)
ffffffff81b03390-ffffffff81b033ba: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81aee920)
Location: net/ipv4/inet_fragment.c:353
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81aee920-ffffffff81aeebe3: inet_frag_find.part.0 (STB_LOCAL)
ffffffff81aeebf0-ffffffff81aeec1a: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81baecf0)
Location: net/ipv4/inet_fragment.c:353
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81baecf0-ffffffff81baefb3: inet_frag_find.part.0 (STB_LOCAL)
ffffffff81baefc0-ffffffff81baefea: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81d42020)
Location: net/ipv4/inet_fragment.c:353
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81d42020-ffffffff81d4231b: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81f0ae60)
Location: net/ipv4/inet_fragment.c:359
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81f0ae60-ffffffff81f0b15b: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81f6a9a0)
Location: net/ipv4/inet_fragment.c:359
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81f6a9a0-ffffffff81f6ad07: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff82031050)
Location: net/ipv4/inet_fragment.c:359
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff82031050-ffffffff820313b7: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffff800010cbf750)
Location: net/ipv4/inet_fragment.c:322
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffff800010cbf750-ffff800010cbf924: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c0dcb110)
Location: net/ipv4/inet_fragment.c:322
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
c0dcb110-c0dcb2f8: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c000000000dda4c0)
Location: net/ipv4/inet_fragment.c:322
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
c000000000dda4c0-c000000000dda7b4: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffe000815452)
Location: net/ipv4/inet_fragment.c:322
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffe000815452-ffffffe0008155cc: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819a6660)
Location: net/ipv4/inet_fragment.c:322
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff819a6660-ffffffff819a687f: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81960120)
Location: net/ipv4/inet_fragment.c:322
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81960120-ffffffff8196033f: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a10f00)
Location: net/ipv4/inet_fragment.c:322
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
```
**Symbols:**

```
ffffffff81a10f00-ffffffff81a1111f: inet_frag_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct inet_frag_queue *inet_frag_find(struct fqdir *fqdir, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a1b860)
Location: net/ipv4/inet_fragment.c:322
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81a1b860-ffffffff81a1ba87: inet_frag_find (STB_GLOBAL)
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
<code>struct inet_frags *f</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int hash</code>
</li>
<li>
<b>Param reordered. </b>
<code>nf, f, key, hash</code> ➡️ <code>nf, key</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fqdir *fqdir</code>
</li>
<li>
<b>Param removed. </b>
<code>struct netns_frags *nf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
