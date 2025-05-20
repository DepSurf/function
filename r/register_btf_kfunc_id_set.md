# Function: <code>register_btf_kfunc_id_set</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_btf_kfunc_id_set(enum bpf_prog_type prog_type, const struct btf_kfunc_id_set *kset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81e6a7d0)
Location: kernel/bpf/btf.c:7148
Inline: True
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_kfunc_init
```
**Symbols:**

```
ffffffff81e6a7bc-ffffffff81e6a7fc: register_btf_kfunc_id_set.cold (STB_LOCAL)
ffffffff812b37a0-ffffffff812b3890: register_btf_kfunc_id_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_btf_kfunc_id_set(enum bpf_prog_type prog_type, const struct btf_kfunc_id_set *kset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81313d00)
Location: kernel/bpf/btf.c:7653
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:bpf_rstat_kfunc_init
  - kernel/trace/bpf_trace.c:bpf_key_sig_kfuncs_init
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/helpers.c:kfunc_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_kfunc_init
```
**Symbols:**

```
ffffffff81313d00-ffffffff81313d2d: register_btf_kfunc_id_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_btf_kfunc_id_set(enum bpf_prog_type prog_type, const struct btf_kfunc_id_set *kset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81343b10)
Location: kernel/bpf/btf.c:7914
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:bpf_rstat_kfunc_init
  - kernel/trace/bpf_trace.c:bpf_key_sig_kfuncs_init
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/cpumask.c:cpumask_kfunc_init
  - kernel/bpf/cpumask.c:cpumask_kfunc_init
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_init
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_init
  - net/core/filter.c:init_subsystem
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/xdp.c:xdp_metadata_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_kfunc_init
```
**Symbols:**

```
ffffffff81343b10-ffffffff81343b3d: register_btf_kfunc_id_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_btf_kfunc_id_set(enum bpf_prog_type prog_type, const struct btf_kfunc_id_set *kset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81369aa0)
Location: kernel/bpf/btf.c:7979
Inline: False
Direct callers:
  - kernel/cgroup/rstat.c:bpf_rstat_kfunc_init
  - kernel/trace/bpf_trace.c:bpf_fs_kfuncs_init
  - kernel/trace/bpf_trace.c:bpf_key_sig_kfuncs_init
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/map_iter.c:init_subsystem
  - kernel/bpf/cpumask.c:cpumask_kfunc_init
  - kernel/bpf/cpumask.c:cpumask_kfunc_init
  - fs/verity/measure.c:fsverity_init_bpf
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_init
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_init
  - net/core/filter.c:init_subsystem
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/filter.c:bpf_kfunc_init
  - net/core/xdp.c:xdp_metadata_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_kfunc_init
  - net/xfrm/xfrm_state_bpf.c:register_xfrm_state_bpf
```
**Symbols:**

```
ffffffff81369aa0-ffffffff81369acd: register_btf_kfunc_id_set (STB_GLOBAL)
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
