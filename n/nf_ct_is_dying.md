# Function: <code>nf_ct_is_dying</code>

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
In net/netfilter/nf_conntrack_core.c (ffffffff8199e4af)
Location: include/net/netfilter/nf_conntrack.h:249
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/netfilter/nf_conntrack_core.c:early_drop
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a182f)
Location: include/net/netfilter/nf_conntrack.h:249
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_show
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2e16)
Location: include/net/netfilter/nf_conntrack.h:249
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_find_expectation
```
```
In net/netfilter/nf_conntrack_ecache.c (ffffffff819a8fe6)
Location: include/net/netfilter/nf_conntrack.h:249
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_ecache.c:nf_ct_deliver_cached_events
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b0a8c)
Location: include/net/netfilter/nf_conntrack.h:249
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
