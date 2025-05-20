# Function: <code>__warn</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81082d90)
Location: kernel/panic.c:483
Inline: False
Direct callers:
  - kernel/panic.c:warn_slowpath_null
  - kernel/panic.c:warn_slowpath_fmt_taint
  - kernel/panic.c:warn_slowpath_fmt
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81082d90-ffffffff81082e73: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81087820)
Location: kernel/panic.c:513
Inline: False
Direct callers:
  - kernel/panic.c:warn_slowpath_null
  - kernel/panic.c:warn_slowpath_fmt_taint
  - kernel/panic.c:warn_slowpath_fmt
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81087820-ffffffff81087903: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810846b0)
Location: kernel/panic.c:515
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff810846b0-ffffffff81084793: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108b090)
Location: kernel/panic.c:520
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8108b090-ffffffff8108b197: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:509
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8108ec2c-ffffffff8108ecf3: __warn.cold.11 (STB_LOCAL)
ffffffff8108e850-ffffffff8108e88b: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:544
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81096fcc-ffffffff81096ffd: __warn.cold.11 (STB_LOCAL)
ffffffff81096ae0-ffffffff81096bc1: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:549
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8109b578-ffffffff8109b5af: __warn.cold (STB_LOCAL)
ffffffff8109b060-ffffffff8109b140: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:558
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff810a1aa4-ffffffff810a1ac4: __warn.cold (STB_LOCAL)
ffffffff810a1580-ffffffff810a1655: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:576
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff810a88f5-ffffffff810a8925: __warn.cold (STB_LOCAL)
ffffffff810a8430-ffffffff810a8535: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:576
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81bdb49d-ffffffff81bdb4d9: __warn.cold (STB_LOCAL)
ffffffff810a4140-ffffffff810a424d: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:576
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81bcd58f-ffffffff81bcd5cb: __warn.cold (STB_LOCAL)
ffffffff810a4d90-ffffffff810a4e9d: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:574
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81ca3d56-ffffffff81ca3d92: __warn.cold (STB_LOCAL)
ffffffff810b65d0-ffffffff810b66dd: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:601
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81e53518-ffffffff81e535b3: __warn.cold (STB_LOCAL)
ffffffff810ccb50-ffffffff810ccc0d: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810eaa40)
Location: kernel/panic.c:652
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff810eaa40-ffffffff810eab99: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810f6620)
Location: kernel/panic.c:652
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff810f6620-ffffffff810f6779: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810ff9d0)
Location: kernel/panic.c:656
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff810ff9d0-ffffffff810ffb29: __warn (STB_GLOBAL)
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
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffff8000100f6720)
Location: kernel/panic.c:558
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffff8000100f6720-ffff8000100f6840: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c0354878)
Location: kernel/panic.c:558
Inline: True
Direct callers:
  - kernel/panic.c:warn_slowpath_fmt
  - kernel/panic.c:warn_slowpath_fmt
  - lib/bug.c:report_bug
```
**Symbols:**

```
c0354878-c0354980: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c00000000013c5e0)
Location: kernel/panic.c:558
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
c00000000013c5e0-c00000000013c74c: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffe0000c2414)
Location: kernel/panic.c:558
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffe0000c2414-ffffffe0000c2512: __warn (STB_GLOBAL)
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
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:558
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8109b3c4-ffffffff8109b3e4: __warn.cold (STB_LOCAL)
ffffffff8109aea0-ffffffff8109af75: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:558
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81089df8-ffffffff81089e18: __warn.cold (STB_LOCAL)
ffffffff810898e0-ffffffff810899b5: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:558
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8109b374-ffffffff8109b394: __warn.cold (STB_LOCAL)
ffffffff8109ae50-ffffffff8109af25: __warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __warn(const char *file, int line, void *caller, unsigned int taint, struct pt_regs *regs, struct warn_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:558
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff810a2feb-ffffffff810a300b: __warn.cold (STB_LOCAL)
ffffffff810a2ac0-ffffffff810a2b95: __warn (STB_GLOBAL)
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
