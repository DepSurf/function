# Function: <code>__attach_mnt</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81266fd0)
Location: fs/namespace.c:860
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff81266fd0-ffffffff81267042: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81274820)
Location: fs/namespace.c:861
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff81274820-ffffffff81274892: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81297150)
Location: fs/namespace.c:928
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff81297150-ffffffff812971c2: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bd390)
Location: fs/namespace.c:938
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff812bd390-ffffffff812bd402: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d26a0)
Location: fs/namespace.c:850
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff812d26a0-ffffffff812d2712: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ef780)
Location: fs/namespace.c:848
Inline: False
Direct callers:
  - fs/namespace.c:commit_tree
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff812ef780-ffffffff812ef7f2: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81301250)
Location: fs/namespace.c:848
Inline: False
Direct callers:
  - fs/namespace.c:commit_tree
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff81301250-ffffffff813012c2: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133a4c0)
Location: fs/namespace.c:864
Inline: True
Direct callers:
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff8133a4c0-ffffffff8133a532: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81346880)
Location: fs/namespace.c:864
Inline: True
Direct callers:
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff81346880-ffffffff813468f2: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134c4f0)
Location: fs/namespace.c:871
Inline: True
Direct callers:
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff8134c4f0-ffffffff8134c562: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8139ae22)
Location: fs/namespace.c:880
Inline: True
Direct callers:
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff8139a540-ffffffff8139a5d5: __attach_mnt (STB_LOCAL)
ffffffff81cc3e73-ffffffff81cc3e8f: __attach_mnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8141e082)
Location: fs/namespace.c:916
Inline: True
Direct callers:
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff8141d0f0-ffffffff8141d193: __attach_mnt (STB_LOCAL)
ffffffff81e76774-ffffffff81e76790: __attach_mnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff814aa792)
Location: fs/namespace.c:1027
Inline: True
Direct callers:
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff814a9410-ffffffff814a94b3: __attach_mnt (STB_LOCAL)
ffffffff82068bd5-ffffffff82068bf1: __attach_mnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:963
Inline: False
Direct callers:
  - fs/namespace.c:commit_tree
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff814de350-ffffffff814de3f3: __attach_mnt (STB_LOCAL)
ffffffff820e8513-ffffffff820e852f: __attach_mnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:951
Inline: False
Direct callers:
  - fs/namespace.c:commit_tree
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff81510dc0-ffffffff81510e63: __attach_mnt (STB_LOCAL)
ffffffff821c526d-ffffffff821c5289: __attach_mnt.cold (STB_LOCAL)
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
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b3af0)
Location: fs/namespace.c:848
Inline: False
Direct callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffff8000103b3af0-ffff8000103b3b78: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05926b0)
Location: fs/namespace.c:848
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
c05926b0-c059272c: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004af760)
Location: fs/namespace.c:848
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
c0000000004af760-c0000000004af7f0: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe0002771b4)
Location: fs/namespace.c:848
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:commit_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffe0002771b4-ffffffe000277232: __attach_mnt (STB_LOCAL)
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
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9830)
Location: fs/namespace.c:848
Inline: False
Direct callers:
  - fs/namespace.c:commit_tree
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff812f9830-ffffffff812f98a2: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ea450)
Location: fs/namespace.c:848
Inline: False
Direct callers:
  - fs/namespace.c:commit_tree
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff812ea450-ffffffff812ea4c2: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f7620)
Location: fs/namespace.c:848
Inline: False
Direct callers:
  - fs/namespace.c:commit_tree
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff812f7620-ffffffff812f7692: __attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __attach_mnt(struct mount *mnt, struct mount *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81308860)
Location: fs/namespace.c:848
Inline: False
Direct callers:
  - fs/namespace.c:commit_tree
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff81308860-ffffffff813088d2: __attach_mnt (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
