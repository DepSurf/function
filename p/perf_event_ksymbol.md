# Function: <code>perf_event_ksymbol</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7814
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffff8120a15d-ffffffff8120a175: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff81208fd0-ffffffff812091a6: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7930
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffff81217457-ffffffff8121746f: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff81216340-ffffffff81216516: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:8481
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
  - kernel/events/core.c:perf_event_bpf_event
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff81242e27-ffffffff81242e3f: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff812421f0-ffffffff812423c4: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:8663
Inline: False
Direct callers:
  - kernel/kprobes.c:__get_insn_slot
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/bpf/trampoline.c:bpf_tramp_image_alloc
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
  - kernel/events/core.c:perf_event_bpf_event
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff81be678b-ffffffff81be67a3: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff8124c940-ffffffff8124cb1d: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:8792
Inline: False
Direct callers:
  - kernel/kprobes.c:__get_insn_slot
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
  - kernel/events/core.c:perf_event_bpf_event
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff81bd848c-ffffffff81bd84a4: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff81250f90-ffffffff81251172: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:8911
Inline: False
Direct callers:
  - kernel/kprobes.c:__get_insn_slot
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
  - kernel/events/core.c:perf_event_bpf_event
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff81cb9976-ffffffff81cb99a2: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff8128bd50-ffffffff8128bf72: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:8816
Inline: False
Direct callers:
  - kernel/kprobes.c:__get_insn_slot
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/events/core.c:perf_event_bpf_event
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff81e6af4e-ffffffff81e6af7a: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff812e0680-ffffffff812e08f5: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:9093
Inline: False
Direct callers:
  - kernel/kprobes.c:__get_insn_slot
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/events/core.c:perf_event_bpf_event
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff82061e38-ffffffff82061e4c: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff81348ad0-ffffffff81348d60: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:9121
Inline: False
Direct callers:
  - kernel/kprobes.c:__get_insn_slot
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
  - kernel/events/core.c:perf_event_bpf_event
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff820e15d2-ffffffff820e15e6: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff81379c00-ffffffff81379e97: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:9191
Inline: False
Direct callers:
  - kernel/kprobes.c:__get_insn_slot
  - kernel/trace/ftrace.c:ftrace_trampoline_free
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/events/core.c:perf_event_bpf_event
  - kernel/events/core.c:perf_event_bpf_event
```
**Symbols:**

```
ffffffff821be035-ffffffff821be049: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff813a2f10-ffffffff813a3158: perf_event_ksymbol (STB_GLOBAL)
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
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102a03e0)
Location: kernel/events/core.c:7930
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffff8000102a03e0-ffff8000102a0560: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04d02f8)
Location: kernel/events/core.c:7930
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
c04d02f8-c04d048c: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000351bf0)
Location: kernel/events/core.c:7930
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
c000000000351bf0-c000000000351e58: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffe0001c61ee)
Location: kernel/events/core.c:7930
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffe0001c61ee-ffffffe0001c6230: perf_event_ksymbol.part.0 (STB_LOCAL)
ffffffe0001cf9da-ffffffe0001cfaae: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7930
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffff8120faa7-ffffffff8120fabf: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff8120e990-ffffffff8120eb66: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7930
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffff81202837-ffffffff8120284f: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff81201740-ffffffff81201916: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7930
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffff8120d847-ffffffff8120d85f: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff8120c730-ffffffff8120c906: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void perf_event_ksymbol(u16 ksym_type, u64 addr, u32 len, bool unregister, const char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7930
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
  - kernel/events/core.c:perf_event_bpf_emit_ksymbols
```
**Symbols:**

```
ffffffff8121c6e7-ffffffff8121c6ff: perf_event_ksymbol.cold (STB_LOCAL)
ffffffff8121b5b0-ffffffff8121b786: perf_event_ksymbol (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
