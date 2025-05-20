# Function: <code>icmpv4_global_allow</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8184de10)
Location: net/ipv4/icmp.c:299
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff8184de10-ffffffff8184de46: icmpv4_global_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff818cdb30)
Location: net/ipv4/icmp.c:299
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff818cdb30-ffffffff818cdb66: icmpv4_global_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff819242d0)
Location: net/ipv4/icmp.c:299
Inline: True
Direct callers:
  - net/ipv4/icmp.c:icmp_send
```
**Symbols:**

```
ffffffff819242d0-ffffffff81924305: icmpv4_global_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81952e90)
Location: net/ipv4/icmp.c:299
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81952e90-ffffffff81952ecb: icmpv4_global_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff819b7920)
Location: net/ipv4/icmp.c:294
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff819b7920-ffffffff819b795c: icmpv4_global_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff819ee620)
Location: net/ipv4/icmp.c:295
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff819ee620-ffffffff819ee65c: icmpv4_global_allow (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff81adc90d)
Location: net/ipv4/icmp.c:295
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
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
In net/ipv4/icmp.c (ffffffff81ae9628)
Location: net/ipv4/icmp.c:298
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
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
In net/ipv4/icmp.c (ffffffff81ad4ab9)
Location: net/ipv4/icmp.c:298
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/icmp.c:icmp_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81b93476)
Location: net/ipv4/icmp.c:298
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
**Symbols:**

```
ffffffff81b93440-ffffffff81b93490: icmpv4_global_allow (STB_LOCAL)
ffffffff81d3c14e-ffffffff81d3c167: icmpv4_global_allow.cold (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff81d24457)
Location: net/ipv4/icmp.c:291
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81eebc37)
Location: net/ipv4/icmp.c:291
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81f4ba1a)
Location: net/ipv4/icmp.c:291
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff82011b2a)
Location: net/ipv4/icmp.c:291
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
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
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffff800010ca3ee8)
Location: net/ipv4/icmp.c:295
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffff800010ca3ee8-ffff800010ca3f58: icmpv4_global_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (c0db0a38)
Location: net/ipv4/icmp.c:295
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
c0db0a38-c0db0a8c: icmpv4_global_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (c000000000db7ba0)
Location: net/ipv4/icmp.c:295
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
c000000000db7ba0-c000000000db7bf0: icmpv4_global_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffe0007ffc14)
Location: net/ipv4/icmp.c:295
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffe0007ffc14-ffffffe0007ffc80: icmpv4_global_allow (STB_LOCAL)
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
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8198e3c0)
Location: net/ipv4/icmp.c:295
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff8198e3c0-ffffffff8198e3fc: icmpv4_global_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81947e80)
Location: net/ipv4/icmp.c:295
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81947e80-ffffffff81947ebc: icmpv4_global_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff819f8c60)
Location: net/ipv4/icmp.c:295
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff819f8c60-ffffffff819f8c9c: icmpv4_global_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool icmpv4_global_allow(struct net *net, int type, int code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81a02be0)
Location: net/ipv4/icmp.c:295
Inline: True
Direct callers:
  - net/ipv4/icmp.c:__icmp_send
```
**Symbols:**

```
ffffffff81a02be0-ffffffff81a02c1c: icmpv4_global_allow (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
