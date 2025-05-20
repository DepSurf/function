# Function: <code>__percpu_counter_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81411bb0)
Location: lib/percpu_counter.c:115
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/flex_proportions.c:fprop_global_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_memcontrol.c:tcp_init_cgroup
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff81411bb0-ffffffff81411c2f: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81459910)
Location: lib/percpu_counter.c:115
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff81459910-ffffffff8145998f: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814782d0)
Location: lib/percpu_counter.c:115
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff814782d0-ffffffff8147834f: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81481610)
Location: lib/percpu_counter.c:122
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
ffffffff81481610-ffffffff8148168f: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814bd450)
Location: lib/percpu_counter.c:123
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
ffffffff814bd450-ffffffff814bd4cf: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814efcb0)
Location: lib/percpu_counter.c:123
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
ffffffff814efcb0-ffffffff814efd2f: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81503bd0)
Location: lib/percpu_counter.c:122
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
ffffffff81503bd0-ffffffff81503c4f: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81531d30)
Location: lib/percpu_counter.c:122
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
ffffffff81531d30-ffffffff81531daf: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81552be0)
Location: lib/percpu_counter.c:122
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
ffffffff81552be0-ffffffff81552c5f: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815dbfc0)
Location: lib/percpu_counter.c:122
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff815dbfc0-ffffffff815dc03f: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815f9c60)
Location: lib/percpu_counter.c:141
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff815f9c60-ffffffff815f9cdf: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815dc840)
Location: lib/percpu_counter.c:141
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff815dc840-ffffffff815dc8bf: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81648180)
Location: lib/percpu_counter.c:141
Inline: False
Direct callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_init_common
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81648180-ffffffff816481ff: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8175e660)
Location: lib/percpu_counter.c:141
Inline: False
Direct callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/jbd2/journal.c:journal_init_common
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
  - io_uring/io_uring.c:io_uring_alloc_task_context
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff8175e660-ffffffff8175e6e9: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8188bda0)
Location: lib/percpu_counter.c:158
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
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
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
ffffffff8188bda0-ffffffff8188be29: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff818ce0c0)
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
ffffffff818ce0c0-ffffffff818ce149: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffff80001065eef8)
Location: lib/percpu_counter.c:122
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
ffff80001065eef8-ffff80001065efec: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (c0808434)
Location: lib/percpu_counter.c:122
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
c0808434-c08084bc: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (c000000000811580)
Location: lib/percpu_counter.c:122
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
c000000000811580-c000000000811648: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffe00048c452)
Location: lib/percpu_counter.c:122
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
ffffffe00048c452-ffffffe00048c484: __percpu_counter_init (STB_GLOBAL)
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
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8154b1c0)
Location: lib/percpu_counter.c:122
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
ffffffff8154b1c0-ffffffff8154b23f: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8153b4a0)
Location: lib/percpu_counter.c:122
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
ffffffff8153b4a0-ffffffff8153b51f: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81546f00)
Location: lib/percpu_counter.c:122
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
ffffffff81546f00-ffffffff81546f7f: __percpu_counter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter *fbc, s64 amount, gfp_t gfp, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81560df0)
Location: lib/percpu_counter.c:122
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_init
  - mm/mmap.c:mmap_init
  - fs/file_table.c:files_init
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_init_percpu
  - lib/flex_proportions.c:fprop_global_init
```
**Symbols:**

```
ffffffff81560df0-ffffffff81560e6f: __percpu_counter_init (STB_GLOBAL)
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
