# Function: <code>__kretprobe_trampoline_handler</code>

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
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long unsigned int __kretprobe_trampoline_handler(struct pt_regs *regs, void *trampoline_address, void *frame_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1863
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
**Symbols:**

```
ffffffff81be4a8b-ffffffff81be4a99: __kretprobe_trampoline_handler.cold (STB_LOCAL)
ffffffff811935c0-ffffffff81193690: __kretprobe_trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long unsigned int __kretprobe_trampoline_handler(struct pt_regs *regs, void *trampoline_address, void *frame_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1868
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
**Symbols:**

```
ffffffff81bd68bf-ffffffff81bd68cd: __kretprobe_trampoline_handler.cold (STB_LOCAL)
ffffffff81194570-ffffffff81194643: __kretprobe_trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int __kretprobe_trampoline_handler(struct pt_regs *regs, void *trampoline_address, void *frame_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1860
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
**Symbols:**

```
ffffffff81cb380b-ffffffff81cb3819: __kretprobe_trampoline_handler.cold (STB_LOCAL)
ffffffff811bd410-ffffffff811bd4e3: __kretprobe_trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
