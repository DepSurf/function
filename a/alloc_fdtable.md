# Function: <code>alloc_fdtable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81229d80)
Location: fs/file.c:103
Inline: False
Direct callers:
  - fs/file.c:expand_files
  - fs/file.c:dup_fd
```
**Symbols:**

```
ffffffff81229d80-ffffffff81229e6a: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812524f0)
Location: fs/file.c:104
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff812524f0-ffffffff812525da: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81265760)
Location: fs/file.c:104
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff81265760-ffffffff8126584a: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81272e90)
Location: fs/file.c:89
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff81272e90-ffffffff81272f8b: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812957c0)
Location: fs/file.c:90
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff812957c0-ffffffff812958bb: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bb940)
Location: fs/file.c:85
Inline: False
Direct callers:
  - fs/file.c:dup_fd
```
**Symbols:**

```
ffffffff812bb940-ffffffff812bba43: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d0b30)
Location: fs/file.c:85
Inline: False
Direct callers:
  - fs/file.c:dup_fd
```
**Symbols:**

```
ffffffff812d0b30-ffffffff812d0c33: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812edb60)
Location: fs/file.c:85
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff812edb60-ffffffff812edc6a: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ff620)
Location: fs/file.c:85
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff812ff620-ffffffff812ff72a: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81338610)
Location: fs/file.c:85
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_fdtable
```
**Symbols:**

```
ffffffff81338610-ffffffff8133871a: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81343fa0)
Location: fs/file.c:90
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_fdtable
```
**Symbols:**

```
ffffffff81343fa0-ffffffff813440aa: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134a340)
Location: fs/file.c:90
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff8134a340-ffffffff8134a449: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:90
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff813980a0-ffffffff813981be: alloc_fdtable (STB_LOCAL)
ffffffff81cc3dad-ffffffff81cc3dcb: alloc_fdtable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:105
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff8141a800-ffffffff8141a923: alloc_fdtable (STB_LOCAL)
ffffffff81e766b0-ffffffff81e766ce: alloc_fdtable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:105
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff814a6590-ffffffff814a66b3: alloc_fdtable (STB_LOCAL)
ffffffff82068b4e-ffffffff82068b6c: alloc_fdtable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:105
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff814db550-ffffffff814db672: alloc_fdtable (STB_LOCAL)
ffffffff820e848c-ffffffff820e84aa: alloc_fdtable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:105
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff8150db50-ffffffff8150dc72: alloc_fdtable (STB_LOCAL)
ffffffff821c51e6-ffffffff821c5204: alloc_fdtable.cold (STB_LOCAL)
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
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b0af8)
Location: fs/file.c:85
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffff8000103b0af8-ffff8000103b0c1c: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c05903dc)
Location: fs/file.c:85
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
c05903dc-c05904ec: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ac500)
Location: fs/file.c:85
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
c0000000004ac500-c0000000004ac674: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe000274f18)
Location: fs/file.c:85
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffe000274f18-ffffffe00027506e: alloc_fdtable (STB_LOCAL)
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
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f7c00)
Location: fs/file.c:85
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff812f7c00-ffffffff812f7d0a: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e8820)
Location: fs/file.c:85
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff812e8820-ffffffff812e892a: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f5a10)
Location: fs/file.c:85
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff812f5a10-ffffffff812f5b1a: alloc_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fdtable *alloc_fdtable(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81306b50)
Location: fs/file.c:85
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff81306b50-ffffffff81306c5a: alloc_fdtable (STB_LOCAL)
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
