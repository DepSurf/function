# Function: <code>security_free_mnt_opts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813477c2)
Location: include/linux/security.h:168
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
```
```
In security/smack/smack_lsm.c (ffffffff81360a18)
Location: include/linux/security.h:168
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137f4f9)
Location: include/linux/security.h:170
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
```
```
In security/smack/smack_lsm.c (ffffffff813979d8)
Location: include/linux/security.h:170
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81395f89)
Location: include/linux/security.h:170
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
```
```
In security/smack/smack_lsm.c (ffffffff813ae5b8)
Location: include/linux/security.h:170
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813ac081)
Location: include/linux/security.h:184
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_parse_opts_str
```
```
In security/smack/smack_lsm.c (ffffffff813c34d8)
Location: include/linux/security.h:184
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813d20f1)
Location: include/linux/security.h:183
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_parse_opts_str
```
```
In security/smack/smack_lsm.c (ffffffff813e9798)
Location: include/linux/security.h:183
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81401864)
Location: include/linux/security.h:181
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_parse_opts_str
```
```
In security/smack/smack_lsm.c (ffffffff8141a6b8)
Location: include/linux/security.h:181
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140d820)
Location: security/security.c:855
Inline: False
Direct callers:
  - fs/super.c:mount_fs
  - fs/super.c:mount_fs
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff8140d820-ffffffff8140d867: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143aa00)
Location: security/security.c:864
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff8143aa00-ffffffff8143aa46: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81454820)
Location: security/security.c:898
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff81454820-ffffffff81454867: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a71b0)
Location: security/security.c:1046
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff814a71b0-ffffffff814a71f7: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c4730)
Location: security/security.c:1048
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff814c4730-ffffffff814c4777: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cabd0)
Location: security/security.c:1086
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff814cabd0-ffffffff814cac17: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815238d0)
Location: security/security.c:1086
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff815238d0-ffffffff81523917: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b7600)
Location: security/security.c:1098
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff815b7600-ffffffff815b764f: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81662930)
Location: security/security.c:1096
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff81662930-ffffffff8166297f: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169ae30)
Location: security/security.c:1391
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff8169ae30-ffffffff8169ae7f: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d9460)
Location: security/security.c:1443
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff816d9460-ffffffff816d94b2: security_free_mnt_opts (STB_GLOBAL)
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
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff80001053f9a8)
Location: security/security.c:898
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffff80001053f9a8-ffff80001053f9fc: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f5a8c)
Location: security/security.c:898
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
c06f5a8c-c06f5aec: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000690a60)
Location: security/security.c:898
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
c000000000690a60-c000000000690af0: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039cdde)
Location: security/security.c:898
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffe00039cdde-ffffffe00039ce24: security_free_mnt_opts (STB_GLOBAL)
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
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ce00)
Location: security/security.c:898
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff8144ce00-ffffffff8144ce47: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143d850)
Location: security/security.c:898
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff8143d850-ffffffff8143d897: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81448ea0)
Location: security/security.c:898
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff81448ea0-ffffffff81448ee7: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_free_mnt_opts(void **mnt_opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81460270)
Location: security/security.c:898
Inline: False
Direct callers:
  - fs/fs_context.c:vfs_clean_context
  - fs/fs_context.c:put_fs_context
```
**Symbols:**

```
ffffffff81460270-ffffffff814602b7: security_free_mnt_opts (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
