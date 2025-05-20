# Function: <code>bpf_prog_array_free</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119e020)
Location: kernel/bpf/core.c:1453
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_put
```
**Symbols:**

```
ffffffff8119e020-ffffffff8119e042: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b2750)
Location: kernel/bpf/core.c:1551
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_put
```
**Symbols:**

```
ffffffff811b2750-ffffffff811b2771: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c12a0)
Location: kernel/bpf/core.c:1802
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_put
```
**Symbols:**

```
ffffffff811c12a0-ffffffff811c12c1: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d19f0)
Location: kernel/bpf/core.c:1797
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811d19f0-ffffffff811d1a11: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811ddf70)
Location: kernel/bpf/core.c:1797
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811ddf70-ffffffff811ddf91: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811faa30)
Location: kernel/bpf/core.c:1875
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811faa30-ffffffff811faa51: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9c80)
Location: kernel/bpf/core.c:1877
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811f9c80-ffffffff811f9ca1: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fabf0)
Location: kernel/bpf/core.c:1973
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff811fabf0-ffffffff811fac11: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122c300)
Location: kernel/bpf/core.c:1986
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff8122c300-ffffffff8122c321: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126df20)
Location: kernel/bpf/core.c:2272
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff8126df20-ffffffff8126df51: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c34b0)
Location: kernel/bpf/core.c:2245
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff812c34b0-ffffffff812c34e1: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812ea300)
Location: kernel/bpf/core.c:2262
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff812ea300-ffffffff812ea332: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81308610)
Location: kernel/bpf/core.c:2438
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_detach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff81308610-ffffffff81308642: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025ef60)
Location: kernel/bpf/core.c:1797
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffff80001025ef60-ffff80001025efa8: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c049249c)
Location: kernel/bpf/core.c:1797
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
c049249c-c04924dc: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000303f30)
Location: kernel/bpf/core.c:1797
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
c000000000303f30-c000000000303f80: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019d0c4)
Location: kernel/bpf/core.c:1797
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffe00019d0c4-ffffffe00019d0fe: bpf_prog_array_free (STB_GLOBAL)
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
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6590)
Location: kernel/bpf/core.c:1797
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811d6590-ffffffff811d65b1: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c9350)
Location: kernel/bpf/core.c:1797
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811c9350-ffffffff811c9371: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d4360)
Location: kernel/bpf/core.c:1797
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811d4360-ffffffff811d4381: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2680)
Location: kernel/bpf/core.c:1797
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:update_effective_progs
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811e2680-ffffffff811e26a1: bpf_prog_array_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
