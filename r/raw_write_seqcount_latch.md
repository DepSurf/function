# Function: <code>raw_write_seqcount_latch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f4b5d)
Location: include/linux/seqlock.h:360
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff8110529d)
Location: include/linux/seqlock.h:360
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fbd1d)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff8110cb7d)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fec1d)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff811145bd)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81034a0c)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In kernel/time/timekeeping.c (ffffffff81100efd)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff8111575d)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff8118f2bf)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036d6c)
Location: include/linux/seqlock.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In kernel/time/timekeeping.c (ffffffff8110bd0d)
Location: include/linux/seqlock.h:364
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff81120d0d)
Location: include/linux/seqlock.h:364
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff8119d72f)
Location: include/linux/seqlock.h:364
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In arch/x86/kernel/tsc.c (ffffffff81037e10)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In kernel/time/timekeeping.c (ffffffff811178ba)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff8112e635)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811b1cf8)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In arch/x86/kernel/tsc.c (ffffffff81038f0a)
Location: include/linux/seqlock.h:363
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff81122eda)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff81139f35)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811c05a8)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In arch/x86/kernel/tsc.c (ffffffff8103b374)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/time/timekeeping.c (ffffffff8112d6ba)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff81145665)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d10b2)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In arch/x86/kernel/tsc.c (ffffffff8103bb24)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/time/timekeeping.c (ffffffff8113962a)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff81151175)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811dd642)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In arch/x86/kernel/tsc.c (ffffffff8103e872)
Location: include/linux/seqlock.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/time/timekeeping.c (ffffffff811482da)
Location: include/linux/seqlock.h:394
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff81166f36)
Location: include/linux/seqlock.h:394
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811fa0bc)
Location: include/linux/seqlock.h:394
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In mm/swap.c (ffffffff8126062c)
Location: include/linux/seqlock.h:394
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
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
In arch/x86/kernel/tsc.c (ffffffff8103e922)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/time/timekeeping.c (ffffffff8114471a)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff811635e6)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f90ec)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In arch/x86/kernel/tsc.c (ffffffff810402f4)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/printk/printk.c (ffffffff81119848)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
```
```
In kernel/time/timekeeping.c (ffffffff8114589a)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff811641ae)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811f9ecc)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In arch/x86/kernel/tsc.c (ffffffff810466c8)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/printk/printk.c (ffffffff81139aa1)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
```
```
In kernel/time/timekeeping.c (ffffffff81168f3a)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff811898bc)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff8122b59c)
Location: include/linux/seqlock.h:783
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In arch/x86/kernel/tsc.c (ffffffff8104f67e)
Location: include/linux/seqlock.h:779
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/printk/printk.c (ffffffff8115e17d)
Location: include/linux/seqlock.h:779
Inline: True
Inline callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
```
```
In kernel/module/tree_lookup.c (ffffffff81190dd5)
Location: include/linux/seqlock.h:779
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
```
```
In kernel/time/timekeeping.c (ffffffff8119cb2a)
Location: include/linux/seqlock.h:779
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/bpf/core.c (ffffffff8126cffc)
Location: include/linux/seqlock.h:779
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In arch/x86/kernel/tsc.c (ffffffff8105c80e)
Location: include/linux/seqlock.h:779
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/printk/printk.c (ffffffff8119106d)
Location: include/linux/seqlock.h:779
Inline: True
Inline callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
```
```
In kernel/module/tree_lookup.c (ffffffff811ce3c5)
Location: include/linux/seqlock.h:779
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
```
```
In kernel/time/timekeeping.c (ffffffff811db5fa)
Location: include/linux/seqlock.h:779
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/bpf/core.c (ffffffff812c213c)
Location: include/linux/seqlock.h:779
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In arch/x86/kernel/tsc.c (ffffffff8105d3fe)
Location: include/linux/seqlock.h:780
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/printk/printk.c (ffffffff811a2a3e)
Location: include/linux/seqlock.h:780
Inline: True
Inline callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
```
```
In kernel/module/tree_lookup.c (ffffffff811e257d)
Location: include/linux/seqlock.h:780
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
```
```
In kernel/time/timekeeping.c (ffffffff811efb9a)
Location: include/linux/seqlock.h:780
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/bpf/core.c (ffffffff812e8ffc)
Location: include/linux/seqlock.h:780
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In arch/x86/kernel/tsc.c (ffffffff810644be)
Location: include/linux/seqlock.h:734
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/printk/printk.c (ffffffff811b08fe)
Location: include/linux/seqlock.h:734
Inline: True
Inline callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
```
```
In kernel/module/tree_lookup.c (ffffffff811f830d)
Location: include/linux/seqlock.h:734
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
```
```
In kernel/time/timekeeping.c (ffffffff81205cda)
Location: include/linux/seqlock.h:734
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/bpf/core.c (ffffffff8130736c)
Location: include/linux/seqlock.h:734
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
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
In kernel/time/timekeeping.c (ffff8000101a33f0)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/time/sched_clock.c (ffff8000101b4378)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:update_clock_read_data
  - kernel/time/sched_clock.c:update_clock_read_data
```
```
In kernel/module.c (ffff8000101c0054)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffff80001025e240)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/time/timekeeping.c (c03ed4cc)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/time/sched_clock.c (c03fdf14)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:update_clock_read_data
  - kernel/time/sched_clock.c:update_clock_read_data
```
```
In kernel/module.c (c0407770)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (c04918dc)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/time/timekeeping.c (c000000000204cac)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (c000000000225cb8)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (c000000000302f14)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In kernel/time/timekeeping.c (ffffffe000130018)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/time/sched_clock.c (ffffffe00013a774)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:update_clock_read_data
  - kernel/time/sched_clock.c:update_clock_read_data
```
```
In kernel/module.c (ffffffe000142464)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffe00019c6e4)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In arch/x86/kernel/tsc.c (ffffffff8103bc84)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/time/timekeeping.c (ffffffff81131dda)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff81149795)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d5c62)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In arch/x86/kernel/tsc.c (ffffffff8102b404)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/time/timekeeping.c (ffffffff8112483a)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff8113ca45)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811c8a22)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In arch/x86/kernel/tsc.c (ffffffff8103bae4)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/time/timekeeping.c (ffffffff8112fafa)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff81147645)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811d3a32)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
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
In arch/x86/kernel/tsc.c (ffffffff8103cba8)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In kernel/time/timekeeping.c (ffffffff8113c51a)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_fast_timekeeper
  - kernel/time/timekeeping.c:update_fast_timekeeper
```
```
In kernel/module.c (ffffffff81154255)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
```
```
In kernel/bpf/core.c (ffffffff811e1d22)
Location: include/linux/seqlock.h:363
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
</details>
</li>
</ul>

## Differences
