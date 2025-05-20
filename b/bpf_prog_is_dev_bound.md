# Function: <code>bpf_prog_is_dev_bound</code>

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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/bpf.h:543
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:543
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bpf.h:543
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/bpf.h:656
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:656
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:656
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/bpf.h:656
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bpf.h:656
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/bpf.h:656
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/bpf.h:739
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:739
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:739
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/bpf.h:739
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bpf.h:739
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/bpf.h:739
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/bpf.h:917
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:917
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:917
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/bpf.h:917
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bpf.h:917
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/bpf.h:917
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811faf02)
Location: include/linux/bpf.h:1506
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/syscall.c (ffffffff81200281)
Location: include/linux/bpf.h:1506
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_get
```
```
In kernel/bpf/verifier.c (ffffffff812131a1)
Location: include/linux/bpf.h:1506
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:opt_hard_wire_dead_code_branches
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/offload.c (ffffffff81229079)
Location: include/linux/bpf.h:1506
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_match
```
```
In net/core/dev.c (ffffffff81a0c7bb)
Location: include/linux/bpf.h:1506
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
```
```
In net/core/filter.c (ffffffff81a2be68)
Location: include/linux/bpf.h:1506
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9863)
Location: include/linux/bpf.h:1728
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/syscall.c (ffffffff811ff6ee)
Location: include/linux/bpf.h:1728
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_get
```
```
In kernel/bpf/verifier.c (ffffffff81214987)
Location: include/linux/bpf.h:1728
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:opt_hard_wire_dead_code_branches
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/offload.c (ffffffff81230b19)
Location: include/linux/bpf.h:1728
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_match
```
```
In net/core/dev.c (ffffffff81a006bd)
Location: include/linux/bpf.h:1728
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/filter.c (ffffffff81a2d248)
Location: include/linux/bpf.h:1728
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa763)
Location: include/linux/bpf.h:1818
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/syscall.c (ffffffff81200099)
Location: include/linux/bpf.h:1818
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_get
```
```
In kernel/bpf/verifier.c (ffffffff81217795)
Location: include/linux/bpf.h:1818
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/offload.c (ffffffff81234cc9)
Location: include/linux/bpf.h:1818
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_match
```
```
In net/core/dev.c (ffffffff819e6b12)
Location: include/linux/bpf.h:1818
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/filter.c (ffffffff81a14719)
Location: include/linux/bpf.h:1818
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122be73)
Location: include/linux/bpf.h:1944
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/syscall.c (ffffffff81231d8c)
Location: include/linux/bpf.h:1944
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_get
```
```
In kernel/bpf/verifier.c (ffffffff8124dd26)
Location: include/linux/bpf.h:1944
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/offload.c (ffffffff8126edd5)
Location: include/linux/bpf.h:1944
Inline: True
```
```
In net/core/dev.c (ffffffff81a9b3f6)
Location: include/linux/bpf.h:1944
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/filter.c (ffffffff81ac6292)
Location: include/linux/bpf.h:1944
Inline: True
Inline callers:
  - net/core/filter.c:xdp_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126d9ea)
Location: include/linux/bpf.h:2083
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/syscall.c (ffffffff8127507c)
Location: include/linux/bpf.h:2083
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_get
```
```
In kernel/bpf/verifier.c (ffffffff81294e91)
Location: include/linux/bpf.h:2083
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:opt_hard_wire_dead_code_branches
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/offload.c (ffffffff812bddf5)
Location: include/linux/bpf.h:2083
Inline: True
```
```
In net/core/dev.c (ffffffff81c14abe)
Location: include/linux/bpf.h:2083
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/filter.c (ffffffff81c41c10)
Location: include/linux/bpf.h:2083
Inline: True
Inline callers:
  - net/core/filter.c:xdp_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c2e29)
Location: include/linux/bpf.h:2491
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/syscall.c (ffffffff812c8204)
Location: include/linux/bpf.h:2491
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_get
```
```
In kernel/bpf/verifier.c (ffffffff812efccd)
Location: include/linux/bpf.h:2491
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:opt_hard_wire_dead_code_branches
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/offload.c (ffffffff81321355)
Location: include/linux/bpf.h:2491
Inline: True
```
```
In net/core/dev.c (ffffffff81dc5bfe)
Location: include/linux/bpf.h:2491
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/filter.c (ffffffff81df73b0)
Location: include/linux/bpf.h:2491
Inline: True
Inline callers:
  - net/core/filter.c:xdp_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e9d1c)
Location: include/linux/bpf.h:2672
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_map_compatible
```
```
In kernel/bpf/syscall.c (ffffffff812f1ed2)
Location: include/linux/bpf.h:2672
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff8131b13c)
Location: include/linux/bpf.h:2672
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
```
In kernel/bpf/offload.c (ffffffff81352e05)
Location: include/linux/bpf.h:2672
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_dev_bound_kfunc_check
  - kernel/bpf/offload.c:bpf_prog_dev_bound_inherit
```
```
In net/core/dev.c (ffffffff81e35071)
Location: include/linux/bpf.h:2672
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/bpf/test_run.c (ffffffff81ecf829)
Location: include/linux/bpf.h:2672
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In kernel/bpf/core.c (ffffffff81308da6)
Location: include/linux/bpf.h:2843
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_map_compatible
```
```
In kernel/bpf/syscall.c (ffffffff81310d43)
Location: include/linux/bpf.h:2843
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff8133d39c)
Location: include/linux/bpf.h:2843
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
```
In kernel/bpf/offload.c (ffffffff8137a2e5)
Location: include/linux/bpf.h:2843
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_dev_bound_kfunc_check
  - kernel/bpf/offload.c:bpf_prog_dev_bound_inherit
```
```
In net/core/dev.c (ffffffff81ef310e)
Location: include/linux/bpf.h:2843
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/bpf/test_run.c (ffffffff81f93179)
Location: include/linux/bpf.h:2843
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0492b80)
Location: include/linux/bpf.h:919
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/syscall.c (c0494368)
Location: include/linux/bpf.h:919
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_get
```
```
In kernel/bpf/verifier.c (c04a6928)
Location: include/linux/bpf.h:919
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/offload.c (c04b95cc)
Location: include/linux/bpf.h:919
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_match
```
```
In net/core/dev.c (c0cf11fc)
Location: include/linux/bpf.h:919
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
```
```
In net/core/filter.c (c0d150a0)
Location: include/linux/bpf.h:919
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/bpf.h:919
Inline: True
```
</details>
</li>
</ul>

## Differences
