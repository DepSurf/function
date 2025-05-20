# Function: <code>uprobe_notify_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81188b90)
Location: kernel/events/uprobes.c:1961
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff81188b90-ffffffff81189648: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8119b260)
Location: kernel/events/uprobes.c:1972
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff8119b260-ffffffff8119bd24: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811aac60)
Location: kernel/events/uprobes.c:1974
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff811aac60-ffffffff811ab716: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811b2180)
Location: kernel/events/uprobes.c:1980
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff811b2180-ffffffff811b2b86: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811c5d90)
Location: kernel/events/uprobes.c:1980
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff811c5d90-ffffffff811c67d2: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1980
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff811e6d56-ffffffff811e6dd9: uprobe_notify_resume.cold.36 (STB_LOCAL)
ffffffff811e6270-ffffffff811e6c5b: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2258
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff811f7993-ffffffff811f7a0c: uprobe_notify_resume.cold.44 (STB_LOCAL)
ffffffff811f6dc0-ffffffff811f77b7: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2246
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff8120f833-ffffffff8120f84e: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff8120f480-ffffffff8120f565: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2298
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff8121ce63-ffffffff8121ce7e: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff8121cb30-ffffffff8121cc15: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2300
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff812491e1-ffffffff812491fc: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff81248ec0-ffffffff81248fa5: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2300
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff81be691c-ffffffff81be6937: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff812535d0-ffffffff812536b5: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2298
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff81bd861d-ffffffff81bd8638: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff81257bf0-ffffffff81257cd5: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2299
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff81cb9b29-ffffffff81cb9b74: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff812934d0-ffffffff8129384d: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2294
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff81e6b123-ffffffff81e6b16d: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff812e8fa0-ffffffff812e9309: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2299
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff82061ecd-ffffffff82061ee2: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff81352b60-ffffffff81353048: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2295
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff820e1667-ffffffff820e167c: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff81383d70-ffffffff8138424b: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2295
Inline: False
Direct callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
**Symbols:**

```
ffffffff821be0ca-ffffffff821be0df: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff813ad1c0-ffffffff813ad659: uprobe_notify_resume (STB_GLOBAL)
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
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a7f58)
Location: kernel/events/uprobes.c:2298
Inline: False
Direct callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
```
**Symbols:**

```
ffff8000102a7f58-ffff8000102a8564: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d75ac)
Location: kernel/events/uprobes.c:2298
Inline: False
Direct callers:
  - arch/arm/kernel/signal.c:do_work_pending
```
**Symbols:**

```
c04d75ac-c04d7714: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c00000000035be10)
Location: kernel/events/uprobes.c:2298
Inline: False
Direct callers:
  - arch/powerpc/kernel/signal.c:do_notify_resume
```
**Symbols:**

```
c00000000035be10-c00000000035bfa8: uprobe_notify_resume (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2298
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff812154b3-ffffffff812154ce: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff81215180-ffffffff81215265: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2298
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff81208213-ffffffff8120822e: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff81207ef0-ffffffff81207fcc: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2298
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff81213253-ffffffff8121326e: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff81212f20-ffffffff81213005: uprobe_notify_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void uprobe_notify_resume(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:2298
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
**Symbols:**

```
ffffffff812221f1-ffffffff8122220c: uprobe_notify_resume.cold (STB_LOCAL)
ffffffff81221e90-ffffffff81221faa: uprobe_notify_resume (STB_GLOBAL)
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
