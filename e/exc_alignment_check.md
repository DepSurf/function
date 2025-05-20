# Function: <code>exc_alignment_check</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void exc_alignment_check(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81bbce30)
Location: arch/x86/kernel/traps.c:289
Inline: False
```
**Symbols:**

```
ffffffff81bbce30-ffffffff81bbcee9: exc_alignment_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exc_alignment_check(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c35530)
Location: arch/x86/kernel/traps.c:293
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
```
**Symbols:**

```
ffffffff81c35530-ffffffff81c355ea: exc_alignment_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exc_alignment_check(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c279c0)
Location: arch/x86/kernel/traps.c:293
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff81c279c0-ffffffff81c27a7a: exc_alignment_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exc_alignment_check(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81d45a10)
Location: arch/x86/kernel/traps.c:293
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff81d45a10-ffffffff81d45aca: exc_alignment_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exc_alignment_check(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81f13cc0)
Location: arch/x86/kernel/traps.c:370
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff81f13cc0-ffffffff81f13d8a: exc_alignment_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exc_alignment_check(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff820baf20)
Location: arch/x86/kernel/traps.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff820baf20-ffffffff820bafea: exc_alignment_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exc_alignment_check(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8213c640)
Location: arch/x86/kernel/traps.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff8213c640-ffffffff8213c70a: exc_alignment_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exc_alignment_check(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8221e640)
Location: arch/x86/kernel/traps.c:293
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff8221e640-ffffffff8221e70a: exc_alignment_check (STB_GLOBAL)
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
