# Function: <code>wake_up_klogd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d7bed)
Location: kernel/printk/printk.c:2741
Inline: True
Direct callers:
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff810d9c40-ffffffff810d9c75: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dcca1)
Location: kernel/printk/printk.c:2883
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
Direct callers:
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff810dee00-ffffffff810dee37: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e33eb)
Location: kernel/printk/printk.c:2715
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
Direct callers:
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff810e5360-ffffffff810e5397: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e29fe)
Location: kernel/printk/printk.c:2713
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
Direct callers:
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff810e4650-ffffffff810e4687: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ea89a)
Location: kernel/printk/printk.c:2707
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
Direct callers:
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff810ec910-ffffffff810ec946: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f46d0)
Location: kernel/printk/printk.c:2880
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff810f46d0-ffffffff810f4706: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ffe60)
Location: kernel/printk/printk.c:2892
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff810ffe60-ffffffff810ffe96: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81108620)
Location: kernel/printk/printk.c:2957
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff81108620-ffffffff81108657: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81114a00)
Location: kernel/printk/printk.c:2967
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff81114a00-ffffffff81114a37: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811202be)
Location: kernel/printk/printk.c:3029
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff811207a0-ffffffff811207e1: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111b260)
Location: kernel/printk/printk.c:3108
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff8111b740-ffffffff8111b781: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111b860)
Location: kernel/printk/printk.c:3172
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff8111be00-ffffffff8111be41: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113be2f)
Location: kernel/printk/printk.c:3231
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff81cac4d4-ffffffff81cac4e8: wake_up_klogd.cold (STB_LOCAL)
ffffffff8113be10-ffffffff8113be60: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115ece9)
Location: kernel/printk/printk.c:3497
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff81e5cb20-ffffffff81e5cb34: wake_up_klogd.cold (STB_LOCAL)
ffffffff8115f360-ffffffff8115f397: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81191c49)
Location: kernel/printk/printk.c:3760
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff82058b99-ffffffff82058bad: wake_up_klogd.cold (STB_LOCAL)
ffffffff81192540-ffffffff81192577: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a34e9)
Location: kernel/printk/printk.c:3801
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff820d7431-ffffffff820d7445: wake_up_klogd.cold (STB_LOCAL)
ffffffff811a3de0-ffffffff811a3e17: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b227a)
Location: kernel/printk/printk.c:3912
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff821b26dc-ffffffff821b26f0: wake_up_klogd.cold (STB_LOCAL)
ffffffff811b3490-ffffffff811b34c7: wake_up_klogd (STB_GLOBAL)
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
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff8000101759c8)
Location: kernel/printk/printk.c:2967
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffff8000101759c8-ffff800010175a38: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c7c18)
Location: kernel/printk/printk.c:2967
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
c03c7c18-c03c7c80: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cf3c0)
Location: kernel/printk/printk.c:2967
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
c0000000001cf3c0-c0000000001cf454: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe000111184)
Location: kernel/printk/printk.c:2967
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffe000111184-ffffffe0001111fc: wake_up_klogd (STB_GLOBAL)
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
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110cfe0)
Location: kernel/printk/printk.c:2967
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff8110cfe0-ffffffff8110d017: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fdda0)
Location: kernel/printk/printk.c:2967
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff810fdda0-ffffffff810fddd7: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110aed0)
Location: kernel/printk/printk.c:2967
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff8110aed0-ffffffff8110af07: wake_up_klogd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wake_up_klogd();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81116360)
Location: kernel/printk/printk.c:2967
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - lib/bust_spinlocks.c:bust_spinlocks
```
**Symbols:**

```
ffffffff81116360-ffffffff811163ad: wake_up_klogd (STB_GLOBAL)
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
