# Function: <code>__alloc_file</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812b0790)
Location: fs/file_table.c:95
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
```
**Symbols:**

```
ffffffff812b0790-ffffffff812b087e: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812cd0d0)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
```
**Symbols:**

```
ffffffff812cd0d0-ffffffff812cd1e0: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812deaf0)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
```
**Symbols:**

```
ffffffff812deaf0-ffffffff812dec00: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81315940)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
  - fs/file_table.c:alloc_empty_file
```
**Symbols:**

```
ffffffff81315940-ffffffff81315a50: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81320ea0)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
  - fs/file_table.c:alloc_empty_file
```
**Symbols:**

```
ffffffff81320ea0-ffffffff81320f7c: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81326fa0)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
  - fs/file_table.c:alloc_empty_file
```
**Symbols:**

```
ffffffff81326fa0-ffffffff8132707c: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81374560)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
  - fs/file_table.c:alloc_empty_file
```
**Symbols:**

```
ffffffff81374560-ffffffff8137463c: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff813f3550)
Location: fs/file_table.c:133
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
  - fs/file_table.c:alloc_empty_file
```
**Symbols:**

```
ffffffff813f3550-ffffffff813f363c: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff8147c300)
Location: fs/file_table.c:133
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
  - fs/file_table.c:alloc_empty_file
```
**Symbols:**

```
ffffffff8147c300-ffffffff8147c3ec: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffff800010385218)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
```
**Symbols:**

```
ffff800010385218-ffff800010385314: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c056e0e4)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
```
**Symbols:**

```
c056e0e4-c056e1d4: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c00000000047b1a0)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
```
**Symbols:**

```
c00000000047b1a0-c00000000047b2e0: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffe00025800a)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
```
**Symbols:**

```
ffffffe00025800a-ffffffe0002580de: __alloc_file (STB_LOCAL)
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
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d70d0)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
```
**Symbols:**

```
ffffffff812d70d0-ffffffff812d71e0: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812c7d50)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
```
**Symbols:**

```
ffffffff812c7d50-ffffffff812c7e60: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d4ee0)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
```
**Symbols:**

```
ffffffff812d4ee0-ffffffff812d4ff0: __alloc_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *__alloc_file(int flags, const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812e5d40)
Location: fs/file_table.c:96
Inline: False
Direct callers:
  - fs/file_table.c:alloc_empty_file_noaccount
```
**Symbols:**

```
ffffffff812e5d40-ffffffff812e5e50: __alloc_file (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
