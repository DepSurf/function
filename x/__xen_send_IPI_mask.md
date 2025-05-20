# Function: <code>__xen_send_IPI_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102adc0)
Location: arch/x86/xen/smp.c:591
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_all
```
**Symbols:**

```
ffffffff8102adc0-ffffffff8102ae0e: __xen_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102a0e0)
Location: arch/x86/xen/smp.c:601
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
**Symbols:**

```
ffffffff8102a0e0-ffffffff8102a12e: __xen_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102a830)
Location: arch/x86/xen/smp.c:595
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
```
**Symbols:**

```
ffffffff8102a830-ffffffff8102a87e: __xen_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81028aa0)
Location: arch/x86/xen/smp.c:153
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
**Symbols:**

```
ffffffff81028aa0-ffffffff81028aee: __xen_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81028cb0)
Location: arch/x86/xen/smp.c:156
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
**Symbols:**

```
ffffffff81028cb0-ffffffff81028cfe: __xen_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029700)
Location: arch/x86/xen/smp.c:156
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
**Symbols:**

```
ffffffff81029700-ffffffff8102974e: __xen_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029ce0)
Location: arch/x86/xen/smp.c:156
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
**Symbols:**

```
ffffffff81029ce0-ffffffff81029d2e: __xen_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102baa0)
Location: arch/x86/xen/smp.c:156
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
**Symbols:**

```
ffffffff8102baa0-ffffffff8102baeb: __xen_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102c3a0)
Location: arch/x86/xen/smp.c:156
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
**Symbols:**

```
ffffffff8102c3a0-ffffffff8102c3eb: __xen_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102e8cb)
Location: arch/x86/xen/smp.c:156
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102f72b)
Location: arch/x86/xen/smp.c:159
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8103024b)
Location: arch/x86/xen/smp.c:159
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8103508b)
Location: arch/x86/xen/smp.c:159
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
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
In arch/x86/xen/smp.c (ffffffff8103adf0)
Location: arch/x86/xen/smp.c:135
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81042a70)
Location: arch/x86/xen/smp.c:135
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
**Symbols:**

```
ffffffff81042a70-ffffffff81042aca: __xen_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81042c70)
Location: arch/x86/xen/smp.c:135
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
**Symbols:**

```
ffffffff81042c70-ffffffff81042cca: __xen_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81049140)
Location: arch/x86/xen/smp.c:147
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
**Symbols:**

```
ffffffff81049140-ffffffff8104919a: __xen_send_IPI_mask (STB_LOCAL)
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
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102c500)
Location: arch/x86/xen/smp.c:156
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
**Symbols:**

```
ffffffff8102c500-ffffffff8102c54b: __xen_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102c360)
Location: arch/x86/xen/smp.c:156
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
**Symbols:**

```
ffffffff8102c360-ffffffff8102c3ab: __xen_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102d150)
Location: arch/x86/xen/smp.c:156
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
**Symbols:**

```
ffffffff8102d150-ffffffff8102d19b: __xen_send_IPI_mask (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
