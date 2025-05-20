# Function: <code>ftrace_test_record</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, int enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81142d30)
Location: kernel/trace/ftrace.c:2124
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81142d30-ffffffff81142d41: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81149dbe)
Location: kernel/trace/ftrace.c:2158
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff8114abe0-ffffffff8114abf1: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81153c3e)
Location: kernel/trace/ftrace.c:2172
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81154ad0-ffffffff81154ae1: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8115702e)
Location: kernel/trace/ftrace.c:2257
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81157430-ffffffff81157441: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81163b9e)
Location: kernel/trace/ftrace.c:2233
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81163fa0-ffffffff81163fb1: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81172a49)
Location: kernel/trace/ftrace.c:2222
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81172e10-ffffffff81172e21: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, int enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81180579)
Location: kernel/trace/ftrace.c:2171
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81180a30-ffffffff81180a41: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118d711)
Location: kernel/trace/ftrace.c:2170
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff8118dfa0-ffffffff8118dfb1: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81199356)
Location: kernel/trace/ftrace.c:2171
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81199730-ffffffff81199741: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aee0b)
Location: kernel/trace/ftrace.c:2224
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff811af600-ffffffff811af611: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac7c7)
Location: kernel/trace/ftrace.c:2226
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff811acfb0-ffffffff811acfc1: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ad2f1)
Location: kernel/trace/ftrace.c:2232
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff811ada50-ffffffff811ada61: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d701d)
Location: kernel/trace/ftrace.c:2233
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff811d77d0-ffffffff811d77e1: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120c2df)
Location: kernel/trace/ftrace.c:2244
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff8120ce30-ffffffff8120ce4b: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81254fee)
Location: kernel/trace/ftrace.c:2295
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff812559b0-ffffffff812559cb: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126c317)
Location: kernel/trace/ftrace.c:2374
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff8126cd30-ffffffff8126cd4b: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81286907)
Location: kernel/trace/ftrace.c:2373
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81287320-ffffffff8128733b: ftrace_test_record (STB_GLOBAL)
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
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010211ebc)
Location: kernel/trace/ftrace.c:2171
Inline: True
```
**Symbols:**

```
ffff8000102122d8-ffff8000102122f4: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c045099c)
Location: kernel/trace/ftrace.c:2171
Inline: True
```
**Symbols:**

```
c0450de0-c0450df8: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000291c70)
Location: kernel/trace/ftrace.c:2171
Inline: True
```
**Symbols:**

```
c000000000292a50-c000000000292a64: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe00017226a)
Location: kernel/trace/ftrace.c:2171
Inline: True
```
**Symbols:**

```
ffffffe00017269e-ffffffe0001726ba: ftrace_test_record (STB_GLOBAL)
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
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81191976)
Location: kernel/trace/ftrace.c:2171
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81191d50-ffffffff81191d61: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81184a86)
Location: kernel/trace/ftrace.c:2171
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff81184e60-ffffffff81184e71: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f746)
Location: kernel/trace/ftrace.c:2171
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff8118fb20-ffffffff8118fb31: ftrace_test_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ftrace_test_record(struct dyn_ftrace *rec, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119d2f6)
Location: kernel/trace/ftrace.c:2171
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
```
**Symbols:**

```
ffffffff8119d6d0-ffffffff8119d6e1: ftrace_test_record (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int enable</code> ➡️ <code>bool enable</code>
</li>
</ul>
</details>
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
