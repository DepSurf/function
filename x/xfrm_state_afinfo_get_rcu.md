# Function: <code>xfrm_state_afinfo_get_rcu</code>

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
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff8187d4fa)
Location: net/xfrm/xfrm_state.c:2129
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff8187d9c0-ffffffff8187d9de: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff818fe366)
Location: net/xfrm/xfrm_state.c:2158
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff818fe790-ffffffff818fe7ae: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81954ea4)
Location: net/xfrm/xfrm_state.c:2159
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81955260-ffffffff81955270: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819898c7)
Location: net/xfrm/xfrm_state.c:2191
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81989e70-ffffffff81989e80: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819edd60)
Location: net/xfrm/xfrm_state.c:2366
Inline: False
Direct callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff819edd60-ffffffff819edd7e: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a24c80)
Location: net/xfrm/xfrm_state.c:2368
Inline: False
Direct callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81a24c80-ffffffff81a24c9e: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b168b0)
Location: net/xfrm/xfrm_state.c:2371
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b168b0-ffffffff81b168ce: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b24ab0)
Location: net/xfrm/xfrm_state.c:2480
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b24ab0-ffffffff81b24ace: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b126d0)
Location: net/xfrm/xfrm_state.c:2479
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b126d0-ffffffff81b126ee: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81bd65d0)
Location: net/xfrm/xfrm_state.c:2539
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81bd65d0-ffffffff81bd6608: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81d6cd90)
Location: net/xfrm/xfrm_state.c:2541
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81d6cd90-ffffffff81d6cdd8: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f38190)
Location: net/xfrm/xfrm_state.c:2705
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81f38190-ffffffff81f381d8: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f97b80)
Location: net/xfrm/xfrm_state.c:2702
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81f97b80-ffffffff81f97bc8: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff82064ef0)
Location: net/xfrm/xfrm_state.c:2702
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff82064ef0-ffffffff82064f38: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
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
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffff800010ce2310)
Location: net/xfrm/xfrm_state.c:2368
Inline: False
Direct callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffff800010ce2310-ffff800010ce2358: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (c0deb190)
Location: net/xfrm/xfrm_state.c:2368
Inline: False
Direct callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_state_finish
```
**Symbols:**

```
c0deb190-c0deb1bc: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (c000000000e04cd0)
Location: net/xfrm/xfrm_state.c:2368
Inline: False
Direct callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_state_finish
```
**Symbols:**

```
c000000000e04cd0-c000000000e04d08: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffe000830ab6)
Location: net/xfrm/xfrm_state.c:2368
Inline: False
Direct callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_state_finish
```
**Symbols:**

```
ffffffe000830ab6-ffffffe000830afa: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
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
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819c4310)
Location: net/xfrm/xfrm_state.c:2368
Inline: False
Direct callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff819c4310-ffffffff819c432e: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81981100)
Location: net/xfrm/xfrm_state.c:2368
Inline: False
Direct callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81981100-ffffffff8198111e: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a2ed90)
Location: net/xfrm/xfrm_state.c:2368
Inline: False
Direct callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81a2ed90-ffffffff81a2edae: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xfrm_state_afinfo *xfrm_state_afinfo_get_rcu(unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a3a250)
Location: net/xfrm/xfrm_state.c:2368
Inline: False
Direct callers:
  - net/ipv4/xfrm4_output.c:__xfrm4_output
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81a3a250-ffffffff81a3a26e: xfrm_state_afinfo_get_rcu (STB_GLOBAL)
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
