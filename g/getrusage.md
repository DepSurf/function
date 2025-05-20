# Function: <code>getrusage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int getrusage(struct task_struct *p, int who, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81095a00)
Location: kernel/sys.c:1631
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:SyS_getrusage
```
**Symbols:**

```
ffffffff81095a00-ffffffff81095a6c: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int getrusage(struct task_struct *p, int who, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81098da0)
Location: kernel/sys.c:1631
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:SyS_getrusage
```
**Symbols:**

```
ffffffff81098da0-ffffffff81098e0c: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int getrusage(struct task_struct *p, int who, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109dd50)
Location: kernel/sys.c:1632
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:SyS_getrusage
```
**Symbols:**

```
ffffffff8109dd50-ffffffff8109ddbc: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109aed0)
Location: kernel/sys.c:1668
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:C_SYSC_getrusage
  - kernel/sys.c:SYSC_getrusage
```
**Symbols:**

```
ffffffff8109aed0-ffffffff8109b30a: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a1bb0)
Location: kernel/sys.c:1675
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:C_SYSC_getrusage
  - kernel/sys.c:SYSC_getrusage
```
**Symbols:**

```
ffffffff810a1bb0-ffffffff810a1fea: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a7ed0)
Location: kernel/sys.c:1729
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff810a7ed0-ffffffff810a8319: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b0be0)
Location: kernel/sys.c:1730
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff810b0be0-ffffffff810b1029: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b6740)
Location: kernel/sys.c:1730
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff810b6740-ffffffff810b6b61: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bcd00)
Location: kernel/sys.c:1720
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff810bcd00-ffffffff810bd121: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c4440)
Location: kernel/sys.c:1736
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff810c4440-ffffffff810c4861: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bf840)
Location: kernel/sys.c:1737
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff810bf840-ffffffff810bfc61: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c1270)
Location: kernel/sys.c:1754
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff810c1270-ffffffff810c1691: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d3d60)
Location: kernel/sys.c:1763
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff810d3d60-ffffffff810d4181: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810eca10)
Location: kernel/sys.c:1775
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff810eca10-ffffffff810ece61: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110ddb0)
Location: kernel/sys.c:1780
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff8110ddb0-ffffffff8110e201: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8111a040)
Location: kernel/sys.c:1798
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff8111a040-ffffffff8111a467: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81123a30)
Location: kernel/sys.c:1798
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff81123a30-ffffffff81123ed3: getrusage (STB_GLOBAL)
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
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff800010119890)
Location: kernel/sys.c:1720
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffff800010119890-ffff800010119be8: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036ddb0)
Location: kernel/sys.c:1720
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__se_sys_getrusage
```
**Symbols:**

```
c036ddb0-c036e1d0: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c0000000001610a0)
Location: kernel/sys.c:1720
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
c0000000001610a0-c000000000161524: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d45e8)
Location: kernel/sys.c:1720
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffe0000d45e8-ffffffe0000d48ee: getrusage (STB_GLOBAL)
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
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b7070)
Location: kernel/sys.c:1720
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff810b7070-ffffffff810b7491: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a59b0)
Location: kernel/sys.c:1720
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff810a59b0-ffffffff810a5dd1: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b65d0)
Location: kernel/sys.c:1720
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff810b65d0-ffffffff810b69f1: getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void getrusage(struct task_struct *p, int who, struct rusage *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810be950)
Location: kernel/sys.c:1720
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:__do_compat_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
```
**Symbols:**

```
ffffffff810be950-ffffffff810bed71: getrusage (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rusage *r</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rusage *ru</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
