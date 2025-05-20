# Function: <code>percpu_counter_destroy_many</code>

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
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy_many(struct percpu_counter *fbc, u32 nr_counters);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8191fc30)
Location: lib/percpu_counter.c:193
Inline: True
Direct callers:
  - kernel/fork.c:__mmdrop
  - kernel/user.c:alloc_uid
  - kernel/user.c:free_uid
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/shmem.c:shmem_put_super
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_percpu_param_destroy
  - fs/ext4/super.c:ext4_percpu_param_destroy
  - fs/ext4/super.c:ext4_percpu_param_destroy
  - fs/ext4/super.c:ext4_percpu_param_destroy
  - fs/ext4/super.c:ext4_percpu_param_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_init_common
  - ipc/msg.c:msg_exit_ns
  - ipc/msg.c:msg_exit_ns
  - ipc/msg.c:msg_init_ns
  - block/blk-cgroup-rwstat.c:blkg_rwstat_exit
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:__io_uring_free
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff8191fc30-ffffffff8191fd4b: percpu_counter_destroy_many (STB_GLOBAL)
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
