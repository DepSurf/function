# Function: <code>dissolve_on_fput</code>

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
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f2ac0)
Location: fs/namespace.c:1839
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff812f2ac0-ffffffff812f2b41: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81304680)
Location: fs/namespace.c:1842
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff81304680-ffffffff81304701: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133e260)
Location: fs/namespace.c:1897
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff8133e260-ffffffff8133e2e1: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134a2c0)
Location: fs/namespace.c:1903
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff8134a2c0-ffffffff8134a341: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81350cb0)
Location: fs/namespace.c:1918
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__do_sys_open_tree
```
**Symbols:**

```
ffffffff81350cb0-ffffffff81350d31: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139f070)
Location: fs/namespace.c:1919
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:__do_sys_open_tree
```
**Symbols:**

```
ffffffff8139f070-ffffffff8139f0f1: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81422350)
Location: fs/namespace.c:1960
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff81422350-ffffffff814223f2: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814ae9a0)
Location: fs/namespace.c:2065
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff814ae9a0-ffffffff814aea42: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e3900)
Location: fs/namespace.c:2052
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff814e3900-ffffffff814e39a2: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81517650)
Location: fs/namespace.c:2054
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff81517650-ffffffff815176f2: dissolve_on_fput (STB_GLOBAL)
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
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b7fe0)
Location: fs/namespace.c:1842
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:__arm64_sys_open_tree
```
**Symbols:**

```
ffff8000103b7fe0-ffff8000103b80f8: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0596134)
Location: fs/namespace.c:1842
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:__se_sys_open_tree
```
**Symbols:**

```
c0596134-c05961e4: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b4da0)
Location: fs/namespace.c:1842
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:__se_sys_open_tree
```
**Symbols:**

```
c0000000004b4da0-c0000000004b4f10: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027a928)
Location: fs/namespace.c:1842
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:__se_sys_open_tree
```
**Symbols:**

```
ffffffe00027a928-ffffffe00027aa06: dissolve_on_fput (STB_GLOBAL)
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
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fcc60)
Location: fs/namespace.c:1842
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff812fcc60-ffffffff812fcce1: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ed880)
Location: fs/namespace.c:1842
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff812ed880-ffffffff812ed901: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812faa50)
Location: fs/namespace.c:1842
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff812faa50-ffffffff812faad1: dissolve_on_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130bd80)
Location: fs/namespace.c:1842
Inline: False
Direct callers:
  - fs/file_table.c:__fput
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff8130bd80-ffffffff8130be12: dissolve_on_fput (STB_GLOBAL)
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
