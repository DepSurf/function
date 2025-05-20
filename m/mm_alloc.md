# Function: <code>mm_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107e350)
Location: kernel/fork.c:669
Inline: False
```
**Symbols:**

```
ffffffff8107e350-ffffffff8107e396: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107fff0)
Location: kernel/fork.c:682
Inline: False
```
**Symbols:**

```
ffffffff8107fff0-ffffffff81080038: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81084940)
Location: kernel/fork.c:833
Inline: False
```
**Symbols:**

```
ffffffff81084940-ffffffff81084996: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081820)
Location: kernel/fork.c:880
Inline: False
```
**Symbols:**

```
ffffffff81081820-ffffffff81081876: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81088100)
Location: kernel/fork.c:890
Inline: False
```
**Symbols:**

```
ffffffff81088100-ffffffff81088156: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108be50)
Location: kernel/fork.c:977
Inline: False
```
**Symbols:**

```
ffffffff8108be50-ffffffff8108bea6: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81093770)
Location: kernel/fork.c:1032
Inline: False
```
**Symbols:**

```
ffffffff81093770-ffffffff810937c6: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097e60)
Location: kernel/fork.c:1049
Inline: False
```
**Symbols:**

```
ffffffff81097e60-ffffffff81097eb6: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e520)
Location: kernel/fork.c:1064
Inline: False
```
**Symbols:**

```
ffffffff8109e520-ffffffff8109e576: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a5bf0)
Location: kernel/fork.c:1078
Inline: False
Direct callers:
  - fs/exec.c:bprm_mm_init
```
**Symbols:**

```
ffffffff810a5bf0-ffffffff810a5c46: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a15d0)
Location: kernel/fork.c:1075
Inline: False
Direct callers:
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810a15d0-ffffffff810a1626: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a2350)
Location: kernel/fork.c:1081
Inline: False
Direct callers:
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810a2350-ffffffff810a23a6: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b3150)
Location: kernel/fork.c:1100
Inline: False
Direct callers:
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810b3150-ffffffff810b31a6: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9320)
Location: kernel/fork.c:1172
Inline: False
Direct callers:
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810c9320-ffffffff810c9385: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e6820)
Location: kernel/fork.c:1192
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810e6820-ffffffff810e6885: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f21b0)
Location: kernel/fork.c:1333
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810f21b0-ffffffff810f2215: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fbdf0)
Location: kernel/fork.c:1328
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
  - fs/exec.c:alloc_bprm
```
**Symbols:**

```
ffffffff810fbdf0-ffffffff810fbe55: mm_alloc (STB_GLOBAL)
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
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f3358)
Location: kernel/fork.c:1064
Inline: False
```
**Symbols:**

```
ffff8000100f3358-ffff8000100f33b8: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0351804)
Location: kernel/fork.c:1064
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
```
**Symbols:**

```
c0351804-c035186c: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000138dc0)
Location: kernel/fork.c:1064
Inline: False
```
**Symbols:**

```
c000000000138dc0-c000000000138e44: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c0f4e)
Location: kernel/fork.c:1064
Inline: False
Direct callers:
  - fs/exec.c:__do_execve_file
```
**Symbols:**

```
ffffffe0000c0f4e-ffffffe0000c0faa: mm_alloc (STB_GLOBAL)
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
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097e40)
Location: kernel/fork.c:1064
Inline: False
```
**Symbols:**

```
ffffffff81097e40-ffffffff81097e96: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810868a0)
Location: kernel/fork.c:1064
Inline: False
```
**Symbols:**

```
ffffffff810868a0-ffffffff810868f6: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097df0)
Location: kernel/fork.c:1064
Inline: False
```
**Symbols:**

```
ffffffff81097df0-ffffffff81097e46: mm_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mm_struct *mm_alloc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f9f0)
Location: kernel/fork.c:1064
Inline: False
```
**Symbols:**

```
ffffffff8109f9f0-ffffffff8109fa46: mm_alloc (STB_GLOBAL)
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
