# Function: <code>prctl_set_mm_exe_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81092a50)
Location: kernel/sys.c:1667
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff81092a50-ffffffff81092bad: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81095be0)
Location: kernel/sys.c:1667
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff81095be0-ffffffff81095d34: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109abd0)
Location: kernel/sys.c:1668
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff8109abd0-ffffffff8109ad0d: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810979d0)
Location: kernel/sys.c:1774
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810979d0-ffffffff81097b0b: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109e6c0)
Location: kernel/sys.c:1781
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff8109e6c0-ffffffff8109e7fb: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a3f20)
Location: kernel/sys.c:1835
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810a3f20-ffffffff810a4064: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810accf0)
Location: kernel/sys.c:1836
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810accf0-ffffffff810ace34: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b2530)
Location: kernel/sys.c:1837
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810b2530-ffffffff810b266a: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b8c00)
Location: kernel/sys.c:1827
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810b8c00-ffffffff810b8d3a: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c0640)
Location: kernel/sys.c:1843
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810c0640-ffffffff810c077a: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bccb0)
Location: kernel/sys.c:1844
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810bccb0-ffffffff810bce54: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810be540)
Location: kernel/sys.c:1861
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810be540-ffffffff810be6e9: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d02c0)
Location: kernel/sys.c:1870
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810d02c0-ffffffff810d0364: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810e91f0)
Location: kernel/sys.c:1882
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810e91f0-ffffffff810e92b0: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110a0a0)
Location: kernel/sys.c:1887
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff8110a0a0-ffffffff8110a167: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81116370)
Location: kernel/sys.c:1905
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff81116370-ffffffff8111643c: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8111fd60)
Location: kernel/sys.c:1918
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff8111fd60-ffffffff8111fe2c: prctl_set_mm_exe_file (STB_LOCAL)
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
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff800010114ff8)
Location: kernel/sys.c:1827
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffff800010114ff8-ffff800010115178: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036ae4c)
Location: kernel/sys.c:1827
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
c036ae4c-c036afb4: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015cf20)
Location: kernel/sys.c:1827
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
c00000000015cf20-c00000000015d128: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d2050)
Location: kernel/sys.c:1827
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffe0000d2050-ffffffe0000d2170: prctl_set_mm_exe_file (STB_LOCAL)
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
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b2f70)
Location: kernel/sys.c:1827
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810b2f70-ffffffff810b30aa: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a18a0)
Location: kernel/sys.c:1827
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810a18a0-ffffffff810a19da: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b24d0)
Location: kernel/sys.c:1827
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810b24d0-ffffffff810b260a: prctl_set_mm_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int prctl_set_mm_exe_file(struct mm_struct *mm, unsigned int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810baad0)
Location: kernel/sys.c:1827
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810baad0-ffffffff810bac0a: prctl_set_mm_exe_file (STB_LOCAL)
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
