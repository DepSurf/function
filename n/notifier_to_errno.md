# Function: <code>notifier_to_errno</code>

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
In kernel/cpu.c (ffffffff81081313)
Location: include/linux/notifier.h:177
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_up
```
```
In kernel/power/main.c (ffffffff810cd66a)
Location: include/linux/notifier.h:177
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff81819d0c)
Location: include/linux/notifier.h:177
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffffffff81203d46)
Location: include/linux/notifier.h:177
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/zsmalloc.c (ffffffff81f8dc9c)
Location: include/linux/notifier.h:177
Inline: True
```
```
In net/core/dev.c (ffffffff817148dc)
Location: include/linux/notifier.h:177
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:__dev_open
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
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
In kernel/cpu.c (ffffffff81083426)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - kernel/cpu.c:__cpu_notify
```
```
In kernel/power/main.c (ffffffff810d2142)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff81893698)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffffffff81228cf4)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/zsmalloc.c (ffffffff81fb825e)
Location: include/linux/notifier.h:179
Inline: True
```
```
In net/core/dev.c (ffffffff8178730a)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/rtnetlink.c (ffffffff81795700)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/net-sysfs.c (ffffffff817a1c9f)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - net/core/net-sysfs.c:change_tx_queue_len
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
In kernel/power/main.c (ffffffff810d8cf2)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff818c7f63)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffffffff8123b2a0)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In net/core/dev.c (ffffffff817b48ca)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/rtnetlink.c (ffffffff817c2f91)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/net-sysfs.c (ffffffff817d05bf)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - net/core/net-sysfs.c:change_tx_queue_len
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
In kernel/power/main.c (ffffffff810d7cf2)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff818ff723)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffffffff81246d21)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In net/core/dev.c (ffffffff817d3540)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/rtnetlink.c (ffffffff817e16c5)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/net-sysfs.c (ffffffff817ef9a8)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - net/core/net-sysfs.c:change_tx_queue_len
```
```
In net/ipv4/devinet.c (ffffffff818509f5)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (ffffffff8188fef3)
Location: include/linux/notifier.h:179
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In kernel/power/main.c (ffffffff810dfd42)
Location: include/linux/notifier.h:180
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff81989a93)
Location: include/linux/notifier.h:180
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffffffff81266eea)
Location: include/linux/notifier.h:180
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In net/core/dev.c (ffffffff8184d96b)
Location: include/linux/notifier.h:180
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/rtnetlink.c (ffffffff8185c208)
Location: include/linux/notifier.h:180
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
```
In net/core/dev_ioctl.c (ffffffff81869446)
Location: include/linux/notifier.h:180
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff8186af48)
Location: include/linux/notifier.h:180
Inline: True
Inline callers:
  - net/core/net-sysfs.c:change_tx_queue_len
```
```
In net/ipv4/devinet.c (ffffffff818d062c)
Location: include/linux/notifier.h:180
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (ffffffff81911916)
Location: include/linux/notifier.h:180
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In kernel/power/main.c (ffffffff810e83e2)
Location: include/linux/notifier.h:204
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff819e6391)
Location: include/linux/notifier.h:204
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffffffff8128b788)
Location: include/linux/notifier.h:204
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In net/core/dev.c (ffffffff81898787)
Location: include/linux/notifier.h:204
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff818ba20a)
Location: include/linux/notifier.h:204
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff81926b8c)
Location: include/linux/notifier.h:204
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (ffffffff8196897a)
Location: include/linux/notifier.h:204
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In kernel/power/main.c (ffffffff810f39f2)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff81a217ce)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffffffff812a06d9)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In net/core/dev.c (ffffffff818babe7)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff818e108a)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff81955c3c)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (ffffffff8199e2bf)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff819fc53e)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff810fbee2)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff81a92177)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffffffff812bb961)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In net/core/dev.c (ffffffff8190651e)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff8192f87a)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff819ba614)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (ffffffff81a0a71f)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff81a6b510)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff81108302)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff81ac9907)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffffffff812cd841)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In net/core/dev.c (ffffffff81938c0e)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff81961aea)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff819f11a4)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (ffffffff81a413d2)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff81aa1efe)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff81112ef2)
Location: include/linux/notifier.h:199
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff81bc1ff5)
Location: include/linux/notifier.h:199
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In net/core/dev.c (ffffffff81a0dda7)
Location: include/linux/notifier.h:199
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:call_netdevice_register_net_notifiers
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff81a350f5)
Location: include/linux/notifier.h:199
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff81adf114)
Location: include/linux/notifier.h:199
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/notifier.h:199
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b36e12)
Location: include/linux/notifier.h:199
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff81b9d8c6)
Location: include/linux/notifier.h:199
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff8110ff7d)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
```
```
In kernel/module.c (ffffffff81163500)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In mm/memory_hotplug.c (ffffffff81c3b0ec)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/base/power/domain.c (ffffffff817e46a6)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
```
```
In drivers/net/tun.c (ffffffff8189eafe)
Location: include/linux/notifier.h:198
Inline: True
```
```
In net/core/dev.c (ffffffff81a0eb87)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:call_netdevice_register_net_notifiers
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff81a37408)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff81aebf14)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (ffffffff81b0adaf)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
```
In net/ipv6/addrconf.c (ffffffff81b45b42)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff81bad1d6)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff811109bd)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
```
```
In kernel/module.c (ffffffff81164478)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In mm/memory_hotplug.c (ffffffff81c2d742)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/base/power/domain.c (ffffffff817c8aa6)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
```
```
In drivers/net/tun.c (ffffffff81881408)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/core/dev.c (ffffffff819f5975)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:call_netdevice_register_net_notifiers
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff81a1e568)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff81ad7584)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (ffffffff81af60ad)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
```
In net/ipv6/addrconf.c (ffffffff81b33935)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff81b9c469)
Location: include/linux/notifier.h:198
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff8113046d)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
```
```
In kernel/module.c (ffffffff81189b68)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In mm/memory_hotplug.c (ffffffff81d4c015)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/base/power/domain.c (ffffffff81852fc6)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
```
```
In drivers/net/tun.c (ffffffff81912d62)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/core/dev.c (ffffffff81aa7354)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:call_netdevice_register_net_notifiers
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff81ad2608)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff81b96034)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (ffffffff81bb8387)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
```
In net/ipv6/addrconf.c (ffffffff81bf9fa5)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff81c69925)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff81151c8d)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
```
```
In kernel/module/main.c (ffffffff8118f6c3)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In mm/memory_hotplug.c (ffffffff81f1b98e)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/base/power/domain.c (ffffffff81999097)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
```
```
In drivers/net/tun.c (ffffffff81a65f7a)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/core/dev.c (ffffffff81c1f1f4)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_get_stats
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:call_netdevice_register_net_notifiers
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff81c50023)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff81d27d79)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (ffffffff81d4c1cb)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
```
In net/ipv6/addrconf.c (ffffffff81d933ab)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff81e0ca18)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff81180a0d)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
```
```
In kernel/module/main.c (ffffffff811cca3f)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In mm/memory_hotplug.c (ffffffff820c391e)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/base/power/domain.c (ffffffff81b0a327)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
```
```
In drivers/net/tun.c (ffffffff81bf131f)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/core/dev.c (ffffffff81dd15f2)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_get_stats
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:call_netdevice_register_net_notifiers
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff81e05383)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff81eef739)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (ffffffff81f1599b)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
```
In net/ipv6/addrconf.c (ffffffff81f61b3b)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff81fe2bb8)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff811918fd)
Location: include/linux/notifier.h:216
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
```
```
In kernel/module/main.c (ffffffff811dfe8b)
Location: include/linux/notifier.h:216
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In mm/memory_hotplug.c (ffffffff821476fc)
Location: include/linux/notifier.h:216
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/base/power/domain.c (ffffffff81b5833d)
Location: include/linux/notifier.h:216
Inline: True
Inline callers:
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
```
```
In drivers/net/tun.c (ffffffff81c49926)
Location: include/linux/notifier.h:216
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/core/dev.c (ffffffff81e421e8)
Location: include/linux/notifier.h:216
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_get_stats
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:call_netdevice_register_net_notifiers
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff81e77bd3)
Location: include/linux/notifier.h:216
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff81f4f0f9)
Location: include/linux/notifier.h:216
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (ffffffff81f7562b)
Location: include/linux/notifier.h:216
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
```
In net/ipv6/addrconf.c (ffffffff81fc1955)
Location: include/linux/notifier.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff8205eed8)
Location: include/linux/notifier.h:216
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff811a02bd)
Location: include/linux/notifier.h:205
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain_robust
```
```
In kernel/module/main.c (ffffffff811f5bbb)
Location: include/linux/notifier.h:205
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In mm/memory_hotplug.c (ffffffff82229f2a)
Location: include/linux/notifier.h:205
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/pmdomain/core.c (ffffffff81a9fcfd)
Location: include/linux/notifier.h:205
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:_genpd_power_off
  - drivers/pmdomain/core.c:_genpd_power_on
```
```
In drivers/base/memory.c (ffffffff81bb88b7)
Location: include/linux/notifier.h:205
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_online
```
```
In drivers/net/tun.c (ffffffff81cff2a8)
Location: include/linux/notifier.h:205
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/core/dev.c (ffffffff81f00cc7)
Location: include/linux/notifier.h:205
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:netdev_offload_xstats_get
  - net/core/dev.c:netdev_offload_xstats_get_stats
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:call_netdevice_register_net_notifiers
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff81f37b93)
Location: include/linux/notifier.h:205
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff82015259)
Location: include/linux/notifier.h:205
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (ffffffff8203bdfb)
Location: include/linux/notifier.h:205
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:replace_nexthop_grp
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:call_nexthop_notifiers
```
```
In net/ipv6/addrconf.c (ffffffff8208ea94)
Location: include/linux/notifier.h:205
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff82131f26)
Location: include/linux/notifier.h:205
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_bridge_port_replay
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffff80001016f584)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In kernel/cpu_pm.c (ffff80001025b474)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/cpu_pm.c:cpu_pm_notify
```
```
In mm/memory_hotplug.c (ffff800010d9cf60)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffff800010371b5c)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In drivers/of/dynamic.c (ffff800010b70bb8)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_changeset_entry_notify
```
```
In drivers/of/overlay.c (ffff800010b772e4)
Location: include/linux/notifier.h:203
Inline: True
```
```
In net/core/dev.c (ffff800010bd7574)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffff800010c057c8)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffff800010ca7424)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (ffff800010d02d84)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffff800010d73408)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In arch/arm/common/bL_switcher.c (c03270bc)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_activation_notify
```
```
In kernel/power/main.c (c03ba1ec)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In kernel/cpu_pm.c (c048e5d4)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/cpu_pm.c:cpu_pm_notify
```
```
In mm/page_isolation.c (0)
Location: include/linux/notifier.h:203
Inline: True
```
```
In drivers/of/dynamic.c (c0c53368)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_changeset_entry_notify
```
```
In drivers/of/overlay.c (c0c593ac)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - drivers/of/overlay.c:overlay_notify
```
```
In net/core/dev.c (c0cf2610)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (c0d1e8a4)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (c0db3b44)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (c0e09b5c)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (c0e7043c)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (c0000000001c746c)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (c0000000004307e0)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (c00000000046330c)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In drivers/of/dynamic.c (c000000000c4c65c)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_changeset_entry_notify
```
```
In drivers/of/overlay.c (c000000000c56128)
Location: include/linux/notifier.h:203
Inline: True
```
```
In net/core/dev.c (c000000000cb74f4)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (c000000000cef944)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (c000000000dbbc04)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (c000000000e2a90c)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (c000000000eb28f4)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In mm/page_isolation.c (0)
Location: include/linux/notifier.h:203
Inline: True
```
```
In drivers/of/dynamic.c (ffffffe000724c0c)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_changeset_entry_notify
```
```
In drivers/of/overlay.c (ffffffe00072a55a)
Location: include/linux/notifier.h:203
Inline: True
```
```
In net/core/dev.c (ffffffe000760bc2)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffe000783fbe)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffe00080257e)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (ffffffe00084c1be)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffe0008a392e)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff81101442)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff81a68777)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffffffff812c5e21)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In net/core/dev.c (ffffffff818d8bde)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff81901aba)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff81990f44)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (ffffffff819e0a62)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff81a4128e)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff810f1802)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff81a25237)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffffffff812b6e61)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In drivers/net/vxlan.c (ffffffff8176c7a1)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fdb_replay
  - drivers/net/vxlan.c:vxlan_fdb_switchdev_call_notifiers
```
```
In net/core/dev.c (ffffffff81892a1e)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff818bb8ea)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff8194aa04)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (ffffffff8199d822)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff819fde7e)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff810fe7d2)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff81ad4b87)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffffffff812c3c31)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In net/core/dev.c (ffffffff81929c0e)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff81952aea)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff819fb7e4)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (ffffffff81a4b4e2)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff81aad13e)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
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
In kernel/power/main.c (ffffffff81109a92)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
```
In mm/memory_hotplug.c (ffffffff81ae1067)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/page_isolation.c (ffffffff812d46d1)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
```
In net/core/dev.c (ffffffff8194b2d9)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_change_tx_queue_len
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:__dev_open
  - net/core/dev.c:dev_change_name
```
```
In net/core/fib_notifier.c (ffffffff8197452a)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/core/fib_notifier.c:call_fib_notifiers
  - net/core/fib_notifier.c:call_fib_notifier
```
```
In net/ipv4/devinet.c (ffffffff81a05b14)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv6/addrconf.c (ffffffff81a573de)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/switchdev/switchdev.c (ffffffff81ab94ae)
Location: include/linux/notifier.h:203
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
</details>
</li>
</ul>

## Differences
