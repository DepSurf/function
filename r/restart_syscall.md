# Function: <code>restart_syscall</code>

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
In kernel/cgroup.c (ffffffff81117933)
Location: include/linux/sched.h:2894
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_mount
```
```
In block/blk-cgroup.c (ffffffff813d909b)
Location: include/linux/sched.h:2894
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff81547da7)
Location: include/linux/sched.h:2894
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81736b86)
Location: include/linux/sched.h:2894
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
```
```
In net/ipv4/devinet.c (ffffffff81792e1e)
Location: include/linux/sched.h:2894
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff817cd3aa)
Location: include/linux/sched.h:2894
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
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
In kernel/cgroup.c (ffffffff8111f99a)
Location: include/linux/sched.h:3171
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
```
```
In block/blk-cgroup.c (ffffffff8141ee16)
Location: include/linux/sched.h:3171
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff81599a07)
Location: include/linux/sched.h:3171
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff817a2d53)
Location: include/linux/sched.h:3171
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
```
```
In net/ipv4/devinet.c (ffffffff818005d4)
Location: include/linux/sched.h:3171
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8183aa9d)
Location: include/linux/sched.h:3171
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup.c (ffffffff81127f44)
Location: include/linux/sched.h:3327
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
```
```
In block/blk-cgroup.c (ffffffff8143a3d6)
Location: include/linux/sched.h:3327
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff815c7cd7)
Location: include/linux/sched.h:3327
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff817d17b3)
Location: include/linux/sched.h:3327
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
```
```
In net/ipv4/devinet.c (ffffffff81831534)
Location: include/linux/sched.h:3327
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8186c49d)
Location: include/linux/sched.h:3327
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (ffffffff8112ac22)
Location: include/linux/sched/signal.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In block/blk-cgroup.c (ffffffff81447b48)
Location: include/linux/sched/signal.h:306
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff815dc967)
Location: include/linux/sched/signal.h:306
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff817f0b9f)
Location: include/linux/sched/signal.h:306
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
```
```
In net/ipv4/devinet.c (ffffffff81852add)
Location: include/linux/sched/signal.h:306
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8188e485)
Location: include/linux/sched/signal.h:306
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (ffffffff811379b8)
Location: include/linux/sched/signal.h:307
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In block/blk-cgroup.c (ffffffff81474748)
Location: include/linux/sched/signal.h:307
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff816439a7)
Location: include/linux/sched/signal.h:307
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff8186c1a6)
Location: include/linux/sched/signal.h:307
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff818d28ed)
Location: include/linux/sched/signal.h:307
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8190f9e5)
Location: include/linux/sched/signal.h:307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (ffffffff81146264)
Location: include/linux/sched/signal.h:335
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In block/blk-cgroup.c (ffffffff814a885b)
Location: include/linux/sched/signal.h:335
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff8167ed57)
Location: include/linux/sched/signal.h:335
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff818bca88)
Location: include/linux/sched/signal.h:335
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff81928e96)
Location: include/linux/sched/signal.h:335
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8196723a)
Location: include/linux/sched/signal.h:335
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (ffffffff81151e0a)
Location: include/linux/sched/signal.h:344
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In block/blk-cgroup.c (ffffffff814c2e16)
Location: include/linux/sched/signal.h:344
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff8169f197)
Location: include/linux/sched/signal.h:344
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff818e3d38)
Location: include/linux/sched/signal.h:344
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff81958186)
Location: include/linux/sched/signal.h:344
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8199c70a)
Location: include/linux/sched/signal.h:344
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115dac6)
Location: include/linux/sched/signal.h:349
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff814f1596)
Location: include/linux/sched/signal.h:349
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff816d77d7)
Location: include/linux/sched/signal.h:349
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81932718)
Location: include/linux/sched/signal.h:349
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff819bcbd7)
Location: include/linux/sched/signal.h:349
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81a08983)
Location: include/linux/sched/signal.h:349
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (ffffffff811696d6)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff8150abd1)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff816fb8f7)
Location: include/linux/sched/signal.h:341
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81965258)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff819f38c7)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81a3f8c3)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (ffffffff8117b359)
Location: include/linux/sched/signal.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff8156bba2)
Location: include/linux/sched/signal.h:350
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff817b623f)
Location: include/linux/sched/signal.h:350
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81a38685)
Location: include/linux/sched/signal.h:350
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/devinet.c (ffffffff81ae12d9)
Location: include/linux/sched/signal.h:350
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81b34a31)
Location: include/linux/sched/signal.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In kernel/cgroup/cgroup-v1.c (ffffffff8117822e)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff815868e9)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff817cb6af)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81a3b8c3)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/devinet.c (ffffffff81aee179)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81b43511)
Location: include/linux/sched/signal.h:351
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In kernel/cgroup/cgroup-v1.c (ffffffff81178da1)
Location: include/linux/sched/signal.h:352
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff8158d5f9)
Location: include/linux/sched/signal.h:352
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff817af01f)
Location: include/linux/sched/signal.h:352
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81a22d35)
Location: include/linux/sched/signal.h:352
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:duplex_show
```
```
In net/ipv4/devinet.c (ffffffff81ad98d7)
Location: include/linux/sched/signal.h:352
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81b31ba1)
Location: include/linux/sched/signal.h:352
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In kernel/cgroup/cgroup-v1.c (ffffffff811a06d1)
Location: include/linux/sched/signal.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff815f309d)
Location: include/linux/sched/signal.h:350
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff8183823b)
Location: include/linux/sched/signal.h:350
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81ad72cc)
Location: include/linux/sched/signal.h:350
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
```
```
In net/ipv4/devinet.c (ffffffff81b98a11)
Location: include/linux/sched/signal.h:350
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81bf9071)
Location: include/linux/sched/signal.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In kernel/cgroup/cgroup-v1.c (ffffffff811d0e2e)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff816a4542)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff8197a5af)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81c579e8)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/devinet.c (ffffffff81d2a890)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81d92450)
Location: include/linux/sched/signal.h:380
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In kernel/cgroup/cgroup-v1.c (ffffffff8121498e)
Location: include/linux/sched/signal.h:381
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff81763230)
Location: include/linux/sched/signal.h:381
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff81ae740f)
Location: include/linux/sched/signal.h:381
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81e0d7a8)
Location: include/linux/sched/signal.h:381
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/devinet.c (ffffffff81ef23a0)
Location: include/linux/sched/signal.h:381
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81f60b70)
Location: include/linux/sched/signal.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In kernel/cgroup/cgroup-v1.c (ffffffff8122a2ae)
Location: include/linux/sched/signal.h:381
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff817a1d5a)
Location: include/linux/sched/signal.h:381
Inline: True
```
```
In drivers/base/core.c (ffffffff81b3583f)
Location: include/linux/sched/signal.h:381
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81e809f8)
Location: include/linux/sched/signal.h:381
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/devinet.c (ffffffff81f51e70)
Location: include/linux/sched/signal.h:381
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81fc09a0)
Location: include/linux/sched/signal.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In kernel/cgroup/cgroup-v1.c (ffffffff8124214e)
Location: include/linux/sched/signal.h:373
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff817e58a7)
Location: include/linux/sched/signal.h:373
Inline: True
```
```
In drivers/base/core.c (ffffffff81b8d25f)
Location: include/linux/sched/signal.h:373
Inline: True
Inline callers:
  - drivers/base/core.c:online_store
```
```
In net/core/net-sysfs.c (ffffffff81f419b5)
Location: include/linux/sched/signal.h:373
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:carrier_store
```
```
In net/ipv4/devinet.c (ffffffff82018149)
Location: include/linux/sched/signal.h:373
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8208de61)
Location: include/linux/sched/signal.h:373
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
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
In kernel/cgroup/cgroup-v1.c (ffff8000101dc9f0)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffff80001060e318)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffff8000108e619c)
Location: include/linux/sched/signal.h:341
Inline: True
```
```
In net/core/net-sysfs.c (ffff800010c0b0b8)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffff800010ca9be8)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffff800010d00b1c)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (c041ec2c)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (c07b8c90)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (c09d4804)
Location: include/linux/sched/signal.h:341
Inline: True
```
```
In net/core/net-sysfs.c (c0d22b10)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (c0db6368)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (c0e06cd4)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (c00000000024a720)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (c0000000007ab764)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (c00000000097bddc)
Location: include/linux/sched/signal.h:341
Inline: True
```
```
In net/core/net-sysfs.c (c000000000cf4848)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (c000000000dbf14c)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (c000000000e27ed8)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (ffffffe000154820)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffe00044685c)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffe00057ac8e)
Location: include/linux/sched/signal.h:341
Inline: True
```
```
In net/core/net-sysfs.c (ffffffe0007881fa)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
```
```
In net/ipv4/devinet.c (ffffffe0008046c8)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffe00084a8fe)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (ffffffff81161cf6)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff815031b1)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff816c10e7)
Location: include/linux/sched/signal.h:341
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81905228)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff81993667)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff819def53)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (ffffffff81154f56)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff814f3685)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff8169c397)
Location: include/linux/sched/signal.h:341
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff818bf058)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff8194d127)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff8199bd13)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115fac6)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff814ff241)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff816ef5b7)
Location: include/linux/sched/signal.h:341
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81956258)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff819fdf07)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81a499d3)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In kernel/cgroup/cgroup-v1.c (ffffffff8116cd2c)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In block/blk-cgroup.c (ffffffff815183c1)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In drivers/base/core.c (ffffffff81709df7)
Location: include/linux/sched/signal.h:341
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81978458)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/ipv4/devinet.c (ffffffff81a08297)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
```
In net/ipv6/addrconf.c (ffffffff81a55913)
Location: include/linux/sched/signal.h:341
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
</details>
</li>
</ul>

## Differences
