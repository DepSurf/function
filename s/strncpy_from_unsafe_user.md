# Function: <code>strncpy_from_unsafe_user</code>

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
long int strncpy_from_unsafe_user(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff8121d9b0)
Location: mm/maccess.c:165
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff8121d9b0-ffffffff8121da46: strncpy_from_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int strncpy_from_unsafe_user(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff8122b450)
Location: mm/maccess.c:202
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff8122b450-ffffffff8122b4e6: strncpy_from_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
long int strncpy_from_unsafe_user(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffff8000102b9e38)
Location: mm/maccess.c:202
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffff8000102b9e38-ffff8000102b9f60: strncpy_from_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int strncpy_from_unsafe_user(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (c04e5fe0)
Location: mm/maccess.c:202
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
c04e5fe0-c04e6094: strncpy_from_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int strncpy_from_unsafe_user(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (c000000000371e30)
Location: mm/maccess.c:202
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
c000000000371e30-c000000000371f48: strncpy_from_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int strncpy_from_unsafe_user(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffe0001dd208)
Location: mm/maccess.c:202
Inline: False
```
**Symbols:**

```
ffffffe0001dd208-ffffffe0001dd292: strncpy_from_unsafe_user (STB_GLOBAL)
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
long int strncpy_from_unsafe_user(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81223aa0)
Location: mm/maccess.c:202
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81223aa0-ffffffff81223b36: strncpy_from_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int strncpy_from_unsafe_user(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81216c50)
Location: mm/maccess.c:202
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81216c50-ffffffff81216ce6: strncpy_from_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int strncpy_from_unsafe_user(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81221840)
Location: mm/maccess.c:202
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81221840-ffffffff812218d6: strncpy_from_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int strncpy_from_unsafe_user(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81230a00)
Location: mm/maccess.c:202
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81230a00-ffffffff81230a96: strncpy_from_unsafe_user (STB_GLOBAL)
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
