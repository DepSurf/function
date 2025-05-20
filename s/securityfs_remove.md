# Function: <code>securityfs_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8133fed0)
Location: security/inode.c:187
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_remove_dir
  - security/apparmor/apparmorfs.c:aafs_remove_dir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffffffff8133fed0-ffffffff8133ff76: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81375560)
Location: security/inode.c:240
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_remove_dir
  - security/apparmor/apparmorfs.c:aafs_remove_dir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81375560-ffffffff813755ef: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8138be90)
Location: security/inode.c:239
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_remove_dir
  - security/apparmor/apparmorfs.c:aafs_remove_dir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffffffff8138be90-ffffffff8138bf1f: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813a1c00)
Location: security/inode.c:289
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffffffff813a1c00-ffffffff813a1c9e: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813c7a00)
Location: security/inode.c:289
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffffffff813c7a00-ffffffff813c7a9e: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813f7030)
Location: security/inode.c:289
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffffffff813f7030-ffffffff813f70c5: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81412ae0)
Location: security/inode.c:290
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffffffff81412ae0-ffffffff81412b75: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814404d0)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffffffff814404d0-ffffffff8144056f: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81459da0)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffffffff81459da0-ffffffff81459e3f: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814ad020)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff814ad020-ffffffff814ad0bf: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814ca570)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff814ca570-ffffffff814ca60f: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814d0ba0)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff814d0ba0-ffffffff814d0c3f: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff815298d0)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff815298d0-ffffffff8152996f: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff815bf0f0)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff815bf0f0-ffffffff815bf197: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8166b4e0)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8166b4e0-ffffffff8166b587: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff816a3c40)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816a3c40-ffffffff816a3ce7: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff816e06a0)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816e06a0-ffffffff816e0747: securityfs_remove (STB_GLOBAL)
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
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffff8000105460f0)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffff8000105460f0-ffff800010546198: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (c06fbec4)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
```
**Symbols:**

```
c06fbec4-c06fbf64: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (c00000000069cb00)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
```
**Symbols:**

```
c00000000069cb00-c00000000069cbf4: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffe0003a1bfe)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffffffe0003a1bfe-ffffffe0003a1ca0: securityfs_remove (STB_GLOBAL)
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
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81452380)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffffffff81452380-ffffffff8145241f: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81442dd0)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffffffff81442dd0-ffffffff81442e6f: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8144e420)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffffffff8144e420-ffffffff8144e4bf: securityfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void securityfs_remove(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814657f0)
Location: security/inode.c:295
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/apparmor/apparmorfs.c:entry_remove_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_release_policy
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
```
**Symbols:**

```
ffffffff814657f0-ffffffff8146588f: securityfs_remove (STB_GLOBAL)
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
