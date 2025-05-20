# Function: <code>xfrm_policy_inexact_insert</code>

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
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81980a70)
Location: net/xfrm/xfrm_policy.c:1166
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff81980a70-ffffffff81980d20: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:1170
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff819ea7d0-ffffffff819eaac1: xfrm_policy_inexact_insert (STB_LOCAL)
ffffffff819ed854-ffffffff819ed88d: xfrm_policy_inexact_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a21820)
Location: net/xfrm/xfrm_policy.c:1172
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff81a21820-ffffffff81a21ac1: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b13330)
Location: net/xfrm/xfrm_policy.c:1175
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff81b13330-ffffffff81b133f0: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b21750)
Location: net/xfrm/xfrm_policy.c:1185
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff81b21750-ffffffff81b21810: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0f370)
Location: net/xfrm/xfrm_policy.c:1184
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff81b0f370-ffffffff81b0f430: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd2780)
Location: net/xfrm/xfrm_policy.c:1186
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff81bd2780-ffffffff81bd2856: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d69470)
Location: net/xfrm/xfrm_policy.c:1186
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff81d69470-ffffffff81d6959b: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f34760)
Location: net/xfrm/xfrm_policy.c:1187
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff81f34760-ffffffff81f3488b: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f94380)
Location: net/xfrm/xfrm_policy.c:1187
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff81f94380-ffffffff81f944ab: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff82061770)
Location: net/xfrm/xfrm_policy.c:1202
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff82061770-ffffffff8206189b: xfrm_policy_inexact_insert (STB_LOCAL)
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
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cdcf88)
Location: net/xfrm/xfrm_policy.c:1172
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffff800010cdcf88-ffff800010cdd260: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de7d6c)
Location: net/xfrm/xfrm_policy.c:1172
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
c0de7d6c-c0de8088: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000dfd040)
Location: net/xfrm/xfrm_policy.c:1172
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
c000000000dfd040-c000000000dfd37c: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082c2e8)
Location: net/xfrm/xfrm_policy.c:1172
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffe00082c2e8-ffffffe00082c4ce: xfrm_policy_inexact_insert (STB_LOCAL)
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
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819c0eb0)
Location: net/xfrm/xfrm_policy.c:1172
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff819c0eb0-ffffffff819c1151: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197dca0)
Location: net/xfrm/xfrm_policy.c:1172
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff8197dca0-ffffffff8197df41: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a2b930)
Location: net/xfrm/xfrm_policy.c:1172
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff81a2b930-ffffffff81a2bbd1: xfrm_policy_inexact_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xfrm_policy *xfrm_policy_inexact_insert(struct xfrm_policy *policy, u8 dir, int excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a37000)
Location: net/xfrm/xfrm_policy.c:1172
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
**Symbols:**

```
ffffffff81a37000-ffffffff81a372a1: xfrm_policy_inexact_insert (STB_LOCAL)
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
