# Function: <code>ipmr_fib_lookup</code>

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
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:295
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
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:270
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
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:275
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
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:276
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
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:293
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
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:316
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
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:319
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
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:313
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a0f020)
Location: net/ipv4/ipmr.c:143
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81a0f020-ffffffff81a0f0bf: ipmr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81afffd0)
Location: net/ipv4/ipmr.c:145
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81afffd0-ffffffff81b0006f: ipmr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b0e010)
Location: net/ipv4/ipmr.c:145
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81b0e010-ffffffff81b0e0af: ipmr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81afbe10)
Location: net/ipv4/ipmr.c:145
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81afbe10-ffffffff81afbeaf: ipmr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81bbd2b0)
Location: net/ipv4/ipmr.c:145
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81bbd2b0-ffffffff81bbd34f: ipmr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81d51a30)
Location: net/ipv4/ipmr.c:145
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81d51a30-ffffffff81d51ae4: ipmr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f1b990)
Location: net/ipv4/ipmr.c:150
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81f1b990-ffffffff81f1ba44: ipmr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f7b450)
Location: net/ipv4/ipmr.c:150
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81f7b450-ffffffff81f7b504: ipmr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff82041b40)
Location: net/ipv4/ipmr.c:150
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff82041b40-ffffffff82041bf4: ipmr_fib_lookup (STB_LOCAL)
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
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010cc8f20)
Location: net/ipv4/ipmr.c:143
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffff800010cc8f20-ffff800010cc8fc4: ipmr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd4320)
Location: net/ipv4/ipmr.c:143
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
c0dd4320-c0dd43c8: ipmr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000de6480)
Location: net/ipv4/ipmr.c:143
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
c000000000de6480-c000000000de6550: ipmr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe00081d166)
Location: net/ipv4/ipmr.c:143
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffe00081d166-ffffffe00081d1de: ipmr_fib_lookup (STB_LOCAL)
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
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:313
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
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:313
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
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:313
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipmr_fib_lookup(struct net *net, struct flowi4 *flp4, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a240c0)
Location: net/ipv4/ipmr.c:143
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rt_fib_lookup
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81a240c0-ffffffff81a2415f: ipmr_fib_lookup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
