# Function: <code>cpu_rmap_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff81415ff0)
Location: lib/cpu_rmap.c:88
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_release
  - lib/cpu_rmap.c:free_irq_cpu_rmap
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffffffff81415ff0-ffffffff81416009: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff8145df66)
Location: lib/cpu_rmap.c:88
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
  - lib/cpu_rmap.c:free_irq_cpu_rmap
```
**Symbols:**

```
ffffffff8145de30-ffffffff8145de49: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff8147c996)
Location: lib/cpu_rmap.c:88
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
  - lib/cpu_rmap.c:free_irq_cpu_rmap
```
**Symbols:**

```
ffffffff8147ca00-ffffffff8147ca19: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff814859c0)
Location: lib/cpu_rmap.c:88
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff814859c0-ffffffff814859d8: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff814c1de5)
Location: lib/cpu_rmap.c:88
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff814c1e90-ffffffff814c1eaf: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff814f2d15)
Location: lib/cpu_rmap.c:88
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff814f2d70-ffffffff814f2d8f: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff81507045)
Location: lib/cpu_rmap.c:88
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff815070a0-ffffffff815070bf: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff8153525c)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff815352a0-ffffffff815352be: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff8155606c)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff815560b0-ffffffff815560ce: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff815df6cb)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff815df500-ffffffff815df548: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff815fce6b)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff815fcca0-ffffffff815fcce8: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff815dfbdb)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff815dfa10-ffffffff815dfa58: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff8164b6eb)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff8164b760-ffffffff8164b7a8: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff8176218d)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff81762210-ffffffff8176225e: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff81890ead)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff81890ff0-ffffffff8189103e: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff818d39af)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff818d3300-ffffffff818d334e: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff81925abe)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff819253e0-ffffffff8192542e: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffff800010662630)
Location: lib/cpu_rmap.c:85
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffff800010662630-ffff800010662674: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (c080b2e8)
Location: lib/cpu_rmap.c:85
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
c080b2e8-c080b314: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (c000000000816820)
Location: lib/cpu_rmap.c:85
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
c000000000816820-c000000000816888: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffe00048f078)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffe00048f128-ffffffe00048f162: cpu_rmap_put (STB_GLOBAL)
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
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff8154e64c)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff8154e690-ffffffff8154e6ae: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff8153e92c)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff8153e970-ffffffff8153e98e: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff8154a38c)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff8154a3d0-ffffffff8154a3ee: cpu_rmap_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int cpu_rmap_put(struct cpu_rmap *rmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpu_rmap.c (ffffffff815641dc)
Location: lib/cpu_rmap.c:85
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
**Symbols:**

```
ffffffff81564220-ffffffff8156423e: cpu_rmap_put (STB_GLOBAL)
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
