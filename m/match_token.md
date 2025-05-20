# Function: <code>match_token</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff813f8160)
Location: lib/parser.c:107
Inline: False
Direct callers:
  - fs/proc/root.c:proc_parse_options
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff813f8160-ffffffff813f8362: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8143f010)
Location: lib/parser.c:107
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
  - fs/proc/root.c:proc_parse_options
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff8143f010-ffffffff8143f20f: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8145c060)
Location: lib/parser.c:107
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_fill_super
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
  - fs/proc/root.c:proc_parse_options
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff8145c060-ffffffff8145c260: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81461530)
Location: lib/parser.c:107
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_fill_super
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/proc/root.c:proc_parse_options
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff81461530-ffffffff81461730: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8148d420)
Location: lib/parser.c:107
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_fill_super
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/proc/root.c:proc_parse_options
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff8148d420-ffffffff8148d626: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff814c2170)
Location: lib/parser.c:107
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_fill_super
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/proc/root.c:proc_parse_options
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff814c2170-ffffffff814c2377: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff814d6870)
Location: lib/parser.c:107
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_fill_super
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/proc/root.c:proc_parse_options
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff814d6870-ffffffff814d6a82: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff815026b0)
Location: lib/parser.c:105
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_fill_super
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/unicode/utf8-core.c:utf8_parse_version
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
**Symbols:**

```
ffffffff815026b0-ffffffff815028c8: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81520650)
Location: lib/parser.c:105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/unicode/utf8-core.c:utf8_load
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81520650-ffffffff81520868: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81583a00)
Location: lib/parser.c:105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/unicode/utf8-core.c:utf8_load
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_parse
  - security/keys/trusted-keys/trusted_tpm1.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81583a00-ffffffff81583a34: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff815a0880)
Location: lib/parser.c:105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/unicode/utf8-core.c:utf8_load
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_parse
  - security/keys/trusted-keys/trusted_tpm1.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff815a0880-ffffffff815a08b4: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff815a7670)
Location: lib/parser.c:105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/unicode/utf8-core.c:utf8_load
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff815a7670-ffffffff815a76a4: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff816105b0)
Location: lib/parser.c:106
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/unicode/utf8-core.c:utf8_load
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff816105b0-ffffffff816105e4: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff816dca20)
Location: lib/parser.c:106
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff816dca20-ffffffff816dca5e: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff817cc770)
Location: lib/parser.c:115
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff817cc770-ffffffff817cc7ae: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8180ab80)
Location: lib/parser.c:115
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8180ab80-ffffffff8180abbe: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81851360)
Location: lib/parser.c:115
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81851360-ffffffff8185139e: match_token (STB_GLOBAL)
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
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffff800010629b58)
Location: lib/parser.c:105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/unicode/utf8-core.c:utf8_load
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffff800010629b58-ffff800010629d84: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (c07d0e30)
Location: lib/parser.c:105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/unicode/utf8-core.c:utf8_load
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/trusted.c:getoptions
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
c07d0e30-c07d1080: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (c0000000007cb610)
Location: lib/parser.c:105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/unicode/utf8-core.c:utf8_load
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
c0000000007cb610-c0000000007cbabc: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffe00045a70c)
Location: lib/parser.c:105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/unicode/utf8-core.c:utf8_load
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffe00045a70c-ffffffe00045a8ba: match_token (STB_GLOBAL)
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
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81518c30)
Location: lib/parser.c:105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/unicode/utf8-core.c:utf8_load
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81518c30-ffffffff81518e48: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81508f30)
Location: lib/parser.c:105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/unicode/utf8-core.c:utf8_load
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81508f30-ffffffff81509148: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81514cc0)
Location: lib/parser.c:105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81514cc0-ffffffff81514ed8: match_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int match_token(char *s, const struct match_token *table, substring_t *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8152e430)
Location: lib/parser.c:105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/super.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/unicode/utf8-core.c:utf8_load
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/pstore/inode.c:parse_options
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:datablob_parse
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8152e430-ffffffff8152e648: match_token (STB_GLOBAL)
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
