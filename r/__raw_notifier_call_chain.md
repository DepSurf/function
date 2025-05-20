# Function: <code>__raw_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a1560)
Location: kernel/notifier.c:390
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
```
**Symbols:**

```
ffffffff810a1560-ffffffff810a1570: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4c96)
Location: kernel/notifier.c:390
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
Direct callers:
  - kernel/cpu.c:__cpu_notify
```
**Symbols:**

```
ffffffff810a4c80-ffffffff810a4c90: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aa8f6)
Location: kernel/notifier.c:390
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810aa8e0-ffffffff810aa8f0: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a7476)
Location: kernel/notifier.c:390
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810a7460-ffffffff810a7470: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810adbf6)
Location: kernel/notifier.c:390
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810adbe0-ffffffff810adbf0: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b4a65)
Location: kernel/notifier.c:390
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810b4a50-ffffffff810b4a60: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bdbb5)
Location: kernel/notifier.c:390
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810bdba0-ffffffff810bdbb0: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3b75)
Location: kernel/notifier.c:392
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810c3b60-ffffffff810c3b70: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ccc85)
Location: kernel/notifier.c:392
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810ccc70-ffffffff810ccc80: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6da5)
Location: kernel/notifier.c:357
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810d6800-ffffffff810d6810: __raw_notifier_call_chain (STB_GLOBAL)
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
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012bae4)
Location: kernel/notifier.c:392
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffff80001012ba60-ffff80001012babc: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037bf24)
Location: kernel/notifier.c:392
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
c037bee0-c037bf0c: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000174640)
Location: kernel/notifier.c:392
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
c000000000174610-c000000000174624: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e07a8)
Location: kernel/notifier.c:392
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffe0000e0740-ffffffe0000e078a: __raw_notifier_call_chain (STB_GLOBAL)
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
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c7005)
Location: kernel/notifier.c:392
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810c6ff0-ffffffff810c7000: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5825)
Location: kernel/notifier.c:392
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810b5810-ffffffff810b5820: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6555)
Location: kernel/notifier.c:392
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810c6540-ffffffff810c6550: __raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v, int nr_to_call, int *nr_calls);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ce965)
Location: kernel/notifier.c:392
Inline: True
Inline callers:
  - kernel/notifier.c:raw_notifier_call_chain
```
**Symbols:**

```
ffffffff810ce950-ffffffff810ce960: __raw_notifier_call_chain (STB_GLOBAL)
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
