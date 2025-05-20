# Function: <code>prctl_set_auxv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81092530)
Location: kernel/sys.c:1919
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff81092530-ffffffff810925ef: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81095690)
Location: kernel/sys.c:1919
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff81095690-ffffffff8109576c: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109a680)
Location: kernel/sys.c:1910
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff8109a680-ffffffff8109a75c: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810978f0)
Location: kernel/sys.c:2016
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810978f0-ffffffff810979cc: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109e5e0)
Location: kernel/sys.c:2019
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff8109e5e0-ffffffff8109e6bc: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a5190)
Location: kernel/sys.c:2079
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810a5190-ffffffff810a526c: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ade40)
Location: kernel/sys.c:2080
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810ade40-ffffffff810adf1c: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b3b90)
Location: kernel/sys.c:2079
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810b3b90-ffffffff810b3c6c: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ba180)
Location: kernel/sys.c:2069
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810ba180-ffffffff810ba25c: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c1e50)
Location: kernel/sys.c:2085
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810c1e50-ffffffff810c1f2c: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bd140)
Location: kernel/sys.c:2089
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810bd140-ffffffff810bd21c: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bf4f0)
Location: kernel/sys.c:2106
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810bf4f0-ffffffff810bf5d6: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d1f70)
Location: kernel/sys.c:2077
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810d1f70-ffffffff810d2056: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810e8680)
Location: kernel/sys.c:2089
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810e8680-ffffffff810e8770: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81109a10)
Location: kernel/sys.c:2094
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff81109a10-ffffffff81109b00: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81115da0)
Location: kernel/sys.c:2112
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff81115da0-ffffffff81115e90: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8111f790)
Location: kernel/sys.c:2125
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff8111f790-ffffffff8111f880: prctl_set_auxv (STB_LOCAL)
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
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff8000101157a8)
Location: kernel/sys.c:2069
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffff8000101157a8-ffff8000101159e0: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036b1f4)
Location: kernel/sys.c:2069
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
c036b1f4-c036b338: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015e150)
Location: kernel/sys.c:2069
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
c00000000015e150-c00000000015e2a8: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d278a)
Location: kernel/sys.c:2069
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffe0000d278a-ffffffe0000d2852: prctl_set_auxv (STB_LOCAL)
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
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b44f0)
Location: kernel/sys.c:2069
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810b44f0-ffffffff810b45cc: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a2e20)
Location: kernel/sys.c:2069
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810a2e20-ffffffff810a2efc: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b3a50)
Location: kernel/sys.c:2069
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810b3a50-ffffffff810b3b2c: prctl_set_auxv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int prctl_set_auxv(struct mm_struct *mm, long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ba490)
Location: kernel/sys.c:2069
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff810ba490-ffffffff810ba56a: prctl_set_auxv (STB_LOCAL)
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
