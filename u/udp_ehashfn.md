# Function: <code>udp_ehashfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 udp_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81788c50)
Location: net/ipv4/udp.c:428
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81788c50-ffffffff81788d53: udp_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 udp_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f65b0)
Location: net/ipv4/udp.c:437
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
**Symbols:**

```
ffffffff817f65b0-ffffffff817f66ad: udp_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 udp_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81827510)
Location: net/ipv4/udp.c:438
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
**Symbols:**

```
ffffffff81827510-ffffffff8182760d: udp_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 udp_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81848c80)
Location: net/ipv4/udp.c:425
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
**Symbols:**

```
ffffffff81848c80-ffffffff81848d82: udp_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 udp_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c86d0)
Location: net/ipv4/udp.c:427
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
**Symbols:**

```
ffffffff818c86d0-ffffffff818c87dd: udp_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 udp_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191cc70)
Location: net/ipv4/udp.c:415
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
**Symbols:**

```
ffffffff8191cc70-ffffffff8191cd71: udp_ehashfn (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff8194bdd0)
Location: net/ipv4/udp.c:412
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
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
In net/ipv4/udp.c (ffffffff819b052c)
Location: net/ipv4/udp.c:396
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
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
In net/ipv4/udp.c (ffffffff819e71f3)
Location: net/ipv4/udp.c:396
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
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
In net/ipv4/udp.c (ffffffff81ad2aaf)
Location: net/ipv4/udp.c:399
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 udp_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81addc00)
Location: net/ipv4/udp.c:400
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81addc00-ffffffff81addd03: udp_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 udp_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ac8bf0)
Location: net/ipv4/udp.c:400
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81ac8bf0-ffffffff81ac8cf7: udp_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 udp_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b87480)
Location: net/ipv4/udp.c:401
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
**Symbols:**

```
ffffffff81b87480-ffffffff81b87587: udp_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 udp_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d182b0)
Location: net/ipv4/udp.c:401
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
**Symbols:**

```
ffffffff81d182b0-ffffffff81d183ce: udp_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 udp_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81edebc0)
Location: net/ipv4/udp.c:408
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
**Symbols:**

```
ffffffff81edebc0-ffffffff81edecde: udp_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 udp_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f3e000)
Location: net/ipv4/udp.c:410
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
**Symbols:**

```
ffffffff81f3e000-ffffffff81f3e11e: udp_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 udp_ehashfn(const struct net *net, const __be32 laddr, const __u16 lport, const __be32 faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82004130)
Location: net/ipv4/udp.c:411
Inline: False
```
**Symbols:**

```
ffffffff82004130-ffffffff8200424e: udp_ehashfn (STB_GLOBAL)
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
In net/ipv4/udp.c (ffff800010c99b48)
Location: net/ipv4/udp.c:396
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
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
In net/ipv4/udp.c (c0daae74)
Location: net/ipv4/udp.c:396
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
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
In net/ipv4/udp.c (c000000000dae6a8)
Location: net/ipv4/udp.c:396
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
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
In net/ipv4/udp.c (ffffffe0007f965e)
Location: net/ipv4/udp.c:396
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
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
In net/ipv4/udp.c (ffffffff81987063)
Location: net/ipv4/udp.c:396
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
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
In net/ipv4/udp.c (ffffffff81940b23)
Location: net/ipv4/udp.c:396
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
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
In net/ipv4/udp.c (ffffffff819f1833)
Location: net/ipv4/udp.c:396
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
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
In net/ipv4/udp.c (ffffffff819fcb39)
Location: net/ipv4/udp.c:396
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
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
