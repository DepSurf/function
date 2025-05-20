# Function: <code>post_copy_siginfo_from_user32</code>

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
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa030)
Location: kernel/signal.c:3195
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff810aa030-ffffffff810aa1de: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af0b0)
Location: kernel/signal.c:3324
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff810af0b0-ffffffff810af269: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b56d0)
Location: kernel/signal.c:3329
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff810b56d0-ffffffff810b5889: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bba80)
Location: kernel/signal.c:3347
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff810bba80-ffffffff810bbc39: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6d40)
Location: kernel/signal.c:3367
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff810b6d40-ffffffff810b6ef9: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8300)
Location: kernel/signal.c:3392
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff810b8300-ffffffff810b84f6: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ca7f0)
Location: kernel/signal.c:3480
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff810ca7f0-ffffffff810ca9e6: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e2160)
Location: kernel/signal.c:3461
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff810e2160-ffffffff810e233b: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81102500)
Location: kernel/signal.c:3463
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff81102500-ffffffff811026db: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110e740)
Location: kernel/signal.c:3487
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff8110e740-ffffffff8110e91c: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811180c0)
Location: kernel/signal.c:3498
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff811180c0-ffffffff8111829c: post_copy_siginfo_from_user32 (STB_LOCAL)
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
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010111848)
Location: kernel/signal.c:3329
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffff800010111848-ffff8000101119d4: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000159460)
Location: kernel/signal.c:3329
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
c000000000159460-c00000000015967c: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afa40)
Location: kernel/signal.c:3329
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff810afa40-ffffffff810afbf9: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109e360)
Location: kernel/signal.c:3329
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff8109e360-ffffffff8109e519: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aefa0)
Location: kernel/signal.c:3329
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff810aefa0-ffffffff810af159: post_copy_siginfo_from_user32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int post_copy_siginfo_from_user32(kernel_siginfo_t *to, const struct compat_siginfo *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7270)
Location: kernel/signal.c:3329
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
**Symbols:**

```
ffffffff810b7270-ffffffff810b7429: post_copy_siginfo_from_user32 (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
