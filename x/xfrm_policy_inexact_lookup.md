# Function: <code>xfrm_policy_inexact_lookup</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197fe76)
Location: net/xfrm/xfrm_policy.c:1990
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
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
In net/xfrm/xfrm_policy.c (ffffffff819e9bfe)
Location: net/xfrm/xfrm_policy.c:1996
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
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
In net/xfrm/xfrm_policy.c (ffffffff81a20c4e)
Location: net/xfrm/xfrm_policy.c:1998
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
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
In net/xfrm/xfrm_policy.c (ffffffff81b13850)
Location: net/xfrm/xfrm_policy.c:1989
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xfrm_pol_inexact_bin *xfrm_policy_inexact_lookup(struct net *net, u8 type, u16 family, u8 dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b21050)
Location: net/xfrm/xfrm_policy.c:1999
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
```
**Symbols:**

```
ffffffff81b21050-ffffffff81b21185: xfrm_policy_inexact_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xfrm_pol_inexact_bin *xfrm_policy_inexact_lookup(struct net *net, u8 type, u16 family, u8 dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0ec80)
Location: net/xfrm/xfrm_policy.c:1998
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
```
**Symbols:**

```
ffffffff81b0ec80-ffffffff81b0edaa: xfrm_policy_inexact_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xfrm_pol_inexact_bin *xfrm_policy_inexact_lookup(struct net *net, u8 type, u16 family, u8 dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd2080)
Location: net/xfrm/xfrm_policy.c:1999
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
```
**Symbols:**

```
ffffffff81bd2080-ffffffff81bd21aa: xfrm_policy_inexact_lookup (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81d6862d)
Location: net/xfrm/xfrm_policy.c:1999
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
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
In net/xfrm/xfrm_policy.c (ffffffff81f336cd)
Location: net/xfrm/xfrm_policy.c:2070
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
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
In net/xfrm/xfrm_policy.c (ffffffff81f92a4d)
Location: net/xfrm/xfrm_policy.c:2072
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xfrm_pol_inexact_bin *xfrm_policy_inexact_lookup(struct net *net, u8 type, u16 family, u8 dir, u32 if_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205d090)
Location: net/xfrm/xfrm_policy.c:2092
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
```
**Symbols:**

```
ffffffff8205d090-ffffffff8205d1ee: xfrm_policy_inexact_lookup (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffff800010cde674)
Location: net/xfrm/xfrm_policy.c:1998
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
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
In net/xfrm/xfrm_policy.c (c0de7160)
Location: net/xfrm/xfrm_policy.c:1998
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
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
In net/xfrm/xfrm_policy.c (c000000000dfe878)
Location: net/xfrm/xfrm_policy.c:1998
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
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
In net/xfrm/xfrm_policy.c (ffffffe00082dbcc)
Location: net/xfrm/xfrm_policy.c:1998
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
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
In net/xfrm/xfrm_policy.c (ffffffff819c02de)
Location: net/xfrm/xfrm_policy.c:1998
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
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
In net/xfrm/xfrm_policy.c (ffffffff8197d0ce)
Location: net/xfrm/xfrm_policy.c:1998
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
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
In net/xfrm/xfrm_policy.c (ffffffff81a2ad5e)
Location: net/xfrm/xfrm_policy.c:1998
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
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
In net/xfrm/xfrm_policy.c (ffffffff81a36376)
Location: net/xfrm/xfrm_policy.c:1998
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
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
</ul>
