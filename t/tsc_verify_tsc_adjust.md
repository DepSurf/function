# Function: <code>tsc_verify_tsc_adjust</code>

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
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff81055460)
Location: arch/x86/kernel/tsc_sync.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81055460-ffffffff81055513: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff81054d80)
Location: arch/x86/kernel/tsc_sync.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81054d80-ffffffff81054e35: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff81058b70)
Location: arch/x86/kernel/tsc_sync.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81058b70-ffffffff81058c2f: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff8105bf34-ffffffff8105bf57: tsc_verify_tsc_adjust.cold.4 (STB_LOCAL)
ffffffff8105ba80-ffffffff8105bb2d: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff81061700)
Location: arch/x86/kernel/tsc_sync.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81061700-ffffffff810617bf: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
```
**Symbols:**

```
ffffffff81065262-ffffffff81065285: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff81064e10-ffffffff81064ebd: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
```
**Symbols:**

```
ffffffff810658d2-ffffffff810658f5: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff81065480-ffffffff8106552d: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
```
**Symbols:**

```
ffffffff8106c225-ffffffff8106c248: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff8106bdc0-ffffffff8106be6d: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
```
**Symbols:**

```
ffffffff81bd6b6c-ffffffff81bd6b8f: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff8106d6a0-ffffffff8106d74d: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
```
**Symbols:**

```
ffffffff81bc8d47-ffffffff81bc8d6a: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff8106e110-ffffffff8106e1bd: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
**Symbols:**

```
ffffffff81c9d714-ffffffff81c9d74c: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff81079940-ffffffff810799fc: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
**Symbols:**

```
ffffffff81e4cb6d-ffffffff81e4cba5: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff81088700-ffffffff81088802: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
**Symbols:**

```
ffffffff82053bd9-ffffffff82053bee: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff8109c1e0-ffffffff8109c2fc: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
**Symbols:**

```
ffffffff820d21ca-ffffffff820d21df: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff8109f320-ffffffff8109f43c: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
**Symbols:**

```
ffffffff821ace2e-ffffffff821ace43: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff810a67b0-ffffffff810a68cc: tsc_verify_tsc_adjust (STB_GLOBAL)
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
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
```
**Symbols:**

```
ffffffff810653c2-ffffffff810653e5: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff81064f70-ffffffff8106501d: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81055712-ffffffff81055735: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff81055250-ffffffff8105531f: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
```
**Symbols:**

```
ffffffff81065872-ffffffff81065895: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff81065420-ffffffff810654cd: tsc_verify_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void tsc_verify_tsc_adjust(bool resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_resume
  - arch/x86/kernel/process.c:arch_cpu_idle_enter
```
**Symbols:**

```
ffffffff81066e52-ffffffff81066e75: tsc_verify_tsc_adjust.cold (STB_LOCAL)
ffffffff81066a00-ffffffff81066aad: tsc_verify_tsc_adjust (STB_GLOBAL)
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
