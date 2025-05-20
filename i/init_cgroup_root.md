# Function: <code>init_cgroup_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void init_cgroup_root(struct cgroup_root *root, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81113810)
Location: kernel/cgroup.c:1938
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_init_early
```
**Symbols:**

```
ffffffff81113810-ffffffff811138b0: init_cgroup_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void init_cgroup_root(struct cgroup_root *root, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111abf0)
Location: kernel/cgroup.c:1962
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_init_early
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff8111abf0-ffffffff8111ac89: init_cgroup_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void init_cgroup_root(struct cgroup_root *root, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81122750)
Location: kernel/cgroup.c:1970
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_init_early
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff81122750-ffffffff811227e9: init_cgroup_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_cgroup_root(struct cgroup_root *root, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81124470)
Location: kernel/cgroup/cgroup.c:1681
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff81124470-ffffffff8112451c: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_cgroup_root(struct cgroup_root *root, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811305d0)
Location: kernel/cgroup/cgroup.c:1855
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff811305d0-ffffffff81130686: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void init_cgroup_root(struct cgroup_root *root, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113eca0)
Location: kernel/cgroup/cgroup.c:1873
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff8113eca0-ffffffff8113ed5e: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void init_cgroup_root(struct cgroup_root *root, struct cgroup_sb_opts *opts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114a6b0)
Location: kernel/cgroup/cgroup.c:1911
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff8114a6b0-ffffffff8114a76e: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81155dd0)
Location: kernel/cgroup/cgroup.c:1970
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81155dd0-ffffffff81155e8f: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81161a30)
Location: kernel/cgroup/cgroup.c:1970
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81161a30-ffffffff81161aef: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172ff0)
Location: kernel/cgroup/cgroup.c:1908
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81172ff0-ffffffff8117308d: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1905
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81be4711-ffffffff81be4729: init_cgroup_root.cold (STB_LOCAL)
ffffffff8116fcb0-ffffffff8116fd8d: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1912
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81bd653b-ffffffff81bd6553: init_cgroup_root.cold (STB_LOCAL)
ffffffff811708e0-ffffffff811709bd: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1966
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81cb2ece-ffffffff81cb2efb: init_cgroup_root.cold (STB_LOCAL)
ffffffff81196e60-ffffffff81196f4b: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1970
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81e63cb2-ffffffff81e63cdf: init_cgroup_root.cold (STB_LOCAL)
ffffffff811c6e60-ffffffff811c6f4e: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2026
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff8205c160-ffffffff8205c175: init_cgroup_root.cold (STB_LOCAL)
ffffffff81209a30-ffffffff81209b31: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2034
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff820da956-ffffffff820da96b: init_cgroup_root.cold (STB_LOCAL)
ffffffff8121f180-ffffffff8121f2b0: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2043
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff821b65d4-ffffffff821b65e9: init_cgroup_root.cold (STB_LOCAL)
ffffffff81236e40-ffffffff81236f67: init_cgroup_root (STB_GLOBAL)
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
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d2d18)
Location: kernel/cgroup/cgroup.c:1970
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffff8000101d2d18-ffff8000101d2df4: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0415b78)
Location: kernel/cgroup/cgroup.c:1970
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
c0415b78-c0415c34: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023dcc0)
Location: kernel/cgroup/cgroup.c:1970
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
c00000000023dcc0-c00000000023dda8: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014c596)
Location: kernel/cgroup/cgroup.c:1970
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffe00014c596-ffffffe00014c64e: init_cgroup_root (STB_GLOBAL)
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
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a050)
Location: kernel/cgroup/cgroup.c:1970
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff8115a050-ffffffff8115a10f: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114d340)
Location: kernel/cgroup/cgroup.c:1970
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff8114d340-ffffffff8114d3ff: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81157e20)
Location: kernel/cgroup/cgroup.c:1970
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81157e20-ffffffff81157edf: init_cgroup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void init_cgroup_root(struct cgroup_fs_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81164e80)
Location: kernel/cgroup/cgroup.c:1970
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init_early
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81164e80-ffffffff81164f3f: init_cgroup_root (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cgroup_fs_context *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cgroup_root *root</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cgroup_sb_opts *opts</code>
</li>
</ul>
</details>
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
