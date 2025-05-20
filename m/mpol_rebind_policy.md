# Function: <code>mpol_rebind_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask, enum mpol_rebind_step step);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e05e0)
Location: mm/mempolicy.c:399
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_task
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:__mpol_dup
```
**Symbols:**

```
ffffffff811e05e0-ffffffff811e0641: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask, enum mpol_rebind_step step);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811fea10)
Location: mm/mempolicy.c:396
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff811fea10-ffffffff811fea74: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask, enum mpol_rebind_step step);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8120f470)
Location: mm/mempolicy.c:398
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff8120f470-ffffffff8120f500: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121c480)
Location: mm/mempolicy.c:347
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff8121c480-ffffffff8121c4d1: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81237630)
Location: mm/mempolicy.c:349
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff81237630-ffffffff81237687: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81259d60)
Location: mm/mempolicy.c:349
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff81259d60-ffffffff81259db6: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126dd70)
Location: mm/mempolicy.c:349
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff8126dd70-ffffffff8126ddc6: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81289100)
Location: mm/mempolicy.c:349
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff81289100-ffffffff81289160: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81298c90)
Location: mm/mempolicy.c:349
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff81298c90-ffffffff81298cf0: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812ce638)
Location: mm/mempolicy.c:375
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_mm
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff812cc9e0-ffffffff812cca3e: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d8380)
Location: mm/mempolicy.c:375
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff812d8380-ffffffff812d83de: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dfd20)
Location: mm/mempolicy.c:375
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff812dfd20-ffffffff812dfd7e: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff813280c2)
Location: mm/mempolicy.c:348
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
Direct callers:
  - mm/mempolicy.c:__mpol_dup
```
**Symbols:**

```
ffffffff81326f60-ffffffff81326fd3: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81395dd0)
Location: mm/mempolicy.c:352
Inline: True
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff81395dd0-ffffffff81395e6a: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81416d27)
Location: mm/mempolicy.c:352
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_task
  - mm/mempolicy.c:mpol_rebind_task
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
```
**Symbols:**

```
ffffffff81415820-ffffffff814158ba: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144a267)
Location: mm/mempolicy.c:352
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_task
  - mm/mempolicy.c:mpol_rebind_task
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
```
**Symbols:**

```
ffffffff81448e00-ffffffff81448e9a: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81483cf7)
Location: mm/mempolicy.c:355
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_task
  - mm/mempolicy.c:mpol_rebind_task
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
```
**Symbols:**

```
ffffffff814827d0-ffffffff8148286a: mpol_rebind_policy (STB_LOCAL)
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
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff800010337518)
Location: mm/mempolicy.c:349
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffff800010337518-ffff800010337588: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000412f80)
Location: mm/mempolicy.c:349
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
c000000000412f80-c000000000413048: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81291270)
Location: mm/mempolicy.c:349
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff81291270-ffffffff812912d0: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81282ef0)
Location: mm/mempolicy.c:349
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff81282ef0-ffffffff81282f50: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128f080)
Location: mm/mempolicy.c:349
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff8128f080-ffffffff8128f0e0: mpol_rebind_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mpol_rebind_policy(struct mempolicy *pol, const nodemask_t *newmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129ef80)
Location: mm/mempolicy.c:349
Inline: False
Direct callers:
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
**Symbols:**

```
ffffffff8129ef80-ffffffff8129efe0: mpol_rebind_policy (STB_LOCAL)
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
<b>Param removed. </b>
<code>enum mpol_rebind_step step</code>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
