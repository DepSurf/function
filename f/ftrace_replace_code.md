# Function: <code>ftrace_replace_code</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105af90)
Location: arch/x86/kernel/ftrace.c:539
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff8105af90-ffffffff8105b320: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105b040)
Location: arch/x86/kernel/ftrace.c:546
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff8105b040-ffffffff8105b3d7: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105de80)
Location: arch/x86/kernel/ftrace.c:546
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff8105de80-ffffffff8105e217: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105d4f0)
Location: arch/x86/kernel/ftrace.c:552
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff8105d4f0-ffffffff8105d84b: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810611b0)
Location: arch/x86/kernel/ftrace.c:553
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff810611b0-ffffffff8106150b: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81173560)
Location: arch/x86/kernel/ftrace.c:553
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff81064946-ffffffff81064a45: ftrace_replace_code.cold.11 (STB_LOCAL)
ffffffff810642d0-ffffffff81064524: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81181170)
Location: arch/x86/kernel/ftrace.c:556
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff8106a5bf-ffffffff8106a6be: ftrace_replace_code.cold.13 (STB_LOCAL)
ffffffff81069f70-ffffffff8106a1c4: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8118e020)
Location: arch/x86/kernel/ftrace.c:579
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff8106de96-ffffffff8106df8e: ftrace_replace_code.cold (STB_LOCAL)
ffffffff8106d7b0-ffffffff8106da38: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81199f00)
Location: arch/x86/kernel/ftrace.c:579
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff8106f482-ffffffff8106f57a: ftrace_replace_code.cold (STB_LOCAL)
ffffffff8106edd0-ffffffff8106f058: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810761d0)
Location: arch/x86/kernel/ftrace.c:194
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff811b4925-ffffffff811b4934: ftrace_replace_code.cold (STB_LOCAL)
ffffffff810761d0-ffffffff81076340: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81076800)
Location: arch/x86/kernel/ftrace.c:194
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff81be53db-ffffffff81be53ea: ftrace_replace_code.cold (STB_LOCAL)
ffffffff81076800-ffffffff81076970: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81077270)
Location: arch/x86/kernel/ftrace.c:194
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff81bd71df-ffffffff81bd71ee: ftrace_replace_code.cold (STB_LOCAL)
ffffffff81077270-ffffffff810773d8: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81084a70)
Location: arch/x86/kernel/ftrace.c:194
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff81cb469f-ffffffff81cb46ae: ftrace_replace_code.cold (STB_LOCAL)
ffffffff81084a70-ffffffff81084bd8: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81094bf0)
Location: arch/x86/kernel/ftrace.c:193
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff81e65667-ffffffff81e65676: ftrace_replace_code.cold (STB_LOCAL)
ffffffff81094bf0-ffffffff81094d83: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810aa650)
Location: arch/x86/kernel/ftrace.c:197
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff810aa650-ffffffff810aa810: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810ada10)
Location: arch/x86/kernel/ftrace.c:197
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff810ada10-ffffffff810adbbd: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810b4590)
Location: arch/x86/kernel/ftrace.c:197
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff810b4590-ffffffff810b473d: ftrace_replace_code (STB_GLOBAL)
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
void ftrace_replace_code(int mod_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010212bc0)
Location: kernel/trace/ftrace.c:2397
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffff800010212bc0-ffff800010212c80: ftrace_replace_code (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ftrace_replace_code(int mod_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0451814)
Location: kernel/trace/ftrace.c:2397
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
c0451814-c04518c8: ftrace_replace_code (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ftrace_replace_code(int mod_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000292b10)
Location: kernel/trace/ftrace.c:2397
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
c000000000292b10-c000000000292c3c: ftrace_replace_code (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ftrace_replace_code(int mod_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000172f4c)
Location: kernel/trace/ftrace.c:2397
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffe000172f4c-ffffffe000172ff2: ftrace_replace_code (STB_WEAK)
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
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81192520)
Location: arch/x86/kernel/ftrace.c:579
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff8106e422-ffffffff8106e51a: ftrace_replace_code.cold (STB_LOCAL)
ffffffff8106dd70-ffffffff8106dff8: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81185630)
Location: arch/x86/kernel/ftrace.c:579
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff8105e842-ffffffff8105e93a: ftrace_replace_code.cold (STB_LOCAL)
ffffffff8105e190-ffffffff8105e418: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff811902f0)
Location: arch/x86/kernel/ftrace.c:579
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff8106e8d2-ffffffff8106e9ca: ftrace_replace_code.cold (STB_LOCAL)
ffffffff8106e220-ffffffff8106e4a8: ftrace_replace_code (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ftrace_replace_code(int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8119dea0)
Location: arch/x86/kernel/ftrace.c:579
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
```
**Symbols:**

```
ffffffff81070b52-ffffffff81070c4a: ftrace_replace_code.cold (STB_LOCAL)
ffffffff810704a0-ffffffff81070728: ftrace_replace_code (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int mod_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int enable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int mod_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int enable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int mod_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int enable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int mod_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int enable</code>
</li>
</ul>
</details>
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
