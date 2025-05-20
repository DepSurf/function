# Function: <code>memory_contains</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (0)
Location: include/asm-generic/sections.h:87
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
In kernel/printk/printk.c (ffffffff826f6822)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/jump_label.c (ffffffff8270024d)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_invalidate_initmem
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
In kernel/printk/printk.c (ffffffff828ad75c)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/jump_label.c (ffffffff828b7264)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffffffff828c6112)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/jump_label.c (ffffffff828d083d)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffffffff828ce757)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/jump_label.c (ffffffff828d8cb7)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffffffff82cefbab)
Location: include/asm-generic/sections.h:108
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/jump_label.c (ffffffff82cf8554)
Location: include/asm-generic/sections.h:108
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffffffff82fdc3fc)
Location: include/asm-generic/sections.h:108
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/debug/debug_core.c (ffffffff8119651a)
Location: include/asm-generic/sections.h:108
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_free_init_mem
```
```
In kernel/static_call.c (ffffffff81239c76)
Location: include/asm-generic/sections.h:108
Inline: True
```
```
In kernel/jump_label.c (ffffffff82fe524d)
Location: include/asm-generic/sections.h:108
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffffffff831e715c)
Location: include/asm-generic/sections.h:108
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/debug/debug_core.c (ffffffff811974ca)
Location: include/asm-generic/sections.h:108
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_free_init_mem
```
```
In kernel/static_call.c (ffffffff8123e3b0)
Location: include/asm-generic/sections.h:108
Inline: True
```
```
In kernel/jump_label.c (ffffffff831ef978)
Location: include/asm-generic/sections.h:108
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffffffff832cb2ed)
Location: include/asm-generic/sections.h:108
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/debug/debug_core.c (ffffffff811c1138)
Location: include/asm-generic/sections.h:108
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_free_init_mem
```
```
In kernel/static_call.c (ffffffff81278e90)
Location: include/asm-generic/sections.h:108
Inline: True
```
```
In kernel/jump_label.c (ffffffff832d50c5)
Location: include/asm-generic/sections.h:108
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffffffff8347e98d)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/debug/debug_core.c (ffffffff811f4708)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_free_init_mem
```
```
In kernel/static_call_inline.c (ffffffff812cbcea)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/static_call_inline.c:__static_call_init
```
```
In kernel/jump_label.c (ffffffff834897d5)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffffffff83eaa750)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/debug/debug_core.c (ffffffff8123b638)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_free_init_mem
```
```
In kernel/static_call_inline.c (ffffffff8133368a)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/static_call_inline.c:__static_call_init
```
```
In kernel/jump_label.c (ffffffff83eb9eca)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffffffff836cf710)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/debug/debug_core.c (ffffffff81252648)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_free_init_mem
```
```
In kernel/static_call_inline.c (ffffffff81364385)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/static_call_inline.c:__static_call_init
```
```
In kernel/jump_label.c (ffffffff836df51a)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffffffff83900b20)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/debug/debug_core.c (ffffffff8126c498)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_free_init_mem
```
```
In kernel/static_call_inline.c (ffffffff8138d2ba)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/static_call_inline.c:__static_call_init
```
```
In kernel/jump_label.c (ffffffff83911b5a)
Location: include/asm-generic/sections.h:91
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffff800011445f94)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/jump_label.c (ffff80001145184c)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In arch/arm/kernel/stacktrace.c (c030ee34)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - arch/arm/kernel/stacktrace.c:save_trace
```
```
In arch/arm/kernel/traps.c (c03101e0)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:dump_backtrace_entry
```
```
In arch/arm/probes/kprobes/core.c (c0328148)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/core.c:arch_within_kprobe_blacklist
  - arch/arm/probes/kprobes/core.c:arch_within_kprobe_blacklist
  - arch/arm/probes/kprobes/core.c:arch_within_kprobe_blacklist
  - arch/arm/probes/kprobes/core.c:arch_within_kprobe_blacklist
```
```
In kernel/printk/printk.c (c15205ec)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
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
In arch/powerpc/lib/code-patching.c (c0000000000a6ebc)
Location: include/asm-generic/sections.h:105
Inline: True
```
```
In kernel/printk/printk.c (c00000000136abe4)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/jump_label.c (c0000000013793d8)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe000007b8c)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
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
In kernel/printk/printk.c (ffffffff828b744f)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/jump_label.c (ffffffff828c1b68)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffffffff828af6da)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/jump_label.c (ffffffff828ba208)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffffffff828ca38b)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/jump_label.c (ffffffff828d48eb)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
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
In kernel/printk/printk.c (ffffffff828cf73d)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/jump_label.c (ffffffff828d9d0c)
Location: include/asm-generic/sections.h:105
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_init
```
</details>
</li>
</ul>

## Differences
