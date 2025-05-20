# Function: <code>tracing_set_default_clock</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tracing_set_default_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff826fcb93)
Location: kernel/trace/trace.c:8629
Inline: False
```
**Symbols:**

```
ffffffff826fcb93-ffffffff826fcbd0: tracing_set_default_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tracing_set_default_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828b3aad)
Location: kernel/trace/trace.c:8703
Inline: False
```
**Symbols:**

```
ffffffff828b3aad-ffffffff828b3aea: tracing_set_default_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tracing_set_default_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828cc829)
Location: kernel/trace/trace.c:9209
Inline: False
```
**Symbols:**

```
ffffffff828cc829-ffffffff828cc866: tracing_set_default_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tracing_set_default_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828d4cf2)
Location: kernel/trace/trace.c:9271
Inline: False
```
**Symbols:**

```
ffffffff828d4cf2-ffffffff828d4d59: tracing_set_default_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tracing_set_default_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff82cf5859)
Location: kernel/trace/trace.c:9557
Inline: False
```
**Symbols:**

```
ffffffff82cf5859-ffffffff82cf58c0: tracing_set_default_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tracing_set_default_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff82fe243e)
Location: kernel/trace/trace.c:9690
Inline: False
```
**Symbols:**

```
ffffffff82fe243e-ffffffff82fe24a5: tracing_set_default_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tracing_set_default_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff831ec90f)
Location: kernel/trace/trace.c:10014
Inline: False
```
**Symbols:**

```
ffffffff831ec90f-ffffffff831ec976: tracing_set_default_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff832d1422)
Location: kernel/trace/trace.c:10171
Inline: True
Inline callers:
  - kernel/trace/trace.c:late_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff83485657)
Location: kernel/trace/trace.c:10225
Inline: True
Inline callers:
  - kernel/trace/trace.c:late_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff83eb45b4)
Location: kernel/trace/trace.c:10322
Inline: True
Inline callers:
  - kernel/trace/trace.c:late_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff836d98c4)
Location: kernel/trace/trace.c:10577
Inline: True
Inline callers:
  - kernel/trace/trace.c:late_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8390be74)
Location: kernel/trace/trace.c:10772
Inline: True
Inline callers:
  - kernel/trace/trace.c:late_trace_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int tracing_set_default_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828bdba3)
Location: kernel/trace/trace.c:9271
Inline: False
```
**Symbols:**

```
ffffffff828bdba3-ffffffff828bdc0a: tracing_set_default_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tracing_set_default_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828b6243)
Location: kernel/trace/trace.c:9271
Inline: False
```
**Symbols:**

```
ffffffff828b6243-ffffffff828b62aa: tracing_set_default_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tracing_set_default_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828d0926)
Location: kernel/trace/trace.c:9271
Inline: False
```
**Symbols:**

```
ffffffff828d0926-ffffffff828d098d: tracing_set_default_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tracing_set_default_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828d5d47)
Location: kernel/trace/trace.c:9271
Inline: False
```
**Symbols:**

```
ffffffff828d5d47-ffffffff828d5dae: tracing_set_default_clock (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
