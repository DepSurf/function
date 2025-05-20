# Function: <code>bpf_base_func_proto</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ea170)
Location: net/core/filter.c:2891
Inline: True
Direct callers:
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:lwt_inout_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
```
**Symbols:**

```
ffffffff817ea170-ffffffff817ea1e3: bpf_base_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81865800)
Location: net/core/filter.c:3331
Inline: True
Direct callers:
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:lwt_inout_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
  - net/core/filter.c:sock_filter_func_proto
```
**Symbols:**

```
ffffffff81865800-ffffffff81865879: bpf_base_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b32e0)
Location: net/core/filter.c:4734
Inline: True
Direct callers:
  - net/core/filter.c:lwt_out_func_proto
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sk_msg_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
  - net/core/filter.c:sock_filter_func_proto
```
**Symbols:**

```
ffffffff818b32e0-ffffffff818b335b: bpf_base_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8130)
Location: net/core/filter.c:5290
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:lwt_out_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sk_msg_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
  - net/core/filter.c:sock_filter_func_proto
```
**Symbols:**

```
ffffffff818d8130-ffffffff818d8213: bpf_base_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81925fb0)
Location: net/core/filter.c:5890
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:lwt_out_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sk_msg_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
  - net/core/filter.c:sock_filter_func_proto
```
**Symbols:**

```
ffffffff81925fb0-ffffffff819260ce: bpf_base_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81958610)
Location: net/core/filter.c:5967
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:lwt_out_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sk_msg_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
  - net/core/filter.c:sock_filter_func_proto
```
**Symbols:**

```
ffffffff81958610-ffffffff8195872e: bpf_base_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81214f60)
Location: kernel/bpf/helpers.c:611
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_in_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sk_msg_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:cg_skb_func_proto
  - net/core/filter.c:sock_addr_func_proto
  - net/core/filter.c:sock_filter_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
```
**Symbols:**

```
ffffffff81214f60-ffffffff81215203: bpf_base_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81216b50)
Location: kernel/bpf/helpers.c:672
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sock_filter_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
```
**Symbols:**

```
ffffffff81216b50-ffffffff81216ea2: bpf_base_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81219fd0)
Location: kernel/bpf/helpers.c:999
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sock_filter_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
```
**Symbols:**

```
ffffffff81219fd0-ffffffff8121a2f5: bpf_base_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81250c80)
Location: kernel/bpf/helpers.c:1343
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/syscall.c:tracing_prog_func_proto
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sock_filter_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
```
**Symbols:**

```
ffffffff81250c80-ffffffff81251053: bpf_base_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812984d0)
Location: kernel/bpf/helpers.c:1591
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/syscall.c:tracing_prog_func_proto
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
  - net/core/filter.c:bpf_sk_base_func_proto
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:sock_filter_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
```
**Symbols:**

```
ffffffff812984d0-ffffffff81298a47: bpf_base_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f3710)
Location: kernel/bpf/helpers.c:1585
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/syscall.c:tracing_prog_func_proto
  - net/core/filter.c:bpf_sk_base_func_proto
  - net/core/filter.c:sk_reuseport_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
```
**Symbols:**

```
ffffffff812f3710-ffffffff812f3ceb: bpf_base_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff813205d0)
Location: kernel/bpf/helpers.c:1666
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/syscall.c:tracing_prog_func_proto
  - net/core/filter.c:bpf_sk_base_func_proto
  - net/core/filter.c:sk_reuseport_func_proto
  - net/netfilter/nf_bpf_link.c:bpf_nf_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
```
**Symbols:**

```
ffffffff813205d0-ffffffff81320bb9: bpf_base_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81342ad0)
Location: kernel/bpf/helpers.c:1685
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/syscall.c:tracing_prog_func_proto
  - net/core/filter.c:bpf_sk_base_func_proto
  - net/core/filter.c:sk_reuseport_func_proto
  - net/netfilter/nf_bpf_link.c:bpf_nf_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
```
**Symbols:**

```
ffffffff81342ad0-ffffffff813430b9: bpf_base_func_proto (STB_GLOBAL)
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
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf9818)
Location: net/core/filter.c:5967
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:lwt_out_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sk_msg_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
  - net/core/filter.c:sock_filter_func_proto
```
**Symbols:**

```
ffff800010bf9818-ffff800010bf99a0: bpf_base_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d130c0)
Location: net/core/filter.c:5967
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:lwt_out_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sk_msg_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
  - net/core/filter.c:sock_filter_func_proto
```
**Symbols:**

```
c0d130c0-c0d1329c: bpf_base_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce10e0)
Location: net/core/filter.c:5967
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:lwt_out_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sk_msg_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
  - net/core/filter.c:sock_filter_func_proto
```
**Symbols:**

```
c000000000ce10e0-c000000000ce1354: bpf_base_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077b6c8)
Location: net/core/filter.c:5967
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:lwt_out_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sk_msg_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
  - net/core/filter.c:sock_filter_func_proto
```
**Symbols:**

```
ffffffe00077b6c8-ffffffe00077b7e0: bpf_base_func_proto (STB_LOCAL)
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
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f85e0)
Location: net/core/filter.c:5967
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:lwt_out_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sk_msg_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
  - net/core/filter.c:sock_filter_func_proto
```
**Symbols:**

```
ffffffff818f85e0-ffffffff818f86fe: bpf_base_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2410)
Location: net/core/filter.c:5967
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:lwt_out_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sk_msg_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
  - net/core/filter.c:sock_filter_func_proto
```
**Symbols:**

```
ffffffff818b2410-ffffffff818b252e: bpf_base_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81949610)
Location: net/core/filter.c:5967
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:lwt_out_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sk_msg_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
  - net/core/filter.c:sock_filter_func_proto
```
**Symbols:**

```
ffffffff81949610-ffffffff8194972e: bpf_base_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *bpf_base_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196af20)
Location: net/core/filter.c:5967
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_func_proto
  - net/core/filter.c:lwt_out_func_proto
  - net/core/filter.c:flow_dissector_func_proto
  - net/core/filter.c:sk_skb_func_proto
  - net/core/filter.c:sk_msg_func_proto
  - net/core/filter.c:sock_ops_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
  - net/core/filter.c:sk_filter_func_proto
  - net/core/filter.c:sock_filter_func_proto
```
**Symbols:**

```
ffffffff8196af20-ffffffff8196b03e: bpf_base_func_proto (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
