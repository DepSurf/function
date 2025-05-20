# Function: <code>sprint_symbol</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8110b4c0)
Location: kernel/kallsyms.c:394
Inline: True
Inline callers:
  - kernel/kallsyms.c:__print_symbol
```
**Symbols:**

```
ffffffff8110b4c0-ffffffff8110b4d7: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81112d36)
Location: kernel/kallsyms.c:418
Inline: True
Inline callers:
  - kernel/kallsyms.c:__print_symbol
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff81112d10-ffffffff81112d27: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8111a446)
Location: kernel/kallsyms.c:418
Inline: True
Inline callers:
  - kernel/kallsyms.c:__print_symbol
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff8111a420-ffffffff8111a437: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8111bf96)
Location: kernel/kallsyms.c:420
Inline: True
Inline callers:
  - kernel/kallsyms.c:__print_symbol
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff8111bf70-ffffffff8111bf87: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811275e6)
Location: kernel/kallsyms.c:425
Inline: True
Inline callers:
  - kernel/kallsyms.c:__print_symbol
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff811275c0-ffffffff811275d7: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81135480)
Location: kernel/kallsyms.c:390
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff81135480-ffffffff81135497: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81140990)
Location: kernel/kallsyms.c:390
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_events_hist.c:hist_trigger_entry_print
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff81140990-ffffffff811409a7: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114bd80)
Location: kernel/kallsyms.c:393
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_sym
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff8114bd80-ffffffff8114bd97: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81157a50)
Location: kernel/kallsyms.c:393
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_sym
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff81157a50-ffffffff81157a67: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81168600)
Location: kernel/kallsyms.c:392
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_events_hist.c:hist_trigger_print_key
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff81168600-ffffffff81168617: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81164bf0)
Location: kernel/kallsyms.c:393
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_events_hist.c:hist_trigger_print_key
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff81164bf0-ffffffff81164c07: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811659c0)
Location: kernel/kallsyms.c:444
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_events_hist.c:hist_trigger_print_key
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff811659c0-ffffffff811659d7: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8118af10)
Location: kernel/kallsyms.c:471
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_events_hist.c:hist_trigger_print_key
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff8118af10-ffffffff8118af27: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811ba0f0)
Location: kernel/kallsyms.c:495
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff811ba0f0-ffffffff811ba113: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811fb940)
Location: kernel/kallsyms.c:568
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff811fb940-ffffffff811fb963: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81211280)
Location: kernel/kallsyms.c:535
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff81211280-ffffffff812112a3: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81228900)
Location: kernel/kallsyms.c:533
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff81228900-ffffffff81228923: sprint_symbol (STB_GLOBAL)
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
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffff8000101c6e70)
Location: kernel/kallsyms.c:393
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_sym
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffff8000101c6e70-ffff8000101c6eac: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c040de18)
Location: kernel/kallsyms.c:393
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_sym
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
c040de18-c040de3c: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c00000000022f050)
Location: kernel/kallsyms.c:393
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_sym
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
c00000000022f050-c00000000022f06c: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffe000147230)
Location: kernel/kallsyms.c:393
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_sym
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffe000147230-ffffffe000147266: sprint_symbol (STB_GLOBAL)
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
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81150070)
Location: kernel/kallsyms.c:393
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_sym
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff81150070-ffffffff81150087: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81143320)
Location: kernel/kallsyms.c:393
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_sym
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff81143320-ffffffff81143337: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114df20)
Location: kernel/kallsyms.c:393
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_sym
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff8114df20-ffffffff8114df37: sprint_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sprint_symbol(char *buffer, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8115ad00)
Location: kernel/kallsyms.c:393
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:seq_print_sym
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff8115ad00-ffffffff8115ad17: sprint_symbol (STB_GLOBAL)
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
