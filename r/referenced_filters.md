# Function: <code>referenced_filters</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114364e)
Location: kernel/trace/ftrace.c:2817
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_process_locs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114d6c8)
Location: kernel/trace/ftrace.c:4938
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81157608)
Location: kernel/trace/ftrace.c:4987
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8115a6fa)
Location: kernel/trace/ftrace.c:5682
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
In kernel/trace/ftrace.c (ffffffff8116738a)
Location: kernel/trace/ftrace.c:5665
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
In kernel/trace/ftrace.c (ffffffff811761fa)
Location: kernel/trace/ftrace.c:5651
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
In kernel/trace/ftrace.c (ffffffff81183e3a)
Location: kernel/trace/ftrace.c:5611
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
In kernel/trace/ftrace.c (ffffffff81190ba1)
Location: kernel/trace/ftrace.c:5659
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
In kernel/trace/ftrace.c (ffffffff8119cba1)
Location: kernel/trace/ftrace.c:5696
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
int referenced_filters(struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aeb30)
Location: kernel/trace/ftrace.c:6184
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff811aeb30-ffffffff811aec63: referenced_filters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int referenced_filters(struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac490)
Location: kernel/trace/ftrace.c:6314
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff811ac490-ffffffff811ac62e: referenced_filters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int referenced_filters(struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ad000)
Location: kernel/trace/ftrace.c:6319
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff811ad000-ffffffff811ad15e: referenced_filters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int referenced_filters(struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6320
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff811d6c90-ffffffff811d6e65: referenced_filters (STB_LOCAL)
ffffffff81cb440c-ffffffff81cb4430: referenced_filters.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int referenced_filters(struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6742
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff8120bfb0-ffffffff8120c13a: referenced_filters (STB_LOCAL)
ffffffff81e653ca-ffffffff81e653ee: referenced_filters.cold (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff8125a3de)
Location: kernel/trace/ftrace.c:6858
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
In kernel/trace/ftrace.c (ffffffff812718ca)
Location: kernel/trace/ftrace.c:6673
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
In kernel/trace/ftrace.c (ffffffff8128bcea)
Location: kernel/trace/ftrace.c:6677
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
In kernel/trace/ftrace.c (ffff8000102159d4)
Location: kernel/trace/ftrace.c:5696
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
In kernel/trace/ftrace.c (c045473c)
Location: kernel/trace/ftrace.c:5696
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
In kernel/trace/ftrace.c (c000000000297420)
Location: kernel/trace/ftrace.c:5696
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
In kernel/trace/ftrace.c (ffffffe0001755a6)
Location: kernel/trace/ftrace.c:5696
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
In kernel/trace/ftrace.c (ffffffff811951c1)
Location: kernel/trace/ftrace.c:5696
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
In kernel/trace/ftrace.c (ffffffff811882d1)
Location: kernel/trace/ftrace.c:5696
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
In kernel/trace/ftrace.c (ffffffff81192f91)
Location: kernel/trace/ftrace.c:5696
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
In kernel/trace/ftrace.c (ffffffff811a0b21)
Location: kernel/trace/ftrace.c:5696
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
