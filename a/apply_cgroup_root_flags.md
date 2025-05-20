# Function: <code>apply_cgroup_root_flags</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81122400)
Location: kernel/cgroup/cgroup.c:1572
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_remount
```
**Symbols:**

```
ffffffff81122400-ffffffff81122441: apply_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112dda0)
Location: kernel/cgroup/cgroup.c:1743
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_remount
```
**Symbols:**

```
ffffffff8112dda0-ffffffff8112dde1: apply_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113c5c0)
Location: kernel/cgroup/cgroup.c:1759
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_remount
```
**Symbols:**

```
ffffffff8113c5c0-ffffffff8113c601: apply_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81147c80)
Location: kernel/cgroup/cgroup.c:1797
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_remount
```
**Symbols:**

```
ffffffff81147c80-ffffffff81147cc1: apply_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81153000)
Location: kernel/cgroup/cgroup.c:1854
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff81153000-ffffffff81153050: apply_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115ec50)
Location: kernel/cgroup/cgroup.c:1854
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff8115ec50-ffffffff8115eca0: apply_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117321f)
Location: kernel/cgroup/cgroup.c:1844
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff8116f000-ffffffff8116f043: apply_cgroup_root_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116ff27)
Location: kernel/cgroup/cgroup.c:1841
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff8116ba30-ffffffff8116ba73: apply_cgroup_root_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170b57)
Location: kernel/cgroup/cgroup.c:1848
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff8116c4e0-ffffffff8116c523: apply_cgroup_root_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119716c)
Location: kernel/cgroup/cgroup.c:1902
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff81192150-ffffffff81192193: apply_cgroup_root_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c719d)
Location: kernel/cgroup/cgroup.c:1906
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff811c21f0-ffffffff811c223d: apply_cgroup_root_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81209dad)
Location: kernel/cgroup/cgroup.c:1957
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff81206820-ffffffff812068d1: apply_cgroup_root_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121f51d)
Location: kernel/cgroup/cgroup.c:1965
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff8121c230-ffffffff8121c2e1: apply_cgroup_root_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812371dd)
Location: kernel/cgroup/cgroup.c:1967
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff81233f60-ffffffff8123402e: apply_cgroup_root_flags.part.0 (STB_LOCAL)
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
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101cf6d8)
Location: kernel/cgroup/cgroup.c:1854
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffff8000101cf6d8-ffff8000101cf758: apply_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0413098)
Location: kernel/cgroup/cgroup.c:1854
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
c0413098-c0413100: apply_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000239b50)
Location: kernel/cgroup/cgroup.c:1854
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
c000000000239b50-c000000000239bd0: apply_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000149c66)
Location: kernel/cgroup/cgroup.c:1854
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffe000149c66-ffffffe000149cdc: apply_cgroup_root_flags (STB_LOCAL)
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
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81157270)
Location: kernel/cgroup/cgroup.c:1854
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff81157270-ffffffff811572c0: apply_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114a590)
Location: kernel/cgroup/cgroup.c:1854
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff8114a590-ffffffff8114a5e0: apply_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81155040)
Location: kernel/cgroup/cgroup.c:1854
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff81155040-ffffffff81155090: apply_cgroup_root_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void apply_cgroup_root_flags(unsigned int root_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81162560)
Location: kernel/cgroup/cgroup.c:1854
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
```
**Symbols:**

```
ffffffff81162560-ffffffff811625b0: apply_cgroup_root_flags (STB_LOCAL)
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
