# Function: <code>percpu_counter_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81411c30)
Location: lib/percpu_counter.c:139
Inline: False
Direct callers:
  - mm/shmem.c:shmem_put_super
  - mm/backing-dev.c:wb_init
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - block/blk-cgroup.c:blkg_free
  - block/blk-cgroup.c:blkg_free
  - block/blk-cgroup.c:blkg_free
  - block/blk-cgroup.c:blkg_free
  - block/blk-cgroup.c:blkg_free
  - block/blk-cgroup.c:blkg_free
  - block/blk-cgroup.c:blkg_free
  - block/blk-cgroup.c:blkg_free
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/flex_proportions.c:fprop_global_destroy
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/tcp_memcontrol.c:tcp_destroy_cgroup
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff81411c30-ffffffff81411c9a: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81459990)
Location: lib/percpu_counter.c:139
Inline: False
Direct callers:
  - mm/shmem.c:shmem_put_super
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_free
  - block/blk-cgroup.c:blkg_free
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff81459990-ffffffff814599fa: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81478350)
Location: lib/percpu_counter.c:139
Inline: False
Direct callers:
  - mm/shmem.c:shmem_put_super
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_free
  - block/blk-cgroup.c:blkg_free
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff81478350-ffffffff814783ba: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81481690)
Location: lib/percpu_counter.c:146
Inline: True
Direct callers:
  - mm/shmem.c:shmem_put_super
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
ffffffff81481690-ffffffff814816fb: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814bd4d0)
Location: lib/percpu_counter.c:147
Inline: True
Direct callers:
  - mm/shmem.c:shmem_put_super
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
ffffffff814bd4d0-ffffffff814bd53b: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814efd30)
Location: lib/percpu_counter.c:147
Inline: True
Direct callers:
  - mm/shmem.c:shmem_put_super
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
ffffffff814efd30-ffffffff814efd9a: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81503c50)
Location: lib/percpu_counter.c:146
Inline: True
Direct callers:
  - mm/shmem.c:shmem_put_super
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
ffffffff81503c50-ffffffff81503cba: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81531db0)
Location: lib/percpu_counter.c:146
Inline: True
Direct callers:
  - mm/shmem.c:shmem_put_super
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
ffffffff81531db0-ffffffff81531e14: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81552cc0)
Location: lib/percpu_counter.c:146
Inline: True
Direct callers:
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
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
ffffffff81552cc0-ffffffff81552d24: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815dc0a0)
Location: lib/percpu_counter.c:146
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fill_super
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
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup-rwstat.c:blkg_rwstat_exit
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
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
ffffffff815dc0a0-ffffffff815dc107: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815f9d40)
Location: lib/percpu_counter.c:165
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/io_uring.c:__io_uring_free
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup-rwstat.c:blkg_rwstat_exit
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
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
ffffffff815f9d40-ffffffff815f9da7: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815dc920)
Location: lib/percpu_counter.c:165
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/io_uring.c:__io_uring_free
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup-rwstat.c:blkg_rwstat_exit
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
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
ffffffff815dc920-ffffffff815dc987: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81648260)
Location: lib/percpu_counter.c:165
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:free_uid
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/io_uring.c:__io_uring_free
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_init_common
  - block/blk-cgroup-rwstat.c:blkg_rwstat_exit
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
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
ffffffff81648260-ffffffff816482c7: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8175e6f0)
Location: lib/percpu_counter.c:165
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:free_uid
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:wb_init
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_init_common
  - block/blk-cgroup-rwstat.c:blkg_rwstat_exit
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
  - io_uring/io_uring.c:__io_uring_free
  - io_uring/io_uring.c:io_uring_alloc_task_context
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
ffffffff8175e6f0-ffffffff8175e76f: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8188be40)
Location: lib/percpu_counter.c:182
Inline: True
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/user.c:alloc_uid
  - kernel/user.c:free_uid
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:wb_init
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
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
ffffffff8188be40-ffffffff8188bebf: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff818ce160)
Location: lib/percpu_counter.c:178
Inline: True
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:__mmdrop
  - kernel/user.c:alloc_uid
  - kernel/user.c:free_uid
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - mm/shmem.c:shmem_fill_super
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:wb_init
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
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
ffffffff818ce160-ffffffff818ce1df: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff81112e43)
Location: include/linux/percpu_counter.h:50
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:free_uid
```
```
In kernel/bpf/hashtab.c (ffffffff8134c0e4)
Location: include/linux/percpu_counter.h:50
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In mm/shmem.c (ffffffff813e5984)
Location: include/linux/percpu_counter.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_put_super
```
```
In mm/backing-dev.c (ffffffff813f4f88)
Location: include/linux/percpu_counter.h:50
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
```
In fs/ext4/extents_status.c (ffffffff815d9c25)
Location: include/linux/percpu_counter.h:50
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
```
```
In fs/ext4/super.c (ffffffff8162e5f5)
Location: include/linux/percpu_counter.h:50
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_percpu_param_destroy
  - fs/ext4/super.c:ext4_percpu_param_destroy
  - fs/ext4/super.c:ext4_percpu_param_destroy
  - fs/ext4/super.c:ext4_percpu_param_destroy
  - fs/ext4/super.c:ext4_percpu_param_destroy
```
```
In fs/jbd2/journal.c (ffffffff8165a6a3)
Location: include/linux/percpu_counter.h:50
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_init_common
```
```
In ipc/msg.c (ffffffff816b4af8)
Location: include/linux/percpu_counter.h:50
Inline: True
Inline callers:
  - ipc/msg.c:msg_exit_ns
  - ipc/msg.c:msg_exit_ns
  - ipc/msg.c:msg_init_ns
```
```
In block/blk-cgroup-rwstat.c (ffffffff817e6a1a)
Location: include/linux/percpu_counter.h:50
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_exit
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In io_uring/tctx.c (ffffffff81821087)
Location: include/linux/percpu_counter.h:50
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:__io_uring_free
```
```
In net/ipv4/xfrm4_policy.c (ffffffff820524a5)
Location: include/linux/percpu_counter.h:50
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff820a7ce4)
Location: include/linux/percpu_counter.h:50
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e0405)
Location: include/linux/percpu_counter.h:50
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
```
In lib/flex_proportions.c (ffffffff82178670)
Location: include/linux/percpu_counter.h:50
Inline: True
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
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffff80001065ebf0)
Location: lib/percpu_counter.c:146
Inline: True
Direct callers:
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
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
ffff80001065ebf0-ffff80001065ecc8: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (c080855c)
Location: lib/percpu_counter.c:146
Inline: True
Direct callers:
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
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
c080855c-c08085c4: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (c000000000811710)
Location: lib/percpu_counter.c:146
Inline: True
Direct callers:
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
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
c000000000811710-c0000000008117cc: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffe00048c484)
Location: lib/percpu_counter.c:146
Inline: False
Direct callers:
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
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
ffffffe00048c484-ffffffe00048c4aa: percpu_counter_destroy (STB_GLOBAL)
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
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8154b2a0)
Location: lib/percpu_counter.c:146
Inline: True
Direct callers:
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
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
ffffffff8154b2a0-ffffffff8154b304: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8153b580)
Location: lib/percpu_counter.c:146
Inline: True
Direct callers:
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
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
ffffffff8153b580-ffffffff8153b5e4: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81546fe0)
Location: lib/percpu_counter.c:146
Inline: True
Direct callers:
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
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
ffffffff81546fe0-ffffffff81547044: percpu_counter_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void percpu_counter_destroy(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81560ed0)
Location: lib/percpu_counter.c:146
Inline: True
Direct callers:
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
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - lib/flex_proportions.c:fprop_local_destroy_percpu
  - lib/flex_proportions.c:fprop_global_destroy
```
**Symbols:**

```
ffffffff81560ed0-ffffffff81560f34: percpu_counter_destroy (STB_GLOBAL)
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
