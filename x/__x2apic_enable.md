# Function: <code>__x2apic_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81053170)
Location: arch/x86/kernel/apic/apic.c:1450
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:x2apic_setup
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
```
**Symbols:**

```
ffffffff81053170-ffffffff810531f7: __x2apic_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81052e20)
Location: arch/x86/kernel/apic/apic.c:1486
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff81052e20-ffffffff81052e7c: __x2apic_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81055b10)
Location: arch/x86/kernel/apic/apic.c:1488
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff81055b10-ffffffff81055b6c: __x2apic_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81055620)
Location: arch/x86/kernel/apic/apic.c:1571
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff81055620-ffffffff8105567c: __x2apic_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810597b0)
Location: arch/x86/kernel/apic/apic.c:1656
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff810597b0-ffffffff8105980c: __x2apic_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1669
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff8105ca60-ffffffff8105caaa: __x2apic_enable (STB_LOCAL)
ffffffff8105daf2-ffffffff8105db0a: __x2apic_enable.cold.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1675
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff810626f0-ffffffff8106273a: __x2apic_enable (STB_LOCAL)
ffffffff81063783-ffffffff8106379b: __x2apic_enable.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1753
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff81065d80-ffffffff81065dca: __x2apic_enable (STB_LOCAL)
ffffffff81066e40-ffffffff81066e58: __x2apic_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1810
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff810663b0-ffffffff810663fa: __x2apic_enable (STB_LOCAL)
ffffffff810674b5-ffffffff810674cd: __x2apic_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1762
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff8106cd30-ffffffff8106cd80: __x2apic_enable (STB_LOCAL)
ffffffff8106e182-ffffffff8106e19a: __x2apic_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1774
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff8106e4d0-ffffffff8106e520: __x2apic_enable (STB_LOCAL)
ffffffff81bd6edc-ffffffff81bd6ef4: __x2apic_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1775
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff8106efc0-ffffffff8106f010: __x2apic_enable (STB_LOCAL)
ffffffff81bc9096-ffffffff81bc90ae: __x2apic_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c9db04)
Location: arch/x86/kernel/apic/apic.c:1772
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff8107a9b0-ffffffff8107aa0c: __x2apic_enable (STB_LOCAL)
ffffffff81c9daf0-ffffffff81c9db1c: __x2apic_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1780
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff810899d0-ffffffff81089a5e: __x2apic_enable (STB_LOCAL)
ffffffff81e4cf77-ffffffff81e4cfa3: __x2apic_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1791
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff8109d8e0-ffffffff8109d95f: __x2apic_enable (STB_LOCAL)
ffffffff82053c2d-ffffffff82053c41: __x2apic_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a092a)
Location: arch/x86/kernel/apic/apic.c:1793
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff810a08c0-ffffffff810a093f: __x2apic_enable (STB_LOCAL)
ffffffff820d2243-ffffffff820d2257: __x2apic_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a806a)
Location: arch/x86/kernel/apic/apic.c:1754
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff810a8000-ffffffff810a807f: __x2apic_enable (STB_LOCAL)
ffffffff821acecf-ffffffff821acee3: __x2apic_enable.cold (STB_LOCAL)
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
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1810
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff81065ea0-ffffffff81065eea: __x2apic_enable (STB_LOCAL)
ffffffff81066fa5-ffffffff81066fbd: __x2apic_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1810
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff81056230-ffffffff810562a6: __x2apic_enable (STB_LOCAL)
ffffffff81057362-ffffffff8105737a: __x2apic_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1810
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff81066350-ffffffff8106639a: __x2apic_enable (STB_LOCAL)
ffffffff81067455-ffffffff8106746d: __x2apic_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __x2apic_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:1810
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/apic.c:x2apic_setup
```
**Symbols:**

```
ffffffff81067930-ffffffff8106797a: __x2apic_enable (STB_LOCAL)
ffffffff81068a35-ffffffff81068a4d: __x2apic_enable.cold (STB_LOCAL)
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
