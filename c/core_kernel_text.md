# Function: <code>core_kernel_text</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/extable.c (ffffffff8109e960)
Location: kernel/extable.c:69
Inline: True
Inline callers:
  - kernel/extable.c:__kernel_text_address
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:func_ptr_is_kernel_text
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
  - kernel/extable.c:__kernel_text_address
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:func_ptr_is_kernel_text
```
**Symbols:**

```
ffffffff8109e960-ffffffff8109e982: core_kernel_text.part.0 (STB_LOCAL)
ffffffff8109e9d0-ffffffff8109ea04: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/extable.c (ffffffff810a21c5)
Location: kernel/extable.c:69
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810a2010-ffffffff810a2033: core_kernel_text.part.0 (STB_LOCAL)
ffffffff810a2080-ffffffff810a20b4: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/extable.c (ffffffff810a7285)
Location: kernel/extable.c:69
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810a70d0-ffffffff810a70f3: core_kernel_text.part.0 (STB_LOCAL)
ffffffff810a7140-ffffffff810a7174: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810a4235)
Location: kernel/extable.c:73
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
```
**Symbols:**

```
ffffffff810a4080-ffffffff810a40bf: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810aa855)
Location: kernel/extable.c:75
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
```
**Symbols:**

```
ffffffff810aa6b0-ffffffff810aa6ef: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810b14c5)
Location: kernel/extable.c:75
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
```
**Symbols:**

```
ffffffff810b1310-ffffffff810b1349: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810ba605)
Location: kernel/extable.c:75
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke
```
**Symbols:**

```
ffffffff810ba450-ffffffff810ba489: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c0515)
Location: kernel/extable.c:63
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
**Symbols:**

```
ffffffff810c0360-ffffffff810c0399: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c6915)
Location: kernel/extable.c:70
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
**Symbols:**

```
ffffffff810c6760-ffffffff810c6799: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810ce915)
Location: kernel/extable.c:73
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:__kernel_text_address
  - kernel/extable.c:__kernel_text_address
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
**Symbols:**

```
ffffffff810ce7e0-ffffffff810ce819: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c9435)
Location: kernel/extable.c:73
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:__kernel_text_address
  - kernel/extable.c:__kernel_text_address
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
**Symbols:**

```
ffffffff810c9300-ffffffff810c9339: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810caf45)
Location: kernel/extable.c:73
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
**Symbols:**

```
ffffffff810cad90-ffffffff810cadc9: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810de025)
Location: kernel/extable.c:73
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/module.c:symbol_put_addr
```
**Symbols:**

```
ffffffff810dde70-ffffffff810ddea9: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810f7c95)
Location: kernel/extable.c:66
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_set
  - arch/x86/kernel/alternative.c:text_poke_copy
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/module/main.c:symbol_put_addr
  - kernel/kprobes.c:check_kprobe_address_safe
```
**Symbols:**

```
ffffffff810f7a80-ffffffff810f7aed: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff8111a4e5)
Location: kernel/extable.c:66
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_set
  - arch/x86/kernel/alternative.c:text_poke_copy_locked
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/module/main.c:symbol_put_addr
  - kernel/kprobes.c:check_kprobe_address_safe
```
**Symbols:**

```
ffffffff8111a2a0-ffffffff8111a30d: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff81127755)
Location: kernel/extable.c:66
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_set
  - arch/x86/kernel/alternative.c:text_poke_copy_locked
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/module/main.c:symbol_put_addr
  - kernel/kprobes.c:check_kprobe_address_safe
```
**Symbols:**

```
ffffffff81127510-ffffffff8112757d: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff81131d35)
Location: kernel/extable.c:66
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_set
  - arch/x86/kernel/alternative.c:text_poke_copy_locked
  - arch/x86/kernel/alternative.c:__text_poke
  - kernel/module/main.c:symbol_put_addr
  - kernel/kprobes.c:check_kprobe_address_safe
```
**Symbols:**

```
ffffffff81131af0-ffffffff81131b5d: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffff800010125558)
Location: kernel/extable.c:70
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
Direct callers:
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
```
**Symbols:**

```
ffff8000101252d0-ffff800010125334: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (c037831c)
Location: kernel/extable.c:70
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
Direct callers:
  - arch/arm/kernel/patch.c:__patch_text_real
```
**Symbols:**

```
c03780b8-c0378130: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (c00000000016f3c0)
Location: kernel/extable.c:70
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
Direct callers:
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_modify_call
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_make_call
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_make_nop
  - kernel/module.c:symbol_put_addr
```
**Symbols:**

```
c00000000016f070-c00000000016f0e4: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffe0000dd23c)
Location: kernel/extable.c:70
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffe0000dd05a-ffffffe0000dd0b0: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c0c95)
Location: kernel/extable.c:70
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
**Symbols:**

```
ffffffff810c0ae0-ffffffff810c0b19: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810af485)
Location: kernel/extable.c:70
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
**Symbols:**

```
ffffffff810af2d0-ffffffff810af309: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c01e5)
Location: kernel/extable.c:70
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
**Symbols:**

```
ffffffff810c0030-ffffffff810c0069: core_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int core_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c8615)
Location: kernel/extable.c:70
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
**Symbols:**

```
ffffffff810c8460-ffffffff810c8499: core_kernel_text (STB_GLOBAL)
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
