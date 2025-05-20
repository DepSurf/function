# Function: <code>kmemdup_nul</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd4b0)
Location: mm/util.c:131
Inline: False
```
**Symbols:**

```
ffffffff811dd4b0-ffffffff811dd503: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f2f30)
Location: mm/util.c:131
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff811f2f30-ffffffff811f2f83: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214220)
Location: mm/util.c:131
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
```
**Symbols:**

```
ffffffff81214220-ffffffff81214273: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812270f0)
Location: mm/util.c:124
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - drivers/pci/pci.c:pci_dev_str_match
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff812270f0-ffffffff81227143: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81236bf0)
Location: mm/util.c:136
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - drivers/pci/pci.c:pci_dev_str_match
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81236bf0-ffffffff81236c42: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81244db0)
Location: mm/util.c:143
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - drivers/pci/pci.c:pci_dev_str_match
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81244db0-ffffffff81244e02: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81272a60)
Location: mm/util.c:143
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - security/security.c:security_setprocattr
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - lib/parser.c:match_number
  - drivers/pci/pci.c:pci_dev_str_match_path
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81272a60-ffffffff81272ab2: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d110)
Location: mm/util.c:144
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - security/security.c:security_setprocattr
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - lib/parser.c:match_number
  - drivers/pci/pci.c:pci_dev_str_match_path
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8127d110-ffffffff8127d162: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812822b0)
Location: mm/util.c:144
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - security/security.c:security_setprocattr
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - lib/parser.c:match_uint
  - lib/parser.c:match_number
  - drivers/pci/pci.c:pci_dev_str_match_path
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff812822b0-ffffffff812822fe: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0320)
Location: mm/util.c:144
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - security/security.c:security_setprocattr
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - lib/parser.c:match_uint
  - lib/parser.c:match_number
  - drivers/pci/pci.c:pci_dev_str_match_path
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff812c0320-ffffffff812c036e: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131cdb0)
Location: mm/util.c:145
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/ext4/super.c:parse_options
  - security/security.c:security_setprocattr
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - lib/parser.c:match_uint
  - lib/parser.c:match_number
  - drivers/pci/pci.c:pci_dev_str_match_path
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8131cdb0-ffffffff8131ce29: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813910a0)
Location: mm/util.c:145
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/ext4/super.c:parse_options
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_strdup
  - drivers/pci/pci.c:pci_dev_str_match_path
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff813910a0-ffffffff8139111e: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c39d0)
Location: mm/util.c:168
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/ext4/super.c:parse_options
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_strdup
  - drivers/pci/pci.c:pci_dev_str_match_path
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff813c39d0-ffffffff813c3a6f: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ee590)
Location: mm/util.c:168
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - fs/fs_context.c:vfs_parse_fs_string
  - fs/ext4/super.c:parse_options
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_strdup
  - drivers/pci/pci.c:pci_dev_str_match_path
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff813ee590-ffffffff813ee62f: kmemdup_nul (STB_GLOBAL)
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
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d7d20)
Location: mm/util.c:143
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - drivers/pci/pci.c:pci_dev_str_match
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffff8000102d7d20-ffff8000102d7da0: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff1e4)
Location: mm/util.c:143
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:append_filter_err
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - lib/parser.c:match_number
  - drivers/pci/pci.c:pci_dev_str_match
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
c04ff1e4-c04ff23c: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000397740)
Location: mm/util.c:143
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - drivers/pci/pci.c:pci_dev_str_match
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
c000000000397740-c000000000397808: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f279e)
Location: mm/util.c:143
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - fs/fs_context.c:vfs_parse_fs_string
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - drivers/pci/pci.c:pci_dev_str_match
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffe0001f279e-ffffffe0001f2800: kmemdup_nul (STB_GLOBAL)
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
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123d400)
Location: mm/util.c:143
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - drivers/pci/pci.c:pci_dev_str_match
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8123d400-ffffffff8123d452: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81230400)
Location: mm/util.c:143
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - drivers/pci/pci.c:pci_dev_str_match
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81230400-ffffffff81230452: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b1a0)
Location: mm/util.c:143
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - drivers/pci/pci.c:pci_dev_str_match
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8123b1a0-ffffffff8123b1f2: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *kmemdup_nul(const char *s, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124a8b0)
Location: mm/util.c:143
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_hist.c:parse_synth_field
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - fs/fs_context.c:vfs_parse_fs_string
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - lib/parser.c:match_u64
  - drivers/pci/pci.c:pci_dev_str_match
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8124a8b0-ffffffff8124a902: kmemdup_nul (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
