# Function: <code>cpu_init_exception_handling</code>

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
void cpu_init_exception_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a530)
Location: arch/x86/kernel/cpu/common.c:1916
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8104a530-ffffffff8104a70f: cpu_init_exception_handling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpu_init_exception_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104bdc0)
Location: arch/x86/kernel/cpu/common.c:1920
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8104bdc0-ffffffff8104bfa4: cpu_init_exception_handling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpu_init_exception_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81053150)
Location: arch/x86/kernel/cpu/common.c:1960
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/cpu/common.c:cpu_init_secondary
```
**Symbols:**

```
ffffffff81053150-ffffffff810533b9: cpu_init_exception_handling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpu_init_exception_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105ebd0)
Location: arch/x86/kernel/cpu/common.c:2203
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/cpu/common.c:cpu_init_secondary
```
**Symbols:**

```
ffffffff8105ebd0-ffffffff8105ee53: cpu_init_exception_handling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpu_init_exception_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106d310)
Location: arch/x86/kernel/cpu/common.c:2205
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/cpu/common.c:cpu_init_secondary
```
**Symbols:**

```
ffffffff8106d310-ffffffff8106d5ba: cpu_init_exception_handling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpu_init_exception_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106eca0)
Location: arch/x86/kernel/cpu/common.c:2195
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8106eca0-ffffffff8106ef4a: cpu_init_exception_handling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpu_init_exception_handling();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81076000)
Location: arch/x86/kernel/cpu/common.c:2242
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81076000-ffffffff810762aa: cpu_init_exception_handling (STB_GLOBAL)
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
