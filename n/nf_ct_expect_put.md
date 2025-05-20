# Function: <code>nf_ct_expect_put</code>

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
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void nf_ct_expect_put(struct nf_conntrack_expect *exp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2150)
Location: net/netfilter/nf_conntrack_expect.c:362
Inline: True
Direct callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_iterate_net
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_iterate_destroy
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expectation_timed_out
  - net/netfilter/nf_conntrack_expect.c:nf_ct_unlink_expect_report
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_ct_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_done
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_attach_expect
```
**Symbols:**

```
ffffffff819a2150-ffffffff819a217e: nf_ct_expect_put (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
</ul>
