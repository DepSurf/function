# Function: <code>apic_bsp_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int apic_bsp_setup(bool upmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81f71c61)
Location: arch/x86/kernel/apic/apic.c:2192
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/apic.c:APIC_init_uniprocessor
```
**Symbols:**

```
ffffffff81f71c61-ffffffff81f71d0d: apic_bsp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apic_bsp_setup(bool upmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81f9a44d)
Location: arch/x86/kernel/apic/apic.c:2233
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/apic.c:APIC_init_uniprocessor
```
**Symbols:**

```
ffffffff81f9a44d-ffffffff81f9a4f9: apic_bsp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apic_bsp_setup(bool upmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81fd5914)
Location: arch/x86/kernel/apic/apic.c:2281
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/apic.c:APIC_init_uniprocessor
```
**Symbols:**

```
ffffffff81fd5914-ffffffff81fd59c0: apic_bsp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apic_bsp_setup(bool upmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff820b6655)
Location: arch/x86/kernel/apic/apic.c:2354
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/apic.c:APIC_init_uniprocessor
```
**Symbols:**

```
ffffffff820b6655-ffffffff820b6706: apic_bsp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void apic_bsp_setup(bool upmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826bce82)
Location: arch/x86/kernel/apic/apic.c:2378
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff826bce82-ffffffff826bcf02: apic_bsp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void apic_bsp_setup(bool upmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826e6c39)
Location: arch/x86/kernel/apic/apic.c:2408
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff826e6c39-ffffffff826e6cb9: apic_bsp_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void apic_bsp_setup(bool upmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289d782)
Location: arch/x86/kernel/apic/apic.c:2416
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff8289d782-ffffffff8289d802: apic_bsp_setup (STB_GLOBAL)
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
In arch/x86/kernel/apic/apic.c (ffffffff828b5334)
Location: arch/x86/kernel/apic/apic.c:2502
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff828b8846)
Location: arch/x86/kernel/apic/apic.c:2559
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff82cdd8d3)
Location: arch/x86/kernel/apic/apic.c:2517
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff82fc9cb1)
Location: arch/x86/kernel/apic/apic.c:2588
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff831d45c5)
Location: arch/x86/kernel/apic/apic.c:2596
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff832b7151)
Location: arch/x86/kernel/apic/apic.c:2593
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff83468c85)
Location: arch/x86/kernel/apic/apic.c:2611
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff83e8d508)
Location: arch/x86/kernel/apic/apic.c:2645
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff836b0d7e)
Location: arch/x86/kernel/apic/apic.c:2662
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff838e146e)
Location: arch/x86/kernel/apic/apic.c:2509
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff828a684d)
Location: arch/x86/kernel/apic/apic.c:2559
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff8289e96d)
Location: arch/x86/kernel/apic/apic.c:2559
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff828b975d)
Location: arch/x86/kernel/apic/apic.c:2559
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff828b985e)
Location: arch/x86/kernel/apic/apic.c:2559
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
