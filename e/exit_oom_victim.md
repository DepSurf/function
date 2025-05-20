# Function: <code>exit_oom_victim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81190a70)
Location: mm/oom_kill.c:437
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81190a70-ffffffff81190ab4: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void exit_oom_victim(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811a4f70)
Location: mm/oom_kill.c:688
Inline: True
Direct callers:
  - kernel/exit.c:do_exit
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff811a4f70-ffffffff811a4fbb: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811b5970)
Location: mm/oom_kill.c:678
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff811b5970-ffffffff811b59b1: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bd6b0)
Location: mm/oom_kill.c:681
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff811bd6b0-ffffffff811bd6f2: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d22f0)
Location: mm/oom_kill.c:705
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff811d22f0-ffffffff811d2332: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811f3240)
Location: mm/oom_kill.c:707
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff811f3240-ffffffff811f3282: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81205230)
Location: mm/oom_kill.c:715
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81205230-ffffffff81205272: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121cd30)
Location: mm/oom_kill.c:725
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8121cd30-ffffffff8121cd71: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122a710)
Location: mm/oom_kill.c:725
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8122a710-ffffffff8122a751: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81257520)
Location: mm/oom_kill.c:727
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff81257520-ffffffff81257561: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81262100)
Location: mm/oom_kill.c:729
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff81262100-ffffffff81262141: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81266b90)
Location: mm/oom_kill.c:728
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff81266b90-ffffffff81266bd1: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812a3390)
Location: mm/oom_kill.c:729
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff812a3390-ffffffff812a33d1: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812fb2a0)
Location: mm/oom_kill.c:786
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff812fb2a0-ffffffff812fb2fd: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81365290)
Location: mm/oom_kill.c:785
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff81365290-ffffffff813652ed: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81397750)
Location: mm/oom_kill.c:785
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff81397750-ffffffff813977ad: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813c1580)
Location: mm/oom_kill.c:782
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff813c1580-ffffffff813c15dd: exit_oom_victim (STB_GLOBAL)
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
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b87d0)
Location: mm/oom_kill.c:725
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffff8000102b87d0-ffff8000102b886c: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e4fb4)
Location: mm/oom_kill.c:725
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
c04e4fb4-c04e5028: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c000000000370a00)
Location: mm/oom_kill.c:725
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
c000000000370a00-c000000000370a94: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001dc52a)
Location: mm/oom_kill.c:725
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffe0001dc52a-ffffffe0001dc580: exit_oom_victim (STB_GLOBAL)
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
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81222d60)
Location: mm/oom_kill.c:725
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81222d60-ffffffff81222da1: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81215f10)
Location: mm/oom_kill.c:725
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81215f10-ffffffff81215f51: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81220b00)
Location: mm/oom_kill.c:725
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81220b00-ffffffff81220b41: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void exit_oom_victim();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122fca0)
Location: mm/oom_kill.c:725
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8122fca0-ffffffff8122fce1: exit_oom_victim (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *tsk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
</ul>
</details>
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
