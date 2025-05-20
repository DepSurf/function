# Function: <code>ftrace_check_record</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81140c20)
Location: kernel/trace/ftrace.c:2015
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_test_record
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff81140c20-ffffffff81140d8c: ftrace_check_record.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81149310)
Location: kernel/trace/ftrace.c:2040
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff81149310-ffffffff811494b1: ftrace_check_record.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811531c0)
Location: kernel/trace/ftrace.c:2054
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff811531c0-ffffffff81153361: ftrace_check_record.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81155680)
Location: kernel/trace/ftrace.c:2139
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff81155680-ffffffff8115582b: ftrace_check_record.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81161f20)
Location: kernel/trace/ftrace.c:2115
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff81161f20-ffffffff811620cb: ftrace_check_record.isra.12 (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff81170df0)
Location: kernel/trace/ftrace.c:2104
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff81170df0-ffffffff81170f96: ftrace_check_record.isra.14 (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff8117e890)
Location: kernel/trace/ftrace.c:2053
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff8117e890-ffffffff8117ea36: ftrace_check_record.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118ad60)
Location: kernel/trace/ftrace.c:2052
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff8118ad60-ffffffff8118aefb: ftrace_check_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81196c50)
Location: kernel/trace/ftrace.c:2053
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff81196c50-ffffffff81196deb: ftrace_check_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811abf50)
Location: kernel/trace/ftrace.c:2068
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff811abf50-ffffffff811ac180: ftrace_check_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a9810)
Location: kernel/trace/ftrace.c:2069
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff811a9810-ffffffff811a9a2b: ftrace_check_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aa3d0)
Location: kernel/trace/ftrace.c:2075
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff811aa3d0-ffffffff811aa5ef: ftrace_check_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d3ee0)
Location: kernel/trace/ftrace.c:2076
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff811d3ee0-ffffffff811d40ff: ftrace_check_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81208a40)
Location: kernel/trace/ftrace.c:2087
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
```
**Symbols:**

```
ffffffff81208a40-ffffffff81208cc7: ftrace_check_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81250fc0)
Location: kernel/trace/ftrace.c:2138
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
```
**Symbols:**

```
ffffffff81250fc0-ffffffff81251270: ftrace_check_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81268340)
Location: kernel/trace/ftrace.c:2183
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
```
**Symbols:**

```
ffffffff81268340-ffffffff812686bb: ftrace_check_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812825b0)
Location: kernel/trace/ftrace.c:2182
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
```
**Symbols:**

```
ffffffff812825b0-ffffffff8128292b: ftrace_check_record (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffff80001020fbe0)
Location: kernel/trace/ftrace.c:2053
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffff80001020fbe0-ffff80001020fd34: ftrace_check_record.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c044de58)
Location: kernel/trace/ftrace.c:2053
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
c044de58-c044dfb8: ftrace_check_record (STB_LOCAL)
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
In kernel/trace/ftrace.c (c00000000028eee0)
Location: kernel/trace/ftrace.c:2053
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
c00000000028eee0-c00000000028f0cc: ftrace_check_record.isra.0 (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffe000170a0c)
Location: kernel/trace/ftrace.c:2053
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffe000170a0c-ffffffe000170b6c: ftrace_check_record.isra.0 (STB_LOCAL)
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
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f270)
Location: kernel/trace/ftrace.c:2053
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff8118f270-ffffffff8118f40b: ftrace_check_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811823b0)
Location: kernel/trace/ftrace.c:2053
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff811823b0-ffffffff8118254b: ftrace_check_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118d040)
Location: kernel/trace/ftrace.c:2053
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff8118d040-ffffffff8118d1db: ftrace_check_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ftrace_check_record(struct dyn_ftrace *rec, bool enable, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119aba0)
Location: kernel/trace/ftrace.c:2053
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff8119aba0-ffffffff8119ad3b: ftrace_check_record (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
