# Function: <code>process_shares_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81190cc9)
Location: mm/oom_kill.c:492
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811a5332)
Location: mm/oom_kill.c:432
Inline: True
Inline callers:
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff811a4e30-ffffffff811a4e8d: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811b563a)
Location: mm/oom_kill.c:441
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff811b5910-ffffffff811b596d: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bd351)
Location: mm/oom_kill.c:446
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff811bd650-ffffffff811bd6ad: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d1f76)
Location: mm/oom_kill.c:465
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff811d2290-ffffffff811d22ed: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811f3bfc)
Location: mm/oom_kill.c:460
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff811f2d20-ffffffff811f2d7d: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81205d4a)
Location: mm/oom_kill.c:481
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff81204d20-ffffffff81204d7d: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121c1ce)
Location: mm/oom_kill.c:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff8121c810-ffffffff8121c861: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81229b9a)
Location: mm/oom_kill.c:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff8122a1e0-ffffffff8122a231: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812569f7)
Location: mm/oom_kill.c:491
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
**Symbols:**

```
ffffffff81256fb0-ffffffff81257001: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81261594)
Location: mm/oom_kill.c:493
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
**Symbols:**

```
ffffffff81261b90-ffffffff81261be1: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81265dd4)
Location: mm/oom_kill.c:492
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
**Symbols:**

```
ffffffff81266660-ffffffff812666b1: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812a25fe)
Location: mm/oom_kill.c:493
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
**Symbols:**

```
ffffffff812a2c30-ffffffff812a2c81: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812fa151)
Location: mm/oom_kill.c:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
**Symbols:**

```
ffffffff812faa40-ffffffff812faaa9: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81364881)
Location: mm/oom_kill.c:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
**Symbols:**

```
ffffffff81365210-ffffffff81365279: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81396d51)
Location: mm/oom_kill.c:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
**Symbols:**

```
ffffffff813976d0-ffffffff81397739: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813c0ac1)
Location: mm/oom_kill.c:487
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
```
**Symbols:**

```
ffffffff813c1500-ffffffff813c1569: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b7980)
Location: mm/oom_kill.c:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffff8000102b81c0-ffff8000102b8230: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e4604)
Location: mm/oom_kill.c:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
c04e4954-c04e49bc: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c00000000036f7b8)
Location: mm/oom_kill.c:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
c000000000370240-c0000000003702a8: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001dbc62)
Location: mm/oom_kill.c:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffe0001dbfe4-ffffffe0001dc044: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812221ea)
Location: mm/oom_kill.c:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff81222830-ffffffff81222881: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121539a)
Location: mm/oom_kill.c:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff812159e0-ffffffff81215a31: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121ff8a)
Location: mm/oom_kill.c:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff812205d0-ffffffff81220621: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool process_shares_mm(struct task_struct *p, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122f085)
Location: mm/oom_kill.c:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:task_will_free_mem
Direct callers:
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff8122f700-ffffffff8122f751: process_shares_mm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
