# Function: <code>rhashtable_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81400250)
Location: lib/rhashtable.c:725
Inline: False
```
**Symbols:**

```
ffffffff81400250-ffffffff81400530: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81447b10)
Location: lib/rhashtable.c:730
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81447b10-ffffffff81447de2: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81466460)
Location: lib/rhashtable.c:836
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff81466460-ffffffff8146672f: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8146bd40)
Location: lib/rhashtable.c:930
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff8146bd40-ffffffff8146bf8f: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81498040)
Location: lib/rhashtable.c:933
Inline: False
Direct callers:
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/sched/act_api.c:tcf_action_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff81498040-ffffffff8149828f: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814ccbb0)
Location: lib/rhashtable.c:1027
Inline: False
Direct callers:
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/sched/act_api.c:tcf_action_net_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff814ccbb0-ffffffff814cce10: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814e1160)
Location: lib/rhashtable.c:1018
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff814e1160-ffffffff814e13c1: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8150cf50)
Location: lib/rhashtable.c:1008
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff8150cf50-ffffffff8150d183: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8152ada0)
Location: lib/rhashtable.c:1008
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/flow_offload.c:init_flow_indr_rhashtable
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff8152ada0-ffffffff8152afd3: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8158e360)
Location: lib/rhashtable.c:1015
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff8158e360-ffffffff8158e5ab: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815aaed0)
Location: lib/rhashtable.c:1015
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff815aaed0-ffffffff815ab11b: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815b59e0)
Location: lib/rhashtable.c:1015
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/xfrm/xfrm_policy.c:xfrm_policy_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff815b59e0-ffffffff815b5c28: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1015
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/ioam6.c:ioam6_net_init
  - net/ipv6/ioam6.c:ioam6_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff81cdab8c-ffffffff81cdabef: rhashtable_init.cold (STB_LOCAL)
ffffffff8161be70-ffffffff8161c0cd: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1015
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/ioam6.c:ioam6_net_init
  - net/ipv6/ioam6.c:ioam6_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff81e9345c-ffffffff81e934bf: rhashtable_init.cold (STB_LOCAL)
ffffffff816e9850-ffffffff816e9aa8: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1019
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/ioam6.c:ioam6_net_init
  - net/ipv6/ioam6.c:ioam6_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff820785c8-ffffffff8207862b: rhashtable_init.cold (STB_LOCAL)
ffffffff817d99f0-ffffffff817d9c48: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1019
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_init
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/ioam6.c:ioam6_net_init
  - net/ipv6/ioam6.c:ioam6_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
  - net/handshake/request.c:handshake_req_hash_init
```
**Symbols:**

```
ffffffff820f8b44-ffffffff820f8ba7: rhashtable_init.cold (STB_LOCAL)
ffffffff81818d70-ffffffff81818fc8: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:1019
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_init
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/ioam6.c:ioam6_net_init
  - net/ipv6/ioam6.c:ioam6_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
  - net/handshake/request.c:handshake_req_hash_init
```
**Symbols:**

```
ffffffff821d6665-ffffffff821d66c8: rhashtable_init.cold (STB_LOCAL)
ffffffff8185e0c0-ffffffff8185e318: rhashtable_init (STB_GLOBAL)
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
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffff800010635e98)
Location: lib/rhashtable.c:1008
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/flow_offload.c:init_flow_indr_rhashtable
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffff800010635e98-ffff8000106360e8: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c07dbdf4)
Location: lib/rhashtable.c:1008
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/flow_offload.c:init_flow_indr_rhashtable
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
c07dbdf4-c07dc028: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c0000000007dc4d0)
Location: lib/rhashtable.c:1008
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/flow_offload.c:init_flow_indr_rhashtable
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
c0000000007dc4d0-c0000000007dc770: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffe000463dc2)
Location: lib/rhashtable.c:1008
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/flow_offload.c:init_flow_indr_rhashtable
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffe000463dc2-ffffffe000464048: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81523380)
Location: lib/rhashtable.c:1008
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/flow_offload.c:init_flow_indr_rhashtable
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff81523380-ffffffff815235b3: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81513660)
Location: lib/rhashtable.c:1008
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/flow_offload.c:init_flow_indr_rhashtable
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff81513660-ffffffff81513893: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8151f410)
Location: lib/rhashtable.c:1008
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/flow_offload.c:init_flow_indr_rhashtable
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff8151f410-ffffffff8151f643: rhashtable_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rhashtable_init(struct rhashtable *ht, const struct rhashtable_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81538e30)
Location: lib/rhashtable.c:1008
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - ipc/util.c:ipc_init_ids
  - security/apparmor/policy_unpack.c:unpack_profile
  - lib/rhashtable.c:rhltable_init
  - net/core/flow_offload.c:init_flow_indr_rhashtable
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
```
**Symbols:**

```
ffffffff81538e30-ffffffff81539063: rhashtable_init (STB_GLOBAL)
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
