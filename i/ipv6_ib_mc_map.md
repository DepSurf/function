# Function: <code>ipv6_ib_mc_map</code>

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
In net/ipv6/ndisc.c (ffffffff817de715)
Location: include/net/if_inet6.h:230
Inline: True
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
In net/ipv6/ndisc.c (ffffffff8184c633)
Location: include/net/if_inet6.h:230
Inline: True
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
In net/ipv6/ndisc.c (ffffffff8187e503)
Location: include/net/if_inet6.h:232
Inline: True
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
In net/ipv6/ndisc.c (ffffffff818a4552)
Location: include/net/if_inet6.h:232
Inline: True
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
In net/ipv6/ndisc.c (ffffffff81926f02)
Location: include/net/if_inet6.h:232
Inline: True
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
In net/ipv6/ndisc.c (ffffffff8197f2c2)
Location: include/net/if_inet6.h:232
Inline: True
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
In net/ipv6/ndisc.c (ffffffff819b5892)
Location: include/net/if_inet6.h:234
Inline: True
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
In net/ipv6/ndisc.c (ffffffff81a243a0)
Location: include/net/if_inet6.h:229
Inline: True
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
In net/ipv6/ndisc.c (ffffffff81a5ae20)
Location: include/net/if_inet6.h:229
Inline: True
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
In net/ipv6/ndisc.c (ffffffff81b53607)
Location: include/net/if_inet6.h:228
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81b61b97)
Location: include/net/if_inet6.h:228
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
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
In net/ipv6/ndisc.c (ffffffff81b4fdfc)
Location: include/net/if_inet6.h:237
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
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
In net/ipv6/ndisc.c (ffffffff81c1715c)
Location: include/net/if_inet6.h:236
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
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
In net/ipv6/ndisc.c (ffffffff81db2ec3)
Location: include/net/if_inet6.h:247
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipv6_ib_mc_map(const struct in6_addr *addr, const unsigned char *broadcast, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81f82a00)
Location: include/net/if_inet6.h:247
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
```
**Symbols:**

```
ffffffff81f82a00-ffffffff81f82a4b: ipv6_ib_mc_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipv6_ib_mc_map(const struct in6_addr *addr, const unsigned char *broadcast, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81fe2d10)
Location: include/net/if_inet6.h:247
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
```
**Symbols:**

```
ffffffff81fe2d10-ffffffff81fe2d5b: ipv6_ib_mc_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipv6_ib_mc_map(const struct in6_addr *addr, const unsigned char *broadcast, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff820b0c30)
Location: include/net/if_inet6.h:243
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
```
**Symbols:**

```
ffffffff820b0c30-ffffffff820b0c7b: ipv6_ib_mc_map (STB_LOCAL)
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
In net/ipv6/ndisc.c (ffff800010d20218)
Location: include/net/if_inet6.h:229
Inline: True
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
In net/ipv6/ndisc.c (c0e24dc4)
Location: include/net/if_inet6.h:229
Inline: True
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
In net/ipv6/ndisc.c (c000000000e4ea20)
Location: include/net/if_inet6.h:229
Inline: True
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
In net/ipv6/ndisc.c (ffffffe000862362)
Location: include/net/if_inet6.h:229
Inline: True
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
In net/ipv6/ndisc.c (ffffffff819fa4b0)
Location: include/net/if_inet6.h:229
Inline: True
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
In net/ipv6/ndisc.c (ffffffff819b7270)
Location: include/net/if_inet6.h:229
Inline: True
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
In net/ipv6/ndisc.c (ffffffff81a64f30)
Location: include/net/if_inet6.h:229
Inline: True
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
In net/ipv6/ndisc.c (ffffffff81a71460)
Location: include/net/if_inet6.h:229
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
