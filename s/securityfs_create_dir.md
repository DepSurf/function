# Function: <code>securityfs_create_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8133feb0)
Location: security/inode.c:166
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_create_dir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8133feb0-ffffffff8133fecd: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81375540)
Location: security/inode.c:219
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_create_dir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81375540-ffffffff81375560: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8138be70)
Location: security/inode.c:218
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_create_dir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8138be70-ffffffff8138be90: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813a1b00)
Location: security/inode.c:222
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff813a1b00-ffffffff813a1b20: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813c7900)
Location: security/inode.c:222
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff813c7900-ffffffff813c7920: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813f6f30)
Location: security/inode.c:222
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff813f6f30-ffffffff813f6f50: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814129e0)
Location: security/inode.c:223
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff814129e0-ffffffff81412a00: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81440420)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81440420-ffffffff81440440: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81459cf0)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81459cf0-ffffffff81459d10: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814acf70)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff814acf70-ffffffff814acf90: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814ca4c0)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff814ca4c0-ffffffff814ca4e0: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814d0af0)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff814d0af0-ffffffff814d0b10: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81529820)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81529820-ffffffff81529840: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff815bf010)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff815bf010-ffffffff815bf042: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8166b3e0)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8166b3e0-ffffffff8166b412: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff816a3b40)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816a3b40-ffffffff816a3b72: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff816e05a0)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816e05a0-ffffffff816e05d2: securityfs_create_dir (STB_GLOBAL)
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
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffff800010546018)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffff800010546018-ffff80001054605c: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (c06fbe00)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
c06fbe00-c06fbe38: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (c00000000069ca00)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
c00000000069ca00-c00000000069ca28: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffe0003a1b46)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffe0003a1b46-ffffffe0003a1b84: securityfs_create_dir (STB_GLOBAL)
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
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814522d0)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff814522d0-ffffffff814522f0: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81442d20)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81442d20-ffffffff81442d40: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8144e370)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8144e370-ffffffff8144e390: securityfs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *securityfs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81465740)
Location: security/inode.c:228
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/apparmor/apparmorfs.c:entry_create_dir
  - security/safesetid/securityfs.c:safesetid_init_securityfs
  - security/integrity/iint.c:integrity_fs_init
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81465740-ffffffff81465760: securityfs_create_dir (STB_GLOBAL)
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
