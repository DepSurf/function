# Function: <code>__module_text_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81106870)
Location: kernel/module.c:4066
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff81106870-ffffffff811068cd: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110e030)
Location: kernel/module.c:4237
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff8110e030-ffffffff8110e08d: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115a10)
Location: kernel/module.c:4258
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff81115a10-ffffffff81115a6d: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81116760)
Location: kernel/module.c:4304
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff81116760-ffffffff811167bc: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81121d60)
Location: kernel/module.c:4342
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff81121d60-ffffffff81121dbc: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112f850)
Location: kernel/module.c:4379
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff8112f850-ffffffff8112f8ad: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113b320)
Location: kernel/module.c:4417
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff8113b320-ffffffff8113b37d: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81146960)
Location: kernel/module.c:4445
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff81146960-ffffffff811469bd: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81152540)
Location: kernel/module.c:4512
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff81152540-ffffffff8115259d: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8116791d)
Location: kernel/module.c:4520
Inline: True
Inline callers:
  - kernel/module.c:is_module_text_address
Direct callers:
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff811621f0-ffffffff81162256: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8116427d)
Location: kernel/module.c:4751
Inline: True
Inline callers:
  - kernel/module.c:is_module_text_address
Direct callers:
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/static_call.c:__static_call_mod_text_reserved
  - kernel/static_call.c:__static_call_mod_text_reserved
  - kernel/jump_label.c:__jump_label_mod_text_reserved
  - kernel/jump_label.c:__jump_label_mod_text_reserved
```
**Symbols:**

```
ffffffff811642e0-ffffffff81164346: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8116504d)
Location: kernel/module.c:4690
Inline: True
Inline callers:
  - kernel/module.c:is_module_text_address
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/static_call.c:static_call_text_reserved
  - kernel/static_call.c:static_call_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff811650c0-ffffffff81165126: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8118a755)
Location: kernel/module.c:4713
Inline: True
Inline callers:
  - kernel/module.c:is_module_text_address
Direct callers:
  - kernel/module.c:symbol_put_addr
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/static_call.c:static_call_text_reserved
  - kernel/static_call.c:static_call_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff8118a7e0-ffffffff8118a84e: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff81190370)
Location: kernel/module/main.c:3100
Inline: False
Direct callers:
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:symbol_put_addr
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff81190370-ffffffff811903f4: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811cd6f0)
Location: kernel/module/main.c:3110
Inline: False
Direct callers:
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:symbol_put_addr
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff811cd6f0-ffffffff811cd774: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811e10f4)
Location: kernel/module/main.c:3314
Inline: True
Inline callers:
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:symbol_put_addr
Direct callers:
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff811e1180-ffffffff811e11d5: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f6e24)
Location: kernel/module/main.c:3325
Inline: True
Inline callers:
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:symbol_put_addr
Direct callers:
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/static_call_inline.c:static_call_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff811f6eb0-ffffffff811f6f05: __module_text_address (STB_GLOBAL)
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
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c1148)
Location: kernel/module.c:4512
Inline: False
Direct callers:
  - arch/arm64/kernel/ftrace.c:ftrace_make_nop
  - arch/arm64/kernel/ftrace.c:ftrace_make_call
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffff8000101c1148-ffff8000101c11cc: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c04088f4)
Location: kernel/module.c:4512
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
```
**Symbols:**

```
c04088f4-c040895c: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (c00000000022e050)
Location: kernel/module.c:4512
Inline: True
Inline callers:
  - kernel/module.c:is_module_text_address
  - kernel/module.c:symbol_put_addr
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/module.c:symbol_put_addr
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
c000000000227ae0-c000000000227b98: __module_text_address.part.0 (STB_LOCAL)
c000000000227ba0-c000000000227be8: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000143444)
Location: kernel/module.c:4512
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
```
**Symbols:**

```
ffffffe000143444-ffffffe0001434b8: __module_text_address (STB_GLOBAL)
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
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114ab60)
Location: kernel/module.c:4512
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff8114ab60-ffffffff8114abbd: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113de10)
Location: kernel/module.c:4512
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff8113de10-ffffffff8113de6d: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81148a10)
Location: kernel/module.c:4512
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff81148a10-ffffffff81148a6d: __module_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct module *__module_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81155680)
Location: kernel/module.c:4512
Inline: False
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
```
**Symbols:**

```
ffffffff81155680-ffffffff811556dd: __module_text_address (STB_GLOBAL)
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
