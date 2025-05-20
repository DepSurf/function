# Function: <code>nf_inet_addr_cmp</code>

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
In net/netfilter/nf_conntrack_core.c (ffffffff8199ded8)
Location: include/linux/netfilter.h:23
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_tuple_taken
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_tuple_taken
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_tuple_taken
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_tuple_taken
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2787)
Location: include/linux/netfilter.h:23
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_find_expectation
  - net/netfilter/nf_conntrack_expect.c:__nf_ct_expect_find
```
```
In net/netfilter/nf_conntrack_proto_icmp.c (ffffffff819a79be)
Location: include/linux/netfilter.h:23
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_inet_error
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819afa34)
Location: include/linux/netfilter.h:23
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_expect
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
