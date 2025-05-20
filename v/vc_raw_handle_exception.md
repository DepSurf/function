# Function: <code>vc_raw_handle_exception</code>

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
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool vc_raw_handle_exception(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:1322
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff81084d70-ffffffff81084f84: vc_raw_handle_exception (STB_LOCAL)
ffffffff81bca2d2-ffffffff81bca34f: vc_raw_handle_exception.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool vc_raw_handle_exception(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:1318
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff81093f30-ffffffff81094144: vc_raw_handle_exception (STB_LOCAL)
ffffffff81c9f715-ffffffff81c9f792: vc_raw_handle_exception.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool vc_raw_handle_exception(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:1864
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff810a5f90-ffffffff810a61ce: vc_raw_handle_exception (STB_LOCAL)
ffffffff81e4ef39-ffffffff81e4efb3: vc_raw_handle_exception.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool vc_raw_handle_exception(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810be6d0)
Location: arch/x86/kernel/sev.c:1864
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff810be6d0-ffffffff810be968: vc_raw_handle_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool vc_raw_handle_exception(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c1d40)
Location: arch/x86/kernel/sev.c:1821
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff810c1d40-ffffffff810c1fb0: vc_raw_handle_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool vc_raw_handle_exception(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c9200)
Location: arch/x86/kernel/sev.c:1859
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
```
**Symbols:**

```
ffffffff810c9200-ffffffff810c9470: vc_raw_handle_exception (STB_LOCAL)
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
