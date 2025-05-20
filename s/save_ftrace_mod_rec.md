# Function: <code>save_ftrace_mod_rec</code>

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
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81162630)
Location: kernel/trace/ftrace.c:5881
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff81162630-ffffffff81162718: save_ftrace_mod_rec.isra.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81171510)
Location: kernel/trace/ftrace.c:5867
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff81171510-ffffffff811715fc: save_ftrace_mod_rec.isra.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117f010)
Location: kernel/trace/ftrace.c:5827
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff8117f010-ffffffff8117f0fc: save_ftrace_mod_rec.isra.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118bee0)
Location: kernel/trace/ftrace.c:5875
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff8118bee0-ffffffff8118bfcd: save_ftrace_mod_rec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81197d10)
Location: kernel/trace/ftrace.c:5912
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff81197d10-ffffffff81197dfd: save_ftrace_mod_rec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void save_ftrace_mod_rec(struct ftrace_mod_map *mod_map, struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac690)
Location: kernel/trace/ftrace.c:6405
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff811ac690-ffffffff811ac77d: save_ftrace_mod_rec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void save_ftrace_mod_rec(struct ftrace_mod_map *mod_map, struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a9fa0)
Location: kernel/trace/ftrace.c:6543
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff811a9fa0-ffffffff811aa08d: save_ftrace_mod_rec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void save_ftrace_mod_rec(struct ftrace_mod_map *mod_map, struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aab60)
Location: kernel/trace/ftrace.c:6548
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff811aab60-ffffffff811aac4d: save_ftrace_mod_rec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void save_ftrace_mod_rec(struct ftrace_mod_map *mod_map, struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d4800)
Location: kernel/trace/ftrace.c:6549
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff811d4800-ffffffff811d48ed: save_ftrace_mod_rec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void save_ftrace_mod_rec(struct ftrace_mod_map *mod_map, struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81209710)
Location: kernel/trace/ftrace.c:6983
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff81209710-ffffffff81209858: save_ftrace_mod_rec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void save_ftrace_mod_rec(struct ftrace_mod_map *mod_map, struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81251de0)
Location: kernel/trace/ftrace.c:7099
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff81251de0-ffffffff81251f28: save_ftrace_mod_rec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void save_ftrace_mod_rec(struct ftrace_mod_map *mod_map, struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81269130)
Location: kernel/trace/ftrace.c:6914
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff81269130-ffffffff81269278: save_ftrace_mod_rec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void save_ftrace_mod_rec(struct ftrace_mod_map *mod_map, struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81283260)
Location: kernel/trace/ftrace.c:6916
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff81283260-ffffffff812833db: save_ftrace_mod_rec (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffff8000102103d8)
Location: kernel/trace/ftrace.c:5912
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffff8000102103d8-ffff8000102104b8: save_ftrace_mod_rec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void save_ftrace_mod_rec(struct ftrace_mod_map *mod_map, struct dyn_ftrace *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c044ea3c)
Location: kernel/trace/ftrace.c:5912
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
c044ea3c-c044eb34: save_ftrace_mod_rec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (c00000000028f600)
Location: kernel/trace/ftrace.c:5912
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
c00000000028f600-c00000000028f730: save_ftrace_mod_rec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000170ea4)
Location: kernel/trace/ftrace.c:5912
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffe000170ea4-ffffffe000170f54: save_ftrace_mod_rec.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81190330)
Location: kernel/trace/ftrace.c:5912
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff81190330-ffffffff8119041d: save_ftrace_mod_rec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81183570)
Location: kernel/trace/ftrace.c:5912
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff81183570-ffffffff8118365d: save_ftrace_mod_rec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118e100)
Location: kernel/trace/ftrace.c:5912
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff8118e100-ffffffff8118e1ed: save_ftrace_mod_rec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119bc90)
Location: kernel/trace/ftrace.c:5912
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff8119bc90-ffffffff8119bd7d: save_ftrace_mod_rec.isra.0 (STB_LOCAL)
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
</ul>
