# Function: <code>xfrm_policy_insert_list</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197c030)
Location: net/xfrm/xfrm_policy.c:1525
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff8197c030-ffffffff8197c1c6: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:1531
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff819e5970-ffffffff819e5b3b: xfrm_policy_insert_list (STB_LOCAL)
ffffffff819ed770-ffffffff819ed7a1: xfrm_policy_insert_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a1c970)
Location: net/xfrm/xfrm_policy.c:1533
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81a1c970-ffffffff81a1cb00: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0ff40)
Location: net/xfrm/xfrm_policy.c:1527
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81b0ff40-ffffffff81b100d5: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1e230)
Location: net/xfrm/xfrm_policy.c:1537
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81b1e230-ffffffff81b1e3c5: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0bb90)
Location: net/xfrm/xfrm_policy.c:1536
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81b0bb90-ffffffff81b0bd26: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bceb50)
Location: net/xfrm/xfrm_policy.c:1538
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81bceb50-ffffffff81bcece6: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d65a80)
Location: net/xfrm/xfrm_policy.c:1538
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81d65a80-ffffffff81d65c5c: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f30a00)
Location: net/xfrm/xfrm_policy.c:1539
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81f30a00-ffffffff81f30bf0: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f90a70)
Location: net/xfrm/xfrm_policy.c:1539
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81f90a70-ffffffff81f90c60: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205e7e0)
Location: net/xfrm/xfrm_policy.c:1555
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff8205e7e0-ffffffff8205e9d0: xfrm_policy_insert_list (STB_LOCAL)
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
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cd8d08)
Location: net/xfrm/xfrm_policy.c:1533
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffff800010cd8d08-ffff800010cd8ee8: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de2918)
Location: net/xfrm/xfrm_policy.c:1533
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
c0de2918-c0de2b38: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000df94b0)
Location: net/xfrm/xfrm_policy.c:1533
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
c000000000df94b0-c000000000df96b0: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe000829268)
Location: net/xfrm/xfrm_policy.c:1533
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffe000829268-ffffffe0008293b6: xfrm_policy_insert_list (STB_LOCAL)
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
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819bc000)
Location: net/xfrm/xfrm_policy.c:1533
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff819bc000-ffffffff819bc190: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81978df0)
Location: net/xfrm/xfrm_policy.c:1533
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81978df0-ffffffff81978f80: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a26a80)
Location: net/xfrm/xfrm_policy.c:1533
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81a26a80-ffffffff81a26c10: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_insert_list(struct hlist_head *chain, struct xfrm_policy *policy, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a31f20)
Location: net/xfrm/xfrm_policy.c:1533
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81a31f20-ffffffff81a320b0: xfrm_policy_insert_list (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
