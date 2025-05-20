# Function: <code>kmemdup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *kmemdup(const void *src, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811abcb0)
Location: mm/util.c:109
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - kernel/cgroup.c:cgroup_init_cftypes
  - kernel/cpuset.c:alloc_trial_cpuset
  - mm/shmem.c:shmem_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/device_cgroup.c:dev_exception_add
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/property.c:device_add_property_set
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/block/xen-blkfront.c:blkif_recover
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/fib_rules.c:fib_rules_register
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff811abcb0-ffffffff811abcf1: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *kmemdup(const void *src, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c4730)
Location: mm/util.c:109
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - kernel/cgroup.c:cgroup_init_cftypes
  - kernel/cpuset.c:alloc_trial_cpuset
  - mm/shmem.c:shmem_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/fuse/dir.c:fuse_setxattr
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/property.c:device_add_properties
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/fib_rules.c:fib_rules_register
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff811c4730-ffffffff811c4771: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *kmemdup(const void *src, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4820)
Location: mm/util.c:109
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/cpu/microcode/intel.c:__alloc_microcode_buf
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/cgroup.c:cgroup_init_cftypes
  - kernel/cpuset.c:alloc_trial_cpuset
  - mm/shmem.c:shmem_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/fuse/xattr.c:fuse_setxattr
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/property.c:device_add_properties
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/fib_rules.c:fib_rules_register
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/sched/act_api.c:nla_memdup_cookie
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff811d4820-ffffffff811d4861: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102b00b)
Location: include/linux/string.h:375
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/cpu/microcode/intel.c:__alloc_microcode_buf
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - mm/shmem.c:shmem_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/keys/key.c:key_alloc
  - security/keys/dh.c:dh_data_from_key
  - security/security.c:security_setprocattr
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/property.c:property_entries_dup
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/fib_rules.c:fib_rules_register
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff811dd470-ffffffff811dd4ac: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102bd36)
Location: include/linux/string.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - mm/shmem.c:shmem_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/property.c:property_entries_dup
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff811f2ef0-ffffffff811f2f2c: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102cd66)
Location: include/linux/string.h:411
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - mm/shmem.c:shmem_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/property.c:property_entries_dup
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
**Symbols:**

```
ffffffff812141e0-ffffffff8121421c: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102dfb6)
Location: include/linux/string.h:418
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - mm/shmem.c:shmem_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:pstore_get_backend_records
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/security.c:security_setprocattr
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/integrity/ima/ima_policy.c:add_rules
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/swnode.c:property_entries_dup
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
**Symbols:**

```
ffffffff812270b0-ffffffff812270ec: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fd15)
Location: include/linux/string.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/io_uring.c:io_submit_sqe
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:pstore_get_backend_records
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/security.c:security_setprocattr
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/integrity/ima/ima_policy.c:add_rules
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
**Symbols:**

```
ffffffff81236bb0-ffffffff81236bee: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030675)
Location: include/linux/string.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:pstore_get_backend_records
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/security.c:security_setprocattr
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/integrity/ima/ima_policy.c:add_rules
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
**Symbols:**

```
ffffffff81244d70-ffffffff81244dae: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81037201)
Location: include/linux/string.h:472
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/module.c:copy_module_elf
  - kernel/module.c:copy_module_elf
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/keyring.c:fscrypt_provisioning_key_preparse
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/device_cgroup.c:dev_exceptions_copy
  - security/integrity/ima/ima_queue_keys.c:ima_alloc_key_entry
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/sed-opal.c:get_active_key_cont
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - net/core/scm.c:scm_fp_dup
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:bpf_prog_store_orig_filter
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_metadata_clone
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/sched/act_api.c:nla_memdup_cookie
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/mptcp/ctrl.c:mptcp_net_init
```
**Symbols:**

```
ffffffff81272a20-ffffffff81272a5e: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff810382c1)
Location: include/linux/string.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/module.c:copy_module_elf
  - kernel/module.c:copy_module_elf
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/io_uring.c:io_identity_cow
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/keyring.c:fscrypt_provisioning_key_preparse
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:decompress_record
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/conditional.c:cond_bools_copy
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/device_cgroup.c:dev_exceptions_copy
  - security/integrity/ima/ima_policy.c:ima_lsm_copy_rule
  - security/integrity/ima/ima_queue_keys.c:ima_alloc_key_entry
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/partitions/core.c:add_partition
  - block/sed-opal.c:get_active_key_cont
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - net/core/scm.c:scm_fp_dup
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:bpf_prog_store_orig_filter
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_metadata_copy
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/sched/act_api.c:nla_memdup_cookie
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/mptcp/ctrl.c:mptcp_net_init
```
**Symbols:**

```
ffffffff8127d0d0-ffffffff8127d10e: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81039e01)
Location: include/linux/fortify-string.h:262
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/module.c:copy_module_elf
  - kernel/module.c:copy_module_elf
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/keyring.c:fscrypt_provisioning_key_preparse
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:decompress_record
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/conditional.c:cond_bools_copy
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/device_cgroup.c:dev_exceptions_copy
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/partitions/core.c:add_partition
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - net/core/scm.c:scm_fp_dup
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prog_store_orig_filter
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/mptcp/ctrl.c:mptcp_net_init
```
**Symbols:**

```
ffffffff81282270-ffffffff812822ae: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff8103f7b1)
Location: include/linux/fortify-string.h:262
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/module.c:copy_module_elf
  - kernel/module.c:copy_module_elf
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/keyring.c:fscrypt_provisioning_key_preparse
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:decompress_record
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_bools_copy
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/device_cgroup.c:dev_exceptions_copy
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/partitions/core.c:add_partition
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/clk/versatile/clk-icst.c:icst_clk_setup
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - net/core/scm.c:scm_fp_dup
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prog_store_orig_filter
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/mptcp/ctrl.c:mptcp_net_init
```
**Symbols:**

```
ffffffff812c02e0-ffffffff812c031e: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const const void * p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81046edd)
Location: include/linux/fortify-string.h:448
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:msi_add_msi_desc
  - kernel/module/livepatch.c:copy_module_elf
  - kernel/module/livepatch.c:copy_module_elf
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - kernel/bpf/syscall.c:bpf_map_copy_kptr_off_tab
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/keyring.c:fscrypt_provisioning_key_preparse
  - fs/posix_acl.c:posix_acl_clone
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:decompress_record
  - ipc/ipc_sysctl.c:setup_ipc_sysctls
  - ipc/mq_sysctl.c:setup_mq_sysctls
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_bools_copy
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/device_cgroup.c:dev_exceptions_copy
  - security/integrity/ima/ima_policy.c:add_rules
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/partitions/core.c:add_partition
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - net/core/scm.c:scm_fp_dup
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prog_store_orig_filter
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/mptcp/ctrl.c:mptcp_net_init
```
**Symbols:**

```
ffffffff8131cd60-ffffffff8131cda8: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const const void * p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff8105103d)
Location: include/linux/fortify-string.h:687
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/module/livepatch.c:copy_module_elf
  - kernel/module/livepatch.c:copy_module_elf
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/keyring.c:fscrypt_provisioning_key_preparse
  - fs/posix_acl.c:posix_acl_clone
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:decompress_record
  - ipc/ipc_sysctl.c:setup_ipc_sysctls
  - ipc/mq_sysctl.c:setup_mq_sysctls
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_bools_copy
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/device_cgroup.c:dev_exceptions_copy
  - security/integrity/ima/ima_policy.c:ima_lsm_copy_rule
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/partitions/core.c:add_partition
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-spi.c:regmap_get_spi_bus
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_reset_rsc_table_on_detach
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - net/core/scm.c:scm_fp_dup
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prog_store_orig_filter
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/inet_hashtables.c:inet_pernet_hashinfo_alloc
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/mptcp/ctrl.c:mptcp_net_init
```
**Symbols:**

```
ffffffff81390eb0-ffffffff81390efd: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const const void * p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81051d6e)
Location: include/linux/fortify-string.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/module/livepatch.c:copy_module_elf
  - kernel/module/livepatch.c:copy_module_elf
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - kernel/bpf/syscall.c:btf_record_dup
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/keyring.c:fscrypt_provisioning_key_preparse
  - fs/posix_acl.c:posix_acl_clone
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:decompress_record
  - ipc/ipc_sysctl.c:setup_ipc_sysctls
  - ipc/mq_sysctl.c:setup_mq_sysctls
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/selinux/hooks.c:selinux_fs_context_dup
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_bools_copy
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/apparmor/policy_unpack.c:aa_unpack_strdup
  - security/device_cgroup.c:dev_exception_add
  - security/device_cgroup.c:dev_exceptions_copy
  - security/integrity/ima/ima_policy.c:ima_lsm_copy_rule
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/partitions/core.c:add_partition
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/char/virtio_console.c:put_chars
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-spi.c:regmap_get_spi_bus
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_dup_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_dup_rule
  - drivers/usb/core/message.c:usb_control_msg_send
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_hw_request
  - drivers/hid/bpf/hid_bpf_dispatch.c:call_hid_bpf_rdesc_fixup
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_reset_rsc_table_on_detach
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - net/core/scm.c:scm_fp_dup
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prog_store_orig_filter
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/inet_hashtables.c:inet_pernet_hashinfo_alloc
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/mptcp/ctrl.c:mptcp_net_init
```
**Symbols:**

```
ffffffff813c37c0-ffffffff813c380d: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const const void * p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81058f8e)
Location: include/linux/fortify-string.h:702
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/module/livepatch.c:copy_module_elf
  - kernel/module/livepatch.c:copy_module_elf
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/memalloc.c:destroy_mem_alloc
  - mm/shmem.c:shmem_symlink
  - mm/memory_hotplug.c:create_altmaps_and_memory_blocks
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/mnt_idmapping.c:copy_mnt_idmap
  - fs/mnt_idmapping.c:copy_mnt_idmap
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/keyring.c:fscrypt_provisioning_key_preparse
  - fs/posix_acl.c:posix_acl_clone
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - ipc/ipc_sysctl.c:setup_ipc_sysctls
  - ipc/mq_sysctl.c:setup_mq_sysctls
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/conditional.c:cond_policydb_dup
  - security/selinux/ss/conditional.c:cond_bools_copy
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/apparmor/policy_unpack.c:aa_unpack_strdup
  - security/device_cgroup.c:dev_exception_add
  - security/device_cgroup.c:dev_exceptions_copy
  - security/integrity/ima/ima_policy.c:ima_lsm_copy_rule
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/partitions/core.c:add_partition
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/char/virtio_console.c:put_chars
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regmap-i2c.c:regmap_get_i2c_bus
  - drivers/base/regmap/regmap-spi.c:regmap_get_spi_bus
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/gpu/drm/drm_connector.c:drm_display_info_set_bus_formats
  - drivers/gpu/drm/drm_edid.c:drm_edid_to_speaker_allocation
  - drivers/gpu/drm/drm_edid.c:drm_edid_duplicate
  - drivers/gpu/drm/drm_edid.c:drm_edid_alloc
  - drivers/gpu/drm/drm_edid.c:_drm_do_get_edid
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_dup_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_dup_rule
  - drivers/usb/core/message.c:usb_control_msg_send
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_hw_request
  - drivers/hid/bpf/hid_bpf_dispatch.c:call_hid_bpf_rdesc_fixup
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_reset_rsc_table_on_detach
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - drivers/dpll/dpll_core.c:dpll_pin_prop_dup
  - net/core/scm.c:scm_fp_dup
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prog_store_orig_filter
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/inet_hashtables.c:inet_pernet_hashinfo_alloc
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
  - net/mptcp/ctrl.c:mptcp_net_init
```
**Symbols:**

```
ffffffff813ee380-ffffffff813ee3cd: kmemdup (STB_GLOBAL)
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
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffff800010130164)
Location: include/linux/string.h:446
Inline: True
Inline callers:
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:pstore_get_backend_records
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/security.c:security_setprocattr
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pci/pci-bridge-emul.c:pci_bridge_emul_init
  - drivers/pci/pci-bridge-emul.c:pci_bridge_emul_init
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/clk/rockchip/clk-pll.c:rockchip_clk_register_pll
  - drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/thermal/of-thermal.c:of_parse_thermal_zones
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/cpuidle/cpuidle-arm.c:arm_idle_init
  - drivers/cpuidle/cpuidle-psci.c:psci_idle_init
  - drivers/of/dynamic.c:__of_prop_dup
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
**Symbols:**

```
ffff8000102d7cd0-ffff8000102d7d20: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mm/cache-l2x0.c (c150a110)
Location: include/linux/string.h:446
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0.c:__l2c_init
  - arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init_module
  - arch/arm/mach-omap2/omap_device.c:omap_device_alloc
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:pstore_get_backend_records
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/security.c:security_setprocattr
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_wkup_init
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pci/pci-bridge-emul.c:pci_bridge_emul_init
  - drivers/pci/pci-bridge-emul.c:pci_bridge_emul_init
  - drivers/clk/rockchip/clk-pll.c:rockchip_clk_register_pll
  - drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk
  - drivers/clk/samsung/clk-pll.c:samsung_clk_register_pll
  - drivers/clk/samsung/clk-cpu.c:exynos_register_cpu_clock
  - drivers/clk/ti/dpll.c:of_ti_dpll_setup
  - drivers/clk/versatile/clk-icst.c:icst_clk_setup
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/mtd/mtdconcat.c:concat_writev
  - drivers/mtd/parsers/cmdlinepart.c:parse_cmdline_partitions
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/thermal/of-thermal.c:of_parse_thermal_zones
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/cpuidle/cpuidle-arm.c:arm_idle_init
  - drivers/cpuidle/cpuidle-psci.c:psci_idle_init
  - drivers/of/dynamic.c:__of_prop_dup
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked
  - sound/soc/soc-ops.c:snd_soc_bytes_put
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/filter.c:bpf_prog_store_orig_filter
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
**Symbols:**

```
c04ff1a4-c04ff1e4: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/nvram_64.c (c0000000000367cc)
Location: include/linux/string.h:446
Inline: True
Inline callers:
  - arch/powerpc/kernel/nvram_64.c:nvram_pstore_read
  - arch/powerpc/platforms/pseries/dlpar.c:queue_hotplug_event
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_configure_connector
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:pstore_get_backend_records
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/security.c:security_setprocattr
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/integrity/ima/ima_policy.c:add_rules
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/thermal/of-thermal.c:of_parse_thermal_zones
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/of/dynamic.c:__of_prop_dup
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
**Symbols:**

```
c0000000003976c0-c000000000397734: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *kmemdup(const void *src, size_t len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f274c)
Location: mm/util.c:123
Inline: False
Direct callers:
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:pstore_get_backend_records
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/security.c:security_setprocattr
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/sed-opal.c:get_active_key
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_parse_dt_config
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/thermal/of-thermal.c:of_parse_thermal_zones
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/of/dynamic.c:__of_prop_dup
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/overlay.c:of_overlay_fdt_apply
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
**Symbols:**

```
ffffffe0001f274c-ffffffe0001f279e: kmemdup (STB_GLOBAL)
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
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810307d5)
Location: include/linux/string.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:pstore_get_backend_records
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/security.c:security_setprocattr
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/integrity/ima/ima_policy.c:add_rules
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
**Symbols:**

```
ffffffff8123d3c0-ffffffff8123d3fe: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81020265)
Location: include/linux/string.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:pstore_get_backend_records
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/security.c:security_setprocattr
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/integrity/ima/ima_policy.c:add_rules
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
**Symbols:**

```
ffffffff812303c0-ffffffff812303fe: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030635)
Location: include/linux/string.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:pstore_get_backend_records
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/security.c:security_setprocattr
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/integrity/ima/ima_policy.c:add_rules
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
**Symbols:**

```
ffffffff8123b160-ffffffff8123b19e: kmemdup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *kmemdup(const void *p, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810314c5)
Location: include/linux/string.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/e820.c:e820__reallocate_tables
  - arch/x86/kernel/cpu/microcode/intel.c:memdup_patch
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - kernel/ucount.c:setup_userns_sysctls
  - kernel/irq/msi.c:alloc_msi_entry
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/cgroup.c:cgroup_init_cftypes
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/user_namespace.c:map_write
  - mm/shmem.c:shmem_symlink
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:legacy_fs_context_dup
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/posix_acl.c:posix_acl_clone
  - fs/ecryptfs/messaging.c:ecryptfs_process_response
  - fs/pstore/platform.c:pstore_get_backend_records
  - security/keys/key.c:key_alloc
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/dh.c:dh_data_from_key
  - security/security.c:security_setprocattr
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/device_cgroup.c:dev_exception_add
  - security/integrity/ima/ima_policy.c:add_rules
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_note_digest
  - block/sed-opal.c:get_active_key
  - lib/iov_iter.c:dup_iter
  - drivers/pinctrl/core.c:pinctrl_register_map
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_add_map_configs
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/virtio_console.c:put_chars
  - drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi
  - drivers/iommu/iommu.c:iommu_report_device_fault
  - drivers/base/platform.c:platform_device_add_data
  - drivers/base/platform.c:platform_device_add_resources
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/nvdimm/core.c:nd_uuid_store
  - drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/net/wireless/ti/wilink_platform_data.c:wl1251_set_platform_data
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
  - drivers/i2c/i2c-core-base.c:i2c_get_dma_safe_msg_buf
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table
  - net/core/scm.c:scm_fp_dup
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_rules.c:fib_rules_register
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ipv6_route_sysctl_init
  - net/ipv6/icmp.c:ipv6_icmp_sysctl_init
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/ipv6/seg6_local.c:parse_nla_srh
```
**Symbols:**

```
ffffffff8124a870-ffffffff8124a8ae: kmemdup (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void *p</code>
</li>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>const void *src</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t len</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const void *p</code> ➡️ <code>const const void * p</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void *src</code>
</li>
<li>
<b>Param added. </b>
<code>size_t len</code>
</li>
<li>
<b>Param removed. </b>
<code>const void *p</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
</ul>
</details>
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
