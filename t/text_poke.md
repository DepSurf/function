# Function: <code>text_poke</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81036720)
Location: arch/x86/kernel/alternative.c:689
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
```
**Symbols:**

```
ffffffff81036720-ffffffff81036935: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035910)
Location: arch/x86/kernel/alternative.c:690
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
**Symbols:**

```
ffffffff81035910-ffffffff81035b40: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035640)
Location: arch/x86/kernel/alternative.c:695
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
**Symbols:**

```
ffffffff81035640-ffffffff8103586f: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81033600)
Location: arch/x86/kernel/alternative.c:700
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
**Symbols:**

```
ffffffff81033600-ffffffff8103380f: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035930)
Location: arch/x86/kernel/alternative.c:689
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
**Symbols:**

```
ffffffff81035930-ffffffff81035b6c: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810368a0)
Location: arch/x86/kernel/alternative.c:689
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
**Symbols:**

```
ffffffff810368a0-ffffffff81036ae6: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81037aa0)
Location: arch/x86/kernel/alternative.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
**Symbols:**

```
ffffffff81037aa0-ffffffff81037cf3: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103a3a2)
Location: arch/x86/kernel/alternative.c:908
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8103a330-ffffffff8103a340: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103ab82)
Location: arch/x86/kernel/alternative.c:908
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8103ab10-ffffffff8103ab20: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103d09a)
Location: arch/x86/kernel/alternative.c:963
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8103d930-ffffffff8103d940: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103d55d)
Location: arch/x86/kernel/alternative.c:975
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8103de20-ffffffff8103de30: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103ed96)
Location: arch/x86/kernel/alternative.c:896
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8103f840-ffffffff8103f850: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81044b06)
Location: arch/x86/kernel/alternative.c:896
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81045650-ffffffff81045660: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8104d179)
Location: arch/x86/kernel/alternative.c:1204
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8104df50-ffffffff8104df7c: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810595b4)
Location: arch/x86/kernel/alternative.c:1667
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8105ad50-ffffffff8105ad7c: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105ab5b)
Location: arch/x86/kernel/alternative.c:1892
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8105c290-ffffffff8105c2bc: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81061e1b)
Location: arch/x86/kernel/alternative.c:1982
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81063350-ffffffff8106337c: text_poke (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103ace2)
Location: arch/x86/kernel/alternative.c:908
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8103ac70-ffffffff8103ac80: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8102a4f2)
Location: arch/x86/kernel/alternative.c:908
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8102a480-ffffffff8102a490: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103ab42)
Location: arch/x86/kernel/alternative.c:908
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8103aad0-ffffffff8103aae0: text_poke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103bb42)
Location: arch/x86/kernel/alternative.c:908
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_disarm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_arm_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8103bad0-ffffffff8103bae0: text_poke (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
