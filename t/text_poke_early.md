# Function: <code>text_poke_early</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035ee0)
Location: arch/x86/kernel/alternative.c:663
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81035ee0-ffffffff81035f1e: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810350d0)
Location: arch/x86/kernel/alternative.c:664
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff810350d0-ffffffff8103510e: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81034ed0)
Location: arch/x86/kernel/alternative.c:670
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81034ed0-ffffffff81034f03: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81032ee0)
Location: arch/x86/kernel/alternative.c:675
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81032ee0-ffffffff81032f13: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035230)
Location: arch/x86/kernel/alternative.c:664
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81035230-ffffffff81035263: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81036370)
Location: arch/x86/kernel/alternative.c:664
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81036370-ffffffff810363a3: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81037560)
Location: arch/x86/kernel/alternative.c:668
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81037560-ffffffff810375a7: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81039e70)
Location: arch/x86/kernel/alternative.c:759
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81039e70-ffffffff81039efd: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103a650)
Location: arch/x86/kernel/alternative.c:759
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff8103a650-ffffffff8103a6dd: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103d480)
Location: arch/x86/kernel/alternative.c:759
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_queue
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_alternatives
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
**Symbols:**

```
ffffffff8103d480-ffffffff8103d50d: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103d960)
Location: arch/x86/kernel/alternative.c:762
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_queue
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_alternatives
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
**Symbols:**

```
ffffffff8103d960-ffffffff8103d9fe: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103f310)
Location: arch/x86/kernel/alternative.c:683
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_queue
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_alternatives
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
**Symbols:**

```
ffffffff8103f310-ffffffff8103f3b2: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810450d0)
Location: arch/x86/kernel/alternative.c:683
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_queue
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_alternatives
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
**Symbols:**

```
ffffffff810450d0-ffffffff81045172: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8104d6b0)
Location: arch/x86/kernel/alternative.c:975
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_queue
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:apply_retpolines
  - arch/x86/kernel/alternative.c:apply_alternatives
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
**Symbols:**

```
ffffffff8104d6b0-ffffffff8104d775: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81059c90)
Location: arch/x86/kernel/alternative.c:1438
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:apply_retpolines
  - arch/x86/kernel/alternative.c:apply_alternatives
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/callthunks.c:patch_call
```
**Symbols:**

```
ffffffff81059c90-ffffffff81059d5b: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105b230)
Location: arch/x86/kernel/alternative.c:1663
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:apply_retpolines
  - arch/x86/kernel/alternative.c:apply_alternatives
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/callthunks.c:patch_call
```
**Symbols:**

```
ffffffff8105b230-ffffffff8105b2fb: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81062530)
Location: arch/x86/kernel/alternative.c:1753
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:apply_retpolines
  - arch/x86/kernel/alternative.c:apply_alternatives
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/callthunks.c:patch_call
```
**Symbols:**

```
ffffffff81062530-ffffffff810625e6: text_poke_early (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103a7b0)
Location: arch/x86/kernel/alternative.c:759
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff8103a7b0-ffffffff8103a83d: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81029fe0)
Location: arch/x86/kernel/alternative.c:759
Inline: True
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81029fe0-ffffffff8102a04e: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103a610)
Location: arch/x86/kernel/alternative.c:759
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff8103a610-ffffffff8103a69d: text_poke_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void text_poke_early(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103b610)
Location: arch/x86/kernel/alternative.c:759
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
  - arch/x86/kernel/alternative.c:apply_paravirt
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff8103b610-ffffffff8103b69d: text_poke_early (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
