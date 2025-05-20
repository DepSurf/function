# Function: <code>load_TLS</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d562)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:do_arch_prctl
```
```
In arch/x86/kernel/tls.c (ffffffff8103d5af)
Location: arch/x86/include/asm/paravirt.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c662)
Location: arch/x86/include/asm/paravirt.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff8103d315)
Location: arch/x86/include/asm/paravirt.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c515)
Location: arch/x86/include/asm/paravirt.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff8103cc05)
Location: arch/x86/include/asm/paravirt.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102a735)
Location: arch/x86/include/asm/paravirt.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff8103ac4f)
Location: arch/x86/include/asm/paravirt.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102b492)
Location: arch/x86/include/asm/paravirt.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff8103d678)
Location: arch/x86/include/asm/paravirt.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c4b2)
Location: arch/x86/include/asm/paravirt.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff8103ebea)
Location: arch/x86/include/asm/paravirt.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d71b)
Location: arch/x86/include/asm/paravirt.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff810401da)
Location: arch/x86/include/asm/paravirt.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102f4e5)
Location: arch/x86/include/asm/paravirt.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff8104287d)
Location: arch/x86/include/asm/paravirt.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fe45)
Location: arch/x86/include/asm/paravirt.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff81042fed)
Location: arch/x86/include/asm/paravirt.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810326e5)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff810465d8)
Location: arch/x86/include/asm/paravirt.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81033374)
Location: arch/x86/include/asm/paravirt.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff81046078)
Location: arch/x86/include/asm/paravirt.h:273
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81034e84)
Location: arch/x86/include/asm/paravirt.h:290
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff81047a97)
Location: arch/x86/include/asm/paravirt.h:290
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103a1a4)
Location: arch/x86/include/asm/paravirt.h:290
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff8104e307)
Location: arch/x86/include/asm/paravirt.h:290
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81041209)
Location: arch/x86/include/asm/paravirt.h:296
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff81059410)
Location: arch/x86/include/asm/paravirt.h:296
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104a959)
Location: arch/x86/include/asm/paravirt.h:296
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff81066d54)
Location: arch/x86/include/asm/paravirt.h:296
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104b199)
Location: arch/x86/include/asm/paravirt.h:298
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff81068472)
Location: arch/x86/include/asm/paravirt.h:298
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81052409)
Location: arch/x86/include/asm/paravirt.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff8106f8f2)
Location: arch/x86/include/asm/paravirt.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102ffa5)
Location: arch/x86/include/asm/paravirt.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff8104316d)
Location: arch/x86/include/asm/paravirt.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fe05)
Location: arch/x86/include/asm/paravirt.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff81042fad)
Location: arch/x86/include/asm/paravirt.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030c55)
Location: arch/x86/include/asm/paravirt.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/tls.c (ffffffff81044492)
Location: arch/x86/include/asm/paravirt.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
</ul>

## Differences
