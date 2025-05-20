# Function: <code>uprobe_copy_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811888c0)
Location: kernel/events/uprobes.c:1477
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811888c0-ffffffff81188a84: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8119af90)
Location: kernel/events/uprobes.c:1483
Inline: False
```
**Symbols:**

```
ffffffff8119af90-ffffffff8119b154: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811aa9a0)
Location: kernel/events/uprobes.c:1484
Inline: False
```
**Symbols:**

```
ffffffff811aa9a0-ffffffff811aab64: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811b1ee0)
Location: kernel/events/uprobes.c:1490
Inline: False
```
**Symbols:**

```
ffffffff811b1ee0-ffffffff811b20ad: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811c5af0)
Location: kernel/events/uprobes.c:1490
Inline: False
```
**Symbols:**

```
ffffffff811c5af0-ffffffff811c5cbd: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1490
Inline: False
```
**Symbols:**

```
ffffffff811e6d45-ffffffff811e6d56: uprobe_copy_process.cold.35 (STB_LOCAL)
ffffffff811e6010-ffffffff811e6197: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1760
Inline: False
```
**Symbols:**

```
ffffffff811f7982-ffffffff811f7993: uprobe_copy_process.cold.43 (STB_LOCAL)
ffffffff811f6b60-ffffffff811f6ce7: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1748
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8120f7ac-ffffffff8120f7ce: uprobe_copy_process.cold (STB_LOCAL)
ffffffff8120e920-ffffffff8120eab9: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8121cdef-ffffffff8121ce11: uprobe_copy_process.cold (STB_LOCAL)
ffffffff8121bf60-ffffffff8121c0f9: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1799
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81249174-ffffffff81249196: uprobe_copy_process.cold (STB_LOCAL)
ffffffff812486d0-ffffffff8124878b: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1799
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81be68af-ffffffff81be68d1: uprobe_copy_process.cold (STB_LOCAL)
ffffffff81252de0-ffffffff81252e9b: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1797
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81bd85b0-ffffffff81bd85d2: uprobe_copy_process.cold (STB_LOCAL)
ffffffff81257000-ffffffff812571de: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1798
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81cb9ad7-ffffffff81cb9af9: uprobe_copy_process.cold (STB_LOCAL)
ffffffff81292d90-ffffffff81292f6e: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1793
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81e6b0d1-ffffffff81e6b0f3: uprobe_copy_process.cold (STB_LOCAL)
ffffffff812e87e0-ffffffff812e89d9: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813524c0)
Location: kernel/events/uprobes.c:1797
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff813524c0-ffffffff8135272d: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813836d0)
Location: kernel/events/uprobes.c:1794
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff813836d0-ffffffff8138393d: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813acad0)
Location: kernel/events/uprobes.c:1794
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff813acad0-ffffffff813acd97: uprobe_copy_process (STB_GLOBAL)
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
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a78b8)
Location: kernel/events/uprobes.c:1800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffff8000102a78b8-ffff8000102a7a48: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d69c4)
Location: kernel/events/uprobes.c:1800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c04d69c4-c04d6b2c: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c00000000035aea0)
Location: kernel/events/uprobes.c:1800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c00000000035aea0-c00000000035b0b4: uprobe_copy_process (STB_GLOBAL)
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
In kernel/fork.c (0)
Location: include/linux/uprobes.h:197
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8121543f-ffffffff81215461: uprobe_copy_process.cold (STB_LOCAL)
ffffffff812145b0-ffffffff81214749: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8120819f-ffffffff812081c1: uprobe_copy_process.cold (STB_LOCAL)
ffffffff81207320-ffffffff812074b9: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff812131df-ffffffff81213201: uprobe_copy_process.cold (STB_LOCAL)
ffffffff81212350-ffffffff812124e9: uprobe_copy_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void uprobe_copy_process(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1800
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8122217d-ffffffff8122219f: uprobe_copy_process.cold (STB_LOCAL)
ffffffff812212d0-ffffffff81221469: uprobe_copy_process (STB_GLOBAL)
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
