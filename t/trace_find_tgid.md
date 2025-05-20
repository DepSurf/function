# Function: <code>trace_find_tgid</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811607b5)
Location: kernel/trace/trace.c:1999
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff811659b0-ffffffff811659d8: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116d875)
Location: kernel/trace/trace.c:2002
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff81172940-ffffffff81172968: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117c885)
Location: kernel/trace/trace.c:2014
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff81181930-ffffffff81181952: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118a085)
Location: kernel/trace/trace.c:2015
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff8118f2f0-ffffffff8118f312: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81197795)
Location: kernel/trace/trace.c:2198
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff8119ccb0-ffffffff8119ccd2: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a3155)
Location: kernel/trace/trace.c:2224
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff811a8660-ffffffff811a8682: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bc4b5)
Location: kernel/trace/trace.c:2328
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_start
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff811c0750-ffffffff811c0772: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ba0c5)
Location: kernel/trace/trace.c:2472
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_start
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff811be370-ffffffff811be392: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be1c0)
Location: kernel/trace/trace.c:2483
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff811be1c0-ffffffff811be1e9: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e8a20)
Location: kernel/trace/trace.c:2497
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff811e8a20-ffffffff811e8a49: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81220640)
Location: kernel/trace/trace.c:2488
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff81220640-ffffffff81220679: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126b450)
Location: kernel/trace/trace.c:2512
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff8126b450-ffffffff8126b489: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812825c0)
Location: kernel/trace/trace.c:2583
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff812825c0-ffffffff812825f9: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129d6b0)
Location: kernel/trace/trace.c:2578
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff8129d6b0-ffffffff8129d6e9: trace_find_tgid (STB_GLOBAL)
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
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001021e378)
Location: kernel/trace/trace.c:2224
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffff8000102251a8-ffff8000102251d0: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045c21c)
Location: kernel/trace/trace.c:2224
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
c0462624-c0462670: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a141c)
Location: kernel/trace/trace.c:2224
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
c0000000002aa6a0-c0000000002aa6e8: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017ae4e)
Location: kernel/trace/trace.c:2224
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffe000180152-ffffffe00018017e: trace_find_tgid (STB_GLOBAL)
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
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119b775)
Location: kernel/trace/trace.c:2224
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff811a0c80-ffffffff811a0ca2: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118e7f5)
Location: kernel/trace/trace.c:2224
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff81193c90-ffffffff81193cb2: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81199545)
Location: kernel/trace/trace.c:2224
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff8119ea50-ffffffff8119ea72: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int trace_find_tgid(int pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a71e5)
Location: kernel/trace/trace.c:2224
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_show
  - kernel/trace/trace.c:saved_tgids_next
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffff811ac740-ffffffff811ac762: trace_find_tgid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
