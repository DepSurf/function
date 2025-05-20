# Function: <code>do_swap</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81502400)
Location: lib/sort.c:135
Inline: True
Direct callers:
  - lib/sort.c:sort
  - lib/sort.c:sort
```
**Symbols:**

```
ffffffff81502400-ffffffff8150245b: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81520310)
Location: lib/sort.c:135
Inline: True
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffff81520310-ffffffff8152036b: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff815834c0)
Location: lib/sort.c:133
Inline: False
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffff815834c0-ffffffff8158351b: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff815a0340)
Location: lib/sort.c:133
Inline: False
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffff815a0340-ffffffff815a039b: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff815a7130)
Location: lib/sort.c:133
Inline: False
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffff815a7130-ffffffff815a718b: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81610070)
Location: lib/sort.c:133
Inline: False
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffff81610070-ffffffff816100cb: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_r_func_t swap_func, const void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff816dc3e0)
Location: lib/sort.c:139
Inline: False
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffff816dc3e0-ffffffff816dc477: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_r_func_t swap_func, const void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff817cc0e0)
Location: lib/sort.c:139
Inline: False
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffff817cc0e0-ffffffff817cc177: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_r_func_t swap_func, const void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff8180a520)
Location: lib/sort.c:139
Inline: False
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffff8180a520-ffffffff8180a5b7: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_r_func_t swap_func, const void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81850d00)
Location: lib/sort.c:139
Inline: False
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffff81850d00-ffffffff81850d97: do_swap (STB_LOCAL)
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
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffff800011440ce0)
Location: lib/sort.c:135
Inline: True
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffff800010629818-ffff80001062989c: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sort.c (c07d0a80)
Location: lib/sort.c:135
Inline: True
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
c07d0a80-c07d0b38: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sort.c (c0000000007cb140)
Location: lib/sort.c:135
Inline: True
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
c0000000007cb140-c0000000007cb248: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffe00045a46a)
Location: lib/sort.c:135
Inline: True
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffe00045a46a-ffffffe00045a4f6: do_swap (STB_LOCAL)
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
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff815188f0)
Location: lib/sort.c:135
Inline: True
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffff815188f0-ffffffff8151894b: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81508bf0)
Location: lib/sort.c:135
Inline: True
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffff81508bf0-ffffffff81508c4b: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff81514980)
Location: lib/sort.c:135
Inline: True
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffff81514980-ffffffff815149db: do_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void do_swap(void *a, void *b, size_t size, swap_func_t swap_func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sort.c (ffffffff8152e0f0)
Location: lib/sort.c:135
Inline: True
Direct callers:
  - lib/sort.c:sort_r
  - lib/sort.c:sort_r
```
**Symbols:**

```
ffffffff8152e0f0-ffffffff8152e14b: do_swap (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void *priv</code>
</li>
<li>
<b>Param type changed. </b>
<code>swap_func_t swap_func</code> ➡️ <code>swap_r_func_t swap_func</code>
</li>
</ul>
</details>
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
