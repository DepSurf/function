# Function: <code>__blocking_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a1700)
Location: kernel/notifier.c:304
Inline: False
Direct callers:
  - kernel/notifier.c:blocking_notifier_call_chain
```
**Symbols:**

```
ffffffff810a1700-ffffffff810a1760: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4e20)
Location: kernel/notifier.c:304
Inline: False
Direct callers:
  - kernel/notifier.c:blocking_notifier_call_chain
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffffffff810a4e20-ffffffff810a4e80: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aaa80)
Location: kernel/notifier.c:304
Inline: False
Direct callers:
  - kernel/notifier.c:blocking_notifier_call_chain
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffffffff810aaa80-ffffffff810aaae0: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a7820)
Location: kernel/notifier.c:304
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffffffff810a7820-ffffffff810a7888: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810adfa0)
Location: kernel/notifier.c:304
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffffffff810adfa0-ffffffff810ae008: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b4e10)
Location: kernel/notifier.c:304
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffffffff810b4e10-ffffffff810b4e78: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bdf60)
Location: kernel/notifier.c:304
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffffffff810bdf60-ffffffff810bdfc8: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c4020)
Location: kernel/notifier.c:306
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffffffff810c4020-ffffffff810c408b: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cd130)
Location: kernel/notifier.c:306
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffffffff810cd130-ffffffff810cd19b: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6b60)
Location: kernel/notifier.c:271
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffffffff810d6b60-ffffffff810d6bcb: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012bfb0)
Location: kernel/notifier.c:306
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffff80001012bfb0-ffff80001012c04c: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037c4dc)
Location: kernel/notifier.c:306
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
c037c4dc-c037c55c: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000174e10)
Location: kernel/notifier.c:306
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
c000000000174e10-c000000000174eb8: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e0c74)
Location: kernel/notifier.c:306
Inline: True
```
**Symbols:**

```
ffffffe0000e0c74-ffffffe0000e0ce2: __blocking_notifier_call_chain (STB_GLOBAL)
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
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c74b0)
Location: kernel/notifier.c:306
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffffffff810c74b0-ffffffff810c751b: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5cd0)
Location: kernel/notifier.c:306
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffffffff810b5cd0-ffffffff810b5d3b: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6a00)
Location: kernel/notifier.c:306
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffffffff810c6a00-ffffffff810c6a6b: __blocking_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __blocking_notifier_call_chain(struct blocking_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ceec0)
Location: kernel/notifier.c:306
Inline: True
Direct callers:
  - kernel/power/main.c:pm_notifier_call_chain
```
**Symbols:**

```
ffffffff810ceec0-ffffffff810cef2b: __blocking_notifier_call_chain (STB_GLOBAL)
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
