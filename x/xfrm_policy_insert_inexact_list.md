# Function: <code>xfrm_policy_insert_inexact_list</code>

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
In net/xfrm/xfrm_policy.c (ffffffff81980b0f)
Location: net/xfrm/xfrm_policy.c:1489
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
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
In net/xfrm/xfrm_policy.c (ffffffff819ea86e)
Location: net/xfrm/xfrm_policy.c:1495
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
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
In net/xfrm/xfrm_policy.c (ffffffff81a218c1)
Location: net/xfrm/xfrm_policy.c:1497
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xfrm_policy_insert_inexact_list(struct hlist_head *chain, struct xfrm_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0dce0)
Location: net/xfrm/xfrm_policy.c:1491
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81b0dce0-ffffffff81b0de95: xfrm_policy_insert_inexact_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xfrm_policy_insert_inexact_list(struct hlist_head *chain, struct xfrm_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1c140)
Location: net/xfrm/xfrm_policy.c:1501
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81b1c140-ffffffff81b1c2f5: xfrm_policy_insert_inexact_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xfrm_policy_insert_inexact_list(struct hlist_head *chain, struct xfrm_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b09e30)
Location: net/xfrm/xfrm_policy.c:1500
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81b09e30-ffffffff81b09fe9: xfrm_policy_insert_inexact_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xfrm_policy_insert_inexact_list(struct hlist_head *chain, struct xfrm_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bccc50)
Location: net/xfrm/xfrm_policy.c:1502
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81bccc50-ffffffff81bcce09: xfrm_policy_insert_inexact_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xfrm_policy_insert_inexact_list(struct hlist_head *chain, struct xfrm_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d629f0)
Location: net/xfrm/xfrm_policy.c:1502
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81d629f0-ffffffff81d62bed: xfrm_policy_insert_inexact_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xfrm_policy_insert_inexact_list(struct hlist_head *chain, struct xfrm_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f2d560)
Location: net/xfrm/xfrm_policy.c:1503
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81f2d560-ffffffff81f2d776: xfrm_policy_insert_inexact_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xfrm_policy_insert_inexact_list(struct hlist_head *chain, struct xfrm_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f8d230)
Location: net/xfrm/xfrm_policy.c:1503
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81f8d230-ffffffff81f8d446: xfrm_policy_insert_inexact_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xfrm_policy_insert_inexact_list(struct hlist_head *chain, struct xfrm_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205abc0)
Location: net/xfrm/xfrm_policy.c:1519
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff8205abc0-ffffffff8205add6: xfrm_policy_insert_inexact_list (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffff800010cdcffc)
Location: net/xfrm/xfrm_policy.c:1497
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
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
In net/xfrm/xfrm_policy.c (c0de7de0)
Location: net/xfrm/xfrm_policy.c:1497
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
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
In net/xfrm/xfrm_policy.c (c000000000dfd0cc)
Location: net/xfrm/xfrm_policy.c:1497
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
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
In net/xfrm/xfrm_policy.c (ffffffe00082c346)
Location: net/xfrm/xfrm_policy.c:1497
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
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
In net/xfrm/xfrm_policy.c (ffffffff819c0f51)
Location: net/xfrm/xfrm_policy.c:1497
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
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
In net/xfrm/xfrm_policy.c (ffffffff8197dd41)
Location: net/xfrm/xfrm_policy.c:1497
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
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
In net/xfrm/xfrm_policy.c (ffffffff81a2b9d1)
Location: net/xfrm/xfrm_policy.c:1497
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
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
In net/xfrm/xfrm_policy.c (ffffffff81a370a1)
Location: net/xfrm/xfrm_policy.c:1497
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
