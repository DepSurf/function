# Function: <code>dbg_deactivate_sw_breakpoints</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8112fbf0)
Location: kernel/debug/debug_core.c:314
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8112fbf0-ffffffff8112fc5e: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81137ef0)
Location: kernel/debug/debug_core.c:314
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81137ef0-ffffffff81137f68: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81141c80)
Location: kernel/debug/debug_core.c:314
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81141c80-ffffffff81141cf8: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811434c0)
Location: kernel/debug/debug_core.c:315
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff811434c0-ffffffff81143538: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81150170)
Location: kernel/debug/debug_core.c:315
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81150170-ffffffff811501e8: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:315
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8115f8d7-ffffffff8115f8ea: dbg_deactivate_sw_breakpoints.cold.20 (STB_LOCAL)
ffffffff8115ed20-ffffffff8115ed8c: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:372
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8116c647-ffffffff8116c65a: dbg_deactivate_sw_breakpoints.cold.20 (STB_LOCAL)
ffffffff8116ba50-ffffffff8116babc: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:372
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8117947b-ffffffff81179492: dbg_deactivate_sw_breakpoints.cold (STB_LOCAL)
ffffffff81178860-ffffffff811788da: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:372
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8118530b-ffffffff81185322: dbg_deactivate_sw_breakpoints.cold (STB_LOCAL)
ffffffff811846b0-ffffffff8118472a: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:370
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_reenter_check
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81199446-ffffffff8119945d: dbg_deactivate_sw_breakpoints.cold (STB_LOCAL)
ffffffff81198710-ffffffff8119876e: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:374
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81be4b1c-ffffffff81be4b33: dbg_deactivate_sw_breakpoints.cold (STB_LOCAL)
ffffffff811954d0-ffffffff8119552e: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:373
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81bd698f-ffffffff81bd69a6: dbg_deactivate_sw_breakpoints.cold (STB_LOCAL)
ffffffff811964c0-ffffffff8119651e: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811bf710)
Location: kernel/debug/debug_core.c:370
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff811bf710-ffffffff811bf893: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811f2d40)
Location: kernel/debug/debug_core.c:371
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_reenter_check
```
**Symbols:**

```
ffffffff811f2d40-ffffffff811f2ece: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff812396e0)
Location: kernel/debug/debug_core.c:359
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_reenter_check
```
**Symbols:**

```
ffffffff812396e0-ffffffff812397f9: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff812506f0)
Location: kernel/debug/debug_core.c:359
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_reenter_check
```
**Symbols:**

```
ffffffff812506f0-ffffffff81250809: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8126a540)
Location: kernel/debug/debug_core.c:359
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_reenter_check
```
**Symbols:**

```
ffffffff8126a540-ffffffff8126a659: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
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
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffff8000101fa030)
Location: kernel/debug/debug_core.c:372
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffff8000101fa030-ffff8000101fa0d8: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c043a0cc)
Location: kernel/debug/debug_core.c:372
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
c043a0cc-c043a15c: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c000000000271930)
Location: kernel/debug/debug_core.c:372
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
c000000000271930-c000000000271a14: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
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
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:372
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8117d92b-ffffffff8117d942: dbg_deactivate_sw_breakpoints.cold (STB_LOCAL)
ffffffff8117ccd0-ffffffff8117cd4a: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:372
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff81170a7b-ffffffff81170a92: dbg_deactivate_sw_breakpoints.cold (STB_LOCAL)
ffffffff8116fe50-ffffffff8116feca: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:372
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8117b6fb-ffffffff8117b712: dbg_deactivate_sw_breakpoints.cold (STB_LOCAL)
ffffffff8117aaa0-ffffffff8117ab1a: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dbg_deactivate_sw_breakpoints();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:372
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
**Symbols:**

```
ffffffff8118901b-ffffffff81189032: dbg_deactivate_sw_breakpoints.cold (STB_LOCAL)
ffffffff811883d0-ffffffff8118844a: dbg_deactivate_sw_breakpoints (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
