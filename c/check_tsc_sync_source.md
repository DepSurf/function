# Function: <code>check_tsc_sync_source</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff81052a10)
Location: arch/x86/kernel/tsc_sync.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81052a10-ffffffff81052b6d: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff81052b30)
Location: arch/x86/kernel/tsc_sync.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81052b30-ffffffff81052c8f: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff810556d0)
Location: arch/x86/kernel/tsc_sync.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff810556d0-ffffffff8105589c: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff81054fd0)
Location: arch/x86/kernel/tsc_sync.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81054fd0-ffffffff810551a2: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff81058db0)
Location: arch/x86/kernel/tsc_sync.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81058db0-ffffffff81058f7a: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8105bfb0-ffffffff8105c008: check_tsc_sync_source.cold.6 (STB_LOCAL)
ffffffff8105bc70-ffffffff8105bdeb: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81061c6d-ffffffff81061c7e: check_tsc_sync_source.cold.5 (STB_LOCAL)
ffffffff81061900-ffffffff81061ac2: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff810652e4-ffffffff8106533c: check_tsc_sync_source.cold (STB_LOCAL)
ffffffff81064fe0-ffffffff8106514a: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81065954-ffffffff810659ac: check_tsc_sync_source.cold (STB_LOCAL)
ffffffff81065650-ffffffff810657ba: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:309
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8106c29f-ffffffff8106c2f7: check_tsc_sync_source.cold (STB_LOCAL)
ffffffff8106bfa0-ffffffff8106c10a: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:309
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81bd6be6-ffffffff81bd6c3e: check_tsc_sync_source.cold (STB_LOCAL)
ffffffff8106d880-ffffffff8106d9ea: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:309
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81bc8dbc-ffffffff81bc8e14: check_tsc_sync_source.cold (STB_LOCAL)
ffffffff8106e2f0-ffffffff8106e45a: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:350
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81c9d7ed-ffffffff81c9d845: check_tsc_sync_source.cold (STB_LOCAL)
ffffffff81079c00-ffffffff81079d8b: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:350
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81e4cc47-ffffffff81e4cc9d: check_tsc_sync_source.cold (STB_LOCAL)
ffffffff81088a20-ffffffff81088bcb: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c5d0)
Location: arch/x86/kernel/tsc_sync.c:350
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8109c5d0-ffffffff8109c7cd: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void check_tsc_sync_source(void *__cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f0e0)
Location: arch/x86/kernel/tsc_sync.c:348
Inline: False
```
**Symbols:**

```
ffffffff8109f0e0-ffffffff8109f2a7: check_tsc_sync_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void check_tsc_sync_source(void *__cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6560)
Location: arch/x86/kernel/tsc_sync.c:356
Inline: False
```
**Symbols:**

```
ffffffff810a6560-ffffffff810a6733: check_tsc_sync_source (STB_LOCAL)
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
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81065444-ffffffff8106549c: check_tsc_sync_source.cold (STB_LOCAL)
ffffffff81065140-ffffffff810652aa: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8105578c-ffffffff810557e4: check_tsc_sync_source.cold (STB_LOCAL)
ffffffff81055490-ffffffff810555fa: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff810658f4-ffffffff8106594c: check_tsc_sync_source.cold (STB_LOCAL)
ffffffff810655f0-ffffffff8106575a: check_tsc_sync_source (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void check_tsc_sync_source(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81066ed4-ffffffff81066f2c: check_tsc_sync_source.cold (STB_LOCAL)
ffffffff81066bd0-ffffffff81066d3a: check_tsc_sync_source (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *__cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
</ul>
</details>
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
