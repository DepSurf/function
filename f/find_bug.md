# Function: <code>find_bug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bug.c (ffffffff813e8c20)
Location: lib/bug.c:130
Inline: True
Inline callers:
  - lib/bug.c:report_bug
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff813e8c20-ffffffff813e8c92: find_bug.part.0 (STB_LOCAL)
ffffffff813e8da0-ffffffff813e8de6: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bug.c (ffffffff8142f07e)
Location: lib/bug.c:130
Inline: True
Inline callers:
  - lib/bug.c:report_bug
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8142ee90-ffffffff8142ef02: find_bug.part.0 (STB_LOCAL)
ffffffff8142f010-ffffffff8142f055: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bug.c (ffffffff8144b1ee)
Location: lib/bug.c:130
Inline: True
Inline callers:
  - lib/bug.c:report_bug
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8144b000-ffffffff8144b072: find_bug.part.2 (STB_LOCAL)
ffffffff8144b180-ffffffff8144b1c5: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bug.c (ffffffff818eb462)
Location: lib/bug.c:131
Inline: True
Inline callers:
  - lib/bug.c:report_bug
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff818eb270-ffffffff818eb2e2: find_bug.part.2 (STB_LOCAL)
ffffffff818eb3f0-ffffffff818eb436: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bug.c (ffffffff819713a0)
Location: lib/bug.c:132
Inline: True
Inline callers:
  - lib/bug.c:report_bug
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff819711b0-ffffffff81971222: find_bug.part.2 (STB_LOCAL)
ffffffff81971330-ffffffff81971376: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff819cd760)
Location: lib/bug.c:132
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff819cd6f0-ffffffff819cd734: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81a06ac0)
Location: lib/bug.c:132
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81a06a50-ffffffff81a06a94: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81a76420)
Location: lib/bug.c:132
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81a763b0-ffffffff81a763fe: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81aad824)
Location: lib/bug.c:132
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81aad7b0-ffffffff81aad7fe: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff815e7800)
Location: lib/bug.c:133
Inline: False
Direct callers:
  - kernel/kprobes.c:check_kprobe_address_safe
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff815e7800-ffffffff815e78ae: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8160c9c0)
Location: lib/bug.c:133
Inline: False
Direct callers:
  - kernel/kprobes.c:check_kprobe_address_safe
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8160c9c0-ffffffff8160ca6e: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff815efc80)
Location: lib/bug.c:146
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff815efc80-ffffffff815efd31: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8165cd90)
Location: lib/bug.c:146
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8165cd90-ffffffff8165ce41: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81776140)
Location: lib/bug.c:145
Inline: False
Direct callers:
  - kernel/kprobes.c:check_kprobe_address_safe
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81776140-ffffffff81776234: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8201ea80)
Location: lib/bug.c:146
Inline: False
Direct callers:
  - kernel/kprobes.c:check_kprobe_address_safe
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8201ea80-ffffffff8201eb74: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff8209eaa0)
Location: lib/bug.c:146
Inline: False
Direct callers:
  - kernel/kprobes.c:check_kprobe_address_safe
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8209eaa0-ffffffff8209eb8f: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff82176aa0)
Location: lib/bug.c:146
Inline: False
Direct callers:
  - kernel/kprobes.c:check_kprobe_address_safe
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff82176aa0-ffffffff82176b8f: find_bug (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffff800010d83ad8)
Location: lib/bug.c:132
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffff800010d83a48-ffff800010d83ab8: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bug.c (c0e7ebd8)
Location: lib/bug.c:132
Inline: True
Inline callers:
  - lib/bug.c:report_bug
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
c0e7ebd8-c0e7ec50: find_bug.part.0 (STB_LOCAL)
c0e7ed3c-c0e7ed8c: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bug.c (c000000000ec2420)
Location: lib/bug.c:132
Inline: True
Inline callers:
  - lib/bug.c:report_bug
Direct callers:
  - arch/powerpc/xmon/xmon.c:excprint
  - lib/bug.c:report_bug
```
**Symbols:**

```
c000000000ec2420-c000000000ec24d8: find_bug.part.0 (STB_LOCAL)
c000000000ec27e0-c000000000ec2834: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffe0008ae0e8)
Location: lib/bug.c:132
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffe0008ae07c-ffffffe0008ae0ca: find_bug (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81a4c674)
Location: lib/bug.c:132
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81a4c600-ffffffff81a4c64e: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81a097a4)
Location: lib/bug.c:132
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81a09730-ffffffff81a0977e: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81ab8a64)
Location: lib/bug.c:132
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81ab89f0-ffffffff81ab8a3e: find_bug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bug_entry *find_bug(long unsigned int bugaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bug.c (ffffffff81ac4e94)
Location: lib/bug.c:132
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81ac4e20-ffffffff81ac4e6e: find_bug (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>const struct bug_entry *</code> ➡️ <code>struct bug_entry *</code>
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
