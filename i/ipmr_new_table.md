# Function: <code>ipmr_new_table</code>

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
In net/ipv4/ipmr.c (ffffffff817a8c26)
Location: net/ipv4/ipmr.c:317
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
In net/ipv4/ipmr.c (ffffffff81816416)
Location: net/ipv4/ipmr.c:297
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
In net/ipv4/ipmr.c (ffffffff81847bc6)
Location: net/ipv4/ipmr.c:302
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
In net/ipv4/ipmr.c (ffffffff8186b626)
Location: net/ipv4/ipmr.c:323
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
In net/ipv4/ipmr.c (ffffffff818ebe3d)
Location: net/ipv4/ipmr.c:356
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_init
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
In net/ipv4/ipmr.c (ffffffff8194264b)
Location: net/ipv4/ipmr.c:397
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_init
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
In net/ipv4/ipmr.c (ffffffff8197243b)
Location: net/ipv4/ipmr.c:400
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_init
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
In net/ipv4/ipmr.c (ffffffff819dbe5b)
Location: net/ipv4/ipmr.c:393
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct mr_table *ipmr_new_table(struct net *net, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a0f7d0)
Location: net/ipv4/ipmr.c:393
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81a0f7d0-ffffffff81a0f82c: ipmr_new_table (STB_LOCAL)
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
In net/ipv4/ipmr.c (ffffffff81b04f74)
Location: net/ipv4/ipmr.c:397
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct mr_table *ipmr_new_table(struct net *net, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b0e890)
Location: net/ipv4/ipmr.c:397
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81b0e890-ffffffff81b0e8ec: ipmr_new_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct mr_table *ipmr_new_table(struct net *net, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81afc580)
Location: net/ipv4/ipmr.c:397
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81afc580-ffffffff81afc5dc: ipmr_new_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct mr_table *ipmr_new_table(struct net *net, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81bbdc70)
Location: net/ipv4/ipmr.c:399
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81bbdc70-ffffffff81bbdccc: ipmr_new_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct mr_table *ipmr_new_table(struct net *net, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81d52560)
Location: net/ipv4/ipmr.c:392
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81d52560-ffffffff81d525da: ipmr_new_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct mr_table *ipmr_new_table(struct net *net, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f1c840)
Location: net/ipv4/ipmr.c:397
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81f1c840-ffffffff81f1c8ba: ipmr_new_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct mr_table *ipmr_new_table(struct net *net, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f7c320)
Location: net/ipv4/ipmr.c:397
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81f7c320-ffffffff81f7c39a: ipmr_new_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct mr_table *ipmr_new_table(struct net *net, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff82042a10)
Location: net/ipv4/ipmr.c:397
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff82042a10-ffffffff82042a8a: ipmr_new_table (STB_LOCAL)
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
struct mr_table *ipmr_new_table(struct net *net, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010cc9668)
Location: net/ipv4/ipmr.c:393
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffff800010cc9668-ffff800010cc9710: ipmr_new_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct mr_table *ipmr_new_table(struct net *net, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd4da4)
Location: net/ipv4/ipmr.c:393
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
c0dd4da4-c0dd4e40: ipmr_new_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct mr_table *ipmr_new_table(struct net *net, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000de7270)
Location: net/ipv4/ipmr.c:393
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
c000000000de7270-c000000000de7318: ipmr_new_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct mr_table *ipmr_new_table(struct net *net, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe00081dbf8)
Location: net/ipv4/ipmr.c:393
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffe00081dbf8-ffffffe00081dc78: ipmr_new_table (STB_LOCAL)
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
In net/ipv4/ipmr.c (ffffffff819b264b)
Location: net/ipv4/ipmr.c:393
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_init
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
In net/ipv4/ipmr.c (ffffffff8196ec7b)
Location: net/ipv4/ipmr.c:393
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_init
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
In net/ipv4/ipmr.c (ffffffff81a1ceeb)
Location: net/ipv4/ipmr.c:393
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct mr_table *ipmr_new_table(struct net *net, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a248b0)
Location: net/ipv4/ipmr.c:393
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81a248b0-ffffffff81a2490c: ipmr_new_table (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
