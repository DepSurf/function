# Function: <code>__request_module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff810967b0)
Location: kernel/kmod.c:124
Inline: False
Direct callers:
  - mm/zpool.c:zpool_has_pool
  - mm/zpool.c:zpool_create_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_larval_lookup
  - crypto/api.c:crypto_larval_lookup
  - block/elevator.c:elevator_get
  - block/elevator.c:load_default_elevator_module
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/scsi/scsi_dh.c:store_dh_state
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm-target.c:dm_get_target_type
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:__sock_create
  - net/core/rtnetlink.c:rtnl_newlink
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netfilter/nf_log.c:nf_logger_find_get
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/xfrm/xfrm_state.c:xfrm_get_mode
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/ipv6/af_inet6.c:inet6_create
  - net/ipv6/af_inet6.c:inet6_create
```
**Symbols:**

```
ffffffff810967b0-ffffffff81096a85: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff81099b70)
Location: kernel/kmod.c:124
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_larval_lookup
  - crypto/api.c:crypto_larval_lookup
  - block/elevator.c:elevator_get
  - block/elevator.c:load_default_elevator_module
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_build_state
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_get_mode
  - net/ipv6/af_inet6.c:inet6_create
  - net/ipv6/af_inet6.c:inet6_create
```
**Symbols:**

```
ffffffff81099b70-ffffffff81099e41: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff8109eb20)
Location: kernel/kmod.c:124
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_larval_lookup
  - crypto/api.c:crypto_larval_lookup
  - block/elevator.c:elevator_get
  - block/elevator.c:load_default_elevator_module
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/ematch.c:tcf_em_tree_validate
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_get_mode
  - net/ipv6/af_inet6.c:inet6_create
  - net/ipv6/af_inet6.c:inet6_create
```
**Symbols:**

```
ffffffff8109eb20-ffffffff8109edf1: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff8109c2f0)
Location: kernel/kmod.c:151
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - block/elevator.c:elevator_get
  - block/elevator.c:load_default_elevator_module
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:rtnl_newlink
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff8109c2f0-ffffffff8109c753: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff810b0ea0)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - block/elevator.c:elevator_get
  - block/elevator.c:load_default_elevator_module
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:rtnl_newlink
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff810b0ea0-ffffffff810b12c1: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kmod.c (0)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/elevator.c:elevator_get
  - block/elevator.c:load_default_elevator_module
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff810b8073-ffffffff810b80d0: __request_module.cold.2 (STB_LOCAL)
ffffffff810b7cb0-ffffffff810b8073: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kmod.c (0)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff810c1150-ffffffff810c11ad: __request_module.cold.4 (STB_LOCAL)
ffffffff810c0da0-ffffffff810c1150: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kmod.c (0)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff810c7234-ffffffff810c7291: __request_module.cold (STB_LOCAL)
ffffffff810c6e90-ffffffff810c7234: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kmod.c (0)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/elevator.c:elevator_get
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff810d0304-ffffffff810d0361: __request_module.cold (STB_LOCAL)
ffffffff810cff60-ffffffff810d0304: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kmod.c (0)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/exec.c:search_binary_handler
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:find_quota_format
  - fs/nls/nls_base.c:load_nls_default
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/elevator.c:elevator_get
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/powernow-k8.c:__request_acpi_cpufreq
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/dev_ioctl.c:dev_load
  - net/core/dev_ioctl.c:dev_load
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netfilter/nf_log.c:nf_logger_find_get
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff810da22a-ffffffff810da287: __request_module.cold (STB_LOCAL)
ffffffff810d9f50-ffffffff810da22a: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kmod.c (0)
Location: kernel/kmod.c:124
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/exec.c:search_binary_handler
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:find_quota_format
  - fs/nls/nls_base.c:load_nls_default
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/elevator.c:elevator_get
  - block/genhd.c:blk_request_module
  - block/genhd.c:blk_request_module
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/powernow-k8.c:__request_acpi_cpufreq
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/dev_ioctl.c:dev_load
  - net/core/dev_ioctl.c:dev_load
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tc_action_load_ops
  - net/sched/act_api.c:tc_action_load_ops
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netfilter/nf_log.c:nf_logger_find_get
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff81bdc3de-ffffffff81bdc43b: __request_module.cold (STB_LOCAL)
ffffffff810d5750-ffffffff810d5a0d: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kmod.c (0)
Location: kernel/kmod.c:124
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/exec.c:search_binary_handler
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/nls/nls_base.c:load_nls_default
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/elevator.c:elevator_get
  - block/genhd.c:blk_request_module
  - block/genhd.c:blk_request_module
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/dev_ioctl.c:dev_load
  - net/core/dev_ioctl.c:dev_load
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tc_action_load_ops
  - net/sched/act_api.c:tc_action_load_ops
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff81bce501-ffffffff81bce564: __request_module.cold (STB_LOCAL)
ffffffff810d7330-ffffffff810d76bc: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kmod.c (0)
Location: kernel/kmod.c:124
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/exec.c:search_binary_handler
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/nls/nls_base.c:load_nls_default
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/elevator.c:elevator_get
  - block/genhd.c:blk_request_module
  - block/genhd.c:blk_request_module
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:br_ioctl_call
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/dev_ioctl.c:dev_load
  - net/core/dev_ioctl.c:dev_load
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tc_action_load_ops
  - net/sched/act_api.c:tc_action_load_ops
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff81ca593f-ffffffff81ca59a2: __request_module.cold (STB_LOCAL)
ffffffff810eabe0-ffffffff810eaf6c: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kmod.c (0)
Location: kernel/kmod.c:124
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/exec.c:search_binary_handler
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/nls/nls_base.c:load_nls_default
  - fs/unicode/utf8-core.c:utf8_load
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_wait_for_test
  - block/elevator.c:elevator_get
  - block/genhd.c:blk_request_module
  - block/genhd.c:blk_request_module
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:br_ioctl_call
  - net/core/sock.c:sock_load_diag_module
  - net/core/sock.c:sock_load_diag_module
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tc_action_load_ops
  - net/sched/act_api.c:tc_action_load_ops
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff81e5523a-ffffffff81e5528b: __request_module.cold (STB_LOCAL)
ffffffff811059f0-ffffffff81105ddf: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff8112b510)
Location: kernel/kmod.c:124
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/exec.c:search_binary_handler
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/nls/nls_base.c:load_nls_default
  - fs/unicode/utf8-core.c:utf8_load
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_wait_for_test
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:blk_request_module
  - block/genhd.c:blk_request_module
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:br_ioctl_call
  - net/core/sock.c:sock_load_diag_module
  - net/core/sock.c:sock_load_diag_module
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tc_action_load_ops
  - net/sched/act_api.c:tc_action_load_ops
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff8112b510-ffffffff8112b93d: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kmod.c (ffffffff811e1650)
Location: kernel/module/kmod.c:132
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/exec.c:search_binary_handler
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/nls/nls_base.c:load_nls_default
  - fs/unicode/utf8-core.c:utf8_load
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_wait_for_test
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:blk_request_module
  - block/genhd.c:blk_request_module
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:br_ioctl_call
  - net/core/sock.c:sock_load_diag_module
  - net/core/sock.c:sock_load_diag_module
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tc_action_load_ops
  - net/sched/act_api.c:tc_action_load_ops
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff811e1650-ffffffff811e1911: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kmod.c (ffffffff811f7380)
Location: kernel/module/kmod.c:132
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/exec.c:search_binary_handler
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/nls/nls_base.c:load_nls_default
  - fs/unicode/utf8-core.c:utf8_load
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_wait_for_test
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:blk_request_module
  - block/genhd.c:blk_request_module
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fb_chrdev.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/gpu/drm/drm_encoder_slave.c:drm_i2c_encoder_init
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:br_ioctl_call
  - net/core/sock.c:sock_load_diag_module
  - net/core/sock.c:sock_load_diag_module
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tc_action_load_ops
  - net/sched/act_api.c:tc_action_load_ops
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netfilter/nf_bpf_link.c:get_proto_defrag_hook
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff811f7380-ffffffff811f7672: __request_module (STB_GLOBAL)
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
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffff8000101304d0)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/of/device.c:of_device_request_module
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffff8000101304d0-ffff800010130968: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (c037fdb8)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/elevator.c:elevator_get
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/mtd/mtdpart.c:parse_mtd_partitions
  - drivers/mtd/mtdpart.c:parse_mtd_partitions
  - drivers/mtd/chips/chipreg.c:do_map_probe
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/of/device.c:of_device_request_module
  - sound/sound_core.c:soundcore_open
  - sound/sound_core.c:soundcore_open
  - sound/sound_core.c:soundcore_open
  - sound/sound_core.c:soundcore_open
  - sound/core/sound.c:snd_open
  - sound/core/timer.c:snd_timer_open
  - sound/core/timer.c:snd_timer_open
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
c037fdb8-c0380248: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (c000000000179b80)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/elevator.c:elevator_get
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/of/device.c:of_device_request_module
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
c000000000179b80-c00000000017a0e8: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffe0000e3a20)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/elevator.c:elevator_get
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/of/device.c:of_device_request_module
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffe0000e3a20-ffffffe0000e3d9c: __request_module (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kmod.c (0)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/elevator.c:elevator_get
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff810ca684-ffffffff810ca6e1: __request_module.cold (STB_LOCAL)
ffffffff810ca2e0-ffffffff810ca684: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kmod.c (0)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/elevator.c:elevator_get
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff810b8e94-ffffffff810b8ef1: __request_module.cold (STB_LOCAL)
ffffffff810b8af0-ffffffff810b8e94: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kmod.c (0)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/elevator.c:elevator_get
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_batch
  - net/netfilter/nfnetlink.c:nfnetlink_rcv_msg
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nf_conntrack_helper.c:nf_nat_helper_try_module_get
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_try_module_get
  - net/netfilter/nf_conntrack_proto.c:nf_ct_netns_do_get
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff810c9bb4-ffffffff810c9c11: __request_module.cold (STB_LOCAL)
ffffffff810c9810-ffffffff810c9bb4: __request_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __request_module(bool wait, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kmod.c (0)
Location: kernel/kmod.c:125
Inline: False
Direct callers:
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_has_pool
  - fs/char_dev.c:base_probe
  - fs/char_dev.c:base_probe
  - fs/filesystems.c:get_fs_type
  - fs/quota/dquot.c:vfs_load_quota_inode
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - block/elevator.c:elevator_get
  - block/genhd.c:base_probe
  - block/genhd.c:base_probe
  - drivers/pwm/core.c:pwm_get
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/char/misc.c:misc_open
  - drivers/scsi/scsi_dh.c:scsi_dh_attach
  - drivers/net/phy/phy_device.c:phy_request_driver_module
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/dm-target.c:dm_get_target_type
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - net/socket.c:__sock_create
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/ipv4/tcp_ulp.c:tcp_set_ulp
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff810d2108-ffffffff810d2165: __request_module.cold (STB_LOCAL)
ffffffff810d1d50-ffffffff810d2108: __request_module (STB_GLOBAL)
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
