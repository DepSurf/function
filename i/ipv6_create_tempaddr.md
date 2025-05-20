# Function: <code>ipv6_create_tempaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817ce860)
Location: net/ipv6/addrconf.c:1146
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff817ce860-ffffffff817cec37: ipv6_create_tempaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183bf40)
Location: net/ipv6/addrconf.c:1160
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
```
**Symbols:**

```
ffffffff8183bf40-ffffffff8183c300: ipv6_create_tempaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186d940)
Location: net/ipv6/addrconf.c:1187
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
```
**Symbols:**

```
ffffffff8186d940-ffffffff8186ddbc: ipv6_create_tempaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81892780)
Location: net/ipv6/addrconf.c:1229
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
```
**Symbols:**

```
ffffffff81892780-ffffffff81892bb1: ipv6_create_tempaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819139b0)
Location: net/ipv6/addrconf.c:1270
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
```
**Symbols:**

```
ffffffff819139b0-ffffffff81913e07: ipv6_create_tempaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8196af80)
Location: net/ipv6/addrconf.c:1256
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff8196af80-ffffffff8196b3eb: ipv6_create_tempaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a09f0)
Location: net/ipv6/addrconf.c:1272
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff819a09f0-ffffffff819a0e69: ipv6_create_tempaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:1305
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff81a0cbe0-ffffffff81a0d04f: ipv6_create_tempaddr (STB_LOCAL)
ffffffff81a1138e-ffffffff81a113b0: ipv6_create_tempaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:1307
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff81a438c0-ffffffff81a43d2f: ipv6_create_tempaddr (STB_LOCAL)
ffffffff81a4801e-ffffffff81a48040: ipv6_create_tempaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b39eb0)
Location: net/ipv6/addrconf.c:1307
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff81b39eb0-ffffffff81b3a425: ipv6_create_tempaddr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b48bb0)
Location: net/ipv6/addrconf.c:1307
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff81b48bb0-ffffffff81b49129: ipv6_create_tempaddr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b36840)
Location: net/ipv6/addrconf.c:1309
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff81b36840-ffffffff81b36d81: ipv6_create_tempaddr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bfcff0)
Location: net/ipv6/addrconf.c:1316
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff81bfcff0-ffffffff81bfd531: ipv6_create_tempaddr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d96990)
Location: net/ipv6/addrconf.c:1323
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff81d96990-ffffffff81d96ef9: ipv6_create_tempaddr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f65520)
Location: net/ipv6/addrconf.c:1323
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff81f65520-ffffffff81f65a93: ipv6_create_tempaddr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc5630)
Location: net/ipv6/addrconf.c:1322
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff81fc5630-ffffffff81fc5ba3: ipv6_create_tempaddr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff82092be0)
Location: net/ipv6/addrconf.c:1349
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff82092be0-ffffffff8209317a: ipv6_create_tempaddr.isra.0 (STB_LOCAL)
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
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d05788)
Location: net/ipv6/addrconf.c:1307
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffff800010d05788-ffff800010d05d94: ipv6_create_tempaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e0c804)
Location: net/ipv6/addrconf.c:1307
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
c0e0c804-c0e0cc28: ipv6_create_tempaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e2f7b0)
Location: net/ipv6/addrconf.c:1307
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
c000000000e2f7b0-c000000000e2fe44: ipv6_create_tempaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084d632)
Location: net/ipv6/addrconf.c:1307
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffe00084d632-ffffffe00084db04: ipv6_create_tempaddr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:1307
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff819e2f50-ffffffff819e33bf: ipv6_create_tempaddr (STB_LOCAL)
ffffffff819e76ae-ffffffff819e76d0: ipv6_create_tempaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:1307
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff8199fd10-ffffffff819a017f: ipv6_create_tempaddr (STB_LOCAL)
ffffffff819a446e-ffffffff819a4490: ipv6_create_tempaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:1307
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff81a4d9d0-ffffffff81a4de3f: ipv6_create_tempaddr (STB_LOCAL)
ffffffff81a5212e-ffffffff81a52150: ipv6_create_tempaddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ipv6_create_tempaddr(struct inet6_ifaddr *ifp, struct inet6_ifaddr *ift, bool block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:1307
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
```
**Symbols:**

```
ffffffff81a59930-ffffffff81a59da1: ipv6_create_tempaddr (STB_LOCAL)
ffffffff81a5e07e-ffffffff81a5e0a0: ipv6_create_tempaddr.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool block</code>
</li>
</ul>
</details>
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
