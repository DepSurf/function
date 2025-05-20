# Function: <code>ftrace_ops_trampoline</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81163584)
Location: kernel/trace/ftrace.c:1124
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff81163530-ffffffff8116357d: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811723a0)
Location: kernel/trace/ftrace.c:1113
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff811723a0-ffffffff811723ed: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117fe10)
Location: kernel/trace/ftrace.c:1062
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff8117fe10-ffffffff8117fe5d: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118cf30)
Location: kernel/trace/ftrace.c:1059
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff8118cf30-ffffffff8118cf71: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81198b40)
Location: kernel/trace/ftrace.c:1060
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff81198b40-ffffffff81198b81: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ae920)
Location: kernel/trace/ftrace.c:1051
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff811ae8d0-ffffffff811ae911: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac280)
Location: kernel/trace/ftrace.c:1050
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff811ac230-ffffffff811ac271: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811acdc0)
Location: kernel/trace/ftrace.c:1050
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff811acd70-ffffffff811acdb1: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d6a20)
Location: kernel/trace/ftrace.c:1051
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff811d69d0-ffffffff811d6a11: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120be60)
Location: kernel/trace/ftrace.c:1045
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff8120be60-ffffffff8120bee2: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81254920)
Location: kernel/trace/ftrace.c:1045
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff81254920-ffffffff812549a2: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126bc40)
Location: kernel/trace/ftrace.c:1076
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff8126bc40-ffffffff8126bcc2: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81286190)
Location: kernel/trace/ftrace.c:1076
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff81286190-ffffffff81286212: ftrace_ops_trampoline (STB_GLOBAL)
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
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010211500)
Location: kernel/trace/ftrace.c:1060
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffff800010211500-ffff800010211554: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0450024)
Location: kernel/trace/ftrace.c:1060
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
c0450024-c045009c: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000290f40)
Location: kernel/trace/ftrace.c:1060
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
c000000000290f40-c000000000290fb4: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000171ad2)
Location: kernel/trace/ftrace.c:1060
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffe000171ad2-ffffffe000171b0e: ftrace_ops_trampoline (STB_GLOBAL)
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
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81191160)
Location: kernel/trace/ftrace.c:1060
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff81191160-ffffffff811911a1: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81184270)
Location: kernel/trace/ftrace.c:1060
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff81184270-ffffffff811842b1: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118ef30)
Location: kernel/trace/ftrace.c:1060
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff8118ef30-ffffffff8118ef71: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ftrace_ops *ftrace_ops_trampoline(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119cac0)
Location: kernel/trace/ftrace.c:1060
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:is_ftrace_trampoline
```
**Symbols:**

```
ffffffff8119cac0-ffffffff8119cb28: ftrace_ops_trampoline (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
