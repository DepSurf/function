# Function: <code>__module_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81106790)
Location: kernel/module.c:4021
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:module_address_lookup
  - kernel/module.c:is_module_address
  - kernel/jump_label.c:jump_label_update
```
**Symbols:**

```
ffffffff81106790-ffffffff81106863: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110df50)
Location: kernel/module.c:4192
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:module_address_lookup
  - kernel/jump_label.c:jump_label_update
```
**Symbols:**

```
ffffffff8110df50-ffffffff8110e026: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115930)
Location: kernel/module.c:4213
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:module_address_lookup
  - kernel/jump_label.c:jump_label_update
```
**Symbols:**

```
ffffffff81115930-ffffffff81115a06: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81116680)
Location: kernel/module.c:4259
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff81116680-ffffffff81116758: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81121c80)
Location: kernel/module.c:4297
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff81121c80-ffffffff81121d5b: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112f770)
Location: kernel/module.c:4334
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff8112f770-ffffffff8112f849: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113b240)
Location: kernel/module.c:4372
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff8113b240-ffffffff8113b31a: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81146880)
Location: kernel/module.c:4400
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff81146880-ffffffff8114695f: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81152460)
Location: kernel/module.c:4467
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff81152460-ffffffff8115253f: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81162110)
Location: kernel/module.c:4475
Inline: True
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_add_module
```
**Symbols:**

```
ffffffff81162110-ffffffff811621eb: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811640b0)
Location: kernel/module.c:4707
Inline: True
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_add_module
```
**Symbols:**

```
ffffffff811640b0-ffffffff8116418b: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81164e80)
Location: kernel/module.c:4646
Inline: True
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_add_module
```
**Symbols:**

```
ffffffff81164e80-ffffffff81164f5b: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8118a755)
Location: kernel/module.c:4669
Inline: True
Inline callers:
  - kernel/module.c:is_module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
Direct callers:
  - kernel/module.c:is_module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_add_module
```
**Symbols:**

```
ffffffff81184680-ffffffff8118474d: __module_address.part.0 (STB_LOCAL)
ffffffff8118a720-ffffffff8118a746: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811901c1)
Location: kernel/module/main.c:3049
Inline: True
Inline callers:
  - kernel/module/main.c:is_module_address
Direct callers:
  - kernel/module/main.c:__module_text_address
  - kernel/module/main.c:search_module_extables
  - kernel/module/kallsyms.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_add_module
```
**Symbols:**

```
ffffffff81190250-ffffffff811902f4: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811cd511)
Location: kernel/module/main.c:3059
Inline: True
Inline callers:
  - kernel/module/main.c:is_module_address
Direct callers:
  - arch/x86/kernel/callthunks.c:is_coretext
  - kernel/module/main.c:__module_text_address
  - kernel/module/main.c:search_module_extables
  - kernel/module/kallsyms.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_add_module
```
**Symbols:**

```
ffffffff811cd5b0-ffffffff811cd654: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811e0de0)
Location: kernel/module/main.c:3262
Inline: False
Direct callers:
  - arch/x86/kernel/callthunks.c:is_coretext
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:is_module_address
  - kernel/module/main.c:search_module_extables
  - kernel/module/main.c:symbol_put_addr
  - kernel/module/kallsyms.c:module_address_lookup
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_add_module
```
**Symbols:**

```
ffffffff811e0de0-ffffffff811e0f6a: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f6b10)
Location: kernel/module/main.c:3273
Inline: False
Direct callers:
  - arch/x86/kernel/callthunks.c:is_coretext
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:is_module_address
  - kernel/module/main.c:search_module_extables
  - kernel/module/main.c:symbol_put_addr
  - kernel/module/kallsyms.c:module_address_lookup
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_add_module
```
**Symbols:**

```
ffffffff811f6b10-ffffffff811f6c9a: __module_address (STB_GLOBAL)
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
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c1028)
Location: kernel/module.c:4467
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffff8000101c1028-ffff8000101c1144: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c04087d8)
Location: kernel/module.c:4467
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
```
**Symbols:**

```
c04087d8-c04088f4: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (c00000000022e050)
Location: kernel/module.c:4467
Inline: True
Inline callers:
  - kernel/module.c:is_module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/module.c:symbol_put_addr
Direct callers:
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
c000000000227930-c000000000227a88: __module_address.part.0 (STB_LOCAL)
c000000000227a90-c000000000227ad8: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000143380)
Location: kernel/module.c:4467
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffffffe000143380-ffffffe000143444: __module_address (STB_GLOBAL)
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
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114aa80)
Location: kernel/module.c:4467
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff8114aa80-ffffffff8114ab5f: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113dd30)
Location: kernel/module.c:4467
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff8113dd30-ffffffff8113de0f: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81148930)
Location: kernel/module.c:4467
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff81148930-ffffffff81148a0f: __module_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct module *__module_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811555a0)
Location: kernel/module.c:4467
Inline: True
Direct callers:
  - kernel/module.c:__module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_address_lookup
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/jump_label.c:jump_label_module_notify
```
**Symbols:**

```
ffffffff811555a0-ffffffff8115567f: __module_address (STB_GLOBAL)
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
