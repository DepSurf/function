# Function: <code>__show_regs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __show_regs(struct pt_regs *regs, int all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d160)
Location: arch/x86/kernel/process_64.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:show_regs
```
**Symbols:**

```
ffffffff8102d160-ffffffff8102d3ed: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __show_regs(struct pt_regs *regs, int all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c160)
Location: arch/x86/kernel/process_64.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:show_regs
```
**Symbols:**

```
ffffffff8102c160-ffffffff8102c3f9: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __show_regs(struct pt_regs *regs, int all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c130)
Location: arch/x86/kernel/process_64.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff8102c130-ffffffff8102c3e6: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __show_regs(struct pt_regs *regs, int all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102a320)
Location: arch/x86/kernel/process_64.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff8102a320-ffffffff8102a5d6: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __show_regs(struct pt_regs *regs, int all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102b0d0)
Location: arch/x86/kernel/process_64.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:show_regs
```
**Symbols:**

```
ffffffff8102b0d0-ffffffff8102b337: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff8102ce66-ffffffff8102d0da: __show_regs.cold.4 (STB_LOCAL)
ffffffff8102c360-ffffffff8102c394: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff8102e0b6-ffffffff8102e32e: __show_regs.cold.7 (STB_LOCAL)
ffffffff8102d4e0-ffffffff8102d514: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff8102fe16-ffffffff8103008e: __show_regs.cold (STB_LOCAL)
ffffffff8102f2d0-ffffffff8102f304: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81030776-ffffffff810309ee: __show_regs.cold (STB_LOCAL)
ffffffff8102fc30-ffffffff8102fc64: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die_body
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81032da6-ffffffff81033004: __show_regs.cold (STB_LOCAL)
ffffffff810324d0-ffffffff81032504: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die_body
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81bd2faf-ffffffff81bd3236: __show_regs.cold (STB_LOCAL)
ffffffff81032fd0-ffffffff8103300a: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die_body
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81bc539f-ffffffff81bc5623: __show_regs.cold (STB_LOCAL)
ffffffff81034a60-ffffffff81034a9a: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die_body
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81c97fbf-ffffffff81c9823a: __show_regs.cold (STB_LOCAL)
ffffffff81039d60-ffffffff81039d9a: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die_body
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81e47435-ffffffff81e476d5: __show_regs.cold (STB_LOCAL)
ffffffff81040d00-ffffffff81040d3b: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104a0b0)
Location: arch/x86/kernel/process_64.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff8104a0b0-ffffffff8104a3ee: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104a8f0)
Location: arch/x86/kernel/process_64.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff8104a8f0-ffffffff8104ac2e: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81051b60)
Location: arch/x86/kernel/process_64.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81051b60-ffffffff81051e9e: __show_regs (STB_GLOBAL)
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
void __show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/process.c (ffff800010089958)
Location: arch/arm64/kernel/process.c:245
Inline: False
Direct callers:
  - arch/arm64/kernel/process.c:show_regs
  - arch/arm64/kernel/traps.c:arm64_serror_panic
  - arch/arm64/kernel/traps.c:handle_bad_stack
  - arch/arm64/kernel/traps.c:arm64_show_signal
```
**Symbols:**

```
ffff800010089958-ffff800010089c30: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/process.c (c030afd4)
Location: arch/arm/kernel/process.c:93
Inline: False
Direct callers:
  - arch/arm/kernel/process.c:show_regs
  - arch/arm/kernel/traps.c:die
```
**Symbols:**

```
c030afd4-c030b220: __show_regs (STB_GLOBAL)
```
</details>
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
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff810308d6-ffffffff81030b4e: __show_regs.cold (STB_LOCAL)
ffffffff8102fd90-ffffffff8102fdc4: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81020366-ffffffff81020575: __show_regs.cold (STB_LOCAL)
ffffffff8101f7b0-ffffffff8101f7e4: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81030736-ffffffff810309ae: __show_regs.cold (STB_LOCAL)
ffffffff8102fbf0-ffffffff8102fc24: __show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __show_regs(struct pt_regs *regs, enum show_regs_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff810315c6-ffffffff8103183e: __show_regs.cold (STB_LOCAL)
ffffffff81030a40-ffffffff81030a74: __show_regs (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum show_regs_mode mode</code>
</li>
<li>
<b>Param removed. </b>
<code>int all</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *log_lvl</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum show_regs_mode mode</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum show_regs_mode mode</code>
</li>
</ul>
</details>
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
