# Function: <code>security_genfs_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_genfs_sid(const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81358dd0)
Location: security/selinux/ss/services.c:2527
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81358dd0-ffffffff81358f0d: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_genfs_sid(const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138ed30)
Location: security/selinux/ss/services.c:2521
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff8138ed30-ffffffff8138ee79: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_genfs_sid(const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a5950)
Location: security/selinux/ss/services.c:2521
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff813a5950-ffffffff813a5a99: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_genfs_sid(const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bc3c0)
Location: security/selinux/ss/services.c:2637
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff813bc3c0-ffffffff813bc502: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_genfs_sid(const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e2530)
Location: security/selinux/ss/services.c:2647
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff813e2530-ffffffff813e2672: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81413350)
Location: security/selinux/ss/services.c:2745
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81413350-ffffffff814134d8: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142f890)
Location: security/selinux/ss/services.c:2711
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8142f890-ffffffff8142f9f9: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145d240)
Location: security/selinux/ss/services.c:2724
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8145d240-ffffffff8145d3aa: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81476ff0)
Location: security/selinux/ss/services.c:2731
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81476ff0-ffffffff8147715a: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cc650)
Location: security/selinux/ss/services.c:2774
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_bools
```
**Symbols:**

```
ffffffff814cc650-ffffffff814cc6b3: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e9a50)
Location: security/selinux/ss/services.c:2848
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff814e9a50-ffffffff814e9a93: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f05c0)
Location: security/selinux/ss/services.c:2914
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
```
**Symbols:**

```
ffffffff814f05c0-ffffffff814f0632: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2924
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
```
**Symbols:**

```
ffffffff81cd50b5-ffffffff81cd50d0: security_genfs_sid.cold (STB_LOCAL)
ffffffff8154ab20-ffffffff8154aba0: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, const char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2927
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
```
**Symbols:**

```
ffffffff81e87f02-ffffffff81e87f1c: security_genfs_sid.cold (STB_LOCAL)
ffffffff815e3820-ffffffff815e38ad: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, const char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2920
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
```
**Symbols:**

```
ffffffff82073deb-ffffffff82073e05: security_genfs_sid.cold (STB_LOCAL)
ffffffff81692aa0-ffffffff81692b2d: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_genfs_sid(const char *fstype, const char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2869
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
```
**Symbols:**

```
ffffffff820f399d-ffffffff820f39b7: security_genfs_sid.cold (STB_LOCAL)
ffffffff816cb000-ffffffff816cb08d: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_genfs_sid(const char *fstype, const char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2878
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
```
**Symbols:**

```
ffffffff821d0b63-ffffffff821d0b7d: security_genfs_sid.cold (STB_LOCAL)
ffffffff81707c40-ffffffff81707ccd: security_genfs_sid (STB_GLOBAL)
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
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010566b60)
Location: security/selinux/ss/services.c:2731
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffff800010566b60-ffff800010566d30: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071b1c4)
Location: security/selinux/ss/services.c:2731
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
c071b1c4-c071b344: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c99d0)
Location: security/selinux/ss/services.c:2731
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
c0000000006c99d0-c0000000006c9d68: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bcb0e)
Location: security/selinux/ss/services.c:2731
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffe0003bcb0e-ffffffe0003bcc36: security_genfs_sid (STB_GLOBAL)
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
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146f5d0)
Location: security/selinux/ss/services.c:2731
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8146f5d0-ffffffff8146f73a: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145fff0)
Location: security/selinux/ss/services.c:2731
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8145fff0-ffffffff8146015a: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146b670)
Location: security/selinux/ss/services.c:2731
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8146b670-ffffffff8146b7da: security_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_genfs_sid(struct selinux_state *state, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81482e20)
Location: security/selinux/ss/services.c:2731
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81482e20-ffffffff81482f87: security_genfs_sid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>fstype, path, orig_sclass, sid</code> ➡️ <code>state, fstype, path, orig_sclass, sid</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *path</code> ➡️ <code>const char *path</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, fstype, path, orig_sclass, sid</code> ➡️ <code>fstype, path, orig_sclass, sid</code>
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
