# Function: <code>uv_system_init</code>

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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:27
Inline: True
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:27
Inline: True
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:27
Inline: True
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:28
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:29
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:29
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:35
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:35
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uv_system_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd8cc)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1579
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
**Symbols:**

```
ffffffff828bd8cc-ffffffff828bd8f5: uv_system_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uv_system_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1c71)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1633
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
**Symbols:**

```
ffffffff82ce1c71-ffffffff82ce1cbd: uv_system_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uv_system_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fcee92)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1819
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
**Symbols:**

```
ffffffff82fcee92-ffffffff82fceede: uv_system_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uv_system_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d992f)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1818
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
**Symbols:**

```
ffffffff831d992f-ffffffff831d9980: uv_system_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uv_system_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc9d4)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1818
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
**Symbols:**

```
ffffffff832bc9d4-ffffffff832bca25: uv_system_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uv_system_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346e30c)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1828
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8346e30c-ffffffff8346e375: uv_system_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uv_system_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e94320)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1828
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
**Symbols:**

```
ffffffff83e94320-ffffffff83e943dc: uv_system_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uv_system_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b7e80)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1900
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
**Symbols:**

```
ffffffff836b7e80-ffffffff836b7f3c: uv_system_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uv_system_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e87c0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1860
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
**Symbols:**

```
ffffffff838e87c0-ffffffff838e887c: uv_system_init (STB_GLOBAL)
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:37
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:37
Inline: True
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:37
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uv_system_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be8f9)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1579
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
**Symbols:**

```
ffffffff828be8f9-ffffffff828be922: uv_system_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
