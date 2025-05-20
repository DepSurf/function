# Function: <code>fill_ldt</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102dcb1)
Location: arch/x86/include/asm/desc.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:do_arch_prctl
```
```
In arch/x86/kernel/ldt.c (ffffffff81032cb2)
Location: arch/x86/include/asm/desc.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff8103d467)
Location: arch/x86/include/asm/desc.h:11
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
In arch/x86/kernel/ldt.c (ffffffff81031e51)
Location: arch/x86/include/asm/desc.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff8103d1b2)
Location: arch/x86/include/asm/desc.h:11
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
In arch/x86/kernel/ldt.c (ffffffff81031ad1)
Location: arch/x86/include/asm/desc.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff8103caa2)
Location: arch/x86/include/asm/desc.h:11
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
In arch/x86/kernel/ldt.c (ffffffff8102fce5)
Location: arch/x86/include/asm/desc.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff8103ab00)
Location: arch/x86/include/asm/desc.h:12
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
In arch/x86/kernel/ldt.c (ffffffff81031fe5)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff8103d52d)
Location: arch/x86/include/asm/desc.h:15
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
In arch/x86/kernel/ldt.c (ffffffff810333a5)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff8103eaad)
Location: arch/x86/include/asm/desc.h:15
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
In arch/x86/kernel/ldt.c (ffffffff81034653)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff8104009d)
Location: arch/x86/include/asm/desc.h:15
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
In arch/x86/kernel/ldt.c (ffffffff810364f5)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff81042739)
Location: arch/x86/include/asm/desc.h:15
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
In arch/x86/kernel/ldt.c (ffffffff81036d25)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff81042ea9)
Location: arch/x86/include/asm/desc.h:15
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
In arch/x86/kernel/ldt.c (ffffffff81038c47)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff810464b5)
Location: arch/x86/include/asm/desc.h:15
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
In arch/x86/kernel/ldt.c (ffffffff810394c7)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff81045f55)
Location: arch/x86/include/asm/desc.h:15
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
In arch/x86/kernel/ldt.c (ffffffff8103af97)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff81047977)
Location: arch/x86/include/asm/desc.h:15
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
In arch/x86/kernel/ldt.c (ffffffff810409c7)
Location: arch/x86/include/asm/desc.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff8104e1ec)
Location: arch/x86/include/asm/desc.h:16
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
In arch/x86/kernel/ldt.c (ffffffff810483a1)
Location: arch/x86/include/asm/desc.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff810592ef)
Location: arch/x86/include/asm/desc.h:16
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
In arch/x86/kernel/ldt.c (ffffffff81053101)
Location: arch/x86/include/asm/desc.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff81066c31)
Location: arch/x86/include/asm/desc.h:16
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
In arch/x86/kernel/ldt.c (ffffffff810540e0)
Location: arch/x86/include/asm/desc.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff81068358)
Location: arch/x86/include/asm/desc.h:16
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
In arch/x86/kernel/ldt.c (ffffffff8105b310)
Location: arch/x86/include/asm/desc.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff8106f7d8)
Location: arch/x86/include/asm/desc.h:16
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
In arch/x86/kernel/ldt.c (ffffffff81036e85)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff81043029)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81026795)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff8103263b)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036ce5)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff81042e69)
Location: arch/x86/include/asm/desc.h:15
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
In arch/x86/kernel/ldt.c (ffffffff81037ce5)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff81044344)
Location: arch/x86/include/asm/desc.h:15
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
</details>
</li>
</ul>

## Differences
