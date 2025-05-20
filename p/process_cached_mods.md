# Function: <code>process_cached_mods</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8115a8a1)
Location: kernel/trace/ftrace.c:4070
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8116742a)
Location: kernel/trace/ftrace.c:4038
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117612c)
Location: kernel/trace/ftrace.c:4026
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81183d6c)
Location: kernel/trace/ftrace.c:3985
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81190ad1)
Location: kernel/trace/ftrace.c:4021
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119cad1)
Location: kernel/trace/ftrace.c:4045
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void process_cached_mods(const char *mod_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b1de0)
Location: kernel/trace/ftrace.c:4172
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff811b1de0-ffffffff811b1e89: process_cached_mods (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void process_cached_mods(const char *mod_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811af850)
Location: kernel/trace/ftrace.c:4249
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff811af850-ffffffff811af8f9: process_cached_mods (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b102b)
Location: kernel/trace/ftrace.c:4249
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
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
In kernel/trace/ftrace.c (ffffffff811daebb)
Location: kernel/trace/ftrace.c:4249
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
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
In kernel/trace/ftrace.c (ffffffff81210e51)
Location: kernel/trace/ftrace.c:4389
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
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
In kernel/trace/ftrace.c (ffffffff8125a2f9)
Location: kernel/trace/ftrace.c:4410
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
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
In kernel/trace/ftrace.c (ffffffff81271763)
Location: kernel/trace/ftrace.c:4565
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
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
In kernel/trace/ftrace.c (ffffffff8128bbbf)
Location: kernel/trace/ftrace.c:4531
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff80001021591c)
Location: kernel/trace/ftrace.c:4045
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c045467c)
Location: kernel/trace/ftrace.c:4045
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000297314)
Location: kernel/trace/ftrace.c:4045
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe00017562a)
Location: kernel/trace/ftrace.c:4045
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811950f1)
Location: kernel/trace/ftrace.c:4045
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81188201)
Location: kernel/trace/ftrace.c:4045
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81192ec1)
Location: kernel/trace/ftrace.c:4045
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a0a51)
Location: kernel/trace/ftrace.c:4045
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
