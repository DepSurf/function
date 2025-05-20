# Function: <code>__mpol_dup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e22d0)
Location: mm/mempolicy.c:2088
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_set_shared_policy
```
**Symbols:**

```
ffffffff811e22d0-ffffffff811e23e7: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81200cc0)
Location: mm/mempolicy.c:2105
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff81200cc0-ffffffff81200dd6: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812126e0)
Location: mm/mempolicy.c:2099
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:SYSC_mbind
```
**Symbols:**

```
ffffffff812126e0-ffffffff812127ef: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121da10)
Location: mm/mempolicy.c:2004
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:SYSC_mbind
```
**Symbols:**

```
ffffffff8121da10-ffffffff8121dafa: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81238c60)
Location: mm/mempolicy.c:2066
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:SYSC_mbind
```
**Symbols:**

```
ffffffff81238c60-ffffffff81238d4a: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125c180)
Location: mm/mempolicy.c:2123
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff8125c180-ffffffff8125c26a: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81270a50)
Location: mm/mempolicy.c:2162
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81270a50-ffffffff81270b3a: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128c050)
Location: mm/mempolicy.c:2183
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff8128c050-ffffffff8128c142: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129bc20)
Location: mm/mempolicy.c:2222
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff8129bc20-ffffffff8129bd12: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cf820)
Location: mm/mempolicy.c:2322
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:vma_replace_policy
```
**Symbols:**

```
ffffffff812cf820-ffffffff812cf912: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812db2f0)
Location: mm/mempolicy.c:2297
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:vma_replace_policy
```
**Symbols:**

```
ffffffff812db2f0-ffffffff812db3e2: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e2b60)
Location: mm/mempolicy.c:2302
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff812e2b60-ffffffff812e2c52: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81329ee0)
Location: mm/mempolicy.c:2220
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff81329ee0-ffffffff81329fd2: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff813995b0)
Location: mm/mempolicy.c:2394
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff813995b0-ffffffff813996ae: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81419410)
Location: mm/mempolicy.c:2409
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff81419410-ffffffff8141950e: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144c8f0)
Location: mm/mempolicy.c:2420
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:vma_replace_policy
```
**Symbols:**

```
ffffffff8144c8f0-ffffffff8144c9ee: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81486270)
Location: mm/mempolicy.c:2322
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:sp_alloc
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff81486270-ffffffff8148636e: __mpol_dup (STB_GLOBAL)
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
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff80001033abc0)
Location: mm/mempolicy.c:2222
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffff80001033abc0-ffff80001033acf8: __mpol_dup (STB_GLOBAL)
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
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000415610)
Location: mm/mempolicy.c:2222
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
c000000000415610-c000000000415778: __mpol_dup (STB_GLOBAL)
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
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81294200)
Location: mm/mempolicy.c:2222
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81294200-ffffffff812942f2: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81285e10)
Location: mm/mempolicy.c:2222
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81285e10-ffffffff81285f02: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292010)
Location: mm/mempolicy.c:2222
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81292010-ffffffff81292102: __mpol_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mempolicy *__mpol_dup(struct mempolicy *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a1e20)
Location: mm/mempolicy.c:2222
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff812a1e20-ffffffff812a1f10: __mpol_dup (STB_GLOBAL)
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
