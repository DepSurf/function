# Function: <code>vc_init_em_ctxt</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
enum es_result vc_init_em_ctxt(struct es_em_ctxt *ctxt, struct pt_regs *regs, long unsigned int exit_code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81c37ef0)
Location: arch/x86/kernel/sev-es-shared.c:76
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
Direct callers:
  - arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb
```
**Symbols:**

```
ffffffff81082bf0-ffffffff81082c23: vc_init_em_ctxt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum es_result vc_init_em_ctxt(struct es_em_ctxt *ctxt, struct pt_regs *regs, long unsigned int exit_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81083370)
Location: arch/x86/kernel/sev-shared.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff81083370-ffffffff810834a9: vc_init_em_ctxt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum es_result vc_init_em_ctxt(struct es_em_ctxt *ctxt, struct pt_regs *regs, long unsigned int exit_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81092480)
Location: arch/x86/kernel/sev-shared.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff81092480-ffffffff810925ea: vc_init_em_ctxt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff8347173a)
Location: arch/x86/kernel/sev-shared.c:174
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83e98942)
Location: arch/x86/kernel/sev-shared.c:174
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum es_result vc_init_em_ctxt(struct es_em_ctxt *ctxt, struct pt_regs *regs, long unsigned int exit_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bee70)
Location: arch/x86/kernel/sev-shared.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff810bee70-ffffffff810beff2: vc_init_em_ctxt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum es_result vc_init_em_ctxt(struct es_em_ctxt *ctxt, struct pt_regs *regs, long unsigned int exit_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c6130)
Location: arch/x86/kernel/sev-shared.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:vc_raw_handle_exception
```
**Symbols:**

```
ffffffff810c6130-ffffffff810c62b2: vc_init_em_ctxt (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
