# Function: <code>selinux_initialized</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b904a)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/ss/services.c (ffffffff814cdbbb)
Location: security/selinux/include/security.h:127
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_preserve_bools
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_sidtab_hash_stats
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_validate_transition_user
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
In security/selinux/hooks.c (ffffffff814d5509)
Location: security/selinux/include/security.h:114
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/ss/services.c (ffffffff814eb0f5)
Location: security/selinux/include/security.h:114
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_allow_unknown
  - security/selinux/ss/services.c:security_get_reject_unknown
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_sidtab_hash_stats
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_validate_transition_user
  - security/selinux/ss/services.c:security_mls_enabled
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
In security/selinux/hooks.c (ffffffff814dc329)
Location: security/selinux/include/security.h:114
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/ss/services.c (ffffffff814f1dc5)
Location: security/selinux/include/security.h:114
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_allow_unknown
  - security/selinux/ss/services.c:security_get_reject_unknown
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_sidtab_hash_stats
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_validate_transition_user
  - security/selinux/ss/services.c:security_mls_enabled
```
```
In security/selinux/ima.c (ffffffff814f5fac)
Location: security/selinux/include/security.h:114
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/selinux/ima.c:selinux_ima_collect_state
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
In security/selinux/hooks.c (ffffffff815357dc)
Location: security/selinux/include/security.h:114
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/ss/services.c (ffffffff8154c4a5)
Location: security/selinux/include/security.h:114
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_allow_unknown
  - security/selinux/ss/services.c:security_get_reject_unknown
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_sidtab_hash_stats
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_validate_transition_user
  - security/selinux/ss/services.c:security_mls_enabled
```
```
In security/selinux/ima.c (ffffffff81550afd)
Location: security/selinux/include/security.h:114
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/selinux/ima.c:selinux_ima_collect_state
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
In security/selinux/hooks.c (ffffffff815c6c75)
Location: security/selinux/include/security.h:116
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_listsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_add_opt
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/ss/services.c (ffffffff815e5345)
Location: security/selinux/include/security.h:116
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_allow_unknown
  - security/selinux/ss/services.c:security_get_reject_unknown
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_sidtab_hash_stats
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_validate_transition_user
  - security/selinux/ss/services.c:security_mls_enabled
```
```
In security/selinux/ima.c (ffffffff815e9fc4)
Location: security/selinux/include/security.h:116
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/selinux/ima.c:selinux_ima_collect_state
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
In security/selinux/hooks.c (ffffffff81674135)
Location: security/selinux/include/security.h:116
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_listsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_add_opt
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/ss/services.c (ffffffff816947a5)
Location: security/selinux/include/security.h:116
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_allow_unknown
  - security/selinux/ss/services.c:security_get_reject_unknown
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_sidtab_hash_stats
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_validate_transition_user
  - security/selinux/ss/services.c:security_mls_enabled
```
```
In security/selinux/ima.c (ffffffff81699964)
Location: security/selinux/include/security.h:116
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/selinux/ima.c:selinux_ima_collect_state
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
In security/selinux/hooks.c (ffffffff816ac945)
Location: security/selinux/include/security.h:111
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_listsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_add_opt
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/ss/services.c (ffffffff816ccca5)
Location: security/selinux/include/security.h:111
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_allow_unknown
  - security/selinux/ss/services.c:security_get_reject_unknown
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_sidtab_hash_stats
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_validate_transition_user
  - security/selinux/ss/services.c:security_mls_enabled
```
```
In security/selinux/ima.c (ffffffff816d215f)
Location: security/selinux/include/security.h:111
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/selinux/ima.c:selinux_ima_collect_state
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
In security/selinux/hooks.c (ffffffff816e9cb5)
Location: security/selinux/include/security.h:110
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_listsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_add_opt
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/ss/services.c (ffffffff817092a5)
Location: security/selinux/include/security.h:110
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_allow_unknown
  - security/selinux/ss/services.c:security_get_reject_unknown
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_sidtab_hash_stats
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_validate_transition_user
  - security/selinux/ss/services.c:security_mls_enabled
```
```
In security/selinux/ima.c (ffffffff8170e7bf)
Location: security/selinux/include/security.h:110
Inline: True
Inline callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/selinux/ima.c:selinux_ima_collect_state
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
