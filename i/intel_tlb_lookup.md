# Function: <code>intel_tlb_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810419ee)
Location: arch/x86/kernel/cpu/intel.c:608
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810419e8)
Location: arch/x86/kernel/cpu/intel.c:650
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81041438)
Location: arch/x86/kernel/cpu/intel.c:689
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8103f47e)
Location: arch/x86/kernel/cpu/intel.c:712
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810427d8)
Location: arch/x86/kernel/cpu/intel.c:767
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810446c7)
Location: arch/x86/kernel/cpu/intel.c:846
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81046147)
Location: arch/x86/kernel/cpu/intel.c:854
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81048b30)
Location: arch/x86/kernel/cpu/intel.c:849
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81049400)
Location: arch/x86/kernel/cpu/intel.c:855
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_tlb_lookup(const unsigned char desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d7b0)
Location: arch/x86/kernel/cpu/intel.c:806
Inline: False
```
**Symbols:**

```
ffffffff8104d7b0-ffffffff8104da63: intel_tlb_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_tlb_lookup(const unsigned char desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104cce0)
Location: arch/x86/kernel/cpu/intel.c:807
Inline: False
```
**Symbols:**

```
ffffffff8104cce0-ffffffff8104cf93: intel_tlb_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_tlb_lookup(const unsigned char desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104e880)
Location: arch/x86/kernel/cpu/intel.c:812
Inline: False
```
**Symbols:**

```
ffffffff8104e880-ffffffff8104eb33: intel_tlb_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_tlb_lookup(const unsigned char desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810562a0)
Location: arch/x86/kernel/cpu/intel.c:816
Inline: False
```
**Symbols:**

```
ffffffff810562a0-ffffffff81056ba8: intel_tlb_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_tlb_lookup(const unsigned char desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81062310)
Location: arch/x86/kernel/cpu/intel.c:844
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
```
**Symbols:**

```
ffffffff81062310-ffffffff81062c65: intel_tlb_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_tlb_lookup(const unsigned char desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81070df0)
Location: arch/x86/kernel/cpu/intel.c:986
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
```
**Symbols:**

```
ffffffff81070df0-ffffffff8107173b: intel_tlb_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_tlb_lookup(const unsigned char desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810729d0)
Location: arch/x86/kernel/cpu/intel.c:986
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
```
**Symbols:**

```
ffffffff810729d0-ffffffff81073326: intel_tlb_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_tlb_lookup(const unsigned char desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8107a2d0)
Location: arch/x86/kernel/cpu/intel.c:803
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
```
**Symbols:**

```
ffffffff8107a2d0-ffffffff8107ac26: intel_tlb_lookup (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81049570)
Location: arch/x86/kernel/cpu/intel.c:855
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8103891e)
Location: arch/x86/kernel/cpu/intel.c:855
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:intel_detect_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810493b0)
Location: arch/x86/kernel/cpu/intel.c:855
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104a7c0)
Location: arch/x86/kernel/cpu/intel.c:855
Inline: True
```
</details>
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
