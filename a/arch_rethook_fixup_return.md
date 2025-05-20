# Function: <code>arch_rethook_fixup_return</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_rethook_fixup_return(struct pt_regs *regs, long unsigned int correct_ret_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rethook.c (ffffffff810954e0)
Location: arch/x86/kernel/rethook.c:107
Inline: False
Direct callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
```
**Symbols:**

```
ffffffff810954e0-ffffffff810954fa: arch_rethook_fixup_return (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_rethook_fixup_return(struct pt_regs *regs, long unsigned int correct_ret_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rethook.c (ffffffff810ab070)
Location: arch/x86/kernel/rethook.c:107
Inline: False
Direct callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
```
**Symbols:**

```
ffffffff810ab070-ffffffff810ab08a: arch_rethook_fixup_return (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_rethook_fixup_return(struct pt_regs *regs, long unsigned int correct_ret_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rethook.c (ffffffff810aec50)
Location: arch/x86/kernel/rethook.c:107
Inline: False
Direct callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
```
**Symbols:**

```
ffffffff810aec50-ffffffff810aec60: arch_rethook_fixup_return (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_rethook_fixup_return(struct pt_regs *regs, long unsigned int correct_ret_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rethook.c (ffffffff810b57d0)
Location: arch/x86/kernel/rethook.c:107
Inline: False
Direct callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
```
**Symbols:**

```
ffffffff810b57d0-ffffffff810b57e0: arch_rethook_fixup_return (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
