# Function: <code>release_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d3f0)
Location: arch/x86/kernel/process_64.c:121
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8102d3f0-ffffffff8102d42e: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c400)
Location: arch/x86/kernel/process_64.c:124
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8102c400-ffffffff8102c441: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c3f0)
Location: arch/x86/kernel/process_64.c:129
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8102c3f0-ffffffff8102c431: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102a5e0)
Location: arch/x86/kernel/process_64.c:137
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8102a5e0-ffffffff8102a621: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102b340)
Location: arch/x86/kernel/process_64.c:135
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8102b340-ffffffff8102b381: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:143
Inline: False
```
**Symbols:**

```
ffffffff8102d0da-ffffffff8102d0f8: release_thread.cold.5 (STB_LOCAL)
ffffffff8102c3a0-ffffffff8102c3c8: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:143
Inline: False
```
**Symbols:**

```
ffffffff8102e32e-ffffffff8102e34c: release_thread.cold.8 (STB_LOCAL)
ffffffff8102d520-ffffffff8102d548: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: arch/x86/kernel/process_64.c:144
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8103008e-ffffffff810300a1: release_thread.cold (STB_LOCAL)
ffffffff8102f310-ffffffff8102f329: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fc70)
Location: arch/x86/kernel/process_64.c:144
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8102fc70-ffffffff8102fc89: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032510)
Location: arch/x86/kernel/process_64.c:142
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff81032510-ffffffff81032529: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81033010)
Location: arch/x86/kernel/process_64.c:143
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff81033010-ffffffff81033029: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81034aa0)
Location: arch/x86/kernel/process_64.c:143
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff81034aa0-ffffffff81034ab9: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81039da0)
Location: arch/x86/kernel/process_64.c:144
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff81039da0-ffffffff81039db9: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81040d40)
Location: arch/x86/kernel/process_64.c:144
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff81040d40-ffffffff81040d65: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104a400)
Location: arch/x86/kernel/process_64.c:144
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8104a400-ffffffff8104a425: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104ac40)
Location: arch/x86/kernel/process_64.c:145
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8104ac40-ffffffff8104ac65: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81051eb0)
Location: arch/x86/kernel/process_64.c:145
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff81051eb0-ffffffff81051ed5: release_thread (STB_GLOBAL)
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
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/process.c (ffff800010089198)
Location: arch/arm64/kernel/process.c:328
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffff800010089198-ffff8000100891b0: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/process.c (c030b300)
Location: arch/arm/kernel/process.c:220
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
c030b300-c030b318: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void release_thread(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/process.c (c000000000021ed0)
Location: arch/powerpc/kernel/process.c:1533
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
c000000000021ed0-c000000000021edc: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (0)
Location: arch/riscv/include/asm/processor.h:54
Inline: True
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
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fdd0)
Location: arch/x86/kernel/process_64.c:144
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8102fdd0-ffffffff8102fde9: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8101f7f0)
Location: arch/x86/kernel/process_64.c:144
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8101f7f0-ffffffff8101f809: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fc30)
Location: arch/x86/kernel/process_64.c:144
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8102fc30-ffffffff8102fc49: release_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void release_thread(struct task_struct *dead_task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030a80)
Location: arch/x86/kernel/process_64.c:144
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff81030a80-ffffffff81030a99: release_thread (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *dead_task</code>
</li>
</ul>
</details>
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
