# Function: <code>kernel_text_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff8109eab0)
Location: kernel/extable.c:120
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/kprobes.c:init_kprobes
  - kernel/jump_label.c:__jump_label_update
```
**Symbols:**

```
ffffffff8109eab0-ffffffff8109eb04: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810a2160)
Location: kernel/extable.c:120
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/kprobes.c:init_kprobes
  - kernel/jump_label.c:__jump_label_update
```
**Symbols:**

```
ffffffff810a2160-ffffffff810a21bc: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810a7220)
Location: kernel/extable.c:120
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/kprobes.c:init_kprobes
  - kernel/jump_label.c:__jump_label_update
```
**Symbols:**

```
ffffffff810a7220-ffffffff810a727c: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810a41a0)
Location: kernel/extable.c:128
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/kprobes.c:init_kprobes
  - kernel/jump_label.c:__jump_label_update
```
**Symbols:**

```
ffffffff810a41a0-ffffffff810a4230: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810aa720)
Location: kernel/extable.c:122
Inline: True
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:init_kprobes
  - kernel/jump_label.c:__jump_label_update
```
**Symbols:**

```
ffffffff810aa720-ffffffff810aa80d: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810b1380)
Location: kernel/extable.c:122
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:init_kprobes
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff810b1380-ffffffff810b1474: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810ba4c0)
Location: kernel/extable.c:122
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff810ba4c0-ffffffff810ba5b4: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c03d0)
Location: kernel/extable.c:110
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff810c03d0-ffffffff810c04c7: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c67d0)
Location: kernel/extable.c:117
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff810c67d0-ffffffff810c68c7: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/extable.c (ffffffff810ce855)
Location: kernel/extable.c:120
Inline: True
Inline callers:
  - kernel/extable.c:__kernel_text_address
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff810ce640-ffffffff810ce6f8: kernel_text_address.part.0 (STB_LOCAL)
ffffffff810ce8c0-ffffffff810ce908: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/extable.c (ffffffff810c9375)
Location: kernel/extable.c:120
Inline: True
Inline callers:
  - kernel/extable.c:__kernel_text_address
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/static_call.c:static_call_add_module
  - kernel/static_call.c:__static_call_update
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff810c9160-ffffffff810c9218: kernel_text_address.part.0 (STB_LOCAL)
ffffffff810c93e0-ffffffff810c9428: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810cae00)
Location: kernel/extable.c:120
Inline: True
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:__static_call_update
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff810cae00-ffffffff810caef4: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810ddee0)
Location: kernel/extable.c:120
Inline: True
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:__static_call_update
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff810ddee0-ffffffff810ddfd4: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810f7af0)
Location: kernel/extable.c:94
Inline: True
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:__static_call_update
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff810f7af0-ffffffff810f7c31: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff8111a320)
Location: kernel/extable.c:94
Inline: True
Direct callers:
  - arch/x86/events/utils.c:get_branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:__static_call_update
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff8111a320-ffffffff8111a461: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff81127590)
Location: kernel/extable.c:94
Inline: True
Direct callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/kernel/static_call.c:__static_call_fixup
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:__static_call_update
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff81127590-ffffffff811276d1: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff81131b70)
Location: kernel/extable.c:94
Inline: True
Direct callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/kernel/static_call.c:__static_call_fixup
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:__static_call_update
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff81131b70-ffffffff81131cb1: kernel_text_address (STB_GLOBAL)
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
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffff800010125390)
Location: kernel/extable.c:117
Inline: False
Direct callers:
  - arch/arm64/kernel/alternative.c:patch_alternative
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffff800010125390-ffff8000101254e0: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (c0378174)
Location: kernel/extable.c:117
Inline: False
Direct callers:
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
```
**Symbols:**

```
c0378174-c03782b4: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (c00000000016f140)
Location: kernel/extable.c:117
Inline: False
Direct callers:
  - arch/powerpc/perf/callchain.c:perf_callchain_kernel
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
c00000000016f140-c00000000016f314: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffe0000dd0ea)
Location: kernel/extable.c:117
Inline: False
Direct callers:
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffe0000dd0ea-ffffffe0000dd1d6: kernel_text_address (STB_GLOBAL)
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
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c0b50)
Location: kernel/extable.c:117
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff810c0b50-ffffffff810c0c47: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810af340)
Location: kernel/extable.c:117
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff810af340-ffffffff810af437: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c00a0)
Location: kernel/extable.c:117
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff810c00a0-ffffffff810c0197: kernel_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c84d0)
Location: kernel/extable.c:117
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/extable.c:__kernel_text_address
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/jump_label.c:__jump_label_update
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff810c84d0-ffffffff810c85c7: kernel_text_address (STB_GLOBAL)
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
