# Function: <code>copy_to_user_nofault</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int copy_to_user_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81258060)
Location: mm/maccess.c:233
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff81258060-ffffffff81258148: copy_to_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int copy_to_user_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81262790)
Location: mm/maccess.c:232
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff81262790-ffffffff8126282d: copy_to_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int copy_to_user_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81267200)
Location: mm/maccess.c:232
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff81267200-ffffffff81267282: copy_to_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int copy_to_user_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812a3c40)
Location: mm/maccess.c:248
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff812a3c40-ffffffff812a3cc2: copy_to_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int copy_to_user_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812fbca0)
Location: mm/maccess.c:137
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff812fbca0-ffffffff812fbd70: copy_to_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int copy_to_user_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81365e80)
Location: mm/maccess.c:137
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff81365e80-ffffffff81365f50: copy_to_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int copy_to_user_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81398330)
Location: mm/maccess.c:143
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
**Symbols:**

```
ffffffff81398330-ffffffff813983e7: copy_to_user_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int copy_to_user_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff813c2150)
Location: mm/maccess.c:143
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
**Symbols:**

```
ffffffff813c2150-ffffffff813c21ef: copy_to_user_nofault (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
