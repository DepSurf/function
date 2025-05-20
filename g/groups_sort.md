# Function: <code>groups_sort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810a431a)
Location: kernel/groups.c:104
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
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
In kernel/groups.c (ffffffff810a7a69)
Location: kernel/groups.c:104
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
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
In kernel/groups.c (ffffffff810adbd9)
Location: kernel/groups.c:80
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810aa7aa)
Location: kernel/groups.c:88
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b172b)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:SyS_setgroups
Direct callers:
  - kernel/uid16.c:SyS_setgroups16
```
**Symbols:**

```
ffffffff810b1490-ffffffff810b14b7: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b8613)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810b8290-ffffffff810b82b7: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c1698)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810c1370-ffffffff810c1397: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c778d)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810c7460-ffffffff810c7487: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d085d)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810d0530-ffffffff810d0557: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810da75a)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810da370-ffffffff810da397: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d5eba)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810d5ad0-ffffffff810d5af7: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d7ba6)
Location: kernel/groups.c:84
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810d7790-ffffffff810d77b7: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810eb456)
Location: kernel/groups.c:84
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810eb040-ffffffff810eb067: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81106386)
Location: kernel/groups.c:84
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff81105ef0-ffffffff81105f26: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff8112bff4)
Location: kernel/groups.c:84
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff8112baa0-ffffffff8112bad6: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81138e54)
Location: kernel/groups.c:84
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff81138900-ffffffff81138936: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81143b91)
Location: kernel/groups.c:84
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__do_sys_setgroups16
```
**Symbols:**

```
ffffffff81143570-ffffffff811435a6: groups_sort (STB_GLOBAL)
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
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffff800010131314)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__arm64_sys_setgroups
Direct callers:
  - kernel/uid16.c:__arm64_sys_setgroups16
```
**Symbols:**

```
ffff800010130ca0-ffff800010130ce0: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c03807e0)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
Direct callers:
  - kernel/uid16.c:__se_sys_setgroups16
```
**Symbols:**

```
c038049c-c03804dc: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c00000000017a964)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
```
**Symbols:**

```
c00000000017a3f0-c00000000017a43c: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffe0000e42da)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
```
**Symbols:**

```
ffffffe0000e4010-ffffffe0000e404a: groups_sort (STB_GLOBAL)
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
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810cabdd)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810ca8b0-ffffffff810ca8d7: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b93ed)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810b90c0-ffffffff810b90e7: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810ca10d)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810c9de0-ffffffff810c9e07: groups_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void groups_sort(struct group_info *group_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d265d)
Location: kernel/groups.c:89
Inline: True
Inline callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810d2330-ffffffff810d2357: groups_sort (STB_GLOBAL)
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
