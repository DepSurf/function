# Function: <code>cgroup_free_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81113150)
Location: kernel/cgroup.c:1124
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff81113150-ffffffff811131a4: cgroup_free_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111f328)
Location: kernel/cgroup.c:1166
Inline: True
Inline callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811276bd)
Location: kernel/cgroup.c:1169
Inline: True
Inline callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81127947)
Location: kernel/cgroup/cgroup.c:1062
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff811243a0-ffffffff811243cb: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81133d43)
Location: kernel/cgroup/cgroup.c:1231
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff81130500-ffffffff8113052b: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811423e4)
Location: kernel/cgroup/cgroup.c:1234
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff8113ebd0-ffffffff8113ebfa: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114de6c)
Location: kernel/cgroup/cgroup.c:1269
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff8114a5e0-ffffffff8114a60a: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81159c29)
Location: kernel/cgroup/cgroup.c:1310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81155d00-ffffffff81155d2c: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116589a)
Location: kernel/cgroup/cgroup.c:1310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81161960-ffffffff8116198c: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81176872)
Location: kernel/cgroup/cgroup.c:1302
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81172f40-ffffffff81172f50: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173562)
Location: kernel/cgroup/cgroup.c:1299
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff8116fc00-ffffffff8116fc10: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174147)
Location: kernel/cgroup/cgroup.c:1299
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81170830-ffffffff81170840: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119b1d7)
Location: kernel/cgroup/cgroup.c:1330
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81196d60-ffffffff81196d70: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cb36e)
Location: kernel/cgroup/cgroup.c:1333
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff811c6d20-ffffffff811c6d36: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120e7b8)
Location: kernel/cgroup/cgroup.c:1352
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff812098c0-ffffffff812098d6: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812241b8)
Location: kernel/cgroup/cgroup.c:1336
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff8121f010-ffffffff8121f026: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123be94)
Location: kernel/cgroup/cgroup.c:1316
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81236ca0-ffffffff81236ccd: cgroup_free_root (STB_GLOBAL)
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
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d7358)
Location: kernel/cgroup/cgroup.c:1310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffff8000101d2c10-ffff8000101d2c48: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0419ff4)
Location: kernel/cgroup/cgroup.c:1310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
c0415a70-c0415aa4: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000243a2c)
Location: kernel/cgroup/cgroup.c:1310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
c00000000023db00-c00000000023db54: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000150488)
Location: kernel/cgroup/cgroup.c:1310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffe00014c470-ffffffe00014c4ac: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115deba)
Location: kernel/cgroup/cgroup.c:1310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81159f80-ffffffff81159fac: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81151194)
Location: kernel/cgroup/cgroup.c:1310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff8114d270-ffffffff8114d29c: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115bc8a)
Location: kernel/cgroup/cgroup.c:1310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81157d50-ffffffff81157d7c: cgroup_free_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cgroup_free_root(struct cgroup_root *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81168d66)
Location: kernel/cgroup/cgroup.c:1310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81164da0-ffffffff81164dcc: cgroup_free_root (STB_GLOBAL)
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
