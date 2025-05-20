# Function: <code>sev_es_init_vc_handling</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sev_es_init_vc_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff82fd121d)
Location: arch/x86/kernel/sev-es.c:685
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
```
**Symbols:**

```
ffffffff82fd121d-ffffffff82fd1328: sev_es_init_vc_handling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sev_es_init_vc_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff831dbe24)
Location: arch/x86/kernel/sev.c:764
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
```
**Symbols:**

```
ffffffff831dbe24-ffffffff831dbfea: sev_es_init_vc_handling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sev_es_init_vc_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff832bef3d)
Location: arch/x86/kernel/sev.c:761
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
```
**Symbols:**

```
ffffffff832bef3d-ffffffff832bf07b: sev_es_init_vc_handling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sev_es_init_vc_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff8347120f)
Location: arch/x86/kernel/sev.c:1373
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
```
**Symbols:**

```
ffffffff8347120f-ffffffff834713d3: sev_es_init_vc_handling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sev_es_init_vc_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83e98230)
Location: arch/x86/kernel/sev.c:1373
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
```
**Symbols:**

```
ffffffff83e98230-ffffffff83e9846f: sev_es_init_vc_handling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sev_es_init_vc_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff836bbc90)
Location: arch/x86/kernel/sev.c:1333
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
```
**Symbols:**

```
ffffffff836bbc90-ffffffff836bbec1: sev_es_init_vc_handling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sev_es_init_vc_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff838ec670)
Location: arch/x86/kernel/sev.c:1362
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
```
**Symbols:**

```
ffffffff838ec670-ffffffff838ec8a1: sev_es_init_vc_handling (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
