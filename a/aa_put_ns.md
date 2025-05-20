# Function: <code>aa_put_ns</code>

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
In security/apparmor/apparmorfs.c (ffffffff81375334)
Location: security/apparmor/include/policy_ns.h:121
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
```
```
In security/apparmor/policy.c (ffffffff8137f92d)
Location: security/apparmor/include/policy_ns.h:121
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_may_open_profiles
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/procattr.c (ffffffff81382d58)
Location: security/apparmor/include/policy_ns.h:121
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81386c27)
Location: security/apparmor/include/policy_ns.h:121
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff8138d1d9)
Location: security/apparmor/include/policy_ns.h:121
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_printk
```
```
In security/apparmor/policy_ns.c (ffffffff81394867)
Location: security/apparmor/include/policy_ns.h:121
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:aa_free_root_ns
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
In security/apparmor/apparmorfs.c (ffffffff813abb89)
Location: security/apparmor/include/policy_ns.h:123
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff813ba8ff)
Location: security/apparmor/include/policy_ns.h:123
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
```
```
In security/apparmor/procattr.c (ffffffff813bcff8)
Location: security/apparmor/include/policy_ns.h:123
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813c15b9)
Location: security/apparmor/include/policy_ns.h:123
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff813c841e)
Location: security/apparmor/include/policy_ns.h:123
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
```
In security/apparmor/policy_ns.c (ffffffff81fc45c4)
Location: security/apparmor/include/policy_ns.h:123
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:aa_free_ns
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
In security/apparmor/apparmorfs.c (ffffffff813c27c6)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff813d26f5)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
```
```
In security/apparmor/procattr.c (ffffffff813d4428)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813d8a59)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff813df9fe)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
```
In security/apparmor/policy_ns.c (ffffffff82000ffb)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:aa_free_ns
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
In security/apparmor/apparmorfs.c (ffffffff813d9f2c)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff813e530d)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813e68fe)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff813e72f8)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813e98f2)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff820e4842)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff813ef0ea)
Location: security/apparmor/include/policy_ns.h:130
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
In security/apparmor/apparmorfs.c (ffffffff81400dfb)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8140c4e9)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8140da84)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8140e512)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814118d7)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff826ed4e0)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff81416e8b)
Location: security/apparmor/include/policy_ns.h:130
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
In security/apparmor/apparmorfs.c (ffffffff814309d1)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8143de29)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8143e734)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff814400ea)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81443b28)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff8271783c)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff814491e0)
Location: security/apparmor/include/policy_ns.h:130
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
In security/apparmor/apparmorfs.c (ffffffff8144d6e1)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8145ac89)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8145b604)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8145cfd2)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81460440)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff828cf294)
Location: security/apparmor/include/policy_ns.h:130
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff81466166)
Location: security/apparmor/include/policy_ns.h:130
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
In security/apparmor/apparmorfs.c (ffffffff8147b3b1)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff814882b3)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81488b54)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8148a580)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8148d32e)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff828e8cfc)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff814936d2)
Location: security/apparmor/include/policy_ns.h:126
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
In security/apparmor/apparmorfs.c (ffffffff81495081)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff814a2163)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2a04)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff814a4440)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814a71ee)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff828f17e8)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff814ad602)
Location: security/apparmor/include/policy_ns.h:126
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
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void aa_put_ns(struct aa_ns *ns);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814ec391)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff814fc3e1)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814fd2de)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff814ff2c7)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81504cf0)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff81508074)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
```
```
In security/apparmor/label.c (ffffffff8150c28c)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
**Symbols:**

```
ffffffff81507550-ffffffff81507595: aa_put_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void aa_put_ns(struct aa_ns *ns);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81509bb1)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff81519651)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a53e)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8151c507)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81521b90)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff81525074)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
```
```
In security/apparmor/label.c (ffffffff8152913c)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
**Symbols:**

```
ffffffff815245f0-ffffffff81524635: aa_put_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void aa_put_ns(struct aa_ns *ns);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff815105d1)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8151ff59)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81520e3a)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81522cdb)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81527f63)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff8152b224)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
```
```
In security/apparmor/label.c (ffffffff8152f2a8)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
**Symbols:**

```
ffffffff8152a7c0-ffffffff8152a805: aa_put_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void aa_put_ns(struct aa_ns *ns);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8156e1d1)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8157e0f9)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8157efda)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81580f4b)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff815861f3)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff815895c4)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
```
```
In security/apparmor/label.c (ffffffff8158d6c8)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
**Symbols:**

```
ffffffff81588b60-ffffffff81588ba5: aa_put_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void aa_put_ns(struct aa_ns *ns);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8160d66d)
Location: security/apparmor/include/policy_ns.h:127
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8161c86d)
Location: security/apparmor/include/policy_ns.h:127
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d48e)
Location: security/apparmor/include/policy_ns.h:127
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff816200e7)
Location: security/apparmor/include/policy_ns.h:127
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/policy_ns.c (ffffffff81629e24)
Location: security/apparmor/include/policy_ns.h:127
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
```
```
In security/apparmor/label.c (ffffffff8162e4af)
Location: security/apparmor/include/policy_ns.h:127
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
**Symbols:**

```
ffffffff81629250-ffffffff816292c5: aa_put_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void aa_put_ns(struct aa_ns *ns);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816bf5ed)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff816cfb0d)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff816d082e)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff816d35f2)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
Direct callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/policy_ns.c (ffffffff83ed3f15)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff816e306f)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
```
In security/apparmor/notify.c (ffffffff816e9c47)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:aa_free_listener_proxy
```
**Symbols:**

```
ffffffff816d3400-ffffffff816d3475: aa_put_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void aa_put_ns(struct aa_ns *ns);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f80fd)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8170872d)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff817096ae)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8170c4c2)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
Direct callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/policy_ns.c (ffffffff836f9055)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff8171c5df)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
```
In security/apparmor/notify.c (ffffffff8172523a)
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:aa_free_listener_proxy
```
**Symbols:**

```
ffffffff8170c2d0-ffffffff8170c345: aa_put_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void aa_put_ns(struct aa_ns *ns);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81734e73)
Location: security/apparmor/include/policy_ns.h:135
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff817461bd)
Location: security/apparmor/include/policy_ns.h:135
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff817471ce)
Location: security/apparmor/include/policy_ns.h:135
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8174a205)
Location: security/apparmor/include/policy_ns.h:135
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
Direct callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/policy_ns.c (ffffffff8392c465)
Location: security/apparmor/include/policy_ns.h:135
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff8175b02f)
Location: security/apparmor/include/policy_ns.h:135
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
```
In security/apparmor/notify.c (ffffffff817663ca)
Location: security/apparmor/include/policy_ns.h:135
Inline: True
Inline callers:
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:aa_free_listener_proxy
```
**Symbols:**

```
ffffffff8174a010-ffffffff8174a085: aa_put_ns (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffff80001058b0c8)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffff800010597cd4)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffff8000105986c4)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffff80001059a204)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffff80001059e1a4)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffff80001146ba10)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffff8000105a4a9c)
Location: security/apparmor/include/policy_ns.h:126
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
In security/apparmor/apparmorfs.c (c073bc58)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (c0748ec4)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (c0749948)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (c074b340)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (c074edb4)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (c154467c)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (c0754ca4)
Location: security/apparmor/include/policy_ns.h:126
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
In security/apparmor/apparmorfs.c (c0000000006fc540)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (c00000000070e404)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (c00000000070f568)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (c000000000711794)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (c0000000007164c0)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (c00000000139a58c)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (c00000000072083c)
Location: security/apparmor/include/policy_ns.h:126
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
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void aa_put_ns(struct aa_ns *ns);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003d989a)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffe0003e4770)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e49de)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffe0003e67f8)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffe0003e9280)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffe0003ebd46)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
```
```
In security/apparmor/label.c (ffffffe0003eea5c)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
**Symbols:**

```
ffffffe0003eb56a-ffffffe0003eb59c: aa_put_ns (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff8148d661)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8149a743)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8149afe4)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8149ca20)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149f7ce)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff828da69c)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff814a5be2)
Location: security/apparmor/include/policy_ns.h:126
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
In security/apparmor/apparmorfs.c (ffffffff8147e081)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff8148b163)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8148ba04)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8148d440)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814901ee)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff828d2db8)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff81496602)
Location: security/apparmor/include/policy_ns.h:126
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
In security/apparmor/apparmorfs.c (ffffffff81489701)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff814967e3)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81497084)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81498ac0)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149b86e)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff828ed410)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff814a1c82)
Location: security/apparmor/include/policy_ns.h:126
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
In security/apparmor/apparmorfs.c (ffffffff814a1361)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/policy.c (ffffffff814ae8b3)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814af154)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff814b0c1c)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814b3bea)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/policy_ns.c (ffffffff828f2832)
Location: security/apparmor/include/policy_ns.h:126
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffff814ba42c)
Location: security/apparmor/include/policy_ns.h:126
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
<b>Arch</b>
<ul>
</ul>
