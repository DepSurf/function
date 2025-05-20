# Function: <code>strnlen_unsafe_user</code>

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
long int strnlen_unsafe_user(const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff8121da50)
Location: mm/maccess.c:206
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff8121da50-ffffffff8121daa8: strnlen_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int strnlen_unsafe_user(const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff8122b4f0)
Location: mm/maccess.c:243
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff8122b4f0-ffffffff8122b548: strnlen_unsafe_user (STB_GLOBAL)
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
long int strnlen_unsafe_user(const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffff8000102b9f60)
Location: mm/maccess.c:243
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffff8000102b9f60-ffff8000102ba03c: strnlen_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int strnlen_unsafe_user(const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (c04e6094)
Location: mm/maccess.c:243
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
c04e6094-c04e6110: strnlen_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int strnlen_unsafe_user(const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (c000000000371f50)
Location: mm/maccess.c:243
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
c000000000371f50-c000000000372000: strnlen_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int strnlen_unsafe_user(const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffe0001dd292)
Location: mm/maccess.c:243
Inline: False
```
**Symbols:**

```
ffffffe0001dd292-ffffffe0001dd2fa: strnlen_unsafe_user (STB_GLOBAL)
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
long int strnlen_unsafe_user(const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81223b40)
Location: mm/maccess.c:243
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81223b40-ffffffff81223b98: strnlen_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int strnlen_unsafe_user(const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81216cf0)
Location: mm/maccess.c:243
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81216cf0-ffffffff81216d48: strnlen_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int strnlen_unsafe_user(const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812218e0)
Location: mm/maccess.c:243
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff812218e0-ffffffff81221938: strnlen_unsafe_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int strnlen_unsafe_user(const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81230aa0)
Location: mm/maccess.c:243
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81230aa0-ffffffff81230af8: strnlen_unsafe_user (STB_GLOBAL)
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
