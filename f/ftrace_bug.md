# Function: <code>ftrace_bug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81142f20)
Location: kernel/trace/ftrace.c:1968
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81142f20-ffffffff811431e7: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114adf0)
Location: kernel/trace/ftrace.c:1984
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff8114adf0-ffffffff8114b116: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81154ce0)
Location: kernel/trace/ftrace.c:1998
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81154ce0-ffffffff81155006: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811576e0)
Location: kernel/trace/ftrace.c:2083
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff811576e0-ffffffff81157969: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811641e0)
Location: kernel/trace/ftrace.c:2059
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff811641e0-ffffffff81164469: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:2048
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81177ab2-ffffffff81177bc9: ftrace_bug.cold.70 (STB_LOCAL)
ffffffff81173060-ffffffff811731df: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1997
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff8118505c-ffffffff81185173: ftrace_bug.cold.67 (STB_LOCAL)
ffffffff81180c80-ffffffff81180dff: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1996
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81192045-ffffffff81192183: ftrace_bug.cold (STB_LOCAL)
ffffffff8118daa0-ffffffff8118dc1c: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1997
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff8119df72-ffffffff8119e087: ftrace_bug.cold (STB_LOCAL)
ffffffff81199a00-ffffffff81199b7c: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b4700)
Location: kernel/trace/ftrace.c:2012
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff811b4700-ffffffff811b490c: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81be51bd)
Location: kernel/trace/ftrace.c:2013
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81be51bd-ffffffff81be53c2: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81bd6fc1)
Location: kernel/trace/ftrace.c:2019
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81bd6fc1-ffffffff81bd71c6: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81cb4454)
Location: kernel/trace/ftrace.c:2020
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81cb4454-ffffffff81cb4659: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81e65412)
Location: kernel/trace/ftrace.c:2031
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81e65412-ffffffff81e65621: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81255e50)
Location: kernel/trace/ftrace.c:2082
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81255e50-ffffffff81256104: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126d200)
Location: kernel/trace/ftrace.c:2126
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff8126d200-ffffffff8126d4c5: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812877f0)
Location: kernel/trace/ftrace.c:2125
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff812877f0-ffffffff81287ab5: ftrace_bug (STB_GLOBAL)
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
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010212520)
Location: kernel/trace/ftrace.c:1997
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffff800010212520-ffff800010212790: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c04510d8)
Location: kernel/trace/ftrace.c:1997
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
c04510d8-c04513cc: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000292140)
Location: kernel/trace/ftrace.c:1997
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
c000000000292140-c000000000292468: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe0001728fc)
Location: kernel/trace/ftrace.c:1997
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffe0001728fc-ffffffe000172b74: ftrace_bug (STB_GLOBAL)
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
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1997
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81196592-ffffffff811966a7: ftrace_bug.cold (STB_LOCAL)
ffffffff81192020-ffffffff8119219c: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1997
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff811896a2-ffffffff811897b7: ftrace_bug.cold (STB_LOCAL)
ffffffff81185130-ffffffff811852ac: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1997
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81194362-ffffffff81194477: ftrace_bug.cold (STB_LOCAL)
ffffffff8118fdf0-ffffffff8118ff6c: ftrace_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ftrace_bug(int failed, struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1997
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff811a1f52-ffffffff811a2067: ftrace_bug.cold (STB_LOCAL)
ffffffff8119d9a0-ffffffff8119db1c: ftrace_bug (STB_GLOBAL)
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
