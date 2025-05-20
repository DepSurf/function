# Function: <code>mount_too_revealing</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81257646)
Location: fs/namespace.c:3263
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff8126aad6)
Location: fs/namespace.c:3407
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff81278287)
Location: fs/namespace.c:3343
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff8129b0c5)
Location: fs/namespace.c:3416
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812c0dab)
Location: fs/namespace.c:3453
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812d6016)
Location: fs/namespace.c:3425
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f0240)
Location: fs/namespace.c:3883
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812f0240-ffffffff812f03f0: mount_too_revealing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81301de0)
Location: fs/namespace.c:3916
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff81301de0-ffffffff81301f90: mount_too_revealing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133b990)
Location: fs/namespace.c:3987
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount_fc
```
**Symbols:**

```
ffffffff8133b990-ffffffff8133ba10: mount_too_revealing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81347830)
Location: fs/namespace.c:4009
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount_fc
```
**Symbols:**

```
ffffffff81347830-ffffffff813478b0: mount_too_revealing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134e440)
Location: fs/namespace.c:4415
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff8134e440-ffffffff8134e61d: mount_too_revealing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8139c493)
Location: fs/namespace.c:4493
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff8139c440-ffffffff8139c628: mount_too_revealing (STB_LOCAL)
ffffffff81cc3f34-ffffffff81cc3f49: mount_too_revealing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8141d7e2)
Location: fs/namespace.c:4586
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff8141d790-ffffffff8141d975: mount_too_revealing (STB_LOCAL)
ffffffff81e767f0-ffffffff81e76804: mount_too_revealing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff814a9c02)
Location: fs/namespace.c:4695
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff814a9bb0-ffffffff814a9d95: mount_too_revealing (STB_LOCAL)
ffffffff82068bf1-ffffffff82068c05: mount_too_revealing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff814deae1)
Location: fs/namespace.c:4886
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff814dea90-ffffffff814dec66: mount_too_revealing (STB_LOCAL)
ffffffff820e852f-ffffffff820e8543: mount_too_revealing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8151170c)
Location: fs/namespace.c:5336
Inline: True
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff815116c0-ffffffff815118a8: mount_too_revealing (STB_LOCAL)
ffffffff821c5289-ffffffff821c529d: mount_too_revealing.cold (STB_LOCAL)
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
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b4530)
Location: fs/namespace.c:3916
Inline: True
Direct callers:
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffff8000103b4530-ffff8000103b4714: mount_too_revealing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05938ec)
Location: fs/namespace.c:3916
Inline: True
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
c05938ec-c0593ac0: mount_too_revealing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b0860)
Location: fs/namespace.c:3916
Inline: True
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
c0000000004b0860-c0000000004b0b10: mount_too_revealing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000277cdc)
Location: fs/namespace.c:3916
Inline: True
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffe000277cdc-ffffffe000277e7a: mount_too_revealing (STB_LOCAL)
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
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fa3c0)
Location: fs/namespace.c:3916
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812fa3c0-ffffffff812fa570: mount_too_revealing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812eafe0)
Location: fs/namespace.c:3916
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812eafe0-ffffffff812eb190: mount_too_revealing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f81b0)
Location: fs/namespace.c:3916
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812f81b0-ffffffff812f8360: mount_too_revealing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool mount_too_revealing(const struct super_block *sb, int *new_mnt_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130a030)
Location: fs/namespace.c:3916
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff8130a030-ffffffff8130a1e0: mount_too_revealing (STB_LOCAL)
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
