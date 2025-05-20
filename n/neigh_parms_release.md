# Function: <code>neigh_parms_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81724880)
Location: net/core/neighbour.c:1474
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81724880-ffffffff81724913: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8178e330)
Location: net/core/neighbour.c:1469
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff8178e330-ffffffff8178e3c3: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817bbc00)
Location: net/core/neighbour.c:1471
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff817bbc00-ffffffff817bbc93: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817db3b0)
Location: net/core/neighbour.c:1513
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff817db3b0-ffffffff817db440: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81855b70)
Location: net/core/neighbour.c:1513
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81855b70-ffffffff81855c00: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818a1030)
Location: net/core/neighbour.c:1529
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff818a1030-ffffffff818a10bf: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818c3990)
Location: net/core/neighbour.c:1639
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff818c3990-ffffffff818c3a1f: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8190fbf0)
Location: net/core/neighbour.c:1653
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff8190fbf0-ffffffff8190fc79: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81942260)
Location: net/core/neighbour.c:1650
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81942260-ffffffff819422e9: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a11a20)
Location: net/core/neighbour.c:1652
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/addrconf.c:ipv6_add_dev
```
**Symbols:**

```
ffffffff81a11a20-ffffffff81a11aa9: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a11d80)
Location: net/core/neighbour.c:1653
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/addrconf.c:ipv6_add_dev
```
**Symbols:**

```
ffffffff81a11d80-ffffffff81a11e09: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff819f89e0)
Location: net/core/neighbour.c:1657
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/addrconf.c:ipv6_add_dev
```
**Symbols:**

```
ffffffff819f89e0-ffffffff819f8a69: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81aaa5a0)
Location: net/core/neighbour.c:1658
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/addrconf.c:ipv6_add_dev
```
**Symbols:**

```
ffffffff81aaa5a0-ffffffff81aaa629: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81c233c0)
Location: net/core/neighbour.c:1718
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/addrconf.c:ipv6_add_dev
```
**Symbols:**

```
ffffffff81c233c0-ffffffff81c23465: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81dd5390)
Location: net/core/neighbour.c:1762
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/addrconf.c:ipv6_add_dev
```
**Symbols:**

```
ffffffff81dd5390-ffffffff81dd5435: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81e462e0)
Location: net/core/neighbour.c:1741
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/addrconf.c:ipv6_add_dev
```
**Symbols:**

```
ffffffff81e462e0-ffffffff81e46385: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81f04f80)
Location: net/core/neighbour.c:1752
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/addrconf.c:ipv6_add_dev
```
**Symbols:**

```
ffffffff81f04f80-ffffffff81f05025: neigh_parms_release (STB_GLOBAL)
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
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffff800010be32e0)
Location: net/core/neighbour.c:1650
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffff800010be32e0-ffff800010be33f4: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0cfcc3c)
Location: net/core/neighbour.c:1650
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
c0cfcc3c-c0cfccdc: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cc5440)
Location: net/core/neighbour.c:1650
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
c000000000cc5440-c000000000cc5534: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe000768a54)
Location: net/core/neighbour.c:1650
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffe000768a54-ffffffe000768af6: neigh_parms_release (STB_GLOBAL)
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
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818e2230)
Location: net/core/neighbour.c:1650
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff818e2230-ffffffff818e22b9: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8189c070)
Location: net/core/neighbour.c:1650
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff8189c070-ffffffff8189c0f9: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81933260)
Location: net/core/neighbour.c:1650
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81933260-ffffffff819332e9: neigh_parms_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void neigh_parms_release(struct neigh_table *tbl, struct neigh_parms *parms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81954b90)
Location: net/core/neighbour.c:1650
Inline: True
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81954b90-ffffffff81954c19: neigh_parms_release (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
