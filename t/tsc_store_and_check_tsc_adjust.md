# Function: <code>tsc_store_and_check_tsc_adjust</code>

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
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff81055520)
Location: arch/x86/kernel/tsc_sync.c:110
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff81055520-ffffffff810556c9: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff81054e40)
Location: arch/x86/kernel/tsc_sync.c:105
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff81054e40-ffffffff81054fc9: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff81058c30)
Location: arch/x86/kernel/tsc_sync.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff81058c30-ffffffff81058da2: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff8105bf57-ffffffff8105bfb0: tsc_store_and_check_tsc_adjust.cold.5 (STB_LOCAL)
ffffffff8105bb30-ffffffff8105bc6b: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff81061c14-ffffffff81061c6d: tsc_store_and_check_tsc_adjust.cold.4 (STB_LOCAL)
ffffffff810617c0-ffffffff810618fb: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff81065285-ffffffff810652e4: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff81064ec0-ffffffff81064fe0: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff810658f5-ffffffff81065954: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff81065530-ffffffff81065650: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff8106c248-ffffffff8106c29f: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff8106be70-ffffffff8106bf96: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff81bd6b8f-ffffffff81bd6be6: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff8106d750-ffffffff8106d876: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff81bc8d6a-ffffffff81bc8dbc: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff8106e1c0-ffffffff8106e2ef: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff81c9d74c-ffffffff81c9d7ed: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff81079a60-ffffffff81079bf1: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff81e4cba5-ffffffff81e4cc47: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff81088870-ffffffff81088a16: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff82053bee-ffffffff82053c2d: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff8109c390-ffffffff8109c5b6: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff820d21df-ffffffff820d221e: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff8109f4d0-ffffffff8109f6f6: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:180
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff821ace43-ffffffff821ace82: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff810a6960-ffffffff810a6b86: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
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
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff810653e5-ffffffff81065444: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff81065020-ffffffff81065140: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff81055735-ffffffff8105578c: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff81055320-ffffffff81055482: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff81065895-ffffffff810658f4: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff810654d0-ffffffff810655f0: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool tsc_store_and_check_tsc_adjust(bool bootcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
**Symbols:**

```
ffffffff81066e75-ffffffff81066ed4: tsc_store_and_check_tsc_adjust.cold (STB_LOCAL)
ffffffff81066ab0-ffffffff81066bd0: tsc_store_and_check_tsc_adjust (STB_GLOBAL)
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
