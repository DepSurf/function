# Function: <code>module_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81060990)
Location: arch/x86/kernel/module.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffff81060990-ffffffff81060a59: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810607a0)
Location: arch/x86/kernel/module.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffff810607a0-ffffffff81060869: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81063840)
Location: arch/x86/kernel/module.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffff81063840-ffffffff81063909: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810627b0)
Location: arch/x86/kernel/module.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffff810627b0-ffffffff81062864: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810668e0)
Location: arch/x86/kernel/module.c:80
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffff810668e0-ffffffff810669a7: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81069490)
Location: arch/x86/kernel/module.c:80
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffff81069490-ffffffff81069560: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8106f1e0)
Location: arch/x86/kernel/module.c:80
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffffffff8106f1e0-ffffffff8106f2b0: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810732c0)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffffffff810732c0-ffffffff81073393: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81074280)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffffffff81074280-ffffffff81074353: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8107b5a0)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module.c:move_module
  - kernel/module.c:move_module
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffffffff8107b5a0-ffffffff8107b673: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8107b500)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module.c:move_module
  - kernel/module.c:move_module
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffffffff8107b500-ffffffff8107b5d3: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8107c720)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module.c:move_module
  - kernel/module.c:move_module
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffffffff8107c720-ffffffff8107c7f3: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8108a840)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module.c:move_module
  - kernel/module.c:move_module
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffffffff8108a840-ffffffff8108a913: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8109add0)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module/main.c:move_module
  - kernel/module/main.c:move_module
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
```
**Symbols:**

```
ffffffff8109add0-ffffffff8109aec7: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810b1870)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module/main.c:move_module
  - kernel/module/main.c:move_module
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
```
**Symbols:**

```
ffffffff810b1870-ffffffff810b196a: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810b48b0)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module/main.c:move_module
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
```
**Symbols:**

```
ffffffff810b48b0-ffffffff810b49aa: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810bbd10)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module/main.c:move_module
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffffffff810bbd10-ffffffff810bbe0a: module_alloc (STB_GLOBAL)
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
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/module.c (ffff8000100a1ed8)
Location: arch/arm64/kernel/module.c:22
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffff8000100a1ed8-ffff8000100a20d0: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/module.c (c03107cc)
Location: arch/arm/kernel/module.c:38
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
c03107cc-c031082c: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000229fd0)
Location: kernel/module.c:2809
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
c000000000229fd0-c00000000022a004: module_alloc (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/module.c (ffffffe0000b8992)
Location: arch/riscv/kernel/module.c:397
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffffffe0000b8992-ffffffe0000b89f0: module_alloc (STB_GLOBAL)
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
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81073280)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffffffff81073280-ffffffff81073353: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81063300)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffffffff81063300-ffffffff810633d3: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81073230)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffffffff81073230-ffffffff81073303: module_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *module_alloc(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81075290)
Location: arch/x86/kernel/module.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/kprobes.c:alloc_insn_page
  - kernel/bpf/core.c:bpf_jit_alloc_exec
```
**Symbols:**

```
ffffffff81075290-ffffffff81075363: module_alloc (STB_GLOBAL)
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
