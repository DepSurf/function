# Function: <code>attach_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122dd10)
Location: fs/namespace.c:862
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
```
**Symbols:**

```
ffffffff8122dd10-ffffffff8122dda6: attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81256500)
Location: fs/namespace.c:862
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff81256500-ffffffff81256596: attach_mnt (STB_LOCAL)
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
In fs/namespace.c (ffffffff8126bc26)
Location: fs/namespace.c:870
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
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
In fs/namespace.c (ffffffff812793ff)
Location: fs/namespace.c:871
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129be3f)
Location: fs/namespace.c:938
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c1f6e)
Location: fs/namespace.c:948
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d720e)
Location: fs/namespace.c:860
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ef800)
Location: fs/namespace.c:858
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff812ef800-ffffffff812ef858: attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813012d0)
Location: fs/namespace.c:858
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff813012d0-ffffffff81301328: attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133df5e)
Location: fs/namespace.c:874
Inline: True
Inline callers:
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff8133adc0-ffffffff8133ae7a: attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81349fbe)
Location: fs/namespace.c:874
Inline: True
Inline callers:
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff81346ab0-ffffffff81346b6a: attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813509ae)
Location: fs/namespace.c:881
Inline: True
Inline callers:
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff8134ce40-ffffffff8134cefa: attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8139ed6e)
Location: fs/namespace.c:890
Inline: True
Inline callers:
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff8139adb0-ffffffff8139ae89: attach_mnt (STB_LOCAL)
ffffffff81cc3f03-ffffffff81cc3f1f: attach_mnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8142202d)
Location: fs/namespace.c:926
Inline: True
Inline callers:
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff8141e010-ffffffff8141e0f7: attach_mnt (STB_LOCAL)
ffffffff81e76851-ffffffff81e7686d: attach_mnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff814ae64d)
Location: fs/namespace.c:1037
Inline: True
Inline callers:
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
```
**Symbols:**

```
ffffffff814aa720-ffffffff814aa807: attach_mnt (STB_LOCAL)
ffffffff82068c52-ffffffff82068c6e: attach_mnt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp, bool beneath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e2d40)
Location: fs/namespace.c:992
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff814e2d40-ffffffff814e2e1f: attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp, bool beneath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81516b30)
Location: fs/namespace.c:980
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff81516b30-ffffffff81516c0f: attach_mnt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103baa54)
Location: fs/namespace.c:858
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05987a4)
Location: fs/namespace.c:858
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b82e0)
Location: fs/namespace.c:858
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027ce92)
Location: fs/namespace.c:858
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
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
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f98b0)
Location: fs/namespace.c:858
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff812f98b0-ffffffff812f9908: attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ea4d0)
Location: fs/namespace.c:858
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff812ea4d0-ffffffff812ea528: attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f76a0)
Location: fs/namespace.c:858
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff812f76a0-ffffffff812f76f8: attach_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void attach_mnt(struct mount *mnt, struct mount *parent, struct mountpoint *mp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813088e0)
Location: fs/namespace.c:858
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:copy_tree
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff813088e0-ffffffff81308938: attach_mnt (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool beneath</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
