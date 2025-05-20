# Function: <code>__wake_up_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __wake_up_bit(wait_queue_head_t *wq, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c3630)
Location: kernel/sched/wait.c:455
Inline: False
Direct callers:
  - kernel/sched/wait.c:wake_up_bit
  - kernel/sched/wait.c:wake_up_atomic_t
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff810c3630-ffffffff810c3696: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __wake_up_bit(wait_queue_head_t *wq, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c6fb0)
Location: kernel/sched/wait.c:455
Inline: False
Direct callers:
  - kernel/sched/wait.c:wake_up_atomic_t
  - kernel/sched/wait.c:wake_up_bit
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff810c6fb0-ffffffff810c7019: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __wake_up_bit(wait_queue_head_t *wq, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ccf20)
Location: kernel/sched/wait.c:452
Inline: False
Direct callers:
  - kernel/sched/wait.c:wake_up_atomic_t
  - kernel/sched/wait.c:wake_up_bit
```
**Symbols:**

```
ffffffff810ccf20-ffffffff810ccf89: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810c9c00)
Location: kernel/sched/wait_bit.c:120
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:wake_up_atomic_t
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff810c9c00-ffffffff810c9c68: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810d1420)
Location: kernel/sched/wait_bit.c:120
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:wake_up_atomic_t
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff810d1420-ffffffff810d1488: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810d99f0)
Location: kernel/sched/wait_bit.c:120
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff810d99f0-ffffffff810d9a58: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810e34f0)
Location: kernel/sched/wait_bit.c:120
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff810e34f0-ffffffff810e3558: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ea100)
Location: kernel/sched/wait_bit.c:121
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff810ea100-ffffffff810ea169: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f5ad0)
Location: kernel/sched/wait_bit.c:121
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff810f5ad0-ffffffff810f5b39: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ff2d3)
Location: kernel/sched/wait_bit.c:121
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff810ff210-ffffffff810ff279: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810fddd3)
Location: kernel/sched/wait_bit.c:121
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff810fdd10-ffffffff810fdd79: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff811001b3)
Location: kernel/sched/wait_bit.c:121
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff811000f0-ffffffff81100159: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff8111c253)
Location: kernel/sched/wait_bit.c:121
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff8111c190-ffffffff8111c1f9: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81141c52)
Location: kernel/sched/wait_bit.c:121
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
```
**Symbols:**

```
ffffffff8113bc20-ffffffff8113bc9b: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116c922)
Location: kernel/sched/wait_bit.c:121
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
```
**Symbols:**

```
ffffffff811666c0-ffffffff8116673b: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117cf42)
Location: kernel/sched/wait_bit.c:121
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
```
**Symbols:**

```
ffffffff81176b30-ffffffff81176bab: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c5d5)
Location: kernel/sched/wait_bit.c:121
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
```
**Symbols:**

```
ffffffff8118c4d0-ffffffff8118c56e: __wake_up_bit (STB_GLOBAL)
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
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffff800010159220)
Location: kernel/sched/wait_bit.c:121
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffff800010159078-ffff800010159104: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c03a6588)
Location: kernel/sched/wait_bit.c:121
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
c03a6408-c03a6488: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c0000000001ad5d0)
Location: kernel/sched/wait_bit.c:121
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
c0000000001ad5d0-c0000000001ad668: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffe0000ff1f2)
Location: kernel/sched/wait_bit.c:121
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffe0000ff1f2-ffffffe0000ff24a: __wake_up_bit (STB_GLOBAL)
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
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810eeed0)
Location: kernel/sched/wait_bit.c:121
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff810eeed0-ffffffff810eef39: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810def50)
Location: kernel/sched/wait_bit.c:121
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff810def50-ffffffff810defb9: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ec000)
Location: kernel/sched/wait_bit.c:121
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff810ec000-ffffffff810ec069: __wake_up_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __wake_up_bit(struct wait_queue_head *wq_head, void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f7050)
Location: kernel/sched/wait_bit.c:121
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
```
**Symbols:**

```
ffffffff810f7050-ffffffff810f70b9: __wake_up_bit (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wait_queue_head *wq_head</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_head_t *wq</code>
</li>
</ul>
</details>
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
