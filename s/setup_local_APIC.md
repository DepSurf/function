# Function: <code>setup_local_APIC</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81053e00)
Location: arch/x86/kernel/apic/apic.c:1214
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
**Symbols:**

```
ffffffff81053e00-ffffffff81054144: setup_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81053f50)
Location: arch/x86/kernel/apic/apic.c:1248
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
```
**Symbols:**

```
ffffffff81053f50-ffffffff810542f3: setup_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81056c50)
Location: arch/x86/kernel/apic/apic.c:1251
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
```
**Symbols:**

```
ffffffff81056c50-ffffffff81056ff3: setup_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810565b0)
Location: arch/x86/kernel/apic/apic.c:1334
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
```
**Symbols:**

```
ffffffff810565b0-ffffffff8105690d: setup_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8105a2c0)
Location: arch/x86/kernel/apic/apic.c:1417
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
```
**Symbols:**

```
ffffffff8105a2c0-ffffffff8105a65b: setup_local_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1470
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
```
**Symbols:**

```
ffffffff8105c370-ffffffff8105c6d5: setup_local_APIC (STB_LOCAL)
ffffffff8105da22-ffffffff8105daa3: setup_local_APIC.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1476
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
```
**Symbols:**

```
ffffffff81061ff0-ffffffff81062356: setup_local_APIC (STB_LOCAL)
ffffffff810636b2-ffffffff81063734: setup_local_APIC.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1554
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff810656a0-ffffffff81065a12: setup_local_APIC (STB_LOCAL)
ffffffff81066d2d-ffffffff81066daf: setup_local_APIC.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1598
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81065d10-ffffffff8106604a: setup_local_APIC (STB_LOCAL)
ffffffff8106739d-ffffffff81067424: setup_local_APIC.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1550
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff8106c740-ffffffff8106c9b1: setup_local_APIC (STB_LOCAL)
ffffffff8106df35-ffffffff8106dfbc: setup_local_APIC.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1562
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff8106def0-ffffffff8106e165: setup_local_APIC (STB_LOCAL)
ffffffff81bd6cac-ffffffff81bd6d33: setup_local_APIC.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1562
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff8106e920-ffffffff8106ec5d: setup_local_APIC (STB_LOCAL)
ffffffff81bc8f14-ffffffff81bc8f9b: setup_local_APIC.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1559
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff8107a2a0-ffffffff8107a5dd: setup_local_APIC (STB_LOCAL)
ffffffff81c9d968-ffffffff81c9d9ef: setup_local_APIC.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1567
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff810894d0-ffffffff8108973a: setup_local_APIC (STB_LOCAL)
ffffffff81e4ce51-ffffffff81e4ce99: setup_local_APIC.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109d110)
Location: arch/x86/kernel/apic/apic.c:1563
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff8109d110-ffffffff8109d4ff: setup_local_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a00b0)
Location: arch/x86/kernel/apic/apic.c:1565
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff810a00b0-ffffffff810a04d9: setup_local_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1525
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff810a7720-ffffffff810a7aa1: setup_local_APIC (STB_LOCAL)
ffffffff821acea7-ffffffff821acecf: setup_local_APIC.cold (STB_LOCAL)
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
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1598
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81065800-ffffffff81065b3a: setup_local_APIC (STB_LOCAL)
ffffffff81066e8d-ffffffff81066f14: setup_local_APIC.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1598
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81055b80-ffffffff81055eba: setup_local_APIC (STB_LOCAL)
ffffffff810571ff-ffffffff81057286: setup_local_APIC.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1598
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81065cb0-ffffffff81065fea: setup_local_APIC (STB_LOCAL)
ffffffff8106733d-ffffffff810673c4: setup_local_APIC.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void setup_local_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1598
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_ap_setup
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff81067290-ffffffff810675ca: setup_local_APIC (STB_LOCAL)
ffffffff8106891d-ffffffff810689a4: setup_local_APIC.cold (STB_LOCAL)
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
