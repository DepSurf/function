# Function: <code>__trace_find_cmdline</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114c920)
Location: kernel/trace/trace.c:1599
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff8114c920-ffffffff8114c9ba: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81155280)
Location: kernel/trace/trace.c:1844
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff81155280-ffffffff8115531a: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115f710)
Location: kernel/trace/trace.c:1888
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff8115f710-ffffffff8115f7aa: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811622c0)
Location: kernel/trace/trace.c:1962
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff811622c0-ffffffff81162448: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116f3d0)
Location: kernel/trace/trace.c:1965
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff8116f3d0-ffffffff8116f448: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117e450)
Location: kernel/trace/trace.c:1977
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff8117e450-ffffffff8117e4c8: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118bd40)
Location: kernel/trace/trace.c:1978
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff8118bd40-ffffffff8118bdb8: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811991e0)
Location: kernel/trace/trace.c:2161
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff811991e0-ffffffff8119925b: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a4b40)
Location: kernel/trace/trace.c:2187
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff811a4b40-ffffffff811a4bbb: __trace_find_cmdline (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff811bbac1)
Location: kernel/trace/trace.c:2291
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff811bb0c0-ffffffff811bb125: __trace_find_cmdline.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b97a1)
Location: kernel/trace/trace.c:2435
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_cmdlines_show
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff811b8c60-ffffffff811b8cc5: __trace_find_cmdline.part.0 (STB_LOCAL)
ffffffff811b8cd0-ffffffff811b8cf3: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b9f11)
Location: kernel/trace/trace.c:2430
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_cmdlines_show
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff811b9510-ffffffff811b957e: __trace_find_cmdline.part.0 (STB_LOCAL)
ffffffff811b9580-ffffffff811b95a3: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e1fd0)
Location: kernel/trace/trace.c:2444
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff811e1fd0-ffffffff811e2056: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81218d70)
Location: kernel/trace/trace.c:2435
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff81218d70-ffffffff81218e36: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81262d80)
Location: kernel/trace/trace.c:2459
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff81262d80-ffffffff81262e43: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81279d60)
Location: kernel/trace/trace.c:2530
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff81279d60-ffffffff81279e23: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81294840)
Location: kernel/trace/trace.c:2525
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff81294840-ffffffff81294904: __trace_find_cmdline (STB_LOCAL)
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
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001021fc20)
Location: kernel/trace/trace.c:2187
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffff80001021fc20-ffff80001021fcd0: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045dd1c)
Location: kernel/trace/trace.c:2187
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
c045dd1c-c045de04: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a36d0)
Location: kernel/trace/trace.c:2187
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
c0000000002a36d0-c0000000002a37c0: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017c60c)
Location: kernel/trace/trace.c:2187
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffe00017c60c-ffffffe00017c6e0: __trace_find_cmdline (STB_LOCAL)
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
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d160)
Location: kernel/trace/trace.c:2187
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff8119d160-ffffffff8119d1db: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811901c0)
Location: kernel/trace/trace.c:2187
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff811901c0-ffffffff8119023b: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119af30)
Location: kernel/trace/trace.c:2187
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff8119af30-ffffffff8119afab: __trace_find_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __trace_find_cmdline(int pid, char *comm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8bd0)
Location: kernel/trace/trace.c:2187
Inline: True
Direct callers:
  - kernel/trace/trace.c:saved_cmdlines_show
  - kernel/trace/trace.c:trace_find_cmdline
```
**Symbols:**

```
ffffffff811a8bd0-ffffffff811a8c4b: __trace_find_cmdline (STB_LOCAL)
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
