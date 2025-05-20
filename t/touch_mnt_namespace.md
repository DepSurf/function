# Function: <code>touch_mnt_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void touch_mnt_namespace(struct mnt_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122bc00)
Location: fs/namespace.c:791
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_pivot_root
```
**Symbols:**

```
ffffffff8122bc00-ffffffff8122bc3c: touch_mnt_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void touch_mnt_namespace(struct mnt_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81254370)
Location: fs/namespace.c:791
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff81254370-ffffffff812543ac: touch_mnt_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void touch_mnt_namespace(struct mnt_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812676a0)
Location: fs/namespace.c:792
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
ffffffff812676a0-ffffffff812676dc: touch_mnt_namespace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8127945b)
Location: fs/namespace.c:793
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
ffffffff81275e40-ffffffff81275e76: touch_mnt_namespace.part.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8129be9b)
Location: fs/namespace.c:860
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
ffffffff812981e0-ffffffff81298216: touch_mnt_namespace.part.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812c1fc5)
Location: fs/namespace.c:870
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
ffffffff812bdaa0-ffffffff812bdad6: touch_mnt_namespace.part.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812d7265)
Location: fs/namespace.c:782
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
ffffffff812d3110-ffffffff812d3146: touch_mnt_namespace.part.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812f56b6)
Location: fs/namespace.c:790
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
ffffffff812f0110-ffffffff812f0146: touch_mnt_namespace.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff81307236)
Location: fs/namespace.c:790
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
ffffffff81301cb0-ffffffff81301ce6: touch_mnt_namespace.part.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff81340a99)
Location: fs/namespace.c:806
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:shrink_submounts
  - fs/namespace.c:shrink_submounts
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:commit_tree
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff8133aac0-ffffffff8133aaf6: touch_mnt_namespace.part.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff8134cb29)
Location: fs/namespace.c:806
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:shrink_submounts
  - fs/namespace.c:shrink_submounts
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:commit_tree
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff81346700-ffffffff81346736: touch_mnt_namespace.part.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff81353703)
Location: fs/namespace.c:813
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:commit_tree
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff8134caa0-ffffffff8134cad6: touch_mnt_namespace.part.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff813a1b53)
Location: fs/namespace.c:822
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:commit_tree
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff8139a9a0-ffffffff8139a9d6: touch_mnt_namespace.part.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff81425552)
Location: fs/namespace.c:858
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:commit_tree
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff8141d740-ffffffff8141d784: touch_mnt_namespace.part.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff814b1cd2)
Location: fs/namespace.c:969
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:commit_tree
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff814a9b50-ffffffff814a9b94: touch_mnt_namespace.part.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff814e6d23)
Location: fs/namespace.c:878
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:commit_tree
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff814dea30-ffffffff814dea74: touch_mnt_namespace.part.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff8151ab63)
Location: fs/namespace.c:866
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:commit_tree
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
```
**Symbols:**

```
ffffffff81511660-ffffffff815116a4: touch_mnt_namespace.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffff8000103baab4)
Location: fs/namespace.c:790
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
ffff8000103b43f0-ffff8000103b443c: touch_mnt_namespace.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (c0598830)
Location: fs/namespace.c:790
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:set_mount_attributes
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:set_mount_attributes
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:do_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
c0593798-c05937f0: touch_mnt_namespace.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (c0000000004b8330)
Location: fs/namespace.c:790
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
c0000000004b06f0-c0000000004b074c: touch_mnt_namespace.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffe00027ceee)
Location: fs/namespace.c:790
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
ffffffe000277bfe-ffffffe000277c40: touch_mnt_namespace.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812ff816)
Location: fs/namespace.c:790
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
ffffffff812fa290-ffffffff812fa2c6: touch_mnt_namespace.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812f0436)
Location: fs/namespace.c:790
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
ffffffff812eaeb0-ffffffff812eaee6: touch_mnt_namespace.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812fd606)
Location: fs/namespace.c:790
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
ffffffff812f8080-ffffffff812f80b6: touch_mnt_namespace.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8130e964)
Location: fs/namespace.c:790
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:commit_tree
```
**Symbols:**

```
ffffffff81309ea0-ffffffff81309ed6: touch_mnt_namespace.part.0 (STB_LOCAL)
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
</ul>
