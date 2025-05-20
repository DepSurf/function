# Function: <code>disable_ioapic_support</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f726d2)
Location: arch/x86/kernel/apic/io_apic.c:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:APIC_init_uniprocessor
```
**Symbols:**

```
ffffffff81056d90-ffffffff81056db9: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f9aef7)
Location: arch/x86/kernel/apic/io_apic.c:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:APIC_init_uniprocessor
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
**Symbols:**

```
ffffffff81057000-ffffffff81057029: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd6430)
Location: arch/x86/kernel/apic/io_apic.c:194
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:APIC_init_uniprocessor
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
**Symbols:**

```
ffffffff81059db0-ffffffff81059dd9: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff820b7171)
Location: arch/x86/kernel/apic/io_apic.c:194
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:APIC_init_uniprocessor
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
**Symbols:**

```
ffffffff81059420-ffffffff81059449: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff826bda73)
Location: arch/x86/kernel/apic/io_apic.c:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff8105d910-ffffffff8105d939: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff826e7825)
Location: arch/x86/kernel/apic/io_apic.c:196
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81060a70-ffffffff81060a99: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289e36e)
Location: arch/x86/kernel/apic/io_apic.c:196
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81066750-ffffffff81066779: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b61ff)
Location: arch/x86/kernel/apic/io_apic.c:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81069dc0-ffffffff81069de9: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b96c2)
Location: arch/x86/kernel/apic/io_apic.c:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
**Symbols:**

```
ffffffff8106a760-ffffffff8106a789: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cde6b5)
Location: arch/x86/kernel/apic/io_apic.c:184
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:__apic_intr_mode_select
```
**Symbols:**

```
ffffffff81071b10-ffffffff81071b39: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcaa67)
Location: arch/x86/kernel/apic/io_apic.c:184
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:__apic_intr_mode_select
```
**Symbols:**

```
ffffffff81072fc0-ffffffff81072fe9: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff831d53c6)
Location: arch/x86/kernel/apic/io_apic.c:184
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
**Symbols:**

```
ffffffff81073a90-ffffffff81073ab9: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff832b7ef8)
Location: arch/x86/kernel/apic/io_apic.c:184
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
**Symbols:**

```
ffffffff81080f30-ffffffff81080f59: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff83469bdd)
Location: arch/x86/kernel/apic/io_apic.c:185
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
**Symbols:**

```
ffffffff810908c0-ffffffff810908ed: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8e915)
Location: arch/x86/kernel/apic/io_apic.c:185
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
**Symbols:**

```
ffffffff810a53e0-ffffffff810a540d: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b21b5)
Location: arch/x86/kernel/apic/io_apic.c:186
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
**Symbols:**

```
ffffffff810a84e0-ffffffff810a850d: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e2a95)
Location: arch/x86/kernel/apic/io_apic.c:186
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
**Symbols:**

```
ffffffff810af570-ffffffff810af59a: disable_ioapic_support (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff828a76c9)
Location: arch/x86/kernel/apic/io_apic.c:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
**Symbols:**

```
ffffffff8106a250-ffffffff8106a279: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289f7c6)
Location: arch/x86/kernel/apic/io_apic.c:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
**Symbols:**

```
ffffffff8105a5b0-ffffffff8105a5d9: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff828ba5d9)
Location: arch/x86/kernel/apic/io_apic.c:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
**Symbols:**

```
ffffffff8106a700-ffffffff8106a729: disable_ioapic_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void disable_ioapic_support();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff828ba6ef)
Location: arch/x86/kernel/apic/io_apic.c:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:parse_noapic
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:arch_disable_smp_support
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_select
```
**Symbols:**

```
ffffffff8106be00-ffffffff8106be29: disable_ioapic_support (STB_GLOBAL)
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
