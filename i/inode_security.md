# Function: <code>inode_security</code>

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
In security/selinux/hooks.c (ffffffff81379a3c)
Location: security/selinux/hooks.c:294
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
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
In security/selinux/hooks.c (ffffffff8139049d)
Location: security/selinux/hooks.c:295
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
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
In security/selinux/hooks.c (ffffffff813a68c5)
Location: security/selinux/hooks.c:287
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
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
In security/selinux/hooks.c (ffffffff813cc315)
Location: security/selinux/hooks.c:288
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
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
In security/selinux/hooks.c (ffffffff813ffe63)
Location: security/selinux/hooks.c:320
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
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
In security/selinux/hooks.c (ffffffff8141bdfc)
Location: security/selinux/hooks.c:305
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
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
In security/selinux/hooks.c (ffffffff8144979c)
Location: security/selinux/hooks.c:306
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
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
In security/selinux/hooks.c (ffffffff81463334)
Location: security/selinux/hooks.c:308
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode_security_struct *inode_security(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b6d90)
Location: security/selinux/hooks.c:293
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
```
**Symbols:**

```
ffffffff814b6d90-ffffffff814b6dec: inode_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode_security_struct *inode_security(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d4a60)
Location: security/selinux/hooks.c:294
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
```
**Symbols:**

```
ffffffff814d4a60-ffffffff814d4abc: inode_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode_security_struct *inode_security(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814db840)
Location: security/selinux/hooks.c:330
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
```
**Symbols:**

```
ffffffff814db840-ffffffff814db89c: inode_security (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct inode_security_struct *inode_security(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:307
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
```
**Symbols:**

```
ffffffff81534cb0-ffffffff81534d1d: inode_security (STB_LOCAL)
ffffffff81cd3d55-ffffffff81cd3d6a: inode_security.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct inode_security_struct *inode_security(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:293
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
```
**Symbols:**

```
ffffffff815caf00-ffffffff815caf77: inode_security (STB_LOCAL)
ffffffff81e86d4b-ffffffff81e86d60: inode_security.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct inode_security_struct *inode_security(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:295
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
```
**Symbols:**

```
ffffffff81677fd0-ffffffff81678047: inode_security (STB_LOCAL)
ffffffff82073711-ffffffff82073726: inode_security.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct inode_security_struct *inode_security(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:291
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
```
**Symbols:**

```
ffffffff816b0280-ffffffff816b02f7: inode_security (STB_LOCAL)
ffffffff820f330a-ffffffff820f331f: inode_security.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct inode_security_struct *inode_security(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:319
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
```
**Symbols:**

```
ffffffff816ed200-ffffffff816ed277: inode_security (STB_LOCAL)
ffffffff821d046c-ffffffff821d0481: inode_security.cold (STB_LOCAL)
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
In security/selinux/hooks.c (ffff8000105511c0)
Location: security/selinux/hooks.c:308
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
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
In security/selinux/hooks.c (c0703d5c)
Location: security/selinux/hooks.c:308
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
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
In security/selinux/hooks.c (c0000000006a7fa0)
Location: security/selinux/hooks.c:308
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
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
In security/selinux/hooks.c (ffffffe0003aa582)
Location: security/selinux/hooks.c:308
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
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
In security/selinux/hooks.c (ffffffff8145b914)
Location: security/selinux/hooks.c:308
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
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
In security/selinux/hooks.c (ffffffff8144c344)
Location: security/selinux/hooks.c:308
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
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
In security/selinux/hooks.c (ffffffff814579b4)
Location: security/selinux/hooks.c:308
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
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
In security/selinux/hooks.c (ffffffff8146c914)
Location: security/selinux/hooks.c:308
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
