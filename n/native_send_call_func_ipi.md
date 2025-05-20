# Function: <code>native_send_call_func_ipi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81050820)
Location: arch/x86/kernel/smp.c:136
Inline: True
```
**Symbols:**

```
ffffffff81050820-ffffffff810508e7: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81050a20)
Location: arch/x86/kernel/smp.c:136
Inline: True
```
**Symbols:**

```
ffffffff81050a20-ffffffff81050aed: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff810532d0)
Location: arch/x86/kernel/smp.c:138
Inline: False
```
**Symbols:**

```
ffffffff810532d0-ffffffff810533d1: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81052e50)
Location: arch/x86/kernel/smp.c:139
Inline: False
```
**Symbols:**

```
ffffffff81052e50-ffffffff81052f6f: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81056b70)
Location: arch/x86/kernel/smp.c:139
Inline: False
```
**Symbols:**

```
ffffffff81056b70-ffffffff81056c98: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/kernel/smp.c:139
Inline: False
```
**Symbols:**

```
ffffffff81059d69-ffffffff81059d75: native_send_call_func_ipi.cold.17 (STB_LOCAL)
ffffffff810599e0-ffffffff81059afc: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/kernel/smp.c:139
Inline: False
```
**Symbols:**

```
ffffffff8105f9e9-ffffffff8105f9f5: native_send_call_func_ipi.cold.18 (STB_LOCAL)
ffffffff8105f660-ffffffff8105f77c: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/kernel/smp.c:137
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff81062e49-ffffffff81062e55: native_send_call_func_ipi.cold (STB_LOCAL)
ffffffff81062af0-ffffffff81062c0d: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81067970)
Location: arch/x86/kernel/apic/ipi.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff81067970-ffffffff81067a26: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8106e6c0)
Location: arch/x86/kernel/apic/ipi.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff8106e6c0-ffffffff8106e773: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8106fb40)
Location: arch/x86/kernel/apic/ipi.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff8106fb40-ffffffff8106fbf3: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81070670)
Location: arch/x86/kernel/apic/ipi.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff81070670-ffffffff81070723: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8107c210)
Location: arch/x86/kernel/apic/ipi.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff8107c210-ffffffff8107c2f2: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8108b580)
Location: arch/x86/kernel/apic/ipi.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff8108b580-ffffffff8108b696: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8109f960)
Location: arch/x86/kernel/apic/ipi.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff8109f960-ffffffff8109fa76: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff810a28f0)
Location: arch/x86/kernel/apic/ipi.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff810a28f0-ffffffff810a2a06: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff810a95a0)
Location: arch/x86/kernel/apic/ipi.c:81
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff810a95a0-ffffffff810a9695: native_send_call_func_ipi (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81067460)
Location: arch/x86/kernel/apic/ipi.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff81067460-ffffffff81067516: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057820)
Location: arch/x86/kernel/apic/ipi.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff81057820-ffffffff810578d6: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81067910)
Location: arch/x86/kernel/apic/ipi.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff81067910-ffffffff810679c6: native_send_call_func_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void native_send_call_func_ipi(const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81068ef0)
Location: arch/x86/kernel/apic/ipi.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
```
**Symbols:**

```
ffffffff81068ef0-ffffffff81068fa6: native_send_call_func_ipi (STB_GLOBAL)
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
