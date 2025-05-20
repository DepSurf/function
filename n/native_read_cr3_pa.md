# Function: <code>native_read_cr3_pa</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int native_read_cr3_pa();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff81080506)
Location: arch/x86/include/asm/processor.h:246
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff81080506-ffffffff81080529: native_read_cr3_pa (STB_LOCAL)
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f04a7)
Location: arch/x86/include/asm/processor.h:244
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a71af)
Location: arch/x86/include/asm/processor.h:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf86d)
Location: arch/x86/include/asm/processor.h:236
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5d0c)
Location: arch/x86/include/asm/processor.h:236
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8fa4)
Location: arch/x86/include/asm/processor.h:250
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6a2a)
Location: arch/x86/include/asm/processor.h:250
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e1474)
Location: arch/x86/include/asm/processor.h:250
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4d06)
Location: arch/x86/include/asm/processor.h:252
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477778)
Location: arch/x86/include/asm/processor.h:255
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0e4f)
Location: arch/x86/include/asm/processor.h:206
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4f5f)
Location: arch/x86/include/asm/processor.h:206
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5b5f)
Location: arch/x86/include/asm/processor.h:221
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0ca4)
Location: arch/x86/include/asm/processor.h:236
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8e29)
Location: arch/x86/include/asm/processor.h:236
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3ba3)
Location: arch/x86/include/asm/processor.h:236
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6d49)
Location: arch/x86/include/asm/processor.h:236
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
