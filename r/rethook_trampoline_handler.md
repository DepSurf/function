# Function: <code>rethook_trampoline_handler</code>

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
long unsigned int rethook_trampoline_handler(struct pt_regs *regs, long unsigned int frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812691d0)
Location: kernel/trace/rethook.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/rethook.c:arch_rethook_trampoline_callback
```
**Symbols:**

```
ffffffff812691d0-ffffffff8126930d: rethook_trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int rethook_trampoline_handler(struct pt_regs *regs, long unsigned int frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812bb530)
Location: kernel/trace/rethook.c:271
Inline: False
Direct callers:
  - arch/x86/kernel/rethook.c:arch_rethook_trampoline_callback
```
**Symbols:**

```
ffffffff812bb530-ffffffff812bb657: rethook_trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int rethook_trampoline_handler(struct pt_regs *regs, long unsigned int frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812df150)
Location: kernel/trace/rethook.c:284
Inline: False
Direct callers:
  - arch/x86/kernel/rethook.c:arch_rethook_trampoline_callback
```
**Symbols:**

```
ffffffff812df150-ffffffff812df27c: rethook_trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int rethook_trampoline_handler(struct pt_regs *regs, long unsigned int frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812fd090)
Location: kernel/trace/rethook.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/rethook.c:arch_rethook_trampoline_callback
```
**Symbols:**

```
ffffffff812fd090-ffffffff812fd1db: rethook_trampoline_handler (STB_GLOBAL)
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
