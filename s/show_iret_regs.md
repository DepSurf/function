# Function: <code>show_iret_regs</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030c40)
Location: arch/x86/kernel/dumpstack.c:72
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff81030c40-ffffffff81030c8a: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031f3f)
Location: arch/x86/kernel/dumpstack.c:138
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff81031f3f-ffffffff81031f7c: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81033204)
Location: arch/x86/kernel/dumpstack.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff81033204-ffffffff81033241: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103507a)
Location: arch/x86/kernel/dumpstack.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff8103507a-ffffffff810350b7: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810358aa)
Location: arch/x86/kernel/dumpstack.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff810358aa-ffffffff810358e7: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81037958)
Location: arch/x86/kernel/dumpstack.c:136
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff81037958-ffffffff81037995: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bd350a)
Location: arch/x86/kernel/dumpstack.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff81bd350a-ffffffff81bd354a: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bc597d)
Location: arch/x86/kernel/dumpstack.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff81bc597d-ffffffff81bc59bc: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81c986c7)
Location: arch/x86/kernel/dumpstack.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff81c986c7-ffffffff81c98706: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81e47c02)
Location: arch/x86/kernel/dumpstack.c:147
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff81e47c02-ffffffff81e47c52: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void show_iret_regs(struct pt_regs *regs, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81051ab0)
Location: arch/x86/kernel/dumpstack.c:147
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff81051ab0-ffffffff81051b1f: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void show_iret_regs(struct pt_regs *regs, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810527f0)
Location: arch/x86/kernel/dumpstack.c:147
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff810527f0-ffffffff8105285f: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void show_iret_regs(struct pt_regs *regs, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81059a10)
Location: arch/x86/kernel/dumpstack.c:147
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff81059a10-ffffffff81059a7f: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035a0a)
Location: arch/x86/kernel/dumpstack.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff81035a0a-ffffffff81035a47: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102535a)
Location: arch/x86/kernel/dumpstack.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff8102535a-ffffffff81025397: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103586a)
Location: arch/x86/kernel/dumpstack.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff8103586a-ffffffff810358a7: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void show_iret_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103684a)
Location: arch/x86/kernel/dumpstack.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
**Symbols:**

```
ffffffff8103684a-ffffffff81036887: show_iret_regs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *log_lvl</code>
</li>
</ul>
</details>
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
