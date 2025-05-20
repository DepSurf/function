# Function: <code>aa_get_ns</code>

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
In security/apparmor/apparmorfs.c (ffffffff81375c96)
Location: security/apparmor/include/policy_ns.h:107
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
```
```
In security/apparmor/policy.c (ffffffff8137fb92)
Location: security/apparmor/include/policy_ns.h:107
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_setup_default_label
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_may_open_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_remove_profiles
```
```
In security/apparmor/procattr.c (ffffffff81382ce8)
Location: security/apparmor/include/policy_ns.h:107
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81386b9a)
Location: security/apparmor/include/policy_ns.h:107
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff8138d16d)
Location: security/apparmor/include/policy_ns.h:107
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_printk
```
```
In security/apparmor/policy_ns.c (ffffffff813948f9)
Location: security/apparmor/include/policy_ns.h:107
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
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
In security/apparmor/apparmorfs.c (ffffffff813acbe6)
Location: security/apparmor/include/policy_ns.h:109
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff813bb26a)
Location: security/apparmor/include/policy_ns.h:109
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_setup_default_label
  - security/apparmor/policy.c:aa_null_profile
```
```
In security/apparmor/procattr.c (ffffffff813bcf6c)
Location: security/apparmor/include/policy_ns.h:109
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813c151c)
Location: security/apparmor/include/policy_ns.h:109
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff813c83a6)
Location: security/apparmor/include/policy_ns.h:109
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
```
In security/apparmor/policy_ns.c (ffffffff813d054b)
Location: security/apparmor/include/policy_ns.h:109
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff813c39f6)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff813d262d)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_setup_default_label
  - security/apparmor/policy.c:aa_null_profile
```
```
In security/apparmor/procattr.c (ffffffff813d439c)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813d89bc)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff813df986)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
```
In security/apparmor/policy_ns.c (ffffffff813e7c4b)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff813d9ea8)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff813e5275)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813e68cb)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff813e72a3)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813e9896)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff813ec598)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff813ef08b)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff81400d69)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8140c445)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8140da4b)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8140e4a4)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81411867)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff81413f28)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff81416e39)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
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
In security/apparmor/apparmorfs.c (ffffffff81432098)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8143dea7)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8143e6f8)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81440028)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81443acb)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff81446292)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff8144917e)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8144de52)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8145ad07)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8145b5c8)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8145cf04)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814603d7)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff814631b2)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff814660f9)
Location: security/apparmor/include/policy_ns.h:116
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147b7c1)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff81488333)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81488b18)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8148a4b3)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8148d2c6)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff8149046d)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff8149366a)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81495491)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff814a21e3)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814a29c8)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff814a4373)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814a7186)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff814aa32d)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff814ad59a)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814ed51d)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff814fc47e)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814fd288)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff814ff1d5)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81504c41)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff81507fb9)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_find_ns
```
```
In security/apparmor/label.c (ffffffff8150c1fa)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8150ab9d)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff815196ee)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a4e8)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8151c415)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81521ae1)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff81524fb9)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff815290aa)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8151131d)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8151fff6)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81520de8)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81522bf4)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81527ec1)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff8152b169)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff8152f21a)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8156ef1d)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8157e196)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ef88)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81580e64)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81586151)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff81589509)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff8158d63a)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8160d5c2)
Location: security/apparmor/include/policy_ns.h:113
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8161c9d5)
Location: security/apparmor/include/policy_ns.h:113
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d438)
Location: security/apparmor/include/policy_ns.h:113
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81620001)
Location: security/apparmor/include/policy_ns.h:113
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/policy_ns.c (ffffffff8349c80a)
Location: security/apparmor/include/policy_ns.h:113
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff8162b41f)
Location: security/apparmor/include/policy_ns.h:113
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_get_current_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816bf542)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff816cfc75)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff816d07d8)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff816d34fe)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/policy_ns.c (ffffffff83ed3e4e)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_find_ns
```
```
In security/apparmor/label.c (ffffffff816dfcbf)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/notify.c (ffffffff816ea755)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_register_listener_proxy
  - security/apparmor/notify.c:aa_get_current_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f8052)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8170883e)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81709658)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8170c3ce)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/policy_ns.c (ffffffff836f8f8e)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_find_ns
```
```
In security/apparmor/label.c (ffffffff817192df)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/notify.c (ffffffff817245f5)
Location: security/apparmor/include/policy_ns.h:124
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_register_listener_proxy
  - security/apparmor/notify.c:aa_get_current_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81734dc5)
Location: security/apparmor/include/policy_ns.h:121
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff817462ce)
Location: security/apparmor/include/policy_ns.h:121
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81747178)
Location: security/apparmor/include/policy_ns.h:121
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8174a114)
Location: security/apparmor/include/policy_ns.h:121
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/policy_ns.c (ffffffff8392c39e)
Location: security/apparmor/include/policy_ns.h:121
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
```
```
In security/apparmor/label.c (ffffffff81757d82)
Location: security/apparmor/include/policy_ns.h:121
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/notify.c (ffffffff8176593c)
Location: security/apparmor/include/policy_ns.h:121
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_register_listener_proxy
  - security/apparmor/notify.c:aa_get_current_ns
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff80001058b534)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffff800010597d4c)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffff800010598690)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffff80001059a150)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffff80001059e15c)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffff8000105a0f40)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffff8000105a4a44)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c073c0d8)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (c0748f38)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (c074990c)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (c074b258)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (c074ed48)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (c07519d0)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (c0754c34)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006fc910)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (c00000000070e4e4)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (c00000000070f514)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (c000000000711688)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (c000000000716414)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (c00000000071b63c)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (c0000000007207a8)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003d9be6)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffe0003e46e0)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e49a8)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffe0003e675a)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffe0003e923a)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffe0003ebcc8)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffe0003eea1c)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148da71)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8149a7c3)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8149afa8)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8149c953)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149f766)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff814a290d)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff814a5b7a)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147e491)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8148b1e3)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8148b9c8)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8148d373)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81490186)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff8149332d)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff8149659a)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81489b11)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff81496863)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81497048)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff814989f3)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149b806)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff8149e9ad)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff814a1c1a)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a1796)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff814ae933)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814af118)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff814b0b49)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814b3b7c)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff814b6fdd)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In security/apparmor/label.c (ffffffff814ba3bf)
Location: security/apparmor/include/policy_ns.h:112
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
</ul>

## Differences
