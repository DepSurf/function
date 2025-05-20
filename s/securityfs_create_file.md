# Function: <code>securityfs_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8133fc80)
Location: security/inode.c:77
Inline: False
Direct callers:
  - security/inode.c:securityfs_create_dir
  - security/apparmor/apparmorfs.c:aafs_create_dir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8133fc80-ffffffff8133fea4: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81375549)
Location: security/inode.c:190
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_create_dir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81375520-ffffffff81375536: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8138be79)
Location: security/inode.c:190
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_create_dir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8138be50-ffffffff8138be66: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813a1b09)
Location: security/inode.c:194
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff813a1ae0-ffffffff813a1af6: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813c7909)
Location: security/inode.c:194
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff813c78e0-ffffffff813c78f6: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff827160a5)
Location: security/inode.c:194
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff813f6f10-ffffffff813f6f26: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff828cdbe1)
Location: security/inode.c:195
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff814129c0-ffffffff814129d6: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff828e762b)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81440400-ffffffff81440416: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff828f0117)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81459cd0-ffffffff81459ce6: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff82d05302)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_create_entry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff814acf50-ffffffff814acf66: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff82ff26cf)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_create_entry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff814ca4a0-ffffffff814ca4b6: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff831fd0ab)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_create_entry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff814d0ad0-ffffffff814d0ae6: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff832e42b0)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_create_entry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81529800-ffffffff81529816: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8349ae1f)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_create_entry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff815befe0-ffffffff815bf008: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff83ed1b9f)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8166b3a0-ffffffff8166b3c8: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff836f6c7f)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816a3b00-ffffffff816a3b28: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff83929fbf)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816e0560-ffffffff816e0588: securityfs_create_file (STB_GLOBAL)
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
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffff80001146a02c)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffff800010545fb8-ffff800010546018: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (c1542c04)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
c06fbdd0-c06fbe00: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (c0000000013984ac)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
c00000000069c9e0-c00000000069c9f8: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffe000025168)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffe0003a1afa-ffffffe0003a1b46: securityfs_create_file (STB_GLOBAL)
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
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff828d8fcb)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff814522b0-ffffffff814522c6: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff828d16e7)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81442d00-ffffffff81442d16: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff828ebd4b)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8144e350-ffffffff8144e366: securityfs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dentry *securityfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff828f1161)
Location: security/inode.c:200
Inline: True
Inline callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_dir
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/lockdown/lockdown.c:lockdown_secfs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81465720-ffffffff81465736: securityfs_create_file (STB_GLOBAL)
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
