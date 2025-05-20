# Function: <code>mpol_new</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e06b0)
Location: mm/mempolicy.c:253
Inline: True
Direct callers:
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_parse_str
```
**Symbols:**

```
ffffffff811e06b0-ffffffff811e07ba: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811fe900)
Location: mm/mempolicy.c:252
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff811fe900-ffffffff811fea09: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8120fee0)
Location: mm/mempolicy.c:252
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff8120fee0-ffffffff81210007: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121b360)
Location: mm/mempolicy.c:240
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff8121b360-ffffffff8121b487: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81236580)
Location: mm/mempolicy.c:242
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81236580-ffffffff812366a7: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81259550)
Location: mm/mempolicy.c:242
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81259550-ffffffff81259678: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126d9d0)
Location: mm/mempolicy.c:242
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff8126d9d0-ffffffff8126daf8: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81288ee0)
Location: mm/mempolicy.c:242
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81288ee0-ffffffff8128900b: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81298a50)
Location: mm/mempolicy.c:242
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81298a50-ffffffff81298b7b: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cc5f0)
Location: mm/mempolicy.c:268
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff812cc5f0-ffffffff812cc71b: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d7e80)
Location: mm/mempolicy.c:268
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff812d7e80-ffffffff812d7fab: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812df940)
Location: mm/mempolicy.c:268
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff812df940-ffffffff812dfa6b: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81326e30)
Location: mm/mempolicy.c:258
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81326e30-ffffffff81326f57: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81395c60)
Location: mm/mempolicy.c:261
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81395c60-ffffffff81395dce: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814156a0)
Location: mm/mempolicy.c:261
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff814156a0-ffffffff8141580e: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81448c80)
Location: mm/mempolicy.c:261
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81448c80-ffffffff81448dee: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81482550)
Location: mm/mempolicy.c:266
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81482550-ffffffff81482656: mpol_new (STB_LOCAL)
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
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff800010337410)
Location: mm/mempolicy.c:242
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffff800010337410-ffff800010337514: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000412170)
Location: mm/mempolicy.c:242
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
c000000000412170-c000000000412330: mpol_new (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81291030)
Location: mm/mempolicy.c:242
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81291030-ffffffff8129115b: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81282cb0)
Location: mm/mempolicy.c:242
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81282cb0-ffffffff81282ddb: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128ee40)
Location: mm/mempolicy.c:242
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff8128ee40-ffffffff8128ef6b: mpol_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *mpol_new(short unsigned int mode, short unsigned int flags, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129ed40)
Location: mm/mempolicy.c:242
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff8129ed40-ffffffff8129ee6b: mpol_new (STB_LOCAL)
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
