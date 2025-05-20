# Function: <code>stack_trace_print</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void stack_trace_print();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff81158130)
Location: kernel/trace/trace_stack.c:43
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:check_stack
```
**Symbols:**

```
ffffffff81158130-ffffffff811581c5: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void stack_trace_print();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff811629b0)
Location: kernel/trace/trace_stack.c:43
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:check_stack
```
**Symbols:**

```
ffffffff811629b0-ffffffff81162a57: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void stack_trace_print();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff8116dce0)
Location: kernel/trace/trace_stack.c:43
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:check_stack
```
**Symbols:**

```
ffffffff8116dce0-ffffffff8116dd87: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void stack_trace_print();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff81170fe0)
Location: kernel/trace/trace_stack.c:44
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:check_stack
```
**Symbols:**

```
ffffffff81170fe0-ffffffff8117107d: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void stack_trace_print();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff8117e1a0)
Location: kernel/trace/trace_stack.c:45
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:check_stack
```
**Symbols:**

```
ffffffff8117e1a0-ffffffff8117e23d: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void stack_trace_print();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff8118d6c2)
Location: kernel/trace/trace_stack.c:45
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:check_stack
```
**Symbols:**

```
ffffffff8118d6c2-ffffffff8118d737: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void stack_trace_print();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (ffffffff8119b042)
Location: kernel/trace/trace_stack.c:45
Inline: False
Direct callers:
  - kernel/trace/trace_stack.c:check_stack
```
**Symbols:**

```
ffffffff8119b042-ffffffff8119b0b7: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void stack_trace_print(long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:23
Inline: True
```
**Symbols:**

```
ffffffff81126189-ffffffff811261cd: stack_trace_print.cold (STB_LOCAL)
ffffffff81125db0-ffffffff81125dde: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:23
Inline: True
```
**Symbols:**

```
ffffffff81132159-ffffffff8113218a: stack_trace_print.cold (STB_LOCAL)
ffffffff81131d80-ffffffff81131dad: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:23
Inline: True
```
**Symbols:**

```
ffffffff811415c6-ffffffff811415f7: stack_trace_print.cold (STB_LOCAL)
ffffffff811411a0-ffffffff811411cd: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:23
Inline: True
```
**Symbols:**

```
ffffffff81be3806-ffffffff81be3837: stack_trace_print.cold (STB_LOCAL)
ffffffff8113d440-ffffffff8113d46d: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:23
Inline: True
```
**Symbols:**

```
ffffffff81bd5688-ffffffff81bd56b9: stack_trace_print.cold (STB_LOCAL)
ffffffff8113e690-ffffffff8113e6bd: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:23
Inline: True
Direct callers:
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff81cb087c-ffffffff81cb08ad: stack_trace_print.cold (STB_LOCAL)
ffffffff81161b20-ffffffff81161b4d: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:24
Inline: True
Direct callers:
  - mm/kfence/report.c:kfence_report_error
  - mm/kfence/report.c:kfence_report_error
  - mm/kfence/report.c:kfence_report_error
  - lib/stackdepot.c:stack_depot_print
```
**Symbols:**

```
ffffffff81e61ddd-ffffffff81e61e22: stack_trace_print.cold (STB_LOCAL)
ffffffff811949f0-ffffffff81194a2e: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811d2660)
Location: kernel/stacktrace.c:24
Inline: True
Direct callers:
  - mm/kfence/report.c:kfence_report_error
  - mm/kfence/report.c:kfence_report_error
  - mm/kfence/report.c:kfence_report_error
  - lib/stackdepot.c:stack_depot_print
```
**Symbols:**

```
ffffffff811d2660-ffffffff811d26d9: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811e6950)
Location: kernel/stacktrace.c:24
Inline: True
Direct callers:
  - mm/kfence/report.c:kfence_report_error
  - mm/kfence/report.c:kfence_report_error
  - mm/kfence/report.c:kfence_report_error
  - lib/stackdepot.c:stack_depot_print
```
**Symbols:**

```
ffffffff811e6950-ffffffff811e69c9: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811fc6a0)
Location: kernel/stacktrace.c:24
Inline: True
Direct callers:
  - mm/kfence/report.c:kfence_report_error
  - mm/kfence/report.c:kfence_report_error
  - mm/kfence/report.c:kfence_report_error
  - lib/stackdepot.c:stack_depot_print
```
**Symbols:**

```
ffffffff811fc6a0-ffffffff811fc719: stack_trace_print (STB_GLOBAL)
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
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffff800010199818)
Location: kernel/stacktrace.c:23
Inline: True
```
**Symbols:**

```
ffff800010199818-ffff8000101998a4: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (c03e4238)
Location: kernel/stacktrace.c:23
Inline: True
```
**Symbols:**

```
c03e4238-c03e42a8: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (c0000000001f9a00)
Location: kernel/stacktrace.c:23
Inline: True
```
**Symbols:**

```
c0000000001f9a00-c0000000001f9ab8: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffe000129e1a)
Location: kernel/stacktrace.c:23
Inline: True
```
**Symbols:**

```
ffffffe000129e1a-ffffffe000129e88: stack_trace_print (STB_GLOBAL)
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
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:23
Inline: True
```
**Symbols:**

```
ffffffff8112a909-ffffffff8112a93a: stack_trace_print.cold (STB_LOCAL)
ffffffff8112a530-ffffffff8112a55d: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:23
Inline: True
```
**Symbols:**

```
ffffffff8111d179-ffffffff8111d1aa: stack_trace_print.cold (STB_LOCAL)
ffffffff8111cda0-ffffffff8111cdcd: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:23
Inline: True
```
**Symbols:**

```
ffffffff81128629-ffffffff8112865a: stack_trace_print.cold (STB_LOCAL)
ffffffff81128250-ffffffff8112827d: stack_trace_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void stack_trace_print(const long unsigned int *entries, unsigned int nr_entries, int spaces);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/stacktrace.c (0)
Location: kernel/stacktrace.c:23
Inline: True
```
**Symbols:**

```
ffffffff81134cb9-ffffffff81134cea: stack_trace_print.cold (STB_LOCAL)
ffffffff811348e0-ffffffff8113490d: stack_trace_print (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *entries</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int nr_entries</code>
</li>
<li>
<b>Param added. </b>
<code>int spaces</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int *entries</code> ➡️ <code>const long unsigned int *entries</code>
</li>
</ul>
</details>
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
