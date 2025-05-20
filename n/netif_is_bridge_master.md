# Function: <code>netif_is_bridge_master</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9dd38)
Location: include/linux/netdevice.h:4802
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81bad65d)
Location: include/linux/netdevice.h:4998
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9c83c)
Location: include/linux/netdevice.h:5129
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
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
In net/core/dev_ioctl.c (ffffffff81ad0bfe)
Location: include/linux/netdevice.h:5177
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/switchdev/switchdev.c (ffffffff81c69570)
Location: include/linux/netdevice.h:5177
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_add_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_add_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_add_to_device
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
In net/core/rtnetlink.c (ffffffff81c31abd)
Location: include/linux/netdevice.h:4997
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
```
In net/core/dev_ioctl.c (ffffffff81c4e3e0)
Location: include/linux/netdevice.h:4997
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/switchdev/switchdev.c (ffffffff81e0c616)
Location: include/linux/netdevice.h:4997
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
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
In net/core/rtnetlink.c (ffffffff81de4e6d)
Location: include/linux/netdevice.h:5041
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
```
In net/core/dev_ioctl.c (ffffffff81e033df)
Location: include/linux/netdevice.h:5041
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/switchdev/switchdev.c (ffffffff81fe2726)
Location: include/linux/netdevice.h:5041
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
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
In net/core/rtnetlink.c (ffffffff81e5687f)
Location: include/linux/netdevice.h:5085
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
```
In net/core/dev_ioctl.c (ffffffff81e75c8e)
Location: include/linux/netdevice.h:5085
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/switchdev/switchdev.c (ffffffff8205ea46)
Location: include/linux/netdevice.h:5085
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
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
In net/core/rtnetlink.c (ffffffff81f15bdc)
Location: include/linux/netdevice.h:5161
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_dump
```
```
In net/core/dev_ioctl.c (ffffffff81f35c19)
Location: include/linux/netdevice.h:5161
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/switchdev/switchdev.c (ffffffff82131726)
Location: include/linux/netdevice.h:5161
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
  - net/switchdev/switchdev.c:__switchdev_handle_fdb_event_to_device
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
