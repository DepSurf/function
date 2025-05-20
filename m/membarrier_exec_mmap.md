# Function: <code>membarrier_exec_mmap</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff811018c0)
Location: kernel/sched/membarrier.c:50
Inline: False
```
**Symbols:**

```
ffffffff811018c0-ffffffff811018e3: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff8110c150)
Location: kernel/sched/membarrier.c:50
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff8110c150-ffffffff8110c173: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff81109330)
Location: kernel/sched/membarrier.c:216
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff81109330-ffffffff81109353: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff8110b1d0)
Location: kernel/sched/membarrier.c:216
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff8110b1d0-ffffffff8110b1f3: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff81129a30)
Location: kernel/sched/membarrier.c:217
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff81129a30-ffffffff81129a53: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114cd00)
Location: kernel/sched/membarrier.c:216
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff8114cd00-ffffffff8114cd29: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117bd20)
Location: kernel/sched/membarrier.c:216
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff8117bd20-ffffffff8117bd49: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c9d0)
Location: kernel/sched/membarrier.c:217
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff8118c9d0-ffffffff8118c9fc: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8119b380)
Location: kernel/sched/membarrier.c:220
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff8119b380-ffffffff8119b3ac: membarrier_exec_mmap (STB_GLOBAL)
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
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffff8000101663e8)
Location: kernel/sched/membarrier.c:50
Inline: False
```
**Symbols:**

```
ffff8000101663e8-ffff800010166424: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (c03b25f8)
Location: kernel/sched/membarrier.c:50
Inline: False
```
**Symbols:**

```
c03b25f8-c03b2638: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (c0000000001bdb60)
Location: kernel/sched/membarrier.c:50
Inline: False
```
**Symbols:**

```
c0000000001bdb60-c0000000001bdbbc: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffe00010854e)
Location: kernel/sched/membarrier.c:50
Inline: False
```
**Symbols:**

```
ffffffe00010854e-ffffffe0001085a2: membarrier_exec_mmap (STB_GLOBAL)
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
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810fabd0)
Location: kernel/sched/membarrier.c:50
Inline: False
```
**Symbols:**

```
ffffffff810fabd0-ffffffff810fabf3: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810eadf0)
Location: kernel/sched/membarrier.c:50
Inline: False
```
**Symbols:**

```
ffffffff810eadf0-ffffffff810eae13: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810f7d90)
Location: kernel/sched/membarrier.c:50
Inline: False
```
**Symbols:**

```
ffffffff810f7d90-ffffffff810f7db3: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void membarrier_exec_mmap(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff81102ed0)
Location: kernel/sched/membarrier.c:50
Inline: False
```
**Symbols:**

```
ffffffff81102ed0-ffffffff81102ef3: membarrier_exec_mmap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
