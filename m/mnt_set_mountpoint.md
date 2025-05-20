# Function: <code>mnt_set_mountpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122dc90)
Location: fs/namespace.c:847
Inline: False
Direct callers:
  - fs/namespace.c:attach_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffff8122dc90-ffffffff8122dd0e: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81256480)
Location: fs/namespace.c:847
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff81256480-ffffffff812564fe: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812697b0)
Location: fs/namespace.c:848
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff812697b0-ffffffff8126982e: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81276f50)
Location: fs/namespace.c:849
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff81276f50-ffffffff81276fce: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81299990)
Location: fs/namespace.c:916
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff81299990-ffffffff81299a0e: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bf830)
Location: fs/namespace.c:926
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff812bf830-ffffffff812bf8ae: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d4a30)
Location: fs/namespace.c:838
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff812d4a30-ffffffff812d4aae: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f3830)
Location: fs/namespace.c:836
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff812f1f30-ffffffff812f1f83: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813053f0)
Location: fs/namespace.c:836
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff81303af0-ffffffff81303b43: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133ecf0)
Location: fs/namespace.c:852
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff8133d8f0-ffffffff8133d943: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134ad50)
Location: fs/namespace.c:852
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff81349850-ffffffff813498a3: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81351600)
Location: fs/namespace.c:859
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff81350230-ffffffff81350283: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139f970)
Location: fs/namespace.c:868
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff8139e5f0-ffffffff8139e643: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81422f0d)
Location: fs/namespace.c:904
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff814217c0-ffffffff81421821: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814af62d)
Location: fs/namespace.c:1015
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff814add20-ffffffff814add81: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e46ae)
Location: fs/namespace.c:924
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_mnt
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff814e2be0-ffffffff814e2c41: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff815183ee)
Location: fs/namespace.c:912
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_mnt
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff815169d0-ffffffff81516a31: mnt_set_mountpoint (STB_GLOBAL)
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
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b7138)
Location: fs/namespace.c:836
Inline: False
Direct callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffff8000103b7138-ffff8000103b71c0: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05957f4)
Location: fs/namespace.c:836
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
c05957f4-c0595864: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b3b90)
Location: fs/namespace.c:836
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
c0000000004b3b90-c0000000004b3c48: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000279d44)
Location: fs/namespace.c:836
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffe000279d44-ffffffe000279dc4: mnt_set_mountpoint (STB_GLOBAL)
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
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fd9d0)
Location: fs/namespace.c:836
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff812fc0d0-ffffffff812fc123: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ee5f0)
Location: fs/namespace.c:836
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff812eccf0-ffffffff812ecd43: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fb7c0)
Location: fs/namespace.c:836
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff812f9ec0-ffffffff812f9f13: mnt_set_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mnt_set_mountpoint(struct mount *mnt, struct mountpoint *mp, struct mount *child_mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130cafd)
Location: fs/namespace.c:836
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_mnt
```
**Symbols:**

```
ffffffff8130b210-ffffffff8130b263: mnt_set_mountpoint (STB_GLOBAL)
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
