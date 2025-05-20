# Function: <code>may_mount</code>

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
In fs/namespace.c (ffffffff8122e2a2)
Location: fs/namespace.c:1583
Inline: True
Inline callers:
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_pivot_root
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
In fs/namespace.c (ffffffff812584f8)
Location: fs/namespace.c:1584
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_oldumount
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
In fs/namespace.c (ffffffff8126b988)
Location: fs/namespace.c:1663
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_oldumount
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
In fs/namespace.c (ffffffff8127915a)
Location: fs/namespace.c:1605
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_oldumount
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
In fs/namespace.c (ffffffff8129bb9a)
Location: fs/namespace.c:1670
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_oldumount
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
In fs/namespace.c (ffffffff812c1cfc)
Location: fs/namespace.c:1696
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff812d6f9c)
Location: fs/namespace.c:1614
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f53fc)
Location: fs/namespace.c:1649
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81306f7c)
Location: fs/namespace.c:1649
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81340755)
Location: fs/namespace.c:1699
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134c7e5)
Location: fs/namespace.c:1702
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:path_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134f417)
Location: fs/namespace.c:1713
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:path_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139d6f7)
Location: fs/namespace.c:1722
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:path_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool may_mount();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814206a6)
Location: fs/namespace.c:1763
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:path_umount
Direct callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
**Symbols:**

```
ffffffff81421b20-ffffffff81421b55: may_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool may_mount();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814acc41)
Location: fs/namespace.c:1868
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:path_umount
Direct callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
**Symbols:**

```
ffffffff814ae0d0-ffffffff814ae105: may_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool may_mount();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e192e)
Location: fs/namespace.c:1842
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:path_umount
Direct callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
**Symbols:**

```
ffffffff814e3070-ffffffff814e30a5: may_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool may_mount();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff815159fe)
Location: fs/namespace.c:1844
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:path_umount
Direct callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
**Symbols:**

```
ffffffff81516dc0-ffffffff81516df5: may_mount (STB_GLOBAL)
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
In fs/namespace.c (ffff8000103ba744)
Location: fs/namespace.c:1649
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_move_mount
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (c0598510)
Location: fs/namespace.c:1649
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (c0000000004b7f78)
Location: fs/namespace.c:1649
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffe00027cc1e)
Location: fs/namespace.c:1649
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:ksys_umount
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ff55c)
Location: fs/namespace.c:1649
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f017c)
Location: fs/namespace.c:1649
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fd34c)
Location: fs/namespace.c:1649
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130e6ac)
Location: fs/namespace.c:1649
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
