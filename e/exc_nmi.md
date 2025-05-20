# Function: <code>exc_nmi</code>

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
void exc_nmi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81bbddf0)
Location: arch/x86/kernel/nmi.c:479
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_nmi
```
**Symbols:**

```
ffffffff81bbddf0-ffffffff81bbdfca: exc_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exc_nmi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81c366d0)
Location: arch/x86/kernel/nmi.c:476
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_nmi
```
**Symbols:**

```
ffffffff81c366d0-ffffffff81c36864: exc_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exc_nmi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81c28b60)
Location: arch/x86/kernel/nmi.c:476
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi_noist
```
**Symbols:**

```
ffffffff81c28b60-ffffffff81c28cf4: exc_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exc_nmi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81d46d00)
Location: arch/x86/kernel/nmi.c:476
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi_noist
```
**Symbols:**

```
ffffffff81d46d00-ffffffff81d46e8e: exc_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exc_nmi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81f15260)
Location: arch/x86/kernel/nmi.c:479
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi_noist
```
**Symbols:**

```
ffffffff81f15260-ffffffff81f153fe: exc_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exc_nmi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff820bc6f0)
Location: arch/x86/kernel/nmi.c:479
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi_noist
```
**Symbols:**

```
ffffffff820bc6f0-ffffffff820bc890: exc_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exc_nmi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8213de40)
Location: arch/x86/kernel/nmi.c:488
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi_kvm_vmx
```
**Symbols:**

```
ffffffff8213de40-ffffffff8213e0f3: exc_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exc_nmi(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8221fe40)
Location: arch/x86/kernel/nmi.c:492
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xenpv_exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi_kvm_vmx
```
**Symbols:**

```
ffffffff8221fe40-ffffffff822200ca: exc_nmi (STB_GLOBAL)
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
