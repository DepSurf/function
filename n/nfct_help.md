# Function: <code>nfct_help</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_conntrack_core.c (ffffffff8199cce8)
Location: include/net/netfilter/nf_conntrack_helper.h:120
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_alter_reply
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2052)
Location: include/net/netfilter/nf_conntrack_helper.h:120
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:exp_seq_show
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_remove_expectations
  - net/netfilter/nf_conntrack_expect.c:nf_ct_unlink_expect_report
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a3151)
Location: include/net/netfilter/nf_conntrack_helper.h:120
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:expect_iter_me
  - net/netfilter/nf_conntrack_helper.c:nf_ct_helper_log
  - net/netfilter/nf_conntrack_helper.c:nf_ct_helper_destroy
  - net/netfilter/nf_conntrack_helper.c:unhelp
  - net/netfilter/nf_conntrack_helper.c:__nf_ct_try_assign_helper
  - net/netfilter/nf_conntrack_helper.c:__nf_ct_try_assign_helper
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a48b0)
Location: include/net/netfilter/nf_conntrack_helper.h:120
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:nf_confirm
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ac9e1)
Location: include/net/netfilter/nf_conntrack_helper.h:120
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:expect_iter_name
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_ct_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_helper
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_helpinfo
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
