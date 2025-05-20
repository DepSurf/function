# Function: <code>bpf_prog_get_type_dev</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811a05f4)
Location: kernel/bpf/syscall.c:1100
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:sockmap_get_from_fd
Direct callers:
  - kernel/events/core.c:perf_ioctl
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff8119f1b0-ffffffff8119f231: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3d63)
Location: kernel/bpf/syscall.c:1201
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/events/core.c:_perf_ioctl
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff811b3cd0-ffffffff811b3cee: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c4419)
Location: kernel/bpf/syscall.c:1387
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/events/core.c:_perf_ioctl
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff811c21d0-ffffffff811c21ee: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d5e03)
Location: kernel/bpf/syscall.c:1524
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/events/core.c:_perf_ioctl
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff811d2950-ffffffff811d296e: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e21a5)
Location: kernel/bpf/syscall.c:1545
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/events/core.c:_perf_ioctl
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff811deda0-ffffffff811dedbe: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200850)
Location: kernel/bpf/syscall.c:1923
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/events/core.c:perf_event_set_bpf_prog
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff811fc960-ffffffff811fc97e: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ffe12)
Location: kernel/bpf/syscall.c:1897
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/events/core.c:perf_event_set_bpf_prog
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff811fbcc0-ffffffff811fbcde: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812007c2)
Location: kernel/bpf/syscall.c:1905
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/events/core.c:perf_event_set_bpf_prog
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff811fc9e0-ffffffff811fc9fe: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81232532)
Location: kernel/bpf/syscall.c:1999
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff8122e390-ffffffff8122e3ae: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8127791b)
Location: kernel/bpf/syscall.c:2245
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_attach
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81270a30-ffffffff81270a58: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cdcab)
Location: kernel/bpf/syscall.c:2279
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_attach
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff812c6570-ffffffff812c6598: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f5239)
Location: kernel/bpf/syscall.c:2358
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_attach
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff812ed870-ffffffff812ed898: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81314039)
Location: kernel/bpf/syscall.c:2398
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_detach
  - kernel/bpf/syscall.c:bpf_prog_attach
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/tcx.c:tcx_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - drivers/net/netkit.c:netkit_prog_attach
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff8130c420-ffffffff8130c448: bpf_prog_get_type_dev (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff80001026531c)
Location: kernel/bpf/syscall.c:1545
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/events/core.c:_perf_ioctl
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffff800010260068-ffff8000102600a4: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0497320)
Location: kernel/bpf/syscall.c:1545
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/events/core.c:_perf_ioctl
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/core/lwt_bpf.c:bpf_parse_prog
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
c049355c-c0493588: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000309ed8)
Location: kernel/bpf/syscall.c:1545
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/events/core.c:_perf_ioctl
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
c0000000003050a0-c0000000003050dc: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe0001a0c62)
Location: kernel/bpf/syscall.c:1545
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/events/core.c:_perf_ioctl
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffe00019de46-ffffffe00019de80: bpf_prog_get_type_dev (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811da7c5)
Location: kernel/bpf/syscall.c:1545
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/events/core.c:_perf_ioctl
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff811d73c0-ffffffff811d73de: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cd585)
Location: kernel/bpf/syscall.c:1545
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/events/core.c:_perf_ioctl
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff811ca180-ffffffff811ca19e: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8595)
Location: kernel/bpf/syscall.c:1545
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/events/core.c:_perf_ioctl
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff811d5190-ffffffff811d51ae: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type_dev(u32 ufd, enum bpf_prog_type type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e6918)
Location: kernel/bpf/syscall.c:1545
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/events/core.c:_perf_ioctl
  - drivers/net/tun.c:tun_set_ebpf
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/ipv6/seg6_local.c:parse_nla_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff811e34c0-ffffffff811e34de: bpf_prog_get_type_dev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
