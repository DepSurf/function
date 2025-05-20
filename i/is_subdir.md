# Function: <code>is_subdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81226540)
Location: fs/dcache.c:3302
Inline: False
Direct callers:
  - fs/namei.c:path_connected
  - fs/namespace.c:copy_tree
  - fs/namespace.c:do_mount
  - fs/namespace.c:is_path_reachable
```
**Symbols:**

```
ffffffff81226540-ffffffff81226590: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124ec00)
Location: fs/dcache.c:3469
Inline: False
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:do_mount
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffff8124ec00-ffffffff8124ec4f: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81261c10)
Location: fs/dcache.c:3479
Inline: False
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:do_mount
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffff81261c10-ffffffff81261c5f: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126f4d0)
Location: fs/dcache.c:3509
Inline: False
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:do_mount
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffff8126f4d0-ffffffff8126f51f: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81291df0)
Location: fs/dcache.c:3521
Inline: False
Direct callers:
  - fs/namei.c:path_connected
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:do_mount
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffff81291df0-ffffffff81291e3e: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b47a0)
Location: fs/dcache.c:3044
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:path_parent_directory
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:do_mount
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffff812b47a0-ffffffff812b47ee: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812c9a20)
Location: fs/dcache.c:2998
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:do_mount
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffff812c9a20-ffffffff812c9a6e: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e6420)
Location: fs/dcache.c:3067
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffff812e6420-ffffffff812e6476: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f7f80)
Location: fs/dcache.c:3067
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffff812f7f80-ffffffff812f7fd6: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81330b60)
Location: fs/dcache.c:3088
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namei.c:follow_dotdot
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:copy_tree
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
```
**Symbols:**

```
ffffffff81330b60-ffffffff81330bba: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133c4d0)
Location: fs/dcache.c:3095
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namei.c:follow_dotdot
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:copy_tree
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
```
**Symbols:**

```
ffffffff8133c4d0-ffffffff8133c549: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81342960)
Location: fs/dcache.c:3121
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namespace.c:path_is_under
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
```
**Symbols:**

```
ffffffff81342960-ffffffff813429d9: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81390280)
Location: fs/dcache.c:3123
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namespace.c:path_is_under
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
```
**Symbols:**

```
ffffffff81390280-ffffffff813902f9: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81411ed0)
Location: fs/dcache.c:3147
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namespace.c:path_is_under
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
```
**Symbols:**

```
ffffffff81411ed0-ffffffff81411f62: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149cca0)
Location: fs/dcache.c:3203
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:path_is_under
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
```
**Symbols:**

```
ffffffff8149cca0-ffffffff8149cd32: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d20c0)
Location: fs/dcache.c:3203
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namespace.c:path_is_under
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
```
**Symbols:**

```
ffffffff814d20c0-ffffffff814d2152: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81504b00)
Location: fs/dcache.c:3030
Inline: True
Direct callers:
  - fs/namei.c:path_pts
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
  - fs/namespace.c:__ia32_sys_listmount
  - fs/namespace.c:__ia32_sys_listmount
  - fs/namespace.c:__x64_sys_listmount
  - fs/namespace.c:__x64_sys_listmount
  - fs/namespace.c:do_statmount
  - fs/namespace.c:path_is_under
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:copy_tree
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
```
**Symbols:**

```
ffffffff81504b00-ffffffff81504b92: is_subdir (STB_GLOBAL)
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
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a5340)
Location: fs/dcache.c:3067
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffff8000103a5340-ffff8000103a53dc: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0587f4c)
Location: fs/dcache.c:3067
Inline: True
Direct callers:
  - fs/namei.c:path_connected
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
c0587f4c-c0588000: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a03d0)
Location: fs/dcache.c:3067
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
c0000000004a03d0-c0000000004a047c: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026c680)
Location: fs/dcache.c:3067
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffe00026c680-ffffffe00026c6f8: is_subdir (STB_GLOBAL)
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
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0560)
Location: fs/dcache.c:3067
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffff812f0560-ffffffff812f05b6: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e1190)
Location: fs/dcache.c:3067
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffff812e1190-ffffffff812e11e6: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ee370)
Location: fs/dcache.c:3067
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffff812ee370-ffffffff812ee3c6: is_subdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_subdir(struct dentry *new_dentry, struct dentry *old_dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ff910)
Location: fs/dcache.c:3067
Inline: True
Direct callers:
  - fs/namei.c:path_parent_directory
  - fs/namei.c:follow_dotdot_rcu
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:copy_tree
```
**Symbols:**

```
ffffffff812ff910-ffffffff812ff98f: is_subdir (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
