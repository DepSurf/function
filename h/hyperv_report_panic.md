# Function: <code>hyperv_report_panic</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102bc50)
Location: arch/x86/hyperv/hv_init.c:245
Inline: True
```
**Symbols:**

```
ffffffff8102bc50-ffffffff8102bcf9: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81029f30)
Location: arch/x86/hyperv/hv_init.c:226
Inline: True
```
**Symbols:**

```
ffffffff81029f30-ffffffff81029fda: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102a110)
Location: arch/x86/hyperv/hv_init.c:221
Inline: True
```
**Symbols:**

```
ffffffff8102a110-ffffffff8102a1d5: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102ad10)
Location: arch/x86/hyperv/hv_init.c:408
Inline: True
```
**Symbols:**

```
ffffffff8102ad10-ffffffff8102add4: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102b260)
Location: arch/x86/hyperv/hv_init.c:427
Inline: True
```
**Symbols:**

```
ffffffff8102b260-ffffffff8102b324: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102cf90)
Location: arch/x86/hyperv/hv_init.c:353
Inline: True
```
**Symbols:**

```
ffffffff8102cf90-ffffffff8102d054: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102d8a0)
Location: arch/x86/hyperv/hv_init.c:365
Inline: True
```
**Symbols:**

```
ffffffff8102d8a0-ffffffff8102d964: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err, bool in_die);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102fd70)
Location: arch/x86/hyperv/hv_init.c:453
Inline: True
```
**Symbols:**

```
ffffffff8102fd70-ffffffff8102fe2a: hyperv_report_panic.part.0 (STB_LOCAL)
ffffffff8102fe30-ffffffff8102fe58: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err, bool in_die);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff810309a0)
Location: arch/x86/hyperv/hv_init.c:480
Inline: True
```
**Symbols:**

```
ffffffff810309a0-ffffffff81030a5a: hyperv_report_panic.part.0 (STB_LOCAL)
ffffffff81030a60-ffffffff81030a88: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err, bool in_die);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff810314a0)
Location: arch/x86/hyperv/hv_init.c:552
Inline: True
```
**Symbols:**

```
ffffffff810314a0-ffffffff81031578: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err, bool in_die);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81036631)
Location: arch/x86/hyperv/hv_init.c:503
Inline: True
```
**Symbols:**

```
ffffffff81c97dd2-ffffffff81c97de7: hyperv_report_panic.cold (STB_LOCAL)
ffffffff810365f0-ffffffff810366d7: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err, bool in_die);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8103c57b)
Location: arch/x86/hyperv/hv_init.c:571
Inline: True
```
**Symbols:**

```
ffffffff81e47213-ffffffff81e47228: hyperv_report_panic.cold (STB_LOCAL)
ffffffff8103c520-ffffffff8103c634: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err, bool in_die);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8104515b)
Location: arch/x86/hyperv/hv_init.c:562
Inline: True
```
**Symbols:**

```
ffffffff82051eab-ffffffff82051ec0: hyperv_report_panic.cold (STB_LOCAL)
ffffffff81045100-ffffffff81045214: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err, bool in_die);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8104529b)
Location: arch/x86/hyperv/hv_init.c:575
Inline: True
Direct callers:
  - drivers/hv/hv_common.c:hv_die_panic_notify_crash
```
**Symbols:**

```
ffffffff820d0320-ffffffff820d0335: hyperv_report_panic.cold (STB_LOCAL)
ffffffff81045240-ffffffff81045354: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err, bool in_die);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8104b8fb)
Location: arch/x86/hyperv/hv_init.c:680
Inline: True
Direct callers:
  - drivers/hv/hv_common.c:hv_die_panic_notify_crash
```
**Symbols:**

```
ffffffff821aacb7-ffffffff821aaccc: hyperv_report_panic.cold (STB_LOCAL)
ffffffff8104b8a0-ffffffff8104b9b4: hyperv_report_panic (STB_GLOBAL)
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
void hyperv_report_panic(struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102da00)
Location: arch/x86/hyperv/hv_init.c:365
Inline: True
```
**Symbols:**

```
ffffffff8102da00-ffffffff8102dac4: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8101d390)
Location: arch/x86/hyperv/hv_init.c:365
Inline: True
Direct callers:
  - drivers/hv/vmbus_drv.c:hyperv_die_event
  - drivers/hv/vmbus_drv.c:hyperv_panic_event
```
**Symbols:**

```
ffffffff8101d390-ffffffff8101d4ee: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102d860)
Location: arch/x86/hyperv/hv_init.c:365
Inline: True
```
**Symbols:**

```
ffffffff8102d860-ffffffff8102d924: hyperv_report_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void hyperv_report_panic(struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102e650)
Location: arch/x86/hyperv/hv_init.c:365
Inline: True
```
**Symbols:**

```
ffffffff8102e650-ffffffff8102e714: hyperv_report_panic (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long int err</code>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool in_die</code>
</li>
</ul>
</details>
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
