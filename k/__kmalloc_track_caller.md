# Function: <code>__kmalloc_track_caller</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811eea40)
Location: mm/slub.c:4023
Inline: False
Direct callers:
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/util.c:kstrndup
  - mm/util.c:memdup_user
  - mm/slab_common.c:__krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff811eea40-ffffffff811eec81: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120ddb0)
Location: mm/slub.c:4250
Inline: False
Direct callers:
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff8120ddb0-ffffffff8120dfa5: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121fdf0)
Location: mm/slub.c:4219
Inline: False
Direct callers:
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff8121fdf0-ffffffff8121ffe5: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8122bb60)
Location: mm/slub.c:4261
Inline: False
Direct callers:
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff8122bb60-ffffffff8122bd4b: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81247270)
Location: mm/slub.c:4277
Inline: False
Direct callers:
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff81247270-ffffffff8124747d: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8126a1a0)
Location: mm/slub.c:4279
Inline: False
Direct callers:
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff8126a1a0-ffffffff8126a3c8: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127ea60)
Location: mm/slub.c:4331
Inline: False
Direct callers:
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff8127ea60-ffffffff8127ec69: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129a840)
Location: mm/slub.c:4322
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff8129a840-ffffffff8129aaa6: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812aa700)
Location: mm/slub.c:4340
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff812aa700-ffffffff812aa966: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812dc980)
Location: mm/slub.c:4417
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff812dc980-ffffffff812dcc01: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e9090)
Location: mm/slub.c:4466
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - lib/kasprintf.c:kvasprintf
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
**Symbols:**

```
ffffffff812e9090-ffffffff812e92d0: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ef880)
Location: mm/slub.c:4547
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - lib/kasprintf.c:kvasprintf
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
**Symbols:**

```
ffffffff812ef880-ffffffff812efae0: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81338850)
Location: mm/slub.c:4903
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:copy_array
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - lib/kasprintf.c:kvasprintf
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
**Symbols:**

```
ffffffff81338850-ffffffff81338b84: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813ab970)
Location: mm/slub.c:4935
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:copy_array
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - lib/kasprintf.c:kvasprintf
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
**Symbols:**

```
ffffffff813ab970-ffffffff813abce6: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034c5a8)
Location: mm/slub.c:4340
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffff80001034c5a8-ffff80001034c890: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0550154)
Location: mm/slub.c:4340
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
  - drivers/base/devres.c:devm_kmalloc
  - drivers/base/devres.c:devres_alloc_node
```
**Symbols:**

```
c0550154-c05504e4: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042c090)
Location: mm/slub.c:4340
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
c00000000042c090-c00000000042c4a8: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023d694)
Location: mm/slub.c:4340
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kmemdup
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
  - drivers/base/devres.c:devm_kmalloc
  - drivers/base/devres.c:devres_alloc_node
```
**Symbols:**

```
ffffffe00023d694-ffffffe00023d94a: __kmalloc_track_caller (STB_GLOBAL)
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
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a2ce0)
Location: mm/slub.c:4340
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff812a2ce0-ffffffff812a2f46: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812947b0)
Location: mm/slub.c:4340
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff812947b0-ffffffff81294a1b: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a0af0)
Location: mm/slub.c:4340
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff812a0af0-ffffffff812a0d56: __kmalloc_track_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b0c30)
Location: mm/slub.c:4340
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - mm/util.c:memdup_user_nul
  - mm/util.c:memdup_user
  - mm/util.c:kmemdup_nul
  - mm/util.c:kstrndup
  - mm/util.c:kstrdup
  - mm/util.c:kmemdup
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:krealloc
  - mm/slab_common.c:__krealloc
  - lib/kasprintf.c:kvasprintf
```
**Symbols:**

```
ffffffff812b0c30-ffffffff812b0ec2: __kmalloc_track_caller (STB_GLOBAL)
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
