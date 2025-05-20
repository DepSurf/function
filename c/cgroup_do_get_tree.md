# Function: <code>cgroup_do_get_tree</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81155e90)
Location: kernel/cgroup/cgroup.c:2091
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81155e90-ffffffff81155fcd: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81161af0)
Location: kernel/cgroup/cgroup.c:2091
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81161af0-ffffffff81161c30: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173090)
Location: kernel/cgroup/cgroup.c:2025
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81173090-ffffffff811731d0: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116fd90)
Location: kernel/cgroup/cgroup.c:2021
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff8116fd90-ffffffff8116fed9: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811709c0)
Location: kernel/cgroup/cgroup.c:2034
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff811709c0-ffffffff81170b09: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2088
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81cb2efb-ffffffff81cb2f0f: cgroup_do_get_tree.cold (STB_LOCAL)
ffffffff81196f50-ffffffff8119710b: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2092
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81e63cdf-ffffffff81e63cf3: cgroup_do_get_tree.cold (STB_LOCAL)
ffffffff811c6f50-ffffffff811c7121: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2149
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff8205c175-ffffffff8205c189: cgroup_do_get_tree.cold (STB_LOCAL)
ffffffff81209b50-ffffffff81209d21: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2157
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff820da96b-ffffffff820da97f: cgroup_do_get_tree.cold (STB_LOCAL)
ffffffff8121f2c0-ffffffff8121f491: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:2166
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff821b65e9-ffffffff821b65fd: cgroup_do_get_tree.cold (STB_LOCAL)
ffffffff81236f80-ffffffff81237155: cgroup_do_get_tree (STB_GLOBAL)
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
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d2df8)
Location: kernel/cgroup/cgroup.c:2091
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffff8000101d2df8-ffff8000101d2f58: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0415c34)
Location: kernel/cgroup/cgroup.c:2091
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
c0415c34-c0415dc0: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023ddb0)
Location: kernel/cgroup/cgroup.c:2091
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
c00000000023ddb0-c00000000023e024: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014c64e)
Location: kernel/cgroup/cgroup.c:2091
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffe00014c64e-ffffffe00014c7f8: cgroup_do_get_tree (STB_GLOBAL)
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
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a110)
Location: kernel/cgroup/cgroup.c:2091
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff8115a110-ffffffff8115a250: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114d400)
Location: kernel/cgroup/cgroup.c:2091
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff8114d400-ffffffff8114d53a: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81157ee0)
Location: kernel/cgroup/cgroup.c:2091
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81157ee0-ffffffff81158020: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_do_get_tree(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81164f40)
Location: kernel/cgroup/cgroup.c:2091
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81164f40-ffffffff81165080: cgroup_do_get_tree (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
