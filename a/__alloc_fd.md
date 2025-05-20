# Function: <code>__alloc_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122a6f0)
Location: fs/file.c:496
Inline: False
Direct callers:
  - fs/file.c:get_unused_fd_flags
  - fs/file.c:f_dupfd
```
**Symbols:**

```
ffffffff8122a6f0-ffffffff8122a872: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81252e60)
Location: fs/file.c:497
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffffffff81252e60-ffffffff81252fd2: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812660d0)
Location: fs/file.c:497
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffffffff812660d0-ffffffff81266235: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812738b0)
Location: fs/file.c:483
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffffffff812738b0-ffffffff81273a13: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812961e0)
Location: fs/file.c:484
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffffffff812961e0-ffffffff81296343: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:479
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffffffff812bccbc-ffffffff812bcce3: __alloc_fd.cold.15 (STB_LOCAL)
ffffffff812bc670-ffffffff812bc7ae: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:479
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffffffff812d1f7c-ffffffff812d1fa3: __alloc_fd.cold.15 (STB_LOCAL)
ffffffff812d1930-ffffffff812d1a6e: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:480
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffffffff812eefbc-ffffffff812eefe6: __alloc_fd.cold (STB_LOCAL)
ffffffff812ee930-ffffffff812eea7e: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:480
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffffffff81300a7c-ffffffff81300aa6: __alloc_fd.cold (STB_LOCAL)
ffffffff813003f0-ffffffff8130053e: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:480
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
ffffffff81339cbc-ffffffff81339ce6: __alloc_fd.cold (STB_LOCAL)
ffffffff81339570-ffffffff813396ba: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b1fe8)
Location: fs/file.c:480
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffff8000103b1fe8-ffff8000103b2208: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c059146c)
Location: fs/file.c:480
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
c059146c-c0591620: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004adde0)
Location: fs/file.c:480
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
c0000000004adde0-c0000000004ae060: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe0002760d8)
Location: fs/file.c:480
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffffffe0002760d8-ffffffe0002762c2: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:480
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffffffff812f905c-ffffffff812f9086: __alloc_fd.cold (STB_LOCAL)
ffffffff812f89d0-ffffffff812f8b1e: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:480
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffffffff812e9c7c-ffffffff812e9ca6: __alloc_fd.cold (STB_LOCAL)
ffffffff812e95f0-ffffffff812e973e: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:480
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffffffff812f6e6c-ffffffff812f6e96: __alloc_fd.cold (STB_LOCAL)
ffffffff812f67e0-ffffffff812f692e: __alloc_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __alloc_fd(struct files_struct *files, unsigned int start, unsigned int end, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file.c (0)
Location: fs/file.c:480
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:get_unused_fd_flags
```
**Symbols:**

```
ffffffff813080dc-ffffffff813080fe: __alloc_fd.cold (STB_LOCAL)
ffffffff81307a10-ffffffff81307b57: __alloc_fd (STB_GLOBAL)
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
