# Function: <code>play_idle</code>

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
void play_idle(long unsigned int duration_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810cdb00)
Location: kernel/sched/idle.c:290
Inline: False
```
**Symbols:**

```
ffffffff810cdb00-ffffffff810cdcf5: play_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void play_idle(long unsigned int duration_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810ca510)
Location: kernel/sched/idle.c:296
Inline: False
```
**Symbols:**

```
ffffffff810ca510-ffffffff810ca656: play_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void play_idle(long unsigned int duration_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d1d20)
Location: kernel/sched/idle.c:296
Inline: False
```
**Symbols:**

```
ffffffff810d1d20-ffffffff810d1e66: play_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void play_idle(long unsigned int duration_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c44b0)
Location: kernel/sched/idle.c:313
Inline: False
```
**Symbols:**

```
ffffffff810c44b0-ffffffff810c45f6: play_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void play_idle(long unsigned int duration_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810cd770)
Location: kernel/sched/idle.c:313
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffffffff810cd770-ffffffff810cd8b6: play_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void play_idle(long unsigned int duration_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d5b60)
Location: kernel/sched/idle.c:314
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffffffff810d5b60-ffffffff810d5ca6: play_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void play_idle(long unsigned int duration_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e0160)
Location: kernel/sched/idle.c:314
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffffffff810e0160-ffffffff810e02a6: play_idle (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void play_idle(long unsigned int duration_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffff80001013fe80)
Location: kernel/sched/idle.c:314
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffff80001013fe80-ffff80001013ffe4: play_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void play_idle(long unsigned int duration_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c038fdcc)
Location: kernel/sched/idle.c:314
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
c038fdcc-c0390054: play_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void play_idle(long unsigned int duration_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c00000000018f070)
Location: kernel/sched/idle.c:314
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
c00000000018f070-c00000000018f230: play_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void play_idle(long unsigned int duration_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffe0000ee070)
Location: kernel/sched/idle.c:314
Inline: False
```
**Symbols:**

```
ffffffe0000ee070-ffffffe0000ee14e: play_idle (STB_GLOBAL)
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
void play_idle(long unsigned int duration_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810da310)
Location: kernel/sched/idle.c:314
Inline: False
```
**Symbols:**

```
ffffffff810da310-ffffffff810da456: play_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void play_idle(long unsigned int duration_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c9320)
Location: kernel/sched/idle.c:314
Inline: False
```
**Symbols:**

```
ffffffff810c9320-ffffffff810c9466: play_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void play_idle(long unsigned int duration_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d6690)
Location: kernel/sched/idle.c:314
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffffffff810d6690-ffffffff810d67d6: play_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void play_idle(long unsigned int duration_us);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e1f90)
Location: kernel/sched/idle.c:314
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_fn
```
**Symbols:**

```
ffffffff810e1f90-ffffffff810e20ed: play_idle (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int duration_us</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int duration_ms</code>
</li>
</ul>
</details>
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
