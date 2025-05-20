# Function: <code>bpf_capable</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa1ca)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff81201535)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_freeze
```
```
In kernel/bpf/verifier.c (ffffffff8121307e)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff81214fc2)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/hashtab.c (ffffffff812171f0)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff8121c0d5)
Location: include/linux/capability.h:259
Inline: True
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff8121de15)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
```
```
In kernel/bpf/cpumap.c (ffffffff81227b35)
Location: include/linux/capability.h:259
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff8122af30)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff8122efb5)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8122fda5)
Location: include/linux/capability.h:259
Inline: True
```
```
In net/core/filter.c (ffffffff81a2c5e8)
Location: include/linux/capability.h:259
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81a60eda)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc_check
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
In kernel/bpf/core.c (ffffffff811f91fa)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff81200e22)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_freeze
```
```
In kernel/bpf/verifier.c (ffffffff8121485e)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff81216bbc)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/hashtab.c (ffffffff812194b3)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff8121f025)
Location: include/linux/capability.h:259
Inline: True
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff81220bb5)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
```
```
In kernel/bpf/cpumap.c (ffffffff8122ea12)
Location: include/linux/capability.h:259
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8123034a)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc_check
```
```
In kernel/bpf/stackmap.c (ffffffff81232e58)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff8123751a)
Location: include/linux/capability.h:259
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81238255)
Location: include/linux/capability.h:259
Inline: True
```
```
In net/core/filter.c (ffffffff81a2db28)
Location: include/linux/capability.h:259
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69985)
Location: include/linux/capability.h:259
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
In kernel/bpf/core.c (ffffffff811f9fe6)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff81201744)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff812170b9)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff8121a034)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/hashtab.c (ffffffff8121ceb3)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff81222ab5)
Location: include/linux/capability.h:262
Inline: True
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff81224645)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122592a)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc_check
```
```
In kernel/bpf/cpumap.c (ffffffff81233866)
Location: include/linux/capability.h:262
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81237008)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff8123bd3a)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123c8b5)
Location: include/linux/capability.h:262
Inline: True
```
```
In net/core/filter.c (ffffffff81a155f8)
Location: include/linux/capability.h:262
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81a52125)
Location: include/linux/capability.h:262
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
In kernel/bpf/core.c (ffffffff8122bb93)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff812336c3)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff8124d896)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff81250ce4)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/hashtab.c (ffffffff81253e83)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff8125a865)
Location: include/linux/capability.h:262
Inline: True
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff8125c585)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d92a)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc_check
```
```
In kernel/bpf/cpumap.c (ffffffff8126d526)
Location: include/linux/capability.h:262
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff812715ec)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff812766ca)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81277305)
Location: include/linux/capability.h:262
Inline: True
```
```
In net/core/filter.c (ffffffff81ac69d8)
Location: include/linux/capability.h:262
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0adb5)
Location: include/linux/capability.h:262
Inline: True
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
In kernel/bpf/core.c (ffffffff8126d6b2)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff81276a57)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_check_btf
```
```
In kernel/bpf/verifier.c (ffffffff81294808)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff81298727)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/hashtab.c (ffffffff8129c387)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff812a3985)
Location: include/linux/capability.h:262
Inline: True
```
```
In kernel/bpf/bloom_filter.c (ffffffff812a48c7)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff812a6265)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7c5e)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc_check
```
```
In kernel/bpf/cpumap.c (ffffffff812bc685)
Location: include/linux/capability.h:262
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff812c075d)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff812c6139)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c6e95)
Location: include/linux/capability.h:262
Inline: True
```
```
In net/core/filter.c (ffffffff81c42200)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - net/core/filter.c:cg_skb_is_valid_access
  - net/core/filter.c:cg_skb_is_valid_access
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91435)
Location: include/linux/capability.h:262
Inline: True
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
In kernel/bpf/core.c (ffffffff812c2a67)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/syscall.c (ffffffff812ccbf7)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_check_btf
```
```
In kernel/bpf/verifier.c (ffffffff812ef3c0)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff812f3800)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In kernel/bpf/hashtab.c (ffffffff812f85c7)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff81301575)
Location: include/linux/capability.h:262
Inline: True
```
```
In kernel/bpf/bloom_filter.c (ffffffff81302607)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff81304005)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813061fe)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc_check
```
```
In kernel/bpf/cpumap.c (ffffffff8131f7a5)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff81323fed)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/reuseport_array.c (ffffffff8132b889)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132c705)
Location: include/linux/capability.h:262
Inline: True
```
```
In net/core/filter.c (ffffffff81df7650)
Location: include/linux/capability.h:262
Inline: True
Inline callers:
  - net/core/filter.c:cg_skb_is_valid_access
  - net/core/filter.c:cg_skb_is_valid_access
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4c995)
Location: include/linux/capability.h:262
Inline: True
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
In kernel/bpf/core.c (ffffffff812e9957)
Location: include/linux/capability.h:200
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/syscall.c (ffffffff812f4a5b)
Location: include/linux/capability.h:200
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_check_btf
```
```
In kernel/bpf/verifier.c (ffffffff8131bdb0)
Location: include/linux/capability.h:200
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff813206d3)
Location: include/linux/capability.h:200
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In net/core/filter.c (ffffffff81e69169)
Location: include/linux/capability.h:200
Inline: True
Inline callers:
  - net/core/filter.c:cg_skb_is_valid_access
  - net/core/filter.c:cg_skb_is_valid_access
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea80b5)
Location: include/linux/capability.h:200
Inline: True
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
In kernel/bpf/core.c (ffffffff81307ba7)
Location: include/linux/capability.h:200
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_charge_modmem
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/syscall.c (ffffffff81313bf1)
Location: include/linux/capability.h:200
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_check_btf
```
```
In kernel/bpf/verifier.c (ffffffff8133e14b)
Location: include/linux/capability.h:200
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/helpers.c (ffffffff81342bd3)
Location: include/linux/capability.h:200
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_base_func_proto
```
```
In net/core/filter.c (ffffffff81f28749)
Location: include/linux/capability.h:200
Inline: True
Inline callers:
  - net/core/filter.c:cg_skb_is_valid_access
  - net/core/filter.c:cg_skb_is_valid_access
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6ab75)
Location: include/linux/capability.h:200
Inline: True
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
