# Function: <code>xfrm_policy_register_afinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(struct xfrm_policy_afinfo *afinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff817b1000)
Location: net/xfrm/xfrm_policy.c:2827
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff817b1000-ffffffff817b10ed: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(struct xfrm_policy_afinfo *afinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8181df50)
Location: net/xfrm/xfrm_policy.c:2831
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff8181df50-ffffffff8181e03f: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(struct xfrm_policy_afinfo *afinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8184f7d0)
Location: net/xfrm/xfrm_policy.c:2859
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff8184f7d0-ffffffff8184f8bf: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818733c0)
Location: net/xfrm/xfrm_policy.c:2838
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff818733c0-ffffffff818734a5: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818f3d60)
Location: net/xfrm/xfrm_policy.c:2756
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff818f3d60-ffffffff818f3e49: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8194afe0)
Location: net/xfrm/xfrm_policy.c:2771
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff8194afe0-ffffffff8194b0c4: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197e4f0)
Location: net/xfrm/xfrm_policy.c:3695
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff8197e4f0-ffffffff8197e5d4: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:3905
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff819ed7d3-ffffffff819ed7ec: xfrm_policy_register_afinfo.cold (STB_LOCAL)
ffffffff819e8390-ffffffff819e846e: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a1f390)
Location: net/xfrm/xfrm_policy.c:3907
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff81a1f390-ffffffff81a1f47e: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b10770)
Location: net/xfrm/xfrm_policy.c:3897
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff81b10770-ffffffff81b1085e: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1ea60)
Location: net/xfrm/xfrm_policy.c:3918
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff81b1ea60-ffffffff81b1eb4e: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0d4d0)
Location: net/xfrm/xfrm_policy.c:3878
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff81b0d4d0-ffffffff81b0d5be: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd0dd0)
Location: net/xfrm/xfrm_policy.c:3914
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff81bd0dd0-ffffffff81bd0ef3: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d62c90)
Location: net/xfrm/xfrm_policy.c:3918
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff81d62c90-ffffffff81d62dc0: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f2d840)
Location: net/xfrm/xfrm_policy.c:3998
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff81f2d840-ffffffff81f2d970: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f8d510)
Location: net/xfrm/xfrm_policy.c:4004
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff81f8d510-ffffffff81f8d640: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205aea0)
Location: net/xfrm/xfrm_policy.c:3923
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff8205aea0-ffffffff8205afd0: xfrm_policy_register_afinfo (STB_GLOBAL)
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
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cdbba8)
Location: net/xfrm/xfrm_policy.c:3907
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffff800010cdbba8-ffff800010cdbd2c: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de2b38)
Location: net/xfrm/xfrm_policy.c:3907
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
c0de2b38-c0de2c88: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000df96b0)
Location: net/xfrm/xfrm_policy.c:3907
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
c000000000df96b0-c000000000df9868: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082be32)
Location: net/xfrm/xfrm_policy.c:3907
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffe00082be32-ffffffe00082bf5a: xfrm_policy_register_afinfo (STB_GLOBAL)
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
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819bea20)
Location: net/xfrm/xfrm_policy.c:3907
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff819bea20-ffffffff819beb0e: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197b810)
Location: net/xfrm/xfrm_policy.c:3907
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff8197b810-ffffffff8197b8fe: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a294a0)
Location: net/xfrm/xfrm_policy.c:3907
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff81a294a0-ffffffff81a2958e: xfrm_policy_register_afinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xfrm_policy_register_afinfo(const struct xfrm_policy_afinfo *afinfo, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a320b0)
Location: net/xfrm/xfrm_policy.c:3907
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
```
**Symbols:**

```
ffffffff81a320b0-ffffffff81a3219c: xfrm_policy_register_afinfo (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int family</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct xfrm_policy_afinfo *afinfo</code> ➡️ <code>const struct xfrm_policy_afinfo *afinfo</code>
</li>
</ul>
</details>
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
