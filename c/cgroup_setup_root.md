# Function: <code>cgroup_setup_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, long unsigned int ss_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81117c00)
Location: kernel/cgroup.c:1959
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_init
```
**Symbols:**

```
ffffffff81117c00-ffffffff81117e71: cgroup_setup_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111f5a0)
Location: kernel/cgroup.c:1982
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff8111f5a0-ffffffff8111f822: cgroup_setup_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811279b0)
Location: kernel/cgroup.c:1990
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff811279b0-ffffffff81127c7f: cgroup_setup_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask, int ref_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81126940)
Location: kernel/cgroup/cgroup.c:1700
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff81126940-ffffffff81126c31: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask, int ref_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81132c40)
Location: kernel/cgroup/cgroup.c:1874
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff81132c40-ffffffff81132f4b: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask, int ref_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811412f0)
Location: kernel/cgroup/cgroup.c:1892
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff811412f0-ffffffff811415eb: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask, int ref_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114cda0)
Location: kernel/cgroup/cgroup.c:1930
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
**Symbols:**

```
ffffffff8114cda0-ffffffff8114d09b: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811589a0)
Location: kernel/cgroup/cgroup.c:1990
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff811589a0-ffffffff81158c90: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81164600)
Location: kernel/cgroup/cgroup.c:1990
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81164600-ffffffff811648f0: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175640)
Location: kernel/cgroup/cgroup.c:1927
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81175640-ffffffff8117597c: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811722f0)
Location: kernel/cgroup/cgroup.c:1924
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff811722f0-ffffffff81172610: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172e30)
Location: kernel/cgroup/cgroup.c:1931
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81172e30-ffffffff811731fb: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81199cb0)
Location: kernel/cgroup/cgroup.c:1985
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff81199cb0-ffffffff8119a115: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c9e50)
Location: kernel/cgroup/cgroup.c:1989
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff811c9e50-ffffffff811ca1ea: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120cff0)
Location: kernel/cgroup/cgroup.c:2046
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff8120cff0-ffffffff8120d387: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812229e0)
Location: kernel/cgroup/cgroup.c:2054
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff812229e0-ffffffff81222d7a: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123a6d0)
Location: kernel/cgroup/cgroup.c:2063
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
**Symbols:**

```
ffffffff8123a6d0-ffffffff8123aa61: cgroup_setup_root (STB_GLOBAL)
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
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d5f20)
Location: kernel/cgroup/cgroup.c:1990
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffff8000101d5f20-ffff8000101d6230: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0418b20)
Location: kernel/cgroup/cgroup.c:1990
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
c0418b20-c0418e84: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000241990)
Location: kernel/cgroup/cgroup.c:1990
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
c000000000241990-c000000000241d9c: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014f194)
Location: kernel/cgroup/cgroup.c:1990
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffe00014f194-ffffffe00014f47e: cgroup_setup_root (STB_GLOBAL)
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
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115cc20)
Location: kernel/cgroup/cgroup.c:1990
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff8115cc20-ffffffff8115cf10: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114ff10)
Location: kernel/cgroup/cgroup.c:1990
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff8114ff10-ffffffff811501fa: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a9f0)
Location: kernel/cgroup/cgroup.c:1990
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff8115a9f0-ffffffff8115ace0: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_setup_root(struct cgroup_root *root, u16 ss_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81167a50)
Location: kernel/cgroup/cgroup.c:1990
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81167a50-ffffffff81167d40: cgroup_setup_root (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int ss_mask</code> ➡️ <code>u16 ss_mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int ref_flags</code>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int ref_flags</code>
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
