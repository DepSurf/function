# Function: <code>__bpf_strtoull</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e6430)
Location: kernel/bpf/helpers.c:364
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff811e6430-ffffffff811e6605: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f2b80)
Location: kernel/bpf/helpers.c:364
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff811f2b80-ffffffff811f2d55: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81214a20)
Location: kernel/bpf/helpers.c:408
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff81214a20-ffffffff81214be0: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812165c0)
Location: kernel/bpf/helpers.c:419
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff812165c0-ffffffff81216780: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81219300)
Location: kernel/bpf/helpers.c:427
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff81219300-ffffffff812194b2: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81250070)
Location: kernel/bpf/helpers.c:441
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff81250070-ffffffff81250252: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81297350)
Location: kernel/bpf/helpers.c:455
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff81297350-ffffffff81297557: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f21a0)
Location: kernel/bpf/helpers.c:439
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff812f21a0-ffffffff812f23a7: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8131ed20)
Location: kernel/bpf/helpers.c:440
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff8131ed20-ffffffff8131ef2e: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81341150)
Location: kernel/bpf/helpers.c:446
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff81341150-ffffffff8134135e: __bpf_strtoull (STB_LOCAL)
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
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffff8000102764e0)
Location: kernel/bpf/helpers.c:364
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffff8000102764e0-ffff80001027665c: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c04a8b8c)
Location: kernel/bpf/helpers.c:364
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
c04a8b8c-c04a8d00: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c00000000031eb40)
Location: kernel/bpf/helpers.c:364
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
c00000000031eb40-c00000000031ed54: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffe0001aead0)
Location: kernel/bpf/helpers.c:364
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffe0001aead0-ffffffe0001aec18: __bpf_strtoull (STB_LOCAL)
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
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811eb1a0)
Location: kernel/bpf/helpers.c:364
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff811eb1a0-ffffffff811eb375: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811ddf50)
Location: kernel/bpf/helpers.c:364
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff811ddf50-ffffffff811de125: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e8f70)
Location: kernel/bpf/helpers.c:364
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff811e8f70-ffffffff811e9145: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __bpf_strtoull(const char *buf, size_t buf_len, u64 flags, long long unsigned int *res, bool *is_negative);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f7320)
Location: kernel/bpf/helpers.c:364
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_strtoul
  - kernel/bpf/helpers.c:bpf_strtol
```
**Symbols:**

```
ffffffff811f7320-ffffffff811f74f5: __bpf_strtoull (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
