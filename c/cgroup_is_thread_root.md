# Function: <code>cgroup_is_thread_root</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112e1db)
Location: kernel/cgroup/cgroup.c:368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff8112e0d0-ffffffff8112e0fa: cgroup_is_thread_root.part.22 (STB_LOCAL)
ffffffff8112f920-ffffffff8112f94c: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113de00)
Location: kernel/cgroup/cgroup.c:371
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff8113de00-ffffffff8113de44: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811497f0)
Location: kernel/cgroup/cgroup.c:376
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff811497f0-ffffffff81149834: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81154e30)
Location: kernel/cgroup/cgroup.c:378
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff81154e30-ffffffff81154e74: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81160a60)
Location: kernel/cgroup/cgroup.c:378
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff81160a60-ffffffff81160aa4: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170fe8)
Location: kernel/cgroup/cgroup.c:371
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff811721d0-ffffffff81172214: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116db99)
Location: kernel/cgroup/cgroup.c:368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff8116ee20-ffffffff8116ee64: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116e829)
Location: kernel/cgroup/cgroup.c:368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff8116fa50-ffffffff8116fa94: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81194a1a)
Location: kernel/cgroup/cgroup.c:392
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff81195ec0-ffffffff81195f04: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c5485)
Location: kernel/cgroup/cgroup.c:393
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
```
**Symbols:**

```
ffffffff811c5d90-ffffffff811c5de8: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81207c35)
Location: kernel/cgroup/cgroup.c:398
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
```
**Symbols:**

```
ffffffff81208800-ffffffff81208858: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121d3c5)
Location: kernel/cgroup/cgroup.c:397
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81234f55)
Location: kernel/cgroup/cgroup.c:399
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
  - kernel/cgroup/cgroup.c:cgroup_is_valid_domain
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
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d1b68)
Location: kernel/cgroup/cgroup.c:378
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffff8000101d1b68-ffff8000101d1bd8: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0414b18)
Location: kernel/cgroup/cgroup.c:378
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
c0414b18-c0414b80: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023c630)
Location: kernel/cgroup/cgroup.c:378
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
c00000000023c630-c00000000023c6a4: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014b636)
Location: kernel/cgroup/cgroup.c:378
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffe00014b636-ffffffe00014b68c: cgroup_is_thread_root (STB_GLOBAL)
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
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81159080)
Location: kernel/cgroup/cgroup.c:378
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff81159080-ffffffff811590c4: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114c390)
Location: kernel/cgroup/cgroup.c:378
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff8114c390-ffffffff8114c3d4: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156e50)
Location: kernel/cgroup/cgroup.c:378
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff81156e50-ffffffff81156e94: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_thread_root(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81163e10)
Location: kernel/cgroup/cgroup.c:378
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff81163e10-ffffffff81163e54: cgroup_is_thread_root (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
