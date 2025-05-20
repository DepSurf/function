# Function: <code>lapic_setup_esr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81052cf0)
Location: arch/x86/kernel/apic/apic.c:1167
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
**Symbols:**

```
ffffffff81052cf0-ffffffff81052de5: lapic_setup_esr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81052e80)
Location: arch/x86/kernel/apic/apic.c:1201
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
```
**Symbols:**

```
ffffffff81052e80-ffffffff81052f75: lapic_setup_esr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81055b70)
Location: arch/x86/kernel/apic/apic.c:1204
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
```
**Symbols:**

```
ffffffff81055b70-ffffffff81055c65: lapic_setup_esr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81055680)
Location: arch/x86/kernel/apic/apic.c:1287
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
```
**Symbols:**

```
ffffffff81055680-ffffffff81055775: lapic_setup_esr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81059320)
Location: arch/x86/kernel/apic/apic.c:1370
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
```
**Symbols:**

```
ffffffff81059320-ffffffff81059426: lapic_setup_esr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1374
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
```
**Symbols:**

```
ffffffff8105c150-ffffffff8105c239: lapic_setup_esr (STB_LOCAL)
ffffffff8105d9fc-ffffffff8105da22: lapic_setup_esr.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1380
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
```
**Symbols:**

```
ffffffff81061dd0-ffffffff81061eb9: lapic_setup_esr (STB_LOCAL)
ffffffff8106368c-ffffffff810636b2: lapic_setup_esr.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1457
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81065480-ffffffff8106556f: lapic_setup_esr (STB_LOCAL)
ffffffff81066d06-ffffffff81066d2d: lapic_setup_esr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1483
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81065af0-ffffffff81065bdf: lapic_setup_esr (STB_LOCAL)
ffffffff81067376-ffffffff8106739d: lapic_setup_esr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1435
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff8106ce20-ffffffff8106cf11: lapic_setup_esr (STB_LOCAL)
ffffffff8106e1b2-ffffffff8106e1d9: lapic_setup_esr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1447
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff8106e5c0-ffffffff8106e6b1: lapic_setup_esr (STB_LOCAL)
ffffffff81bd6f0c-ffffffff81bd6f33: lapic_setup_esr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1447
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff8106f0b0-ffffffff8106f1a1: lapic_setup_esr (STB_LOCAL)
ffffffff81bc90c6-ffffffff81bc90ed: lapic_setup_esr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1444
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff8107aab0-ffffffff8107aba1: lapic_setup_esr (STB_LOCAL)
ffffffff81c9db48-ffffffff81c9db6f: lapic_setup_esr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1452
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81089b40-ffffffff81089c3b: lapic_setup_esr (STB_LOCAL)
ffffffff81e4cfcf-ffffffff81e4cff5: lapic_setup_esr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109da20)
Location: arch/x86/kernel/apic/apic.c:1448
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff8109da20-ffffffff8109db46: lapic_setup_esr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a0a00)
Location: arch/x86/kernel/apic/apic.c:1450
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff810a0a00-ffffffff810a0b26: lapic_setup_esr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a6e30)
Location: arch/x86/kernel/apic/apic.c:1410
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff810a6e30-ffffffff810a6f04: lapic_setup_esr (STB_LOCAL)
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
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1483
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff810655e0-ffffffff810656cf: lapic_setup_esr (STB_LOCAL)
ffffffff81066e66-ffffffff81066e8d: lapic_setup_esr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1483
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81055920-ffffffff81055a0f: lapic_setup_esr (STB_LOCAL)
ffffffff810571d8-ffffffff810571ff: lapic_setup_esr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1483
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81065a90-ffffffff81065b7f: lapic_setup_esr (STB_LOCAL)
ffffffff81067316-ffffffff8106733d: lapic_setup_esr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void lapic_setup_esr();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1483
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81067070-ffffffff8106715f: lapic_setup_esr (STB_LOCAL)
ffffffff810688f6-ffffffff8106891d: lapic_setup_esr.cold (STB_LOCAL)
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
