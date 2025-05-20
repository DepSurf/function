# Function: <code>__unregister_ftrace_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81141d50)
Location: kernel/trace/ftrace.c:456
Inline: False
```
**Symbols:**

```
ffffffff81141d50-ffffffff81141ef6: __unregister_ftrace_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811489f0)
Location: kernel/trace/ftrace.c:433
Inline: False
```
**Symbols:**

```
ffffffff811489f0-ffffffff81148a95: __unregister_ftrace_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811528a0)
Location: kernel/trace/ftrace.c:433
Inline: False
```
**Symbols:**

```
ffffffff811528a0-ffffffff81152945: __unregister_ftrace_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81154cc0)
Location: kernel/trace/ftrace.c:446
Inline: False
```
**Symbols:**

```
ffffffff81154cc0-ffffffff81154d60: __unregister_ftrace_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811614f0)
Location: kernel/trace/ftrace.c:417
Inline: False
```
**Symbols:**

```
ffffffff811614f0-ffffffff81161588: __unregister_ftrace_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81170410)
Location: kernel/trace/ftrace.c:406
Inline: False
```
**Symbols:**

```
ffffffff81170410-ffffffff811704ab: __unregister_ftrace_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117fa70)
Location: kernel/trace/ftrace.c:351
Inline: False
```
**Symbols:**

```
ffffffff8117fa70-ffffffff8117fb11: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:348
Inline: False
```
**Symbols:**

```
ffffffff81191fc1-ffffffff81191fd9: __unregister_ftrace_function.cold (STB_LOCAL)
ffffffff8118cb70-ffffffff8118cc20: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81198770)
Location: kernel/trace/ftrace.c:349
Inline: False
```
**Symbols:**

```
ffffffff81198770-ffffffff81198828: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ae7e0)
Location: kernel/trace/ftrace.c:345
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff811ae7e0-ffffffff811ae89b: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac140)
Location: kernel/trace/ftrace.c:345
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff811ac140-ffffffff811ac1f9: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811acc80)
Location: kernel/trace/ftrace.c:345
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff811acc80-ffffffff811acd39: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d68e0)
Location: kernel/trace/ftrace.c:345
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff811d68e0-ffffffff811d6999: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120bd90)
Location: kernel/trace/ftrace.c:342
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:modify_ftrace_direct_multi
  - kernel/trace/ftrace.c:unregister_ftrace_direct_multi
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_startup
  - kernel/trace/ftrace.c:ftrace_startup
```
**Symbols:**

```
ffffffff8120bd90-ffffffff8120be46: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81254830)
Location: kernel/trace/ftrace.c:342
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_startup
  - kernel/trace/ftrace.c:ftrace_startup
```
**Symbols:**

```
ffffffff81254830-ffffffff812548e6: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126bb60)
Location: kernel/trace/ftrace.c:373
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_startup
  - kernel/trace/ftrace.c:ftrace_startup
```
**Symbols:**

```
ffffffff8126bb60-ffffffff8126bc09: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812860b0)
Location: kernel/trace/ftrace.c:373
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_startup
  - kernel/trace/ftrace.c:ftrace_startup
```
**Symbols:**

```
ffffffff812860b0-ffffffff81286159: __unregister_ftrace_function (STB_GLOBAL)
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
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff8000102110f8)
Location: kernel/trace/ftrace.c:349
Inline: False
```
**Symbols:**

```
ffff8000102110f8-ffff8000102111d4: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c044fc24)
Location: kernel/trace/ftrace.c:349
Inline: False
```
**Symbols:**

```
c044fc24-c044fd04: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000290990)
Location: kernel/trace/ftrace.c:349
Inline: False
```
**Symbols:**

```
c000000000290990-c000000000290a8c: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe0001717ce)
Location: kernel/trace/ftrace.c:349
Inline: False
```
**Symbols:**

```
ffffffe0001717ce-ffffffe00017185a: __unregister_ftrace_function (STB_GLOBAL)
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
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81190d90)
Location: kernel/trace/ftrace.c:349
Inline: False
```
**Symbols:**

```
ffffffff81190d90-ffffffff81190e48: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81183ea0)
Location: kernel/trace/ftrace.c:349
Inline: False
```
**Symbols:**

```
ffffffff81183ea0-ffffffff81183f58: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118eb60)
Location: kernel/trace/ftrace.c:349
Inline: False
```
**Symbols:**

```
ffffffff8118eb60-ffffffff8118ec18: __unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119c6f0)
Location: kernel/trace/ftrace.c:349
Inline: False
```
**Symbols:**

```
ffffffff8119c6f0-ffffffff8119c7a8: __unregister_ftrace_function (STB_GLOBAL)
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
