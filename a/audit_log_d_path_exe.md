# Function: <code>audit_log_d_path_exe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811228d0)
Location: kernel/audit.c:1856
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff811228d0-ffffffff81122928: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8112a800)
Location: kernel/audit.c:1867
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff8112a800-ffffffff8112a858: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81134520)
Location: kernel/audit.c:2006
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff81134520-ffffffff81134578: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811359d0)
Location: kernel/audit.c:2173
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff811359d0-ffffffff81135a28: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81142710)
Location: kernel/audit.c:2181
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff81142710-ffffffff81142768: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811510f0)
Location: kernel/audit.c:2234
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff811510f0-ffffffff81151148: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115dda0)
Location: kernel/audit.c:2232
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff8115dda0-ffffffff8115ddf8: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116a0d0)
Location: kernel/audit.c:2085
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff8116a0d0-ffffffff8116a12b: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81175f70)
Location: kernel/audit.c:2087
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff81175f70-ffffffff81175fcb: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81188771)
Location: kernel/audit.c:2236
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_multicast
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff811884f0-ffffffff8118854b: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81185ac1)
Location: kernel/audit.c:2253
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_multicast
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff81185840-ffffffff8118589b: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81186aae)
Location: kernel/audit.c:2253
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_multicast
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff81186830-ffffffff8118688b: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811aeede)
Location: kernel/audit.c:2292
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_multicast
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff811aec60-ffffffff811aecbb: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e145d)
Location: kernel/audit.c:2338
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_multicast
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff811e0e90-ffffffff811e0f00: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812272dd)
Location: kernel/audit.c:2336
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_multicast
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff81226cc0-ffffffff81226d30: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123d8fd)
Location: kernel/audit.c:2336
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_multicast
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff8123d2d0-ffffffff8123d343: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8125781e)
Location: kernel/audit.c:2358
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_multicast
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff81257200-ffffffff81257273: audit_log_d_path_exe (STB_GLOBAL)
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
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101eafa0)
Location: kernel/audit.c:2087
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffff8000101eafa0-ffff8000101eb014: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042abd8)
Location: kernel/audit.c:2087
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
c042abd8-c042ac3c: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025c520)
Location: kernel/audit.c:2087
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
c00000000025c520-c00000000025c5c8: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015f89e)
Location: kernel/audit.c:2087
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffe00015f89e-ffffffe00015f912: audit_log_d_path_exe (STB_GLOBAL)
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
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116e590)
Location: kernel/audit.c:2087
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff8116e590-ffffffff8116e5eb: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81161730)
Location: kernel/audit.c:2087
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff81161730-ffffffff8116178b: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116c360)
Location: kernel/audit.c:2087
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff8116c360-ffffffff8116c3bb: audit_log_d_path_exe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_log_d_path_exe(struct audit_buffer *ab, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81179b20)
Location: kernel/audit.c:2087
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_task
```
**Symbols:**

```
ffffffff81179b20-ffffffff81179b7b: audit_log_d_path_exe (STB_GLOBAL)
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
