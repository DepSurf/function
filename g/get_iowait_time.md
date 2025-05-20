# Function: <code>get_iowait_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 get_iowait_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff81282c50)
Location: fs/proc/stat.c:62
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81282c50-ffffffff81282ca8: get_iowait_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 get_iowait_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff812afcd0)
Location: fs/proc/stat.c:62
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812afcd0-ffffffff812afd21: get_iowait_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 get_iowait_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff812c5690)
Location: fs/proc/stat.c:62
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812c5690-ffffffff812c56e1: get_iowait_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 get_iowait_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff812d28c0)
Location: fs/proc/stat.c:63
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812d28c0-ffffffff812d290c: get_iowait_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 get_iowait_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff812f7100)
Location: fs/proc/stat.c:64
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812f7100-ffffffff812f714c: get_iowait_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 get_iowait_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff813244a0)
Location: fs/proc/stat.c:64
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff813244a0-ffffffff813244ec: get_iowait_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 get_iowait_time(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff8133b640)
Location: fs/proc/stat.c:64
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8133b640-ffffffff8133b68c: get_iowait_time (STB_LOCAL)
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
In fs/proc/stat.c (ffffffff813637f0)
Location: fs/proc/stat.c:64
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff813637f0-ffffffff81363829: get_iowait_time.isra.0 (STB_LOCAL)
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
In fs/proc/stat.c (ffffffff8137bad0)
Location: fs/proc/stat.c:64
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8137bad0-ffffffff8137bb09: get_iowait_time.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 get_iowait_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff813c5240)
Location: fs/proc/stat.c:64
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff813c5240-ffffffff813c5280: get_iowait_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 get_iowait_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff813d7190)
Location: fs/proc/stat.c:65
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff813d7190-ffffffff813d71d0: get_iowait_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 get_iowait_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff813de0b0)
Location: fs/proc/stat.c:65
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff813de0b0-ffffffff813de0f0: get_iowait_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 get_iowait_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff8142f850)
Location: fs/proc/stat.c:65
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8142f850-ffffffff8142f890: get_iowait_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 get_iowait_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff814a9490)
Location: fs/proc/stat.c:65
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff814a9490-ffffffff814a94e0: get_iowait_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 get_iowait_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff8153ef60)
Location: fs/proc/stat.c:65
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8153ef60-ffffffff8153efb0: get_iowait_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 get_iowait_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff815772b0)
Location: fs/proc/stat.c:41
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff815772b0-ffffffff81577300: get_iowait_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 get_iowait_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff815afbc0)
Location: fs/proc/stat.c:41
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff815afbc0-ffffffff815afc10: get_iowait_time (STB_LOCAL)
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
In fs/proc/stat.c (ffff800010448290)
Location: fs/proc/stat.c:64
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffff800010448290-ffff800010448314: get_iowait_time.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 get_iowait_time(struct kernel_cpustat *kcs, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (c060d118)
Location: fs/proc/stat.c:64
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
c060d118-c060d1cc: get_iowait_time (STB_LOCAL)
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
In fs/proc/stat.c (c00000000055e7c0)
Location: fs/proc/stat.c:64
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
c00000000055e7c0-c00000000055e86c: get_iowait_time.isra.0 (STB_LOCAL)
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
In fs/proc/stat.c (ffffffe0002dde10)
Location: fs/proc/stat.c:64
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffe0002dde10-ffffffe0002dde84: get_iowait_time.isra.0 (STB_LOCAL)
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
In fs/proc/stat.c (ffffffff813740b0)
Location: fs/proc/stat.c:64
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff813740b0-ffffffff813740e9: get_iowait_time.isra.0 (STB_LOCAL)
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
In fs/proc/stat.c (ffffffff81364b80)
Location: fs/proc/stat.c:64
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81364b80-ffffffff81364bb9: get_iowait_time.isra.0 (STB_LOCAL)
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
In fs/proc/stat.c (ffffffff81371b80)
Location: fs/proc/stat.c:64
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81371b80-ffffffff81371bb9: get_iowait_time.isra.0 (STB_LOCAL)
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
In fs/proc/stat.c (ffffffff81385560)
Location: fs/proc/stat.c:64
Inline: True
Direct callers:
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81385560-ffffffff81385599: get_iowait_time.isra.0 (STB_LOCAL)
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
