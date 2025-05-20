# Function: <code>trace_printk_seq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81153050)
Location: kernel/trace/trace.c:7045
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff81153050-ffffffff81153102: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115c270)
Location: kernel/trace/trace.c:7453
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff8115c270-ffffffff8115c322: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81166aa0)
Location: kernel/trace/trace.c:7739
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff81166aa0-ffffffff81166b52: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81169fa0)
Location: kernel/trace/trace.c:8111
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff81169fa0-ffffffff8116a02a: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81176f40)
Location: kernel/trace/trace.c:8122
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff81176f40-ffffffff81176fca: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8225
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff8118658d-ffffffff811865dc: trace_printk_seq.cold.83 (STB_LOCAL)
ffffffff811860c0-ffffffff81186109: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81193f1d)
Location: kernel/trace/trace.c:8299
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff81193f1d-ffffffff81193f6c: trace_printk_seq.cold.83 (STB_LOCAL)
ffffffff81193a20-ffffffff81193a69: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a1bdb)
Location: kernel/trace/trace.c:8808
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff811a1bdb-ffffffff811a1c2a: trace_printk_seq.cold (STB_LOCAL)
ffffffff811a1560-ffffffff811a15a9: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ad5c6)
Location: kernel/trace/trace.c:8864
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff811ad5c6-ffffffff811ad615: trace_printk_seq.cold (STB_LOCAL)
ffffffff811ad010-ffffffff811ad059: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c560d)
Location: kernel/trace/trace.c:9147
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
**Symbols:**

```
ffffffff811c560d-ffffffff811c565f: trace_printk_seq.cold (STB_LOCAL)
ffffffff811c4d10-ffffffff811c4d59: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81be592a)
Location: kernel/trace/trace.c:9280
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
**Symbols:**

```
ffffffff81be592a-ffffffff81be597c: trace_printk_seq.cold (STB_LOCAL)
ffffffff811c2950-ffffffff811c2999: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81bd77d2)
Location: kernel/trace/trace.c:9619
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
**Symbols:**

```
ffffffff81bd77d2-ffffffff81bd7824: trace_printk_seq.cold (STB_LOCAL)
ffffffff811c39c0-ffffffff811c3a09: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811eeb70)
Location: kernel/trace/trace.c:9783
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
**Symbols:**

```
ffffffff811eeb70-ffffffff811eec1b: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81226fc0)
Location: kernel/trace/trace.c:9828
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
**Symbols:**

```
ffffffff81226fc0-ffffffff81227075: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812722f0)
Location: kernel/trace/trace.c:9923
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
**Symbols:**

```
ffffffff812722f0-ffffffff812723a5: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812895f0)
Location: kernel/trace/trace.c:10088
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
**Symbols:**

```
ffffffff812895f0-ffffffff812896a5: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a4970)
Location: kernel/trace/trace.c:10283
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
**Symbols:**

```
ffffffff812a4970-ffffffff812a4a28: trace_printk_seq (STB_GLOBAL)
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
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001022a000)
Location: kernel/trace/trace.c:8864
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffff80001022a000-ffff80001022a07c: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0467698)
Location: kernel/trace/trace.c:8864
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
c0467698-c0467744: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002b1b70)
Location: kernel/trace/trace.c:8864
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
c0000000002b1b70-c0000000002b1c18: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00018467c)
Location: kernel/trace/trace.c:8864
Inline: True
```
**Symbols:**

```
ffffffe00018467c-ffffffe0001846f2: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a5be6)
Location: kernel/trace/trace.c:8864
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff811a5be6-ffffffff811a5c35: trace_printk_seq.cold (STB_LOCAL)
ffffffff811a5630-ffffffff811a5679: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81198b76)
Location: kernel/trace/trace.c:8864
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff81198b76-ffffffff81198bc5: trace_printk_seq.cold (STB_LOCAL)
ffffffff811985e0-ffffffff81198629: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a39b6)
Location: kernel/trace/trace.c:8864
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff811a39b6-ffffffff811a3a05: trace_printk_seq.cold (STB_LOCAL)
ffffffff811a3400-ffffffff811a3449: trace_printk_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_seq(struct trace_seq *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b1746)
Location: kernel/trace/trace.c:8864
Inline: True
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff811b1746-ffffffff811b1795: trace_printk_seq.cold (STB_LOCAL)
ffffffff811b1190-ffffffff811b11d9: trace_printk_seq (STB_GLOBAL)
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
