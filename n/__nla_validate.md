# Function: <code>__nla_validate</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815344b1)
Location: lib/nlattr.c:419
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
Direct callers:
  - kernel/taskstats.c:taskstats_pre_doit
  - lib/nlattr.c:validate_nla
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff815349b0-ffffffff815349bd: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81555339)
Location: lib/nlattr.c:419
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
Direct callers:
  - kernel/taskstats.c:taskstats_pre_doit
  - lib/nlattr.c:validate_nla
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff815557e0-ffffffff815557ed: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815df380)
Location: lib/nlattr.c:571
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_pre_doit
  - net/ethtool/strset.c:strset_parse_request
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
**Symbols:**

```
ffffffff815df380-ffffffff815df38f: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fcb90)
Location: lib/nlattr.c:626
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
**Symbols:**

```
ffffffff815fcb90-ffffffff815fcb9f: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815df900)
Location: lib/nlattr.c:626
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
**Symbols:**

```
ffffffff815df900-ffffffff815df90f: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8164b540)
Location: lib/nlattr.c:626
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
**Symbols:**

```
ffffffff8164b540-ffffffff8164b54f: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81761f70)
Location: lib/nlattr.c:626
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
**Symbols:**

```
ffffffff81761f70-ffffffff81761f91: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81890d30)
Location: lib/nlattr.c:641
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
**Symbols:**

```
ffffffff81890d30-ffffffff81890d51: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d3130)
Location: lib/nlattr.c:641
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
**Symbols:**

```
ffffffff818d3130-ffffffff818d3151: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81925210)
Location: lib/nlattr.c:673
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_parse_request
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
**Symbols:**

```
ffffffff81925210-ffffffff81925231: __nla_validate (STB_GLOBAL)
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
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff800010661714)
Location: lib/nlattr.c:419
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
Direct callers:
  - kernel/taskstats.c:taskstats_pre_doit
  - lib/nlattr.c:validate_nla
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffff800010661c00-ffff800010661c18: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080a860)
Location: lib/nlattr.c:419
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
Direct callers:
  - kernel/taskstats.c:taskstats_pre_doit
  - lib/nlattr.c:validate_nla
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_common
```
**Symbols:**

```
c080acd4-c080ad08: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c000000000815898)
Location: lib/nlattr.c:419
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
Direct callers:
  - kernel/taskstats.c:taskstats_pre_doit
  - lib/nlattr.c:validate_nla
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
c000000000815de0-c000000000815df0: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048e2b8)
Location: lib/nlattr.c:419
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
Direct callers:
  - kernel/taskstats.c:taskstats_pre_doit
  - lib/nlattr.c:validate_nla
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffe00048e502-ffffffe00048e51c: __nla_validate (STB_GLOBAL)
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
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8154d919)
Location: lib/nlattr.c:419
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
Direct callers:
  - kernel/taskstats.c:taskstats_pre_doit
  - lib/nlattr.c:validate_nla
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff8154ddc0-ffffffff8154ddcd: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8153dbf9)
Location: lib/nlattr.c:419
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
Direct callers:
  - kernel/taskstats.c:taskstats_pre_doit
  - lib/nlattr.c:validate_nla
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff8153e0a0-ffffffff8153e0ad: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81549659)
Location: lib/nlattr.c:419
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
Direct callers:
  - kernel/taskstats.c:taskstats_pre_doit
  - lib/nlattr.c:validate_nla
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple_proto
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff81549b00-ffffffff81549b0d: __nla_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __nla_validate(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815634a9)
Location: lib/nlattr.c:419
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
Direct callers:
  - kernel/taskstats.c:taskstats_pre_doit
  - lib/nlattr.c:validate_nla
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff81563950-ffffffff8156395d: __nla_validate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
