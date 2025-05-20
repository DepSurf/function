# Function: <code>generic_exec_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int generic_exec_single(int cpu, struct call_single_data *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81103810)
Location: kernel/smp.c:144
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single_async
```
**Symbols:**

```
ffffffff81103810-ffffffff8110392e: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int generic_exec_single(int cpu, struct call_single_data *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8110ac40)
Location: kernel/smp.c:128
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff8110ac40-ffffffff8110ad52: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int generic_exec_single(int cpu, struct call_single_data *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81112460)
Location: kernel/smp.c:132
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff81112460-ffffffff81112572: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int generic_exec_single(int cpu, struct call_single_data *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81113a40)
Location: kernel/smp.c:141
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff81113a40-ffffffff81113af0: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8111efc0)
Location: kernel/smp.c:141
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff8111efc0-ffffffff8111f079: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8112c2f0)
Location: kernel/smp.c:141
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff8112c2f0-ffffffff8112c3b8: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81137bc0)
Location: kernel/smp.c:141
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff81137bc0-ffffffff81137c88: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:142
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff81142d00-ffffffff81142de4: generic_exec_single (STB_LOCAL)
ffffffff81143839-ffffffff8114386f: generic_exec_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8114e860)
Location: kernel/smp.c:142
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff8114e860-ffffffff8114e930: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115f360)
Location: kernel/smp.c:158
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff8115f360-ffffffff8115f432: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115b300)
Location: kernel/smp.c:279
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff8115b300-ffffffff8115b3d2: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_exec_single(int cpu, struct __call_single_data *csd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115c9f0)
Location: kernel/smp.c:504
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff8115c9f0-ffffffff8115cab2: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int generic_exec_single(int cpu, struct __call_single_data *csd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81181ba0)
Location: kernel/smp.c:504
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff81181ba0-ffffffff81181c9a: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int generic_exec_single(int cpu, struct __call_single_data *csd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811b82c0)
Location: kernel/smp.c:507
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff811b82c0-ffffffff811b83c0: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_exec_single(int cpu, struct __call_single_data *csd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811f95d0)
Location: kernel/smp.c:506
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff811f95d0-ffffffff811f96dc: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_exec_single(int cpu, struct __call_single_data *csd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8120ec30)
Location: kernel/smp.c:375
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff8120ec30-ffffffff8120ed75: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff812263d0)
Location: kernel/smp.c:390
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff812263d0-ffffffff81226515: generic_exec_single (STB_LOCAL)
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
int generic_exec_single(int cpu, call_single_data_t *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffff8000101bcd18)
Location: kernel/smp.c:142
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffff8000101bcd18-ffff8000101bce74: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c0404c40)
Location: kernel/smp.c:142
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
c0404c40-c0404d88: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c000000000222c80)
Location: kernel/smp.c:142
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
c000000000222c80-c000000000222e24: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffe0001404e4)
Location: kernel/smp.c:142
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffe0001404e4-ffffffe0001405cc: generic_exec_single (STB_LOCAL)
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
int generic_exec_single(int cpu, call_single_data_t *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81146e80)
Location: kernel/smp.c:142
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff81146e80-ffffffff81146f50: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8113a180)
Location: kernel/smp.c:142
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff8113a180-ffffffff8113a238: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81144d30)
Location: kernel/smp.c:142
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff81144d30-ffffffff81144e00: generic_exec_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int generic_exec_single(int cpu, call_single_data_t *csd, smp_call_func_t func, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811518b0)
Location: kernel/smp.c:142
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
```
**Symbols:**

```
ffffffff811518b0-ffffffff81151980: generic_exec_single (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct call_single_data *csd</code> ➡️ <code>call_single_data_t *csd</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>smp_call_func_t func</code>
</li>
<li>
<b>Param removed. </b>
<code>void *info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>call_single_data_t *csd</code> ➡️ <code>struct __call_single_data *csd</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __call_single_data *csd</code> ➡️ <code>call_single_data_t *csd</code>
</li>
</ul>
</details>
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
