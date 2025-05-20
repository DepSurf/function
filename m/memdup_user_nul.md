# Function: <code>memdup_user_nul</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c4850)
Location: mm/util.c:187
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff811c4850-ffffffff811c48ca: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4960)
Location: mm/util.c:187
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff811d4960-ffffffff811d49da: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd700)
Location: mm/util.c:214
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/integrity/ima/ima_fs.c:ima_write_policy
```
**Symbols:**

```
ffffffff811dd700-ffffffff811dd77d: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f3180)
Location: mm/util.c:214
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/page_alloc.c:numa_zonelist_order_handler
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/integrity/ima/ima_fs.c:ima_write_policy
```
**Symbols:**

```
ffffffff811f3180-ffffffff811f31fd: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812143c0)
Location: mm/util.c:236
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
**Symbols:**

```
ffffffff812143c0-ffffffff8121443d: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227290)
Location: mm/util.c:229
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - drivers/media/cec/cec-core.c:cec_error_inj_write
```
**Symbols:**

```
ffffffff81227290-ffffffff8122730d: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81236e40)
Location: mm/util.c:243
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/media/cec/cec-core.c:cec_error_inj_write
```
**Symbols:**

```
ffffffff81236e40-ffffffff81236ec7: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81245000)
Location: mm/util.c:250
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/media/cec/cec-core.c:cec_error_inj_write
```
**Symbols:**

```
ffffffff81245000-ffffffff81245092: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81273240)
Location: mm/util.c:250
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:handle_policy_update
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parse_user
```
**Symbols:**

```
ffffffff81273240-ffffffff812732d2: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d9a0)
Location: mm/util.c:251
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:handle_policy_update
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parse_user
```
**Symbols:**

```
ffffffff8127d9a0-ffffffff8127da32: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282b70)
Location: mm/util.c:251
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:handle_policy_update
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parse_user
```
**Symbols:**

```
ffffffff81282b70-ffffffff81282c02: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0560)
Location: mm/util.c:251
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:handle_policy_update
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parse_user
```
**Symbols:**

```
ffffffff812c0560-ffffffff812c05f2: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131d5b0)
Location: mm/util.c:252
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:handle_policy_update
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parse_user
```
**Symbols:**

```
ffffffff8131d5b0-ffffffff8131d660: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81391270)
Location: mm/util.c:252
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:handle_policy_update
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parse_user
  - lib/string_helpers.c:parse_int_array_user
```
**Symbols:**

```
ffffffff81391270-ffffffff81391317: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c3c30)
Location: mm/util.c:275
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:handle_policy_update
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parse_user
  - lib/string_helpers.c:parse_int_array_user
  - drivers/pinctrl/pinmux.c:pinmux_select
```
**Symbols:**

```
ffffffff813c3c30-ffffffff813c3cd7: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ee7e0)
Location: mm/util.c:275
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:handle_policy_update
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap-str.c:bitmap_parselist_user
  - lib/bitmap-str.c:bitmap_parse_user
  - lib/string_helpers.c:parse_int_array_user
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/gpu/drm/drm_debugfs_crc.c:crc_control_write
```
**Symbols:**

```
ffffffff813ee7e0-ffffffff813ee887: memdup_user_nul (STB_GLOBAL)
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
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d8620)
Location: mm/util.c:250
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/fsopen.c:__arm64_sys_fsconfig
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/media/cec/cec-core.c:cec_error_inj_write
```
**Symbols:**

```
ffff8000102d8620-ffff8000102d86dc: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ffac8)
Location: mm/util.c:250
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/media/cec/cec-core.c:cec_error_inj_write
```
**Symbols:**

```
c04ffac8-c04ffbdc: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000397ba0)
Location: mm/util.c:250
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/media/cec/cec-core.c:cec_error_inj_write
```
**Symbols:**

```
c000000000397ba0-c000000000397cb4: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f291a)
Location: mm/util.c:250
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/media/cec/cec-core.c:cec_error_inj_write
```
**Symbols:**

```
ffffffe0001f291a-ffffffe0001f29be: memdup_user_nul (STB_GLOBAL)
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
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123d650)
Location: mm/util.c:250
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/media/cec/cec-core.c:cec_error_inj_write
```
**Symbols:**

```
ffffffff8123d650-ffffffff8123d6e2: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81230650)
Location: mm/util.c:250
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/media/cec/cec-core.c:cec_error_inj_write
```
**Symbols:**

```
ffffffff81230650-ffffffff812306e2: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b3f0)
Location: mm/util.c:250
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/media/cec/cec-core.c:cec_error_inj_write
```
**Symbols:**

```
ffffffff8123b3f0-ffffffff8123b482: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *memdup_user_nul(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124ab00)
Location: mm/util.c:250
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/user_namespace.c:map_write
  - kernel/trace/blktrace.c:blk_msg_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/page_alloc.c:numa_zonelist_order_handler
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/proc/generic.c:proc_simple_write
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/lockdown/lockdown.c:lockdown_write
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
  - lib/bitmap.c:bitmap_parselist_user
  - drivers/media/cec/cec-core.c:cec_error_inj_write
```
**Symbols:**

```
ffffffff8124ab00-ffffffff8124ab92: memdup_user_nul (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
