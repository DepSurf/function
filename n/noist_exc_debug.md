# Function: <code>noist_exc_debug</code>

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
void noist_exc_debug(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81bbd820)
Location: arch/x86/kernel/traps.c:930
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_debug
```
**Symbols:**

```
ffffffff81bbd820-ffffffff81bbd887: noist_exc_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void noist_exc_debug(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c35ea0)
Location: arch/x86/kernel/traps.c:1001
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_debug
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
```
**Symbols:**

```
ffffffff81c35ea0-ffffffff81c35fcc: noist_exc_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void noist_exc_debug(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c28320)
Location: arch/x86/kernel/traps.c:1003
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_debug
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
```
**Symbols:**

```
ffffffff81c28320-ffffffff81c28469: noist_exc_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void noist_exc_debug(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81d46490)
Location: arch/x86/kernel/traps.c:1038
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_debug
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
```
**Symbols:**

```
ffffffff81d46490-ffffffff81d465d9: noist_exc_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void noist_exc_debug(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81f14760)
Location: arch/x86/kernel/traps.c:1169
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_debug
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
```
**Symbols:**

```
ffffffff81f14760-ffffffff81f148c4: noist_exc_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void noist_exc_debug(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff820bbae0)
Location: arch/x86/kernel/traps.c:1178
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_debug
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
```
**Symbols:**

```
ffffffff820bbae0-ffffffff820bbc44: noist_exc_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void noist_exc_debug(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8213d210)
Location: arch/x86/kernel/traps.c:1179
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_debug
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
```
**Symbols:**

```
ffffffff8213d210-ffffffff8213d37b: noist_exc_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void noist_exc_debug(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8221f230)
Location: arch/x86/kernel/traps.c:1093
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_debug
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
```
**Symbols:**

```
ffffffff8221f230-ffffffff8221f39b: noist_exc_debug (STB_GLOBAL)
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
