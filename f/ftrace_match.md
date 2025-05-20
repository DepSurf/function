# Function: <code>ftrace_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811412d0)
Location: kernel/trace/ftrace.c:3435
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
```
**Symbols:**

```
ffffffff811412d0-ffffffff81141387: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114c190)
Location: kernel/trace/ftrace.c:3470
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
```
**Symbols:**

```
ffffffff8114c190-ffffffff8114c242: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81156080)
Location: kernel/trace/ftrace.c:3488
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
```
**Symbols:**

```
ffffffff81156080-ffffffff8115613e: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81158b50)
Location: kernel/trace/ftrace.c:3730
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff81158b50-ffffffff81158c0e: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81165640)
Location: kernel/trace/ftrace.c:3698
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff81165640-ffffffff81165708: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81174330)
Location: kernel/trace/ftrace.c:3687
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff81174330-ffffffff811743f8: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81181f80)
Location: kernel/trace/ftrace.c:3646
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff81181f80-ffffffff81182047: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118ed00)
Location: kernel/trace/ftrace.c:3652
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff8118ed00-ffffffff8118edcc: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119acc0)
Location: kernel/trace/ftrace.c:3676
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff8119acc0-ffffffff8119ad8c: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0b40)
Location: kernel/trace/ftrace.c:3803
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff811b0b40-ffffffff811b0c16: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ae5b0)
Location: kernel/trace/ftrace.c:3881
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff811ae5b0-ffffffff811ae686: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aef70)
Location: kernel/trace/ftrace.c:3881
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff811aef70-ffffffff811af03c: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d8da0)
Location: kernel/trace/ftrace.c:3882
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff811d8da0-ffffffff811d8e6c: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120e7d0)
Location: kernel/trace/ftrace.c:3999
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_match_record
  - kernel/trace/ftrace.c:ftrace_match_record
```
**Symbols:**

```
ffffffff8120e7d0-ffffffff8120e8e2: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81257ac0)
Location: kernel/trace/ftrace.c:4019
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_match_record
  - kernel/trace/ftrace.c:ftrace_match_record
```
**Symbols:**

```
ffffffff81257ac0-ffffffff81257bd2: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126f0c0)
Location: kernel/trace/ftrace.c:4174
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_match_record
  - kernel/trace/ftrace.c:ftrace_match_record
```
**Symbols:**

```
ffffffff8126f0c0-ffffffff8126f1cf: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812896d0)
Location: kernel/trace/ftrace.c:4140
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_match_record
  - kernel/trace/ftrace.c:ftrace_match_record
```
**Symbols:**

```
ffffffff812896d0-ffffffff812897df: ftrace_match (STB_LOCAL)
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
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010213a20)
Location: kernel/trace/ftrace.c:3676
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffff800010213a20-ffff800010213b20: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0452840)
Location: kernel/trace/ftrace.c:3676
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_match_record
  - kernel/trace/ftrace.c:ftrace_match_record
```
**Symbols:**

```
c0452840-c0452900: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000294000)
Location: kernel/trace/ftrace.c:3676
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
c000000000294000-c0000000002942b8: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000173bfe)
Location: kernel/trace/ftrace.c:3676
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffe000173bfe-ffffffe000173cde: ftrace_match (STB_LOCAL)
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
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811932e0)
Location: kernel/trace/ftrace.c:3676
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff811932e0-ffffffff811933ac: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811863f0)
Location: kernel/trace/ftrace.c:3676
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff811863f0-ffffffff811864bc: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811910b0)
Location: kernel/trace/ftrace.c:3676
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff811910b0-ffffffff8119117c: ftrace_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ftrace_match(char *str, struct ftrace_glob *g);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119ec40)
Location: kernel/trace/ftrace.c:3676
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff8119ec40-ffffffff8119ed0c: ftrace_match (STB_LOCAL)
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
