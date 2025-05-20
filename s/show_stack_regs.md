# Function: <code>show_stack_regs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031190)
Location: arch/x86/kernel/dumpstack.c:208
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff81031190-ffffffff810311be: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030de0)
Location: arch/x86/kernel/dumpstack.c:177
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff81030de0-ffffffff81030e05: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102f0f0)
Location: arch/x86/kernel/dumpstack.c:179
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff8102f0f0-ffffffff8102f115: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810310f0)
Location: arch/x86/kernel/dumpstack.c:239
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff810310f0-ffffffff81031115: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810322f1)
Location: arch/x86/kernel/dumpstack.c:305
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff810322f1-ffffffff81032316: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810335b6)
Location: arch/x86/kernel/dumpstack.c:296
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff810335b6-ffffffff810335db: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810353e6)
Location: arch/x86/kernel/dumpstack.c:296
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff810353e6-ffffffff8103540b: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035c16)
Location: arch/x86/kernel/dumpstack.c:296
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff81035c16-ffffffff81035c3b: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81037d51)
Location: arch/x86/kernel/dumpstack.c:304
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff81037d51-ffffffff81037d76: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bd3916)
Location: arch/x86/kernel/dumpstack.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_wrmsr_fault
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_rdmsr_fault
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff81bd3916-ffffffff81bd393b: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bc5d88)
Location: arch/x86/kernel/dumpstack.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_wrmsr_fault
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_rdmsr_fault
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff81bc5d88-ffffffff81bc5dad: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81c98ad2)
Location: arch/x86/kernel/dumpstack.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_wrmsr_fault
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_rdmsr_fault
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff81c98ad2-ffffffff81c98af7: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81e48078)
Location: arch/x86/kernel/dumpstack.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_msr_mce
  - arch/x86/mm/extable.c:ex_handler_msr
  - arch/x86/mm/extable.c:ex_handler_msr
```
**Symbols:**

```
ffffffff81e48078-ffffffff81e480a9: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81051bb0)
Location: arch/x86/kernel/dumpstack.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_msr_mce
  - arch/x86/mm/extable.c:ex_handler_msr
  - arch/x86/mm/extable.c:ex_handler_msr
```
**Symbols:**

```
ffffffff81051bb0-ffffffff81051be1: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810528f0)
Location: arch/x86/kernel/dumpstack.c:324
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_msr_mce
  - arch/x86/mm/extable.c:ex_handler_msr
  - arch/x86/mm/extable.c:ex_handler_msr
```
**Symbols:**

```
ffffffff810528f0-ffffffff81052921: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81059b10)
Location: arch/x86/kernel/dumpstack.c:324
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:ex_handler_msr_mce
  - arch/x86/mm/extable.c:ex_handler_msr
  - arch/x86/mm/extable.c:ex_handler_msr
```
**Symbols:**

```
ffffffff81059b10-ffffffff81059b41: show_stack_regs (STB_GLOBAL)
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
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035d76)
Location: arch/x86/kernel/dumpstack.c:296
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff81035d76-ffffffff81035d9b: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810256c6)
Location: arch/x86/kernel/dumpstack.c:296
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff810256c6-ffffffff810256eb: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035bd6)
Location: arch/x86/kernel/dumpstack.c:296
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff81035bd6-ffffffff81035bfb: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void show_stack_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81036bb6)
Location: arch/x86/kernel/dumpstack.c:296
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:ex_handler_wrmsr_unsafe
  - arch/x86/mm/extable.c:ex_handler_rdmsr_unsafe
```
**Symbols:**

```
ffffffff81036bb6-ffffffff81036bdb: show_stack_regs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
