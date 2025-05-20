# Function: <code>match_strdup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff813f83b0)
Location: lib/parser.c:281
Inline: False
Direct callers:
  - fs/ext4/super.c:set_qf_name
  - fs/ext4/super.c:handle_mount_opt
  - fs/fat/inode.c:parse_options
  - fs/fuse/inode.c:fuse_match_uint
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
```
**Symbols:**

```
ffffffff813f83b0-ffffffff813f83f4: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8143f250)
Location: lib/parser.c:281
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_addr_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
  - fs/fuse/inode.c:fuse_match_uint
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
```
**Symbols:**

```
ffffffff8143f250-ffffffff8143f294: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8145c2a0)
Location: lib/parser.c:328
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_addr_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
  - fs/fuse/inode.c:fuse_match_uint
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
```
**Symbols:**

```
ffffffff8145c2a0-ffffffff8145c2e4: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81461770)
Location: lib/parser.c:328
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
  - fs/fuse/inode.c:fuse_match_uint
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
```
**Symbols:**

```
ffffffff81461770-ffffffff814617b4: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8148d670)
Location: lib/parser.c:328
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
  - fs/fuse/inode.c:fuse_match_uint
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
```
**Symbols:**

```
ffffffff8148d670-ffffffff8148d6b4: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff814c23c0)
Location: lib/parser.c:328
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
  - fs/fuse/inode.c:fuse_match_uint
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/selinux/hooks.c:selinux_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/smack/smack_lsm.c:smack_parse_opts_str
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
```
**Symbols:**

```
ffffffff814c23c0-ffffffff814c2404: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff814d6c2b)
Location: lib/parser.c:322
Inline: True
Inline callers:
  - lib/parser.c:match_u64
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
  - fs/fuse/inode.c:fuse_match_uint
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
```
**Symbols:**

```
ffffffff814d6ad0-ffffffff814d6aed: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81502a6b)
Location: lib/parser.c:320
Inline: True
Inline callers:
  - lib/parser.c:match_u64
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
  - fs/fuse/inode.c:fuse_match_uint
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
```
**Symbols:**

```
ffffffff81502910-ffffffff8150292d: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81520a0b)
Location: lib/parser.c:320
Inline: True
Inline callers:
  - lib/parser.c:match_u64
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
```
**Symbols:**

```
ffffffff815208b0-ffffffff815208cd: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81583acb)
Location: lib/parser.c:320
Inline: True
Inline callers:
  - lib/parser.c:match_u64
  - lib/parser.c:match_number
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/crypto/policy.c:fscrypt_set_test_dummy_encryption
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
```
**Symbols:**

```
ffffffff81583a80-ffffffff81583a9d: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff815a094b)
Location: lib/parser.c:320
Inline: True
Inline callers:
  - lib/parser.c:match_u64
  - lib/parser.c:match_number
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
**Symbols:**

```
ffffffff815a0900-ffffffff815a091d: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff815a779b)
Location: lib/parser.c:357
Inline: True
Inline callers:
  - lib/parser.c:match_u64
  - lib/parser.c:match_uint
  - lib/parser.c:match_number
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
**Symbols:**

```
ffffffff815a76f0-ffffffff815a770d: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff816106db)
Location: lib/parser.c:358
Inline: True
Inline callers:
  - lib/parser.c:match_u64
  - lib/parser.c:match_uint
  - lib/parser.c:match_number
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
**Symbols:**

```
ffffffff81610630-ffffffff8161064d: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff816dcb73)
Location: lib/parser.c:358
Inline: True
Inline callers:
  - lib/parser.c:match_u64
  - lib/parser.c:match_uint
  - lib/parser.c:match_number
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/fat/inode.c:parse_options
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
**Symbols:**

```
ffffffff816dcab0-ffffffff816dcad7: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff817cc7c0)
Location: lib/parser.c:359
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/fat/inode.c:parse_options
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
**Symbols:**

```
ffffffff817cc7c0-ffffffff817cc7e7: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8180abd0)
Location: lib/parser.c:359
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/fat/inode.c:parse_options
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
**Symbols:**

```
ffffffff8180abd0-ffffffff8180abf7: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff818513b0)
Location: lib/parser.c:359
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - fs/fat/inode.c:parse_options
  - security/integrity/ima/ima_policy.c:ima_lsm_rule_init
  - security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list
```
**Symbols:**

```
ffffffff818513b0-ffffffff818513d7: match_strdup (STB_GLOBAL)
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
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffff800010629de0)
Location: lib/parser.c:320
Inline: True
Inline callers:
  - lib/parser.c:match_u64
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
```
**Symbols:**

```
ffff800010629de0-ffff800010629e00: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (c07d1208)
Location: lib/parser.c:320
Inline: True
Inline callers:
  - lib/parser.c:match_u64
  - lib/parser.c:match_number
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
```
**Symbols:**

```
c07d10c0-c07d10e0: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (c0000000007cbd1c)
Location: lib/parser.c:320
Inline: True
Inline callers:
  - lib/parser.c:match_u64
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
```
**Symbols:**

```
c0000000007cbb50-c0000000007cbb90: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffe00045aa12)
Location: lib/parser.c:320
Inline: True
Inline callers:
  - lib/parser.c:match_u64
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
```
**Symbols:**

```
ffffffe00045a900-ffffffe00045a926: match_strdup (STB_GLOBAL)
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
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff81518feb)
Location: lib/parser.c:320
Inline: True
Inline callers:
  - lib/parser.c:match_u64
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
```
**Symbols:**

```
ffffffff81518e90-ffffffff81518ead: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff815092eb)
Location: lib/parser.c:320
Inline: True
Inline callers:
  - lib/parser.c:match_u64
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
```
**Symbols:**

```
ffffffff81509190-ffffffff815091ad: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8151507b)
Location: lib/parser.c:320
Inline: True
Inline callers:
  - lib/parser.c:match_u64
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
```
**Symbols:**

```
ffffffff81514f20-ffffffff81514f3d: match_strdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
char *match_strdup(const substring_t *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/parser.c (ffffffff8152e7eb)
Location: lib/parser.c:320
Inline: True
Inline callers:
  - lib/parser.c:match_u64
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
  - fs/fat/inode.c:parse_options
```
**Symbols:**

```
ffffffff8152e690-ffffffff8152e6ad: match_strdup (STB_GLOBAL)
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
