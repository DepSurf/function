# Function: <code>__percpu_counter_init_many</code>

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
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __percpu_counter_init_many(struct percpu_counter *fbc, s64 amount, gfp_t gfp, u32 nr_counters, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8191fb20)
Location: lib/percpu_counter.c:154
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_percpu_param_init
  - fs/ext4/super.c:ext4_percpu_param_init
  - fs/ext4/super.c:ext4_percpu_param_init
  - fs/ext4/super.c:ext4_percpu_param_init
  - fs/ext4/super.c:ext4_percpu_param_init
  - fs/jbd2/journal.c:journal_init_common
  - ipc/msg.c:msg_init_ns
  - ipc/msg.c:msg_init_ns
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
  - io_uring/tctx.c:io_uring_alloc_task_context
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
ffffffff8191fb20-ffffffff8191fc18: __percpu_counter_init_many (STB_GLOBAL)
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
<b>Regular</b>
<ul>
</ul>
