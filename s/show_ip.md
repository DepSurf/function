# Function: <code>show_ip</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031f04)
Location: arch/x86/kernel/dumpstack.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_iret_regs
```
**Symbols:**

```
ffffffff81031f04-ffffffff81031f3f: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810331c9)
Location: arch/x86/kernel/dumpstack.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_iret_regs
```
**Symbols:**

```
ffffffff810331c9-ffffffff81033204: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103503d)
Location: arch/x86/kernel/dumpstack.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_iret_regs
```
**Symbols:**

```
ffffffff8103503d-ffffffff8103507a: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103586d)
Location: arch/x86/kernel/dumpstack.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_iret_regs
```
**Symbols:**

```
ffffffff8103586d-ffffffff810358aa: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103791b)
Location: arch/x86/kernel/dumpstack.c:126
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_iret_regs
```
**Symbols:**

```
ffffffff8103791b-ffffffff81037958: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bd34cd)
Location: arch/x86/kernel/dumpstack.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_iret_regs
```
**Symbols:**

```
ffffffff81bd34cd-ffffffff81bd350a: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bc5940)
Location: arch/x86/kernel/dumpstack.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_iret_regs
```
**Symbols:**

```
ffffffff81bc5940-ffffffff81bc597d: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81c9868a)
Location: arch/x86/kernel/dumpstack.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_iret_regs
```
**Symbols:**

```
ffffffff81c9868a-ffffffff81c986c7: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81e47bb9)
Location: arch/x86/kernel/dumpstack.c:137
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_iret_regs
```
**Symbols:**

```
ffffffff81e47bb9-ffffffff81e47c02: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81051a50)
Location: arch/x86/kernel/dumpstack.c:137
Inline: True
```
**Symbols:**

```
ffffffff81051a50-ffffffff81051a99: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81052790)
Location: arch/x86/kernel/dumpstack.c:137
Inline: True
```
**Symbols:**

```
ffffffff81052790-ffffffff810527d9: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810599b0)
Location: arch/x86/kernel/dumpstack.c:137
Inline: True
```
**Symbols:**

```
ffffffff810599b0-ffffffff810599f9: show_ip (STB_GLOBAL)
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
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810359cd)
Location: arch/x86/kernel/dumpstack.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_iret_regs
```
**Symbols:**

```
ffffffff810359cd-ffffffff81035a0a: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102531d)
Location: arch/x86/kernel/dumpstack.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_iret_regs
```
**Symbols:**

```
ffffffff8102531d-ffffffff8102535a: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103582d)
Location: arch/x86/kernel/dumpstack.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_iret_regs
```
**Symbols:**

```
ffffffff8103582d-ffffffff8103586a: show_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void show_ip(struct pt_regs *regs, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103680d)
Location: arch/x86/kernel/dumpstack.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_iret_regs
```
**Symbols:**

```
ffffffff8103680d-ffffffff8103684a: show_ip (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
