# Function: <code>perf_callchain_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810075e0)
Location: arch/x86/events/core.c:2185
Inline: False
```
**Symbols:**

```
ffffffff810075e0-ffffffff81007640: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007760)
Location: arch/x86/events/core.c:2273
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81007760-ffffffff810077cf: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007760)
Location: arch/x86/events/core.c:2280
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81007760-ffffffff81007864: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810074f0)
Location: arch/x86/events/core.c:2302
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff810074f0-ffffffff810075f1: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007920)
Location: arch/x86/events/core.c:2337
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81007920-ffffffff81007a27: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007f50)
Location: arch/x86/events/core.c:2343
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81007f50-ffffffff81008052: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007e30)
Location: arch/x86/events/core.c:2359
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81007e30-ffffffff81007f32: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810080f0)
Location: arch/x86/events/core.c:2321
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff810080f0-ffffffff81008223: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008310)
Location: arch/x86/events/core.c:2410
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81008310-ffffffff81008443: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009380)
Location: arch/x86/events/core.c:2423
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81009380-ffffffff810094b1: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008430)
Location: arch/x86/events/core.c:2534
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81008430-ffffffff81008561: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008e00)
Location: arch/x86/events/core.c:2764
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81008e00-ffffffff81008f31: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:2763
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81c9539c-ffffffff81c953d4: perf_callchain_kernel.cold (STB_LOCAL)
ffffffff81009c90-ffffffff81009dec: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:2777
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81e44664-ffffffff81e4469c: perf_callchain_kernel.cold (STB_LOCAL)
ffffffff810093d0-ffffffff8100953e: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:2761
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff8205036b-ffffffff820503a3: perf_callchain_kernel.cold (STB_LOCAL)
ffffffff8100a860-ffffffff8100a9ce: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:2759
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff820ce7c9-ffffffff820ce801: perf_callchain_kernel.cold (STB_LOCAL)
ffffffff8100a0b0-ffffffff8100a21e: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:2756
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff821a9005-ffffffff821a903d: perf_callchain_kernel.cold (STB_LOCAL)
ffffffff8100f7d0-ffffffff8100f93e: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/perf_callchain.c (ffff8000100a3928)
Location: arch/arm64/kernel/perf_callchain.c:147
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffff8000100a3928-ffff8000100a39c4: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/perf_callchain.c (c0317df4)
Location: arch/arm/kernel/perf_callchain.c:99
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
c0317df4-c0317ea4: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/perf/callchain.c (c000000000125540)
Location: arch/powerpc/perf/callchain.c:47
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
c000000000125540-c0000000001257d4: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/perf_callchain.c (ffffffe0000b99dc)
Location: arch/riscv/kernel/perf_callchain.c:84
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffe0000b99dc-ffffffe0000b9a3a: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008310)
Location: arch/x86/events/core.c:2410
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81008310-ffffffff81008443: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006b00)
Location: arch/x86/events/core.c:2410
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81006b00-ffffffff81006c33: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810082d0)
Location: arch/x86/events/core.c:2410
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff810082d0-ffffffff81008403: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_callchain_kernel(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008430)
Location: arch/x86/events/core.c:2410
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81008430-ffffffff81008563: perf_callchain_kernel (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct perf_callchain_entry *entry</code> ➡️ <code>struct perf_callchain_entry_ctx *entry</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
