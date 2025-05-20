# Function: <code>ip6mr_mfc_add</code>

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
In net/ipv6/ip6mr.c (ffffffff817faae8)
Location: net/ipv6/ip6mr.c:1449
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8186a344)
Location: net/ipv6/ip6mr.c:1451
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8189d194)
Location: net/ipv6/ip6mr.c:1451
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In net/ipv6/ip6mr.c (ffffffff818c36b3)
Location: net/ipv6/ip6mr.c:1454
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In net/ipv6/ip6mr.c (ffffffff81946953)
Location: net/ipv6/ip6mr.c:1454
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8199ef00)
Location: net/ipv6/ip6mr.c:1388
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8199ef00-ffffffff8199f799: ip6mr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d5a20)
Location: net/ipv6/ip6mr.c:1406
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff819d5a20-ffffffff819d62c7: ip6mr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a44ad0)
Location: net/ipv6/ip6mr.c:1401
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81a44ad0-ffffffff81a453cd: ip6mr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a7b6c0)
Location: net/ipv6/ip6mr.c:1401
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81a7b6c0-ffffffff81a7bfbd: ip6mr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1406
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81b765d0-ffffffff81b769bd: ip6mr_mfc_add (STB_LOCAL)
ffffffff81b77e3f-ffffffff81b77e65: ip6mr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1406
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81b85390-ffffffff81b85782: ip6mr_mfc_add (STB_LOCAL)
ffffffff81c32fd8-ffffffff81c32ffe: ip6mr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1406
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81b73f00-ffffffff81b74432: ip6mr_mfc_add (STB_LOCAL)
ffffffff81c252db-ffffffff81c25305: ip6mr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1407
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81c3e7a0-ffffffff81c3ed1a: ip6mr_mfc_add (STB_LOCAL)
ffffffff81d41397-ffffffff81d413c1: ip6mr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1416
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81ddcf20-ffffffff81ddd52b: ip6mr_mfc_add (STB_LOCAL)
ffffffff81f0dcf4-ffffffff81f0dd44: ip6mr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1425
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81fae3b0-ffffffff81fae9c2: ip6mr_mfc_add (STB_LOCAL)
ffffffff820b50a2-ffffffff820b50ca: ip6mr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1425
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8200f830-ffffffff8200fe42: ip6mr_mfc_add (STB_LOCAL)
ffffffff82135fd4-ffffffff82135ffc: ip6mr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1425
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff820de7c0-ffffffff820dedd2: ip6mr_mfc_add (STB_LOCAL)
ffffffff82217c09-ffffffff82217c31: ip6mr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffff800010d45258)
Location: net/ipv6/ip6mr.c:1401
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffff800010d45258-ffff800010d45b40: ip6mr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c0e47e1c)
Location: net/ipv6/ip6mr.c:1401
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
c0e47e1c-c0e4879c: ip6mr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c000000000e7ad30)
Location: net/ipv6/ip6mr.c:1401
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
c000000000e7ad30-c000000000e7b754: ip6mr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffe00088055c)
Location: net/ipv6/ip6mr.c:1401
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffe00088055c-ffffffe000880d7e: ip6mr_mfc_add (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a1ad50)
Location: net/ipv6/ip6mr.c:1401
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81a1ad50-ffffffff81a1b64d: ip6mr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d7b10)
Location: net/ipv6/ip6mr.c:1401
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff819d7b10-ffffffff819d840d: ip6mr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a857d0)
Location: net/ipv6/ip6mr.c:1401
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81a857d0-ffffffff81a860cd: ip6mr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6mr_mfc_add(struct net *net, struct mr_table *mrt, struct mf6cctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a92230)
Location: net/ipv6/ip6mr.c:1401
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81a92230-ffffffff81a92c82: ip6mr_mfc_add (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
