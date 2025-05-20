# Function: <code>get_idle_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 get_idle_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff81282bf0)
Location: fs/proc/stat.c:46
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81282bf0-ffffffff81282c48: get_idle_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 get_idle_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff812afc70)
Location: fs/proc/stat.c:46
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812afc70-ffffffff812afcc1: get_idle_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 get_idle_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff812c5630)
Location: fs/proc/stat.c:46
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812c5630-ffffffff812c5681: get_idle_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 get_idle_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff812d2870)
Location: fs/proc/stat.c:47
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812d2870-ffffffff812d28bc: get_idle_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 get_idle_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff812f70b0)
Location: fs/proc/stat.c:48
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812f70b0-ffffffff812f70fc: get_idle_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 get_idle_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff81324450)
Location: fs/proc/stat.c:48
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81324450-ffffffff8132449c: get_idle_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 get_idle_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff8133b5f0)
Location: fs/proc/stat.c:48
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8133b5f0-ffffffff8133b63c: get_idle_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/stat.c (ffffffff813637b0)
Location: fs/proc/stat.c:48
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff813637b0-ffffffff813637e9: get_idle_time.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/stat.c (ffffffff8137ba90)
Location: fs/proc/stat.c:48
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8137ba90-ffffffff8137bac9: get_idle_time.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 get_idle_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff813c5200)
Location: fs/proc/stat.c:48
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff813c5200-ffffffff813c5240: get_idle_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 get_idle_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff813d7150)
Location: fs/proc/stat.c:49
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff813d7150-ffffffff813d7190: get_idle_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 get_idle_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff813de070)
Location: fs/proc/stat.c:49
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff813de070-ffffffff813de0b0: get_idle_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 get_idle_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff8142f890)
Location: fs/proc/stat.c:49
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
```
**Symbols:**

```
ffffffff8142f890-ffffffff8142f8d0: get_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 get_idle_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff814a94e0)
Location: fs/proc/stat.c:49
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
```
**Symbols:**

```
ffffffff814a94e0-ffffffff814a9530: get_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 get_idle_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff8153efc0)
Location: fs/proc/stat.c:49
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
```
**Symbols:**

```
ffffffff8153efc0-ffffffff8153f010: get_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 get_idle_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff81577310)
Location: fs/proc/stat.c:25
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
```
**Symbols:**

```
ffffffff81577310-ffffffff81577360: get_idle_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 get_idle_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff815afc20)
Location: fs/proc/stat.c:25
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
```
**Symbols:**

```
ffffffff815afc20-ffffffff815afc70: get_idle_time (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/stat.c (ffff800010448208)
Location: fs/proc/stat.c:48
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffff800010448208-ffff80001044828c: get_idle_time.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 get_idle_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (c060d064)
Location: fs/proc/stat.c:48
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
c060d064-c060d118: get_idle_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/stat.c (c00000000055e710)
Location: fs/proc/stat.c:48
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
c00000000055e710-c00000000055e7bc: get_idle_time.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/stat.c (ffffffe0002ddd9c)
Location: fs/proc/stat.c:48
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffe0002ddd9c-ffffffe0002dde10: get_idle_time.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/stat.c (ffffffff81374070)
Location: fs/proc/stat.c:48
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81374070-ffffffff813740a9: get_idle_time.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/stat.c (ffffffff81364b40)
Location: fs/proc/stat.c:48
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81364b40-ffffffff81364b79: get_idle_time.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/stat.c (ffffffff81371b40)
Location: fs/proc/stat.c:48
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81371b40-ffffffff81371b79: get_idle_time.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/stat.c (ffffffff81385520)
Location: fs/proc/stat.c:48
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81385520-ffffffff81385559: get_idle_time.isra.0 (STB_LOCAL)
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
