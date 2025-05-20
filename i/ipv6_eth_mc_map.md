# Function: <code>ipv6_eth_mc_map</code>

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
In net/ipv6/ndisc.c (ffffffff817de778)
Location: include/net/if_inet6.h:211
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
In net/ipv6/ndisc.c (ffffffff8184c696)
Location: include/net/if_inet6.h:211
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
In net/ipv6/ndisc.c (ffffffff8187e566)
Location: include/net/if_inet6.h:213
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
In net/ipv6/ndisc.c (ffffffff818a45ad)
Location: include/net/if_inet6.h:213
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
In net/ipv6/ndisc.c (ffffffff81926f5d)
Location: include/net/if_inet6.h:213
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
In net/ipv6/ndisc.c (ffffffff8197f2a9)
Location: include/net/if_inet6.h:213
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
In net/ipv6/ndisc.c (ffffffff819b5879)
Location: include/net/if_inet6.h:215
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
In net/ipv6/ndisc.c (ffffffff81a2438e)
Location: include/net/if_inet6.h:210
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
In net/ipv6/ndisc.c (ffffffff81a5ae0e)
Location: include/net/if_inet6.h:210
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
In net/ipv6/ndisc.c (ffffffff81b535ee)
Location: include/net/if_inet6.h:209
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
In net/ipv6/ndisc.c (ffffffff81b61b7e)
Location: include/net/if_inet6.h:209
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
In net/ipv6/ndisc.c (ffffffff81b4fde1)
Location: include/net/if_inet6.h:218
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
In net/ipv6/ndisc.c (ffffffff81c17141)
Location: include/net/if_inet6.h:217
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
In net/ipv6/ndisc.c (ffffffff81db2ea0)
Location: include/net/if_inet6.h:228
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
void ipv6_eth_mc_map(const struct in6_addr *addr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81f82960)
Location: include/net/if_inet6.h:228
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
```
**Symbols:**

```
ffffffff81f82960-ffffffff81f8297b: ipv6_eth_mc_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipv6_eth_mc_map(const struct in6_addr *addr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81fe2c70)
Location: include/net/if_inet6.h:228
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
```
**Symbols:**

```
ffffffff81fe2c70-ffffffff81fe2c89: ipv6_eth_mc_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipv6_eth_mc_map(const struct in6_addr *addr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff820b0b90)
Location: include/net/if_inet6.h:224
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_mc_map
```
**Symbols:**

```
ffffffff820b0b90-ffffffff820b0ba9: ipv6_eth_mc_map (STB_LOCAL)
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
In net/ipv6/ndisc.c (ffff800010d2019c)
Location: include/net/if_inet6.h:210
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
In net/ipv6/ndisc.c (c0e24e2c)
Location: include/net/if_inet6.h:210
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
In net/ipv6/ndisc.c (c000000000e4ea00)
Location: include/net/if_inet6.h:210
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
In net/ipv6/ndisc.c (ffffffe000862294)
Location: include/net/if_inet6.h:210
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
In net/ipv6/ndisc.c (ffffffff819fa49e)
Location: include/net/if_inet6.h:210
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
In net/ipv6/ndisc.c (ffffffff819b725e)
Location: include/net/if_inet6.h:210
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
In net/ipv6/ndisc.c (ffffffff81a64f1e)
Location: include/net/if_inet6.h:210
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
In net/ipv6/ndisc.c (ffffffff81a7144e)
Location: include/net/if_inet6.h:210
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
