# Function: <code>proc_clear_tty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e1d50)
Location: drivers/tty/tty_io.c:505
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
  - drivers/tty/tty_io.c:session_clear_tty
  - drivers/tty/tty_io.c:no_tty
```
**Symbols:**

```
ffffffff814e1d50-ffffffff814e1dc3: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81533000)
Location: drivers/tty/tty_io.c:512
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
  - drivers/tty/tty_io.c:no_tty
  - drivers/tty/tty_io.c:session_clear_tty
```
**Symbols:**

```
ffffffff81533000-ffffffff81533072: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155f730)
Location: drivers/tty/tty_io.c:512
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
  - drivers/tty/tty_io.c:no_tty
  - drivers/tty/tty_io.c:session_clear_tty
```
**Symbols:**

```
ffffffff8155f730-ffffffff8155f7a2: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8157d040)
Location: drivers/tty/tty_jobctrl.c:72
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
ffffffff8157d040-ffffffff8157d09e: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff815e1b60)
Location: drivers/tty/tty_jobctrl.c:73
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
ffffffff815e1b60-ffffffff815e1bbe: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8161ae10)
Location: drivers/tty/tty_jobctrl.c:73
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
ffffffff8161ae10-ffffffff8161ae6e: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81638080)
Location: drivers/tty/tty_jobctrl.c:73
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
ffffffff81638080-ffffffff816380de: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8166c370)
Location: drivers/tty/tty_jobctrl.c:73
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
ffffffff8166c370-ffffffff8166c3c0: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8168e9e0)
Location: drivers/tty/tty_jobctrl.c:73
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
ffffffff8168e9e0-ffffffff8168ea30: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81741940)
Location: drivers/tty/tty_jobctrl.c:73
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:session_clear_tty
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff81740f70-ffffffff81740fc0: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8175d845)
Location: drivers/tty/tty_jobctrl.c:74
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:session_clear_tty
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff8175cea0-ffffffff8175cef0: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff817411fd)
Location: drivers/tty/tty_jobctrl.c:75
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff81740b60-ffffffff81740bb0: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff817c1c5d)
Location: drivers/tty/tty_jobctrl.c:75
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff817c15c0-ffffffff817c1610: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff818fe6ad)
Location: drivers/tty/tty_jobctrl.c:75
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff818fdfb0-ffffffff818fe00a: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81a57edd)
Location: drivers/tty/tty_jobctrl.c:75
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff81a57780-ffffffff81a577da: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81aa24dd)
Location: drivers/tty/tty_jobctrl.c:75
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff81aa1d80-ffffffff81aa1dda: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81af4ebd)
Location: drivers/tty/tty_jobctrl.c:75
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
Direct callers:
  - kernel/sys.c:ksys_setsid
```
**Symbols:**

```
ffffffff81af47e0-ffffffff81af483a: proc_clear_tty (STB_GLOBAL)
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
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffff800010860110)
Location: drivers/tty/tty_jobctrl.c:73
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
ffff800010860110-ffff8000108601b8: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (c096728c)
Location: drivers/tty/tty_jobctrl.c:73
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
c096728c-c09672d4: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (c0000000008ff560)
Location: drivers/tty/tty_jobctrl.c:73
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
c0000000008ff560-c0000000008ff5d8: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffe000538130)
Location: drivers/tty/tty_jobctrl.c:73
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
ffffffe000538130-ffffffe000538184: proc_clear_tty (STB_GLOBAL)
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
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81654460)
Location: drivers/tty/tty_jobctrl.c:73
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
ffffffff81654460-ffffffff816544b0: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81634840)
Location: drivers/tty/tty_jobctrl.c:73
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
ffffffff81634840-ffffffff81634890: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81682820)
Location: drivers/tty/tty_jobctrl.c:73
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
ffffffff81682820-ffffffff81682870: proc_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void proc_clear_tty(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8169ce80)
Location: drivers/tty/tty_jobctrl.c:73
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:session_clear_tty
```
**Symbols:**

```
ffffffff8169ce80-ffffffff8169ced0: proc_clear_tty (STB_GLOBAL)
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
