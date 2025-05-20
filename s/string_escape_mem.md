# Function: <code>string_escape_mem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81401260)
Location: lib/string_helpers.c:489
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff81401260-ffffffff814014c8: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81448a00)
Location: lib/string_helpers.c:493
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_pid_status
  - lib/vsprintf.c:escaped_string
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
```
**Symbols:**

```
ffffffff81448a00-ffffffff81448c69: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff814673f0)
Location: lib/string_helpers.c:493
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_pid_status
  - lib/vsprintf.c:escaped_string
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
```
**Symbols:**

```
ffffffff814673f0-ffffffff81467659: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8146cae0)
Location: lib/string_helpers.c:493
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_pid_status
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff8146cae0-ffffffff8146cd57: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81498e00)
Location: lib/string_helpers.c:493
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_pid_status
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff81498e00-ffffffff81499081: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff814ce140)
Location: lib/string_helpers.c:493
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff814ce140-ffffffff814ce386: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff814e2a30)
Location: lib/string_helpers.c:493
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff814e2a30-ffffffff814e2c76: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8150ed80)
Location: lib/string_helpers.c:497
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff8150ed80-ffffffff8150efec: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8152cc80)
Location: lib/string_helpers.c:497
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff8152cc80-ffffffff8152ceec: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81590c04)
Location: lib/string_helpers.c:497
Inline: True
Inline callers:
  - lib/string_helpers.c:kstrdup_quotable
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff81590860-ffffffff81590ad5: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff815ad7a4)
Location: lib/string_helpers.c:497
Inline: True
Inline callers:
  - lib/string_helpers.c:kstrdup_quotable
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff815ad3d0-ffffffff815ad645: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff815b8444)
Location: lib/string_helpers.c:497
Inline: True
Inline callers:
  - lib/string_helpers.c:kstrdup_quotable
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff815b8070-ffffffff815b82eb: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8161e8c0)
Location: lib/string_helpers.c:519
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape_mem
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff8161e8c0-ffffffff8161ebdc: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff816ec720)
Location: lib/string_helpers.c:520
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape_mem
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff816ec720-ffffffff816eca92: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff817dcfe0)
Location: lib/string_helpers.c:564
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape_mem
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff817dcfe0-ffffffff817dd329: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8181c760)
Location: lib/string_helpers.c:564
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape_mem
  - fs/seq_file.c:seq_escape_mem
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff8181c760-ffffffff8181cb38: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81862510)
Location: lib/string_helpers.c:566
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape_mem
  - fs/seq_file.c:seq_escape_mem
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff81862510-ffffffff818628e8: string_escape_mem (STB_GLOBAL)
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
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffff800010638d70)
Location: lib/string_helpers.c:497
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffff800010638d70-ffff800010639038: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (c07de468)
Location: lib/string_helpers.c:497
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
c07de468-c07de6f8: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (c0000000007df470)
Location: lib/string_helpers.c:497
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
c0000000007df470-c0000000007df7fc: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffe000465a24)
Location: lib/string_helpers.c:497
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffe000465a24-ffffffe000465c64: string_escape_mem (STB_GLOBAL)
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
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81525260)
Location: lib/string_helpers.c:497
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff81525260-ffffffff815254cc: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81515540)
Location: lib/string_helpers.c:497
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff81515540-ffffffff815157ac: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff815212f0)
Location: lib/string_helpers.c:497
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff815212f0-ffffffff8152155c: string_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int string_escape_mem(const char *src, size_t isz, char *dst, size_t osz, unsigned int flags, const char *only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8153ac70)
Location: lib/string_helpers.c:497
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:kstrdup_quotable
  - lib/vsprintf.c:escaped_string
```
**Symbols:**

```
ffffffff8153ac70-ffffffff8153aedc: string_escape_mem (STB_GLOBAL)
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
