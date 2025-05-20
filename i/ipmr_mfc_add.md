# Function: <code>ipmr_mfc_add</code>

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
In net/ipv4/ipmr.c (ffffffff817a9d6e)
Location: net/ipv4/ipmr.c:1123
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818173c0)
Location: net/ipv4/ipmr.c:1111
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff818173c0-ffffffff81817746: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81848c30)
Location: net/ipv4/ipmr.c:1116
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81848c30-ffffffff81848fb6: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8186c0d0)
Location: net/ipv4/ipmr.c:1170
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff8186c0d0-ffffffff8186c69d: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818ec980)
Location: net/ipv4/ipmr.c:1298
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff818ec980-ffffffff818ecf7c: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81942780)
Location: net/ipv4/ipmr.c:1215
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81942780-ffffffff81942ee7: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81972850)
Location: net/ipv4/ipmr.c:1221
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81972850-ffffffff81972fb3: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819dc2f0)
Location: net/ipv4/ipmr.c:1213
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff819dc2f0-ffffffff819dcac1: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a132e0)
Location: net/ipv4/ipmr.c:1213
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81a132e0-ffffffff81a13ab1: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1181
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81b03820-ffffffff81b03c62: ipmr_mfc_add (STB_LOCAL)
ffffffff81b05d48-ffffffff81b05d6e: ipmr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1188
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81b11990-ffffffff81b11dd7: ipmr_mfc_add (STB_LOCAL)
ffffffff81c32a46-ffffffff81c32a6c: ipmr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1188
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81b00230-ffffffff81b007af: ipmr_mfc_add (STB_LOCAL)
ffffffff81c24d3f-ffffffff81c24d66: ipmr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1190
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81bc2320-ffffffff81bc28b7: ipmr_mfc_add (STB_LOCAL)
ffffffff81d3eaff-ffffffff81d3eb4e: ipmr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1184
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81d57100-ffffffff81d5751e: ipmr_mfc_add (STB_LOCAL)
ffffffff81f0b436-ffffffff81f0b484: ipmr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1198
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81f207a0-ffffffff81f20bd3: ipmr_mfc_add (STB_LOCAL)
ffffffff820b2c94-ffffffff820b2cbc: ipmr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1198
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81f80fc0-ffffffff81f813f3: ipmr_mfc_add (STB_LOCAL)
ffffffff82133e9d-ffffffff82133ec5: ipmr_mfc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1197
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff82047640-ffffffff82047a73: ipmr_mfc_add (STB_LOCAL)
ffffffff822158a9-ffffffff822158d1: ipmr_mfc_add.cold (STB_LOCAL)
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
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010ccd860)
Location: net/ipv4/ipmr.c:1213
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffff800010ccd860-ffff800010cce10c: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd8920)
Location: net/ipv4/ipmr.c:1213
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
c0dd8920-c0dd9210: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000dea250)
Location: net/ipv4/ipmr.c:1213
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
c000000000dea250-c000000000deac74: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe00081fd64)
Location: net/ipv4/ipmr.c:1213
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffe00081fd64-ffffffe0008204b0: ipmr_mfc_add (STB_LOCAL)
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
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819b2ae0)
Location: net/ipv4/ipmr.c:1213
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff819b2ae0-ffffffff819b32b1: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196f110)
Location: net/ipv4/ipmr.c:1213
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff8196f110-ffffffff8196f8e1: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a1d380)
Location: net/ipv4/ipmr.c:1213
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81a1d380-ffffffff81a1db51: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipmr_mfc_add(struct net *net, struct mr_table *mrt, struct mfcctl *mfc, int mrtsock, int parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a284e0)
Location: net/ipv4/ipmr.c:1213
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81a284e0-ffffffff81a28da4: ipmr_mfc_add (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
