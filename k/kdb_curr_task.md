# Function: <code>kdb_curr_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81134c30)
Location: kernel/debug/kdb/kdb_main.c:188
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81134c30-ffffffff81134c40: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8113fda3)
Location: kernel/debug/kdb/kdb_main.c:188
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8113d0d0-ffffffff8113d0e0: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81149b75)
Location: kernel/debug/kdb/kdb_main.c:187
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81146e80-ffffffff81146e90: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8114b974)
Location: kernel/debug/kdb/kdb_main.c:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81148bd0-ffffffff81148be0: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81158236)
Location: kernel/debug/kdb/kdb_main.c:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81155480-ffffffff81155490: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81166e36)
Location: kernel/debug/kdb/kdb_main.c:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81163fe0-ffffffff81163ff0: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81173b96)
Location: kernel/debug/kdb/kdb_main.c:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81170d10-ffffffff81170d20: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81180964)
Location: kernel/debug/kdb/kdb_main.c:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8117da80-ffffffff8117da90: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8118c7d4)
Location: kernel/debug/kdb/kdb_main.c:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81189900-ffffffff81189910: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811a0ff7)
Location: kernel/debug/kdb/kdb_main.c:189
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8119e6e0-ffffffff8119e6f0: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119e16c)
Location: kernel/debug/kdb/kdb_main.c:189
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8119b7a0-ffffffff8119b7b0: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119edcc)
Location: kernel/debug/kdb/kdb_main.c:159
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8119c510-ffffffff8119c520: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811c8c44)
Location: kernel/debug/kdb/kdb_main.c:158
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff811c6250-ffffffff811c6260: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811fc7ee)
Location: kernel/debug/kdb/kdb_main.c:158
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff811f9ad0-ffffffff811f9ae6: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81243eb4)
Location: kernel/debug/kdb/kdb_main.c:158
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81241030-ffffffff81241046: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8125af94)
Location: kernel/debug/kdb/kdb_main.c:158
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff812580c0-ffffffff812580d6: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81274e64)
Location: kernel/debug/kdb/kdb_main.c:158
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81271fb0-ffffffff81271fc6: kdb_curr_task (STB_GLOBAL)
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
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffff800010203acc)
Location: kernel/debug/kdb/kdb_main.c:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffff800010200b10-ffff800010200b3c: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (c0442a48)
Location: kernel/debug/kdb/kdb_main.c:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
c043fbe8-c043fc04: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (c00000000027e290)
Location: kernel/debug/kdb/kdb_main.c:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
c0000000002797e0-c000000000279814: kdb_curr_task (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81184df4)
Location: kernel/debug/kdb/kdb_main.c:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81181f20-ffffffff81181f30: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81177f34)
Location: kernel/debug/kdb/kdb_main.c:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81175060-ffffffff81175070: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81182bc4)
Location: kernel/debug/kdb/kdb_main.c:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8117fcf0-ffffffff8117fd00: kdb_curr_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *kdb_curr_task(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811904e4)
Location: kernel/debug/kdb/kdb_main.c:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8118d610-ffffffff8118d620: kdb_curr_task (STB_GLOBAL)
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
