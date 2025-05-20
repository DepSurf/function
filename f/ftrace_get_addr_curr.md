# Function: <code>ftrace_get_addr_curr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81142e10)
Location: kernel/trace/ftrace.c:2274
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
  - kernel/trace/ftrace.c:__ftrace_replace_code
```
**Symbols:**

```
ffffffff81142e10-ffffffff81142f1f: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114acd0)
Location: kernel/trace/ftrace.c:2326
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff8114acd0-ffffffff8114aded: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81154bc0)
Location: kernel/trace/ftrace.c:2340
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81154bc0-ffffffff81154cdd: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81157510)
Location: kernel/trace/ftrace.c:2425
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81157510-ffffffff8115761b: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81163ff0)
Location: kernel/trace/ftrace.c:2401
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81163ff0-ffffffff811640fb: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81172e60)
Location: kernel/trace/ftrace.c:2390
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81172e60-ffffffff81172f6b: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81180a80)
Location: kernel/trace/ftrace.c:2339
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81180a80-ffffffff81180b8b: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118c2e8)
Location: kernel/trace/ftrace.c:2338
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff8118c190-ffffffff8118c2a6: ftrace_get_addr_curr.part.0 (STB_LOCAL)
ffffffff8118dff0-ffffffff8118e01e: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81199810)
Location: kernel/trace/ftrace.c:2339
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81199810-ffffffff81199939: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:2442
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff811b46c1-ffffffff811b4700: ftrace_get_addr_curr.cold (STB_LOCAL)
ffffffff811af780-ffffffff811af7e6: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:2471
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81be517e-ffffffff81be51bd: ftrace_get_addr_curr.cold (STB_LOCAL)
ffffffff811ad140-ffffffff811ad1a6: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811adbe0)
Location: kernel/trace/ftrace.c:2477
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff811adbe0-ffffffff811add07: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d79a0)
Location: kernel/trace/ftrace.c:2478
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff811d79a0-ffffffff811d7ac7: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120d020)
Location: kernel/trace/ftrace.c:2522
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff8120d020-ffffffff8120d159: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81255bf0)
Location: kernel/trace/ftrace.c:2571
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81255bf0-ffffffff81255d36: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126cfa0)
Location: kernel/trace/ftrace.c:2654
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff8126cfa0-ffffffff8126d0e6: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81287590)
Location: kernel/trace/ftrace.c:2620
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81287590-ffffffff812876d6: ftrace_get_addr_curr (STB_GLOBAL)
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
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010212320)
Location: kernel/trace/ftrace.c:2339
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffff800010212320-ffff800010212428: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0450ed8)
Location: kernel/trace/ftrace.c:2339
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
c0450ed8-c0451018: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (c00000000028fef0)
Location: kernel/trace/ftrace.c:2339
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
c00000000028fd10-c00000000028fea8: ftrace_get_addr_curr.part.0 (STB_LOCAL)
c000000000292ac0-c000000000292b04: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe0001726f8)
Location: kernel/trace/ftrace.c:2339
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffe0001726f8-ffffffe000172808: ftrace_get_addr_curr (STB_GLOBAL)
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
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81191e30)
Location: kernel/trace/ftrace.c:2339
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81191e30-ffffffff81191f59: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81184f40)
Location: kernel/trace/ftrace.c:2339
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff81184f40-ffffffff81185069: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118fc00)
Location: kernel/trace/ftrace.c:2339
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff8118fc00-ffffffff8118fd29: ftrace_get_addr_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ftrace_get_addr_curr(struct dyn_ftrace *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119d7b0)
Location: kernel/trace/ftrace.c:2339
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - kernel/trace/ftrace.c:__ftrace_replace_code
  - kernel/trace/ftrace.c:ftrace_bug
```
**Symbols:**

```
ffffffff8119d7b0-ffffffff8119d8d9: ftrace_get_addr_curr (STB_GLOBAL)
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
