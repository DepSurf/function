# Function: <code>get_net</code>

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
In kernel/audit.c (ffffffff81121d55)
Location: include/net/net_namespace.h:182
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81125388)
Location: include/net/net_namespace.h:182
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In fs/proc/proc_net.c (ffffffff8128648e)
Location: include/net/net_namespace.h:182
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In net/core/sock.c (ffffffff817013b4)
Location: include/net/net_namespace.h:182
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/net_namespace.c (ffffffff8170fa5f)
Location: include/net/net_namespace.h:182
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff8172b6b8)
Location: include/net/net_namespace.h:182
Inline: True
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
In kernel/audit.c (ffffffff81129c95)
Location: include/net/net_namespace.h:185
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8112d425)
Location: include/net/net_namespace.h:185
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In fs/proc/proc_net.c (ffffffff812b362f)
Location: include/net/net_namespace.h:185
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81656357)
Location: include/net/net_namespace.h:185
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/core/sock.c (ffffffff8176a822)
Location: include/net/net_namespace.h:185
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff81777d7f)
Location: include/net/net_namespace.h:185
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:get_net_ns_by_id
```
```
In net/core/rtnetlink.c (ffffffff81794e35)
Location: include/net/net_namespace.h:185
Inline: True
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
In kernel/audit.c (ffffffff811339b5)
Location: include/net/net_namespace.h:186
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81137155)
Location: include/net/net_namespace.h:186
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In fs/proc/proc_net.c (ffffffff812c8e7f)
Location: include/net/net_namespace.h:186
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81684041)
Location: include/net/net_namespace.h:186
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffff8178f18c)
Location: include/net/net_namespace.h:186
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff81797942)
Location: include/net/net_namespace.h:186
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff817a4d62)
Location: include/net/net_namespace.h:186
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:get_net_ns_by_id
```
```
In net/core/rtnetlink.c (ffffffff817c26b5)
Location: include/net/net_namespace.h:186
Inline: True
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
In kernel/audit.c (ffffffff811367a9)
Location: include/net/net_namespace.h:194
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff81138438)
Location: include/net/net_namespace.h:194
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In fs/proc/proc_net.c (ffffffff812d6181)
Location: include/net/net_namespace.h:194
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81699071)
Location: include/net/net_namespace.h:194
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffff817ad18c)
Location: include/net/net_namespace.h:194
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff817b5512)
Location: include/net/net_namespace.h:194
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff817c2f7f)
Location: include/net/net_namespace.h:194
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:get_net_ns_by_id
```
```
In net/core/rtnetlink.c (ffffffff817e0fe1)
Location: include/net/net_namespace.h:194
Inline: True
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
In kernel/audit.c (ffffffff81143139)
Location: include/net/net_namespace.h:196
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff81145148)
Location: include/net/net_namespace.h:196
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In fs/proc/proc_net.c (ffffffff812fa9c1)
Location: include/net/net_namespace.h:196
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81705e61)
Location: include/net/net_namespace.h:196
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffff8182518c)
Location: include/net/net_namespace.h:196
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff8182d99e)
Location: include/net/net_namespace.h:196
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff8183cacf)
Location: include/net/net_namespace.h:196
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff8185b741)
Location: include/net/net_namespace.h:196
Inline: True
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
In kernel/audit.c (ffffffff81151aa0)
Location: include/net/net_namespace.h:215
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff81153ac7)
Location: include/net/net_namespace.h:215
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff811cb8eb)
Location: include/net/net_namespace.h:215
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/proc/proc_net.c (ffffffff81327f94)
Location: include/net/net_namespace.h:215
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81743b61)
Location: include/net/net_namespace.h:215
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffff8186f1b5)
Location: include/net/net_namespace.h:215
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff81877d40)
Location: include/net/net_namespace.h:215
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff81887110)
Location: include/net/net_namespace.h:215
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff818a76f5)
Location: include/net/net_namespace.h:215
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819ca896)
Location: include/net/net_namespace.h:215
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (ffffffff8115e755)
Location: include/net/net_namespace.h:218
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff81160857)
Location: include/net/net_namespace.h:218
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff811df0c0)
Location: include/net/net_namespace.h:218
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/proc/proc_net.c (ffffffff8133f17e)
Location: include/net/net_namespace.h:218
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81766811)
Location: include/net/net_namespace.h:218
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffff8188f635)
Location: include/net/net_namespace.h:218
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff81898220)
Location: include/net/net_namespace.h:218
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff818a7820)
Location: include/net/net_namespace.h:218
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff818cb0e5)
Location: include/net/net_namespace.h:218
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a033cd)
Location: include/net/net_namespace.h:218
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (ffffffff8116ad72)
Location: include/net/net_namespace.h:227
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff8116ced7)
Location: include/net/net_namespace.h:227
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff811f4a3f)
Location: include/net/net_namespace.h:227
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff8130a66f)
Location: include/net/net_namespace.h:227
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff813674b1)
Location: include/net/net_namespace.h:227
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a5662)
Location: include/net/net_namespace.h:227
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffff818d9695)
Location: include/net/net_namespace.h:227
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff818e2782)
Location: include/net/net_namespace.h:227
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff818f2d15)
Location: include/net/net_namespace.h:227
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff81917b25)
Location: include/net/net_namespace.h:227
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a7264d)
Location: include/net/net_namespace.h:227
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (ffffffff81176c1d)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff81178d77)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff81201a4f)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff8131d62f)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff8137f731)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c7cc2)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffff8190b695)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff81914952)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff81924c75)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff8194a145)
Location: include/net/net_namespace.h:236
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa8e0d)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (ffffffff81189939)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff8118bfc2)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff8122917f)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff813576e2)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff813c9a01)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818923f3)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffff819dee85)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff819e6eb2)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff819f8d1d)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff81a1a541)
Location: include/net/net_namespace.h:246
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba559e)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/subflow.c (ffffffff81bafbc0)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/audit.c (ffffffff81183f37)
Location: include/net/net_namespace.h:240
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_set
```
```
In kernel/auditfilter.c (ffffffff811891d2)
Location: include/net/net_namespace.h:240
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff81230d0f)
Location: include/net/net_namespace.h:240
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff813640c2)
Location: include/net/net_namespace.h:240
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff813db671)
Location: include/net/net_namespace.h:240
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a090b)
Location: include/net/net_namespace.h:240
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffff819de715)
Location: include/net/net_namespace.h:240
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff819e66e2)
Location: include/net/net_namespace.h:240
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff819f87f3)
Location: include/net/net_namespace.h:240
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff81a1a5b1)
Location: include/net/net_namespace.h:240
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb4a6e)
Location: include/net/net_namespace.h:240
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/subflow.c (ffffffff81bc3663)
Location: include/net/net_namespace.h:240
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/audit.c (ffffffff81187c8f)
Location: include/net/net_namespace.h:241
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff81189f98)
Location: include/net/net_namespace.h:241
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff81234eaf)
Location: include/net/net_namespace.h:241
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff8136ab42)
Location: include/net/net_namespace.h:241
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff813e25a1)
Location: include/net/net_namespace.h:241
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882f9b)
Location: include/net/net_namespace.h:241
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/core/sock.c (ffffffff819cc4f2)
Location: include/net/net_namespace.h:241
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff819df023)
Location: include/net/net_namespace.h:241
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:get_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff81a015bc)
Location: include/net/net_namespace.h:241
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba3a4e)
Location: include/net/net_namespace.h:241
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/subflow.c (ffffffff81bb3cd3)
Location: include/net/net_namespace.h:241
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/audit.c (ffffffff811b00ef)
Location: include/net/net_namespace.h:243
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff811b29d8)
Location: include/net/net_namespace.h:243
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff8126efdf)
Location: include/net/net_namespace.h:243
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff813b9802)
Location: include/net/net_namespace.h:243
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff814340b1)
Location: include/net/net_namespace.h:243
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8191493b)
Location: include/net/net_namespace.h:243
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/core/sock.c (ffffffff81a7bb42)
Location: include/net/net_namespace.h:243
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff81a8f403)
Location: include/net/net_namespace.h:243
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:get_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff81ab379c)
Location: include/net/net_namespace.h:243
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c7104e)
Location: include/net/net_namespace.h:243
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/subflow.c (ffffffff81c82412)
Location: include/net/net_namespace.h:243
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/audit.c (ffffffff811e22d9)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff811e4d38)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff812bdf40)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff8143f26d)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff814ae136)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69f51)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/core/sock.c (ffffffff81bef9ce)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff81c05263)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:get_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff81c2c3b9)
Location: include/net/net_namespace.h:246
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e14c3e)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/subflow.c (ffffffff81e28144)
Location: include/net/net_namespace.h:246
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/audit.c (ffffffff8122817d)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff8122ad58)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff813215c0)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff814ce134)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff81544706)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfcb51)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/core/sock.c (ffffffff81d9c81b)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff81db4af3)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:get_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff81ddf489)
Location: include/net/net_namespace.h:256
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81febb4e)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/subflow.c (ffffffff820000a6)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/audit.c (ffffffff8123e78c)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff81241358)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff81351120)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff81504334)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff8157c306)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c621d1)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/core/sock.c (ffffffff81e0b077)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff81e25193)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:get_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff81e507a9)
Location: include/net/net_namespace.h:256
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82067dee)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/subflow.c (ffffffff8207c211)
Location: include/net/net_namespace.h:256
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/audit.c (ffffffff81255084)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_set
```
```
In kernel/auditfilter.c (ffffffff8125b187)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff81378580)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff81538ff6)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff815b4c16)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18c00)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/core/sock.c (ffffffff81ec7a67)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff81ee30f3)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:get_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff81f0f849)
Location: include/net/net_namespace.h:258
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b06e)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/subflow.c (ffffffff821516cb)
Location: include/net/net_namespace.h:258
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/audit.c (ffff8000101ebbd4)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffff8000101edeb4)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffff800010289984)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffff8000103d5a58)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffff80001044d088)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a0033c)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffff800010ba1778)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffff800010bad774)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffff800010bc0718)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffff800010beba84)
Location: include/net/net_namespace.h:236
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d3d4)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (c042b7e0)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (c042dfd4)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (c04b91e4)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (c05af418)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (c061162c)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (c0add708)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (c0cc3758)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (c0ccb30c)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (c0cdc37c)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (c0d045c8)
Location: include/net/net_namespace.h:236
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (c0e77280)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (c00000000025d20c)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (c000000000260994)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (c000000000335074)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (c0000000004d8310)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (c0000000005645f4)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa80d0)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (c000000000c749f8)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (c000000000c83048)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (c000000000c9a0b8)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (c000000000cced90)
Location: include/net/net_namespace.h:236
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebbab8)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (ffffffe00016031c)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffe000162314)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffe0001bdc0e)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffe00028f504)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffe0002e1d62)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062cada)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffe0007388d8)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffe00073f98a)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffe00074e194)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffe00076f132)
Location: include/net/net_namespace.h:236
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aa2c2)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (ffffffff8116f23d)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff81171397)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff811fa06f)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff81315c0f)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff81377d11)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178c7a2)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffff818ab695)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff818b4952)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff818c4c75)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff818ea115)
Location: include/net/net_namespace.h:236
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a4819d)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (ffffffff811623dd)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff81164537)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff811ecdbf)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff813067ff)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff813687e1)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81775572)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffff818655e5)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff8186e8a2)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff8187ebb5)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff818a3f55)
Location: include/net/net_namespace.h:236
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a04d8d)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (ffffffff8116d00d)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff8116f167)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff811f7e3f)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff813139ff)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff813757e1)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bcb42)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffff818fc695)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff81905952)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff81915c75)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff8193b145)
Location: include/net/net_namespace.h:236
Inline: True
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199bbf1)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab404d)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (ffffffff8117a7f8)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
```
```
In kernel/auditfilter.c (ffffffff8117c957)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/offload.c (ffffffff812063bf)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In fs/fs_context.c (ffffffff8132524f)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc/proc_net.c (ffffffff8138928a)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d774d)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/socket.c (ffffffff8191d695)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff81926974)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/net_namespace.c (ffffffff81936e75)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/rtnetlink.c (ffffffff8195c985)
Location: include/net/net_namespace.h:236
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac03ed)
Location: include/net/net_namespace.h:236
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
</details>
</li>
</ul>

## Differences
