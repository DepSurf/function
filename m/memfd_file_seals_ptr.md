# Function: <code>memfd_file_seals_ptr</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int *memfd_file_seals_ptr(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff81293c50)
Location: mm/memfd.c:137
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff81293c50-ffffffff81293caa: memfd_file_seals_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int *memfd_file_seals_ptr(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812a8910)
Location: mm/memfd.c:118
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff812a8910-ffffffff812a896a: memfd_file_seals_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int *memfd_file_seals_ptr(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812c5070)
Location: mm/memfd.c:118
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff812c5070-ffffffff812c50ca: memfd_file_seals_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int *memfd_file_seals_ptr(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812d6a00)
Location: mm/memfd.c:120
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff812d6a00-ffffffff812d6a5a: memfd_file_seals_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int *memfd_file_seals_ptr(struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff8130ba90)
Location: mm/memfd.c:120
Inline: True
Direct callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff8130ba90-ffffffff8130baf3: memfd_file_seals_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff81317b60)
Location: mm/memfd.c:120
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff8131dd50)
Location: mm/memfd.c:120
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff8136b0f0)
Location: mm/memfd.c:136
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff813e909a)
Location: mm/memfd.c:136
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff81471016)
Location: mm/memfd.c:136
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff814a5ff5)
Location: mm/memfd.c:137
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff814d6f16)
Location: mm/memfd.c:137
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
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
unsigned int *memfd_file_seals_ptr(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffff80001037bb58)
Location: mm/memfd.c:120
Inline: False
Direct callers:
  - mm/memfd.c:__arm64_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffff80001037bb58-ffff80001037bbe4: memfd_file_seals_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (c05670f8)
Location: mm/memfd.c:120
Inline: True
Inline callers:
  - mm/memfd.c:__se_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int *memfd_file_seals_ptr(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (c000000000470c60)
Location: mm/memfd.c:120
Inline: False
Direct callers:
  - mm/memfd.c:__se_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
c000000000470c60-c000000000470d0c: memfd_file_seals_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int *memfd_file_seals_ptr(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffe000252326)
Location: mm/memfd.c:120
Inline: False
Direct callers:
  - mm/memfd.c:__se_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffe000252326-ffffffe000252386: memfd_file_seals_ptr (STB_LOCAL)
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
unsigned int *memfd_file_seals_ptr(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812cefe0)
Location: mm/memfd.c:120
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff812cefe0-ffffffff812cf03a: memfd_file_seals_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int *memfd_file_seals_ptr(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812bfc70)
Location: mm/memfd.c:120
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff812bfc70-ffffffff812bfcca: memfd_file_seals_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int *memfd_file_seals_ptr(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812ccdf0)
Location: mm/memfd.c:120
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff812ccdf0-ffffffff812cce4a: memfd_file_seals_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int *memfd_file_seals_ptr(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812ddb90)
Location: mm/memfd.c:120
Inline: False
Direct callers:
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff812ddb90-ffffffff812ddbea: memfd_file_seals_ptr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
