# Function: <code>amd_e400_c1e_apic_setup</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81038100)
Location: arch/x86/kernel/process.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81038100-ffffffff81038142: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81036290)
Location: arch/x86/kernel/process.c:468
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81036290-ffffffff810362d3: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81038620)
Location: arch/x86/kernel/process.c:500
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81038620-ffffffff81038662: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:645
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81039d7b-ffffffff81039da7: amd_e400_c1e_apic_setup.cold.11 (STB_LOCAL)
ffffffff81039b00-ffffffff81039b1d: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103b030)
Location: arch/x86/kernel/process.c:709
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff8103b030-ffffffff8103b071: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:725
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff8103d8cf-ffffffff8103d8fb: amd_e400_c1e_apic_setup.cold (STB_LOCAL)
ffffffff8103d640-ffffffff8103d65d: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:725
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff8103e08f-ffffffff8103e0bb: amd_e400_c1e_apic_setup.cold (STB_LOCAL)
ffffffff8103de00-ffffffff8103de1d: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:832
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff8104115f-ffffffff8104118b: amd_e400_c1e_apic_setup.cold (STB_LOCAL)
ffffffff81040ec0-ffffffff81040edd: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:832
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81bd44f0-ffffffff81bd451c: amd_e400_c1e_apic_setup.cold (STB_LOCAL)
ffffffff81040e20-ffffffff81040e3d: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:844
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81bc6a0f-ffffffff81bc6a3c: amd_e400_c1e_apic_setup.cold (STB_LOCAL)
ffffffff81042820-ffffffff81042835: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:861
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81c99d3d-ffffffff81c99d6a: amd_e400_c1e_apic_setup.cold (STB_LOCAL)
ffffffff81048b90-ffffffff81048ba5: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:884
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81e49873-ffffffff81e498ac: amd_e400_c1e_apic_setup.cold (STB_LOCAL)
ffffffff81051e80-ffffffff81051e9f: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105f640)
Location: arch/x86/kernel/process.c:899
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff8105f640-ffffffff8105f69c: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81060da0)
Location: arch/x86/kernel/process.c:946
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81060da0-ffffffff81060dff: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81067e50)
Location: arch/x86/kernel/process.c:958
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81067e50-ffffffff81067eac: amd_e400_c1e_apic_setup (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:725
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff8103e20f-ffffffff8103e23b: amd_e400_c1e_apic_setup.cold (STB_LOCAL)
ffffffff8103df80-ffffffff8103df9d: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:725
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff8102da2f-ffffffff8102da53: amd_e400_c1e_apic_setup.cold (STB_LOCAL)
ffffffff8102d790-ffffffff8102d7ad: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:725
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff8103e04f-ffffffff8103e07b: amd_e400_c1e_apic_setup.cold (STB_LOCAL)
ffffffff8103ddc0-ffffffff8103dddd: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void amd_e400_c1e_apic_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:725
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_secondary_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff8103f1cb-ffffffff8103f1f7: amd_e400_c1e_apic_setup.cold (STB_LOCAL)
ffffffff8103ef20-ffffffff8103ef3d: amd_e400_c1e_apic_setup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
