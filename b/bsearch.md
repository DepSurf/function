# Function: <code>bsearch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff813fde10)
Location: lib/bsearch.c:33
Inline: False
Direct callers:
  - kernel/module.c:find_symbol_in_section
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/trace/ftrace.c:ftrace_location_range
  - kernel/trace/trace_events.c:check_ignore_pid
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
```
**Symbols:**

```
ffffffff813fde10-ffffffff813fde9d: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff81445480)
Location: lib/bsearch.c:33
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_symbol_in_section
  - kernel/trace/ftrace.c:ftrace_location_range
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
```
**Symbols:**

```
ffffffff81445480-ffffffff8144550d: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff81463c70)
Location: lib/bsearch.c:33
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_symbol_in_section
  - kernel/trace/ftrace.c:ftrace_location_range
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
```
**Symbols:**

```
ffffffff81463c70-ffffffff81463cfd: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff81468d20)
Location: lib/bsearch.c:33
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_symbol_in_section
  - kernel/trace/ftrace.c:ftrace_free_init_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffff81468d20-ffffffff81468d9f: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff81494fd0)
Location: lib/bsearch.c:33
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffff81494fd0-ffffffff81495052: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff814ca300)
Location: lib/bsearch.c:33
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - kernel/bpf/verifier.c:find_subprog
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffff814ca300-ffffffff814ca381: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff814df020)
Location: lib/bsearch.c:33
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - kernel/bpf/verifier.c:find_subprog
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffff814df020-ffffffff814df0a1: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff8150aed0)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - kernel/bpf/verifier.c:find_subprog
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffff8150aed0-ffffffff8150af56: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff81528cf0)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - kernel/bpf/verifier.c:find_subprog
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffff81528cf0-ffffffff81528d76: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff8158c5c0)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:lookup_rec
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_max_stack_depth
  - lib/extable.c:search_extable
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw
  - drivers/base/regmap/regcache.c:regcache_sync_block_single
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
```
**Symbols:**

```
ffffffff8158c5c0-ffffffff8158c646: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff815a9030)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:lookup_rec
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_max_stack_depth
  - kernel/bpf/btf.c:btf_id_set_contains
  - lib/extable.c:search_extable
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw
  - drivers/base/regmap/regcache.c:regcache_sync_block_single
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
```
**Symbols:**

```
ffffffff815a9030-ffffffff815a90b6: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff815b3c70)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:lookup_rec
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_max_stack_depth
  - kernel/bpf/verifier.c:bpf_jit_find_kfunc_model
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/btf.c:btf_id_set_contains
  - lib/extable.c:search_extable
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
```
**Symbols:**

```
ffffffff815b3c70-ffffffff815b3cf6: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff81619e60)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:lookup_rec
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_max_stack_depth
  - kernel/bpf/verifier.c:bpf_jit_find_kfunc_model
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/btf.c:btf_id_set_contains
  - lib/extable.c:search_extable
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
```
**Symbols:**

```
ffffffff81619e60-ffffffff81619ee6: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff816e7330)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - kernel/module/main.c:find_exported_symbol_in_section
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:kallsyms_callback
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:lookup_rec
  - kernel/trace/bpf_trace.c:bpf_get_attach_cookie_kprobe_multi
  - kernel/bpf/syscall.c:bpf_map_kptr_off_contains
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_max_stack_depth
  - kernel/bpf/verifier.c:bpf_jit_find_kfunc_model
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
  - kernel/bpf/btf.c:btf_parse_kptrs
  - lib/extable.c:search_extable
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/base/regmap/regcache.c:regcache_reg_needs_sync
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
```
**Symbols:**

```
ffffffff816e7330-ffffffff816e73bd: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff817d6bc0)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - kernel/module/main.c:find_exported_symbol_in_section
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:kallsyms_callback
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:lookup_rec
  - kernel/trace/bpf_trace.c:module_callback
  - kernel/trace/bpf_trace.c:bpf_get_attach_cookie_kprobe_multi
  - kernel/bpf/syscall.c:btf_record_find
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_max_stack_depth
  - kernel/bpf/verifier.c:bpf_jit_find_kfunc_model
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/btf.c:btf_kfunc_is_modify_return
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_check_and_fixup_fields
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/bpf_lsm.c:bpf_lsm_is_trusted
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
  - kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog
  - kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffff817d6bc0-ffffffff817d6c4d: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff81815bd0)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_numa_find_nth_cpu
  - kernel/module/main.c:find_exported_symbol_in_section
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:kallsyms_callback
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:lookup_rec
  - kernel/trace/bpf_trace.c:bpf_get_attach_cookie_kprobe_multi
  - kernel/bpf/syscall.c:btf_record_find
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:fixup_kfunc_call
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_max_stack_depth_subprog
  - kernel/bpf/verifier.c:backtrack_insn
  - kernel/bpf/verifier.c:bpf_jit_find_kfunc_model
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/verifier.c:bpf_get_kfunc_addr
  - kernel/bpf/btf.c:__btf_kfunc_id_set_contains
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_check_and_fixup_fields
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/bpf_lsm.c:bpf_lsm_is_trusted
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
  - kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog
  - kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/base/regmap/regcache.c:regcache_reg_needs_sync
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
  - net/core/filter.c:tracing_iter_filter
  - net/core/xdp.c:bpf_dev_bound_kfunc_id
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffff81815bd0-ffffffff81815c5d: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, cmp_func_t cmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff8185ad10)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sched_numa_find_nth_cpu
  - kernel/module/main.c:find_exported_symbol_in_section
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:kallsyms_callback
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:lookup_rec
  - kernel/trace/bpf_trace.c:bpf_get_file_xattr_filter
  - kernel/trace/bpf_trace.c:bpf_get_attach_cookie_kprobe_multi
  - kernel/bpf/syscall.c:btf_record_find
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:fixup_kfunc_call
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_max_stack_depth_subprog
  - kernel/bpf/verifier.c:backtrack_insn
  - kernel/bpf/verifier.c:bpf_jit_find_kfunc_model
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/verifier.c:bpf_get_kfunc_addr
  - kernel/bpf/btf.c:__btf_kfunc_id_set_contains
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_check_and_fixup_fields
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/bpf_lsm.c:bpf_lsm_is_trusted
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
  - kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog
  - kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim
  - fs/verity/measure.c:bpf_get_fsverity_digest_filter
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/base/regmap/regcache.c:regcache_reg_needs_sync
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
  - net/core/filter.c:tracing_iter_filter
  - net/core/xdp.c:bpf_dev_bound_kfunc_id
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffff8185ad10-ffffffff8185ad9d: bsearch (STB_GLOBAL)
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
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffff800010633658)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - arch/arm64/kernel/cpufeature.c:do_emulate_mrs
  - arch/arm64/kernel/cpufeature.c:init_cpu_ftr_reg
  - virt/kvm/kvm_main.c:kvm_io_bus_get_first_dev
  - arch/arm64/kvm/sys_regs.c:find_reg
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_get_mmio_region
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - kernel/bpf/verifier.c:find_subprog
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffff800010633658-ffff800010633700: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (c07d9ac4)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - kernel/bpf/verifier.c:find_subprog
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
  - lib/extable.c:search_extable
```
**Symbols:**

```
c07d9ac4-c07d9b34: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (c0000000007d8930)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - kernel/bpf/verifier.c:find_subprog
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - lib/extable.c:search_extable
```
**Symbols:**

```
c0000000007d8930-c0000000007d8a40: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffe000461670)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - kernel/bpf/verifier.c:find_subprog
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffe000461670-ffffffe0004616d2: bsearch (STB_GLOBAL)
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
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff815212d0)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - kernel/bpf/verifier.c:find_subprog
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffff815212d0-ffffffff81521356: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff815115c0)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - kernel/bpf/verifier.c:find_subprog
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffff815115c0-ffffffff81511646: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff8151d360)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - kernel/bpf/verifier.c:find_subprog
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffff8151d360-ffffffff8151d3e6: bsearch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *bsearch(const void *key, const void *base, size_t num, size_t size, int (*cmp)(const void *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bsearch.c (ffffffff81536bd0)
Location: lib/bsearch.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_exported_symbol_in_section
  - kernel/user_namespace.c:map_id_up
  - kernel/user_namespace.c:map_id_range_down
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_location_range
  - kernel/bpf/verifier.c:find_subprog
  - drivers/base/regmap/regcache.c:regcache_lookup_reg
  - drivers/firmware/efi/efi.c:efi_status_to_str
  - drivers/firmware/efi/efi.c:efi_status_to_err
  - lib/extable.c:search_extable
```
**Symbols:**

```
ffffffff81536bd0-ffffffff81536c56: bsearch (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*cmp)(const void *, const void *)</code> ➡️ <code>cmp_func_t cmp</code>
</li>
</ul>
</details>
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
