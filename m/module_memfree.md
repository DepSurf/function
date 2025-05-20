# Function: <code>module_memfree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81107560)
Location: kernel/module.c:1972
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - kernel/module.c:do_free_init
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_binary_free
```
**Symbols:**

```
ffffffff81107560-ffffffff81107570: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110ea30)
Location: kernel/module.c:2072
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_binary_free
```
**Symbols:**

```
ffffffff8110ea30-ffffffff8110ea40: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81116350)
Location: kernel/module.c:2084
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_binary_free
```
**Symbols:**

```
ffffffff81116350-ffffffff81116360: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81117810)
Location: kernel/module.c:2111
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff81117810-ffffffff81117820: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81122df0)
Location: kernel/module.c:2119
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff81122df0-ffffffff81122e00: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81130e90)
Location: kernel/module.c:2118
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff81130e90-ffffffff81130ea0: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113c740)
Location: kernel/module.c:2117
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffffffff8113c740-ffffffff8113c750: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2114
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffffffff8114b1b2-ffffffff8114b1c5: module_memfree.cold (STB_LOCAL)
ffffffff81147e00-ffffffff81147e2c: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81153c40)
Location: kernel/module.c:2171
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffffffff81153c40-ffffffff81153c67: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81165670)
Location: kernel/module.c:2163
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:move_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffffffff81165670-ffffffff81165697: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81161de0)
Location: kernel/module.c:2225
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:move_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffffffff81161de0-ffffffff81161e07: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81162870)
Location: kernel/module.c:2135
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:move_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffffffff81162870-ffffffff81162897: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81187de0)
Location: kernel/module.c:2137
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:create_trampoline
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:move_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_optinsn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffffffff81187de0-ffffffff81187e07: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8118df20)
Location: kernel/module/main.c:1124
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:create_trampoline
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_free_init
  - kernel/module/main.c:move_module
  - kernel/module/main.c:free_module
  - kernel/module/main.c:free_module
  - kernel/kprobes.c:free_optinsn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
```
**Symbols:**

```
ffffffff8118df20-ffffffff8118df57: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811caaf0)
Location: kernel/module/main.c:1127
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:create_trampoline
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_free_init
  - kernel/module/main.c:move_module
  - kernel/module/main.c:free_module
  - kernel/module/main.c:free_module
  - kernel/kprobes.c:free_optinsn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
```
**Symbols:**

```
ffffffff811caaf0-ffffffff811cab27: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811dddb0)
Location: kernel/module/main.c:1182
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:create_trampoline
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_free_init
  - kernel/module/main.c:do_free_init
  - kernel/module/main.c:do_free_init
  - kernel/module/main.c:move_module
  - kernel/module/main.c:free_module
  - kernel/module/main.c:free_module
  - kernel/kprobes.c:free_optinsn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
```
**Symbols:**

```
ffffffff811dddb0-ffffffff811ddde7: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f3ab0)
Location: kernel/module/main.c:1182
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:create_trampoline
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_free_init
  - kernel/module/main.c:do_free_init
  - kernel/module/main.c:do_free_init
  - kernel/module/main.c:move_module
  - kernel/module/main.c:free_module
  - kernel/module/main.c:free_module
  - kernel/kprobes.c:free_optinsn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffffffff811f3ab0-ffffffff811f3ae7: module_memfree (STB_WEAK)
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
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c3018)
Location: kernel/module.c:2171
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffff8000101c3018-ffff8000101c306c: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040a204)
Location: kernel/module.c:2171
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
c040a204-c040a268: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0000000002295c0)
Location: kernel/module.c:2171
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
c0000000002295c0-c000000000229610: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000143fd4)
Location: kernel/module.c:2171
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffffffe000143fd4-ffffffe000144026: module_memfree (STB_WEAK)
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
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114c260)
Location: kernel/module.c:2171
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffffffff8114c260-ffffffff8114c287: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113f510)
Location: kernel/module.c:2171
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffffffff8113f510-ffffffff8113f537: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114a110)
Location: kernel/module.c:2171
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffffffff8114a110-ffffffff8114a137: module_memfree (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void module_memfree(void *module_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81156df0)
Location: kernel/module.c:2171
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_free_init
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/kprobes.c:free_insn_page
  - kernel/bpf/core.c:bpf_jit_free_exec
```
**Symbols:**

```
ffffffff81156df0-ffffffff81156e17: module_memfree (STB_WEAK)
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
