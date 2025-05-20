# Function: <code>__oom_reap_task_mm</code>

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
bool __oom_reap_task_mm(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811b4b80)
Location: mm/oom_kill.c:464
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff811b4b80-ffffffff811b4d70: __oom_reap_task_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bc580)
Location: mm/oom_kill.c:469
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff811bc580-ffffffff811bc867: __oom_reap_task_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d1180)
Location: mm/oom_kill.c:488
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff811d1180-ffffffff811d147b: __oom_reap_task_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811f2d80)
Location: mm/oom_kill.c:482
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff811f2d80-ffffffff811f2e85: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81204d80)
Location: mm/oom_kill.c:503
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff81204d80-ffffffff81204ef4: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121c870)
Location: mm/oom_kill.c:512
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff8121c870-ffffffff8121c9f6: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122a240)
Location: mm/oom_kill.c:512
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff8122a240-ffffffff8122a3d4: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81257010)
Location: mm/oom_kill.c:513
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff81257010-ffffffff812571a4: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81261bf0)
Location: mm/oom_kill.c:515
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reap_task_mm
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff81261bf0-ffffffff81261d84: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812666c0)
Location: mm/oom_kill.c:514
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff812666c0-ffffffff81266838: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812a2c90)
Location: mm/oom_kill.c:515
Inline: False
Direct callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff812a2c90-ffffffff812a2e08: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812faab0)
Location: mm/oom_kill.c:512
Inline: False
Direct callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff812faab0-ffffffff812fac4d: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81362be0)
Location: mm/oom_kill.c:512
Inline: False
Direct callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff81362be0-ffffffff81362d96: __oom_reap_task_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81395000)
Location: mm/oom_kill.c:512
Inline: False
Direct callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff81395000-ffffffff813951d0: __oom_reap_task_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813bedc0)
Location: mm/oom_kill.c:509
Inline: False
Direct callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff813bedc0-ffffffff813bef8d: __oom_reap_task_mm (STB_LOCAL)
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
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b8230)
Location: mm/oom_kill.c:512
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffff8000102b8230-ffff8000102b8398: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e49bc)
Location: mm/oom_kill.c:512
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
c04e49bc-c04e4b40: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c0000000003702b0)
Location: mm/oom_kill.c:512
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
c0000000003702b0-c0000000003704b4: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001dc044)
Location: mm/oom_kill.c:512
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffe0001dc044-ffffffe0001dc164: __oom_reap_task_mm (STB_GLOBAL)
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
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81222890)
Location: mm/oom_kill.c:512
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff81222890-ffffffff81222a24: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81215a40)
Location: mm/oom_kill.c:512
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff81215a40-ffffffff81215bd4: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81220630)
Location: mm/oom_kill.c:512
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff81220630-ffffffff812207c4: __oom_reap_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122f760)
Location: mm/oom_kill.c:512
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff8122f760-ffffffff8122f8e6: __oom_reap_task_mm (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm</code> ➡️ <code>mm</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
