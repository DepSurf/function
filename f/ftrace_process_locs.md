# Function: <code>ftrace_process_locs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81143280)
Location: kernel/trace/ftrace.c:4798
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_init
  - kernel/trace/ftrace.c:ftrace_init
```
**Symbols:**

```
ffffffff81143280-ffffffff811437eb: ftrace_process_locs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114b120)
Location: kernel/trace/ftrace.c:4835
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff8114b120-ffffffff8114b525: ftrace_process_locs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81155010)
Location: kernel/trace/ftrace.c:4884
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff81155010-ffffffff81155415: ftrace_process_locs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81157970)
Location: kernel/trace/ftrace.c:5579
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff81157970-ffffffff81157d33: ftrace_process_locs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81164470)
Location: kernel/trace/ftrace.c:5543
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff81164470-ffffffff81164833: ftrace_process_locs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5529
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff811731e0-ffffffff81173551: ftrace_process_locs (STB_LOCAL)
ffffffff81177bc9-ffffffff81177bdf: ftrace_process_locs.cold.71 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5489
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff81180e00-ffffffff8118116c: ftrace_process_locs (STB_LOCAL)
ffffffff81185173-ffffffff81185189: ftrace_process_locs.cold.68 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5537
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff8118dc20-ffffffff8118df74: ftrace_process_locs (STB_LOCAL)
ffffffff81192183-ffffffff8119221e: ftrace_process_locs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5574
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff81199b80-ffffffff81199eff: ftrace_process_locs (STB_LOCAL)
ffffffff8119e087-ffffffff8119e09e: ftrace_process_locs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811af970)
Location: kernel/trace/ftrace.c:6062
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff811af970-ffffffff811afae4: ftrace_process_locs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ad330)
Location: kernel/trace/ftrace.c:6171
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff811ad330-ffffffff811ad4a4: ftrace_process_locs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6174
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff811addd0-ffffffff811ae011: ftrace_process_locs.isra.0 (STB_LOCAL)
ffffffff81bd71c6-ffffffff81bd71df: ftrace_process_locs.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6175
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff811d7b90-ffffffff811d7de5: ftrace_process_locs.isra.0 (STB_LOCAL)
ffffffff81cb4659-ffffffff81cb469f: ftrace_process_locs.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6588
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff8120d250-ffffffff8120d51f: ftrace_process_locs (STB_LOCAL)
ffffffff81e65621-ffffffff81e65667: ftrace_process_locs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6672
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff81256120-ffffffff812563e2: ftrace_process_locs (STB_LOCAL)
ffffffff8205cdea-ffffffff8205ce1f: ftrace_process_locs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6476
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff8126d4e0-ffffffff8126d8eb: ftrace_process_locs (STB_LOCAL)
ffffffff820db718-ffffffff820db7ab: ftrace_process_locs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6480
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff81287ad0-ffffffff81287ddf: ftrace_process_locs (STB_LOCAL)
ffffffff821b7489-ffffffff821b74b6: ftrace_process_locs.cold (STB_LOCAL)
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
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010212790)
Location: kernel/trace/ftrace.c:5574
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffff800010212790-ffff800010212bc0: ftrace_process_locs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c04513cc)
Location: kernel/trace/ftrace.c:5574
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
c04513cc-c0451814: ftrace_process_locs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000292470)
Location: kernel/trace/ftrace.c:5574
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
c000000000292470-c000000000292a30: ftrace_process_locs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000172b74)
Location: kernel/trace/ftrace.c:5574
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffe000172b74-ffffffe000172f4c: ftrace_process_locs (STB_LOCAL)
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
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5574
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff811921a0-ffffffff8119251f: ftrace_process_locs (STB_LOCAL)
ffffffff811966a7-ffffffff811966be: ftrace_process_locs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5574
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff811852b0-ffffffff81185626: ftrace_process_locs (STB_LOCAL)
ffffffff811897b7-ffffffff811897cd: ftrace_process_locs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5574
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff8118ff70-ffffffff811902ef: ftrace_process_locs (STB_LOCAL)
ffffffff81194477-ffffffff8119448e: ftrace_process_locs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ftrace_process_locs(struct module *mod, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5574
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init
  - kernel/trace/ftrace.c:ftrace_module_init
```
**Symbols:**

```
ffffffff8119db20-ffffffff8119de9f: ftrace_process_locs (STB_LOCAL)
ffffffff811a2067-ffffffff811a207e: ftrace_process_locs.cold (STB_LOCAL)
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
