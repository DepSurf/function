# Function: <code>ipv6_ipgre_mc_map</code>

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
In net/ipv6/ndisc.c (ffffffff817de68c)
Location: include/net/if_inet6.h:248
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
In net/ipv6/ndisc.c (ffffffff8184c5ac)
Location: include/net/if_inet6.h:248
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
In net/ipv6/ndisc.c (ffffffff8187e47c)
Location: include/net/if_inet6.h:250
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
In net/ipv6/ndisc.c (ffffffff818a4515)
Location: include/net/if_inet6.h:250
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
In net/ipv6/ndisc.c (ffffffff81926ec5)
Location: include/net/if_inet6.h:250
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
In net/ipv6/ndisc.c (ffffffff8197f30d)
Location: include/net/if_inet6.h:250
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
In net/ipv6/ndisc.c (ffffffff819b58dd)
Location: include/net/if_inet6.h:252
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
In net/ipv6/ndisc.c (ffffffff81a24341)
Location: include/net/if_inet6.h:247
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
In net/ipv6/ndisc.c (ffffffff81a5adc1)
Location: include/net/if_inet6.h:247
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
In net/ipv6/ndisc.c (ffffffff81b535a1)
Location: include/net/if_inet6.h:246
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
In net/ipv6/ndisc.c (ffffffff81b61b31)
Location: include/net/if_inet6.h:246
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
In net/ipv6/ndisc.c (ffffffff81b4fd93)
Location: include/net/if_inet6.h:255
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
In net/ipv6/ndisc.c (ffffffff81c170f3)
Location: include/net/if_inet6.h:254
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
In net/ipv6/ndisc.c (ffffffff81db2e52)
Location: include/net/if_inet6.h:265
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
int ipv6_ipgre_mc_map(const struct in6_addr *addr, const unsigned char *broadcast, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81f82990)
Location: include/net/if_inet6.h:265
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
```
**Symbols:**

```
ffffffff81f82990-ffffffff81f829e9: ipv6_ipgre_mc_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipv6_ipgre_mc_map(const struct in6_addr *addr, const unsigned char *broadcast, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81fe2ca0)
Location: include/net/if_inet6.h:265
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
```
**Symbols:**

```
ffffffff81fe2ca0-ffffffff81fe2cf9: ipv6_ipgre_mc_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipv6_ipgre_mc_map(const struct in6_addr *addr, const unsigned char *broadcast, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff820b0bc0)
Location: include/net/if_inet6.h:261
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
```
**Symbols:**

```
ffffffff820b0bc0-ffffffff820b0c19: ipv6_ipgre_mc_map (STB_LOCAL)
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
In net/ipv6/ndisc.c (ffff800010d201d0)
Location: include/net/if_inet6.h:247
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
In net/ipv6/ndisc.c (c0e24d80)
Location: include/net/if_inet6.h:247
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
In net/ipv6/ndisc.c (c000000000e4e990)
Location: include/net/if_inet6.h:247
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
In net/ipv6/ndisc.c (ffffffe0008622e2)
Location: include/net/if_inet6.h:247
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
In net/ipv6/ndisc.c (ffffffff819fa451)
Location: include/net/if_inet6.h:247
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
In net/ipv6/ndisc.c (ffffffff819b7211)
Location: include/net/if_inet6.h:247
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
In net/ipv6/ndisc.c (ffffffff81a64ed1)
Location: include/net/if_inet6.h:247
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
In net/ipv6/ndisc.c (ffffffff81a71401)
Location: include/net/if_inet6.h:247
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
