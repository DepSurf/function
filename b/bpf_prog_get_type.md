# Function: <code>bpf_prog_get_type</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_get_type(u32 ufd, enum bpf_prog_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81180cc0)
Location: kernel/bpf/syscall.c:712
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81180cc0-ffffffff81180cdb: bpf_prog_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type(u32 ufd, enum bpf_prog_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118da24)
Location: kernel/bpf/syscall.c:809
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
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
ffffffff8118ca00-ffffffff8118ca1b: bpf_prog_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_get_type(u32 ufd, enum bpf_prog_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81192c2e)
Location: kernel/bpf/syscall.c:914
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
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
ffffffff81191c70-ffffffff81191ceb: bpf_prog_get_type (STB_GLOBAL)
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
In kernel/bpf/syscall.c (ffffffff811a05f4)
Location: include/linux/bpf.h:529
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:sockmap_get_from_fd
```
```
In kernel/events/core.c (ffffffff811bf1a2)
Location: include/linux/bpf.h:529
Inline: True
Inline callers:
  - kernel/events/core.c:perf_ioctl
```
```
In net/core/filter.c (ffffffff81868379)
Location: include/linux/bpf.h:529
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff81876b2f)
Location: include/linux/bpf.h:529
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/packet/af_packet.c (ffffffff81956715)
Location: include/linux/bpf.h:529
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffff811b3d63)
Location: include/linux/bpf.h:629
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
```
In kernel/bpf/cgroup.c (ffffffff811d2765)
Location: include/linux/bpf.h:629
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
```
In kernel/events/core.c (ffffffff811df162)
Location: include/linux/bpf.h:629
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
```
In drivers/net/tun.c (ffffffff8173c133)
Location: include/linux/bpf.h:629
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff818b84e3)
Location: include/linux/bpf.h:629
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff818c82ef)
Location: include/linux/bpf.h:629
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819a858a)
Location: include/linux/bpf.h:629
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff819b31fc)
Location: include/linux/bpf.h:629
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffff811c4419)
Location: include/linux/bpf.h:703
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (ffffffff811e24f5)
Location: include/linux/bpf.h:703
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
```
In kernel/events/core.c (ffffffff811ef5a2)
Location: include/linux/bpf.h:703
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
```
In drivers/net/tun.c (ffffffff8175fa73)
Location: include/linux/bpf.h:703
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff818def5a)
Location: include/linux/bpf.h:703
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff818f145f)
Location: include/linux/bpf.h:703
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819df0da)
Location: include/linux/bpf.h:703
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff819ea84d)
Location: include/linux/bpf.h:703
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffff811d5e03)
Location: include/linux/bpf.h:880
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (ffffffff811f9656)
Location: include/linux/bpf.h:880
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
```
In kernel/events/core.c (ffffffff81206cc2)
Location: include/linux/bpf.h:880
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
```
In drivers/net/tun.c (ffffffff8179d2a4)
Location: include/linux/bpf.h:880
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff8192ce61)
Location: include/linux/bpf.h:880
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff81942d83)
Location: include/linux/bpf.h:880
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a4dc4f)
Location: include/linux/bpf.h:880
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff81a599a5)
Location: include/linux/bpf.h:880
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffff811e21a5)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (ffffffff81206726)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
```
In kernel/events/core.c (ffffffff81214032)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
```
In drivers/net/tun.c (ffffffff817c0d44)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff8195f161)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff81977d33)
Location: include/linux/bpf.h:882
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a8481f)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff81a8fab5)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffff8120084d)
Location: include/linux/bpf.h:1469
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
```
```
In kernel/bpf/net_namespace.c (ffffffff8122aa92)
Location: include/linux/bpf.h:1469
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
```
```
In kernel/bpf/cgroup.c (ffffffff8122e1f6)
Location: include/linux/bpf.h:1469
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In kernel/events/core.c (ffffffff8123124a)
Location: include/linux/bpf.h:1469
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_bpf_prog
```
```
In drivers/net/tun.c (ffffffff8188a674)
Location: include/linux/bpf.h:1469
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff81a32541)
Location: include/linux/bpf.h:1469
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff81a4c96e)
Location: include/linux/bpf.h:1469
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f9ef)
Location: include/linux/bpf.h:1469
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff81b8aa7b)
Location: include/linux/bpf.h:1469
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffff811ffe12)
Location: include/linux/bpf.h:1688
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
```
In kernel/bpf/cpumap.c (ffffffff8122e874)
Location: include/linux/bpf.h:1688
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/bpf/net_namespace.c (ffffffff812328c8)
Location: include/linux/bpf.h:1688
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
```
```
In kernel/bpf/cgroup.c (ffffffff81236716)
Location: include/linux/bpf.h:1688
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In kernel/events/core.c (ffffffff8123ae72)
Location: include/linux/bpf.h:1688
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_bpf_prog
```
```
In drivers/net/tun.c (ffffffff818987a4)
Location: include/linux/bpf.h:1688
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff81a34881)
Location: include/linux/bpf.h:1688
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff81a525ee)
Location: include/linux/bpf.h:1688
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ea9f)
Location: include/linux/bpf.h:1688
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff81b99d73)
Location: include/linux/bpf.h:1688
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_set_data
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
In kernel/bpf/syscall.c (ffffffff812007c2)
Location: include/linux/bpf.h:1778
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
```
In kernel/bpf/cpumap.c (ffffffff81233752)
Location: include/linux/bpf.h:1778
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/bpf/net_namespace.c (ffffffff81236a68)
Location: include/linux/bpf.h:1778
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
```
```
In kernel/bpf/cgroup.c (ffffffff8123a976)
Location: include/linux/bpf.h:1778
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In kernel/events/core.c (ffffffff8123f632)
Location: include/linux/bpf.h:1778
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_bpf_prog
```
```
In drivers/net/tun.c (ffffffff8187aee4)
Location: include/linux/bpf.h:1778
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff81a1b8f1)
Location: include/linux/bpf.h:1778
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff81a37cbe)
Location: include/linux/bpf.h:1778
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d9bf)
Location: include/linux/bpf.h:1778
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff81b8a004)
Location: include/linux/bpf.h:1778
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffff81232532)
Location: include/linux/bpf.h:1904
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
```
In kernel/bpf/cpumap.c (ffffffff8126d3d4)
Location: include/linux/bpf.h:1904
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/bpf/net_namespace.c (ffffffff81271048)
Location: include/linux/bpf.h:1904
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
```
```
In kernel/bpf/cgroup.c (ffffffff81275556)
Location: include/linux/bpf.h:1904
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In drivers/net/tun.c (ffffffff8190c3e4)
Location: include/linux/bpf.h:1904
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff81acefd1)
Location: include/linux/bpf.h:1904
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff81aedace)
Location: include/linux/bpf.h:1904
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/ipv6/seg6_local.c (ffffffff81c4913f)
Location: include/linux/bpf.h:1904
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff81c5611b)
Location: include/linux/bpf.h:1904
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffff8127791b)
Location: include/linux/bpf.h:2041
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_attach
```
```
In kernel/bpf/cpumap.c (ffffffff812bc509)
Location: include/linux/bpf.h:2041
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/bpf/net_namespace.c (ffffffff812c0139)
Location: include/linux/bpf.h:2041
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
```
```
In kernel/bpf/cgroup.c (ffffffff812c4eda)
Location: include/linux/bpf.h:2041
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In drivers/net/tun.c (ffffffff81a5ff8a)
Location: include/linux/bpf.h:2041
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff81c4c6d0)
Location: include/linux/bpf.h:2041
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff81c709b6)
Location: include/linux/bpf.h:2041
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/ipv6/seg6_local.c (ffffffff81de89bc)
Location: include/linux/bpf.h:2041
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff81df8219)
Location: include/linux/bpf.h:2041
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffff812cdcab)
Location: include/linux/bpf.h:2449
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_attach
```
```
In kernel/bpf/cpumap.c (ffffffff8131fa1c)
Location: include/linux/bpf.h:2449
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/bpf/net_namespace.c (ffffffff81323949)
Location: include/linux/bpf.h:2449
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
```
```
In kernel/bpf/cgroup.c (ffffffff8132a3da)
Location: include/linux/bpf.h:2449
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In drivers/net/tun.c (ffffffff81beb37a)
Location: include/linux/bpf.h:2449
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff81e014b0)
Location: include/linux/bpf.h:2449
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff81e289d6)
Location: include/linux/bpf.h:2449
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc0ec)
Location: include/linux/bpf.h:2449
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff81fc9e4d)
Location: include/linux/bpf.h:2449
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_set_data
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
In kernel/bpf/syscall.c (ffffffff812f5239)
Location: include/linux/bpf.h:2625
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_attach
```
```
In kernel/bpf/cpumap.c (ffffffff8134fa1c)
Location: include/linux/bpf.h:2625
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/bpf/net_namespace.c (ffffffff81353b79)
Location: include/linux/bpf.h:2625
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
```
```
In kernel/bpf/cgroup.c (ffffffff8135a51a)
Location: include/linux/bpf.h:2625
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In drivers/net/tun.c (ffffffff81c437ba)
Location: include/linux/bpf.h:2625
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff81e72f70)
Location: include/linux/bpf.h:2625
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff81e9dff6)
Location: include/linux/bpf.h:2625
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/ipv6/seg6_local.c (ffffffff8201c9ec)
Location: include/linux/bpf.h:2625
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff8202ab47)
Location: include/linux/bpf.h:2625
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_set_data
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
In kernel/bpf/syscall.c (ffffffff81314039)
Location: include/linux/bpf.h:2796
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_detach
  - kernel/bpf/syscall.c:bpf_prog_attach
```
```
In kernel/bpf/cpumap.c (ffffffff81376f2c)
Location: include/linux/bpf.h:2796
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/bpf/net_namespace.c (ffffffff8137b069)
Location: include/linux/bpf.h:2796
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
```
```
In kernel/bpf/tcx.c (ffffffff8137c02c)
Location: include/linux/bpf.h:2796
Inline: True
Inline callers:
  - kernel/bpf/tcx.c:tcx_prog_attach
```
```
In kernel/bpf/cgroup.c (ffffffff813830da)
Location: include/linux/bpf.h:2796
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In drivers/net/netkit.c (ffffffff81ce618e)
Location: include/linux/bpf.h:2796
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_prog_attach
```
```
In drivers/net/tun.c (ffffffff81cf90ca)
Location: include/linux/bpf.h:2796
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff81f326e0)
Location: include/linux/bpf.h:2796
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff81f60779)
Location: include/linux/bpf.h:2796
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/ipv6/seg6_local.c (ffffffff820eb9cf)
Location: include/linux/bpf.h:2796
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff820fa637)
Location: include/linux/bpf.h:2796
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_set_data
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
In kernel/bpf/syscall.c (ffff800010265318)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (ffff80001028fd9c)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
```
In kernel/events/core.c (ffff80001029e0d0)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
```
In drivers/net/tun.c (ffff8000109dc184)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffff800010c0262c)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffff800010c1e56c)
Location: include/linux/bpf.h:882
Inline: True
```
```
In net/ipv6/seg6_local.c (ffff800010d50854)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffff800010d5cbc8)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (c049731c)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (c04bf474)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
```
In kernel/events/core.c (c04cda50)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
```
In drivers/net/tun.c (c0ac631c)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (c0d1baf4)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (c0d365c8)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/ipv6/seg6_local.c (c0e513b0)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (c0e5e040)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (c000000000309ed4)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (c00000000033ca00)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
```
In kernel/events/core.c (c00000000034f20c)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
```
In drivers/net/tun.c (c000000000a9dd34)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (c000000000ceba74)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (c000000000d1052c)
Location: include/linux/bpf.h:882
Inline: True
```
```
In net/ipv6/seg6_local.c (c000000000e88500)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (c000000000e98988)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffe0001a0c62)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (ffffffe0001c2a10)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
```
In kernel/events/core.c (ffffffe0001c8fdc)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
```
In drivers/net/tun.c (ffffffe000626236)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffe0007819f2)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffe00079828c)
Location: include/linux/bpf.h:882
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffe00088887a)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffe0008933b4)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffff811da7c5)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (ffffffff811fed46)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
```
In kernel/events/core.c (ffffffff8120c682)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
```
In drivers/net/tun.c (ffffffff81785814)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff818ff131)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff81917ba3)
Location: include/linux/bpf.h:882
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a23eaf)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff81a2f145)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffff811cd585)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (ffffffff811f1a96)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
```
In kernel/events/core.c (ffffffff811ff452)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
```
In drivers/net/tun.c (ffffffff81765164)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff818b8f61)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff818d1953)
Location: include/linux/bpf.h:882
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819e0c6f)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff819ec335)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffff811d8595)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (ffffffff811fcb16)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
```
In kernel/events/core.c (ffffffff8120a422)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
```
In drivers/net/tun.c (ffffffff817b5bc4)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff81950161)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff81968d33)
Location: include/linux/bpf.h:882
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a8e92f)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff81a9acf5)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/bpf/syscall.c (ffffffff811e6918)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (ffffffff8120b796)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
```
```
In kernel/events/core.c (ffffffff812191ec)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
```
```
In drivers/net/tun.c (ffffffff817cff64)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In net/core/filter.c (ffffffff81971b31)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_attach_bpf
```
```
In net/core/lwt_bpf.c (ffffffff8198b113)
Location: include/linux/bpf.h:882
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b69f)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/packet/af_packet.c (ffffffff81aa7a5e)
Location: include/linux/bpf.h:882
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
