# Function: <code>show_opcodes</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031e23)
Location: arch/x86/kernel/dumpstack.c:95
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_ip
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81031e23-ffffffff81031f04: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_ip
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81033193-ffffffff810331c9: show_opcodes.cold.11 (STB_LOCAL)
ffffffff81033070-ffffffff810330df: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_ip
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81034ff5-ffffffff8103503d: show_opcodes.cold (STB_LOCAL)
ffffffff81034e80-ffffffff81034ee4: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_ip
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81035825-ffffffff8103586d: show_opcodes.cold (STB_LOCAL)
ffffffff810356b0-ffffffff81035714: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:109
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_ip
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810378d2-ffffffff8103791b: show_opcodes.cold (STB_LOCAL)
ffffffff810375c0-ffffffff81037656: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_ip
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81bd34ae-ffffffff81bd34cd: show_opcodes.cold (STB_LOCAL)
ffffffff810385e0-ffffffff810386ca: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_ip
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81bc5921-ffffffff81bc5940: show_opcodes.cold (STB_LOCAL)
ffffffff8103a120-ffffffff8103a1ed: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_ip
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81c9866b-ffffffff81c9868a: show_opcodes.cold (STB_LOCAL)
ffffffff8103fad0-ffffffff8103fb9d: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_ip
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81e47b9a-ffffffff81e47bb9: show_opcodes.cold (STB_LOCAL)
ffffffff81047250-ffffffff81047325: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810514c0)
Location: arch/x86/kernel/dumpstack.c:113
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810514c0-ffffffff810515af: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81052220)
Location: arch/x86/kernel/dumpstack.c:113
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81052220-ffffffff8105230f: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81059440)
Location: arch/x86/kernel/dumpstack.c:113
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81059440-ffffffff8105952f: show_opcodes (STB_GLOBAL)
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
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_ip
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81035985-ffffffff810359cd: show_opcodes.cold (STB_LOCAL)
ffffffff81035810-ffffffff81035874: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_ip
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810252d5-ffffffff8102531d: show_opcodes.cold (STB_LOCAL)
ffffffff81025160-ffffffff810251c4: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_ip
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810357e5-ffffffff8103582d: show_opcodes.cold (STB_LOCAL)
ffffffff81035670-ffffffff810356d4: show_opcodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void show_opcodes(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_ip
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810367c5-ffffffff8103680d: show_opcodes.cold (STB_LOCAL)
ffffffff81036650-ffffffff810366b4: show_opcodes (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
