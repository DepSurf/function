# Function: <code>hpet_mask_rtc_irq_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81062d80)
Location: arch/x86/kernel/hpet.c:1135
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff81062d80-ffffffff81062de3: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81062a20)
Location: arch/x86/kernel/hpet.c:1132
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff81062a20-ffffffff81062a83: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81065a00)
Location: arch/x86/kernel/hpet.c:1227
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff81065a00-ffffffff81065a63: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064bb0)
Location: arch/x86/kernel/hpet.c:1222
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff81064bb0-ffffffff81064c13: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81068d40)
Location: arch/x86/kernel/hpet.c:1222
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff81068d40-ffffffff81068da3: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106b770)
Location: arch/x86/kernel/hpet.c:1222
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff8106b770-ffffffff8106b7c8: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81071580)
Location: arch/x86/kernel/hpet.c:1218
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff81071580-ffffffff810715d8: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81075400)
Location: arch/x86/kernel/hpet.c:1134
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff81075400-ffffffff81075459: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810763d0)
Location: arch/x86/kernel/hpet.c:1134
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff810763d0-ffffffff81076429: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d670)
Location: arch/x86/kernel/hpet.c:1134
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff8107d670-ffffffff8107d6c9: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d5e0)
Location: arch/x86/kernel/hpet.c:1244
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff8107d5e0-ffffffff8107d639: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107e5a0)
Location: arch/x86/kernel/hpet.c:1244
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff8107e5a0-ffffffff8107e5f9: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8108d171)
Location: arch/x86/kernel/hpet.c:1325
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff81c9eea4-ffffffff81c9eece: hpet_mask_rtc_irq_bit.cold (STB_LOCAL)
ffffffff8108d110-ffffffff8108d190: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8109de69)
Location: arch/x86/kernel/hpet.c:1325
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff81e4e31a-ffffffff81e4e344: hpet_mask_rtc_irq_bit.cold (STB_LOCAL)
ffffffff8109de20-ffffffff8109deb0: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b5099)
Location: arch/x86/kernel/hpet.c:1325
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff8205430f-ffffffff82054339: hpet_mask_rtc_irq_bit.cold (STB_LOCAL)
ffffffff810b5050-ffffffff810b50e0: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b8169)
Location: arch/x86/kernel/hpet.c:1327
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff820d28d0-ffffffff820d28fa: hpet_mask_rtc_irq_bit.cold (STB_LOCAL)
ffffffff810b8120-ffffffff810b81b0: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810bf5a9)
Location: arch/x86/kernel/hpet.c:1327
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff821ad736-ffffffff821ad760: hpet_mask_rtc_irq_bit.cold (STB_LOCAL)
ffffffff810bf560-ffffffff810bf5f0: hpet_mask_rtc_irq_bit (STB_GLOBAL)
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
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810753d0)
Location: arch/x86/kernel/hpet.c:1134
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff810753d0-ffffffff81075429: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81065490)
Location: arch/x86/kernel/hpet.c:1134
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff81065490-ffffffff810654e9: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81075380)
Location: arch/x86/kernel/hpet.c:1134
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff81075380-ffffffff810753d9: hpet_mask_rtc_irq_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int hpet_mask_rtc_irq_bit(long unsigned int bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810773e0)
Location: arch/x86/kernel/hpet.c:1134
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
```
**Symbols:**

```
ffffffff810773e0-ffffffff81077439: hpet_mask_rtc_irq_bit (STB_GLOBAL)
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
