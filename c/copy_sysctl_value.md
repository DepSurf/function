# Function: <code>copy_sysctl_value</code>

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
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f7930)
Location: kernel/bpf/cgroup.c:1188
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff811f7930-ffffffff811f79b2: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812048d0)
Location: kernel/bpf/cgroup.c:1207
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff812048d0-ffffffff81204952: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122c5f0)
Location: kernel/bpf/cgroup.c:1528
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff8122c5f0-ffffffff8122c672: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81234a20)
Location: kernel/bpf/cgroup.c:1558
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff81234a20-ffffffff81234aa2: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81238390)
Location: kernel/bpf/cgroup.c:1644
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff81238390-ffffffff81238412: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81272970)
Location: kernel/bpf/cgroup.c:1674
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff81272970-ffffffff812729f2: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c1fa0)
Location: kernel/bpf/cgroup.c:1806
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff812c1fa0-ffffffff812c2033: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81326bc0)
Location: kernel/bpf/cgroup.c:2045
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff81326bc0-ffffffff81326c66: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81356f10)
Location: kernel/bpf/cgroup.c:2063
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff81356f10-ffffffff81356fb6: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8137fa40)
Location: kernel/bpf/cgroup.c:2081
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff8137fa40-ffffffff8137fae6: copy_sysctl_value (STB_LOCAL)
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
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028cc68)
Location: kernel/bpf/cgroup.c:1207
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffff80001028cc68-ffff80001028cd1c: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bca84)
Location: kernel/bpf/cgroup.c:1207
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
c04bca84-c04bcb34: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c000000000339270)
Location: kernel/bpf/cgroup.c:1207
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
c000000000339270-c000000000339380: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c0e54)
Location: kernel/bpf/cgroup.c:1207
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffe0001c0e54-ffffffe0001c0ee6: copy_sysctl_value (STB_LOCAL)
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
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fcef0)
Location: kernel/bpf/cgroup.c:1207
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff811fcef0-ffffffff811fcf72: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811efc40)
Location: kernel/bpf/cgroup.c:1207
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff811efc40-ffffffff811efcc2: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811facc0)
Location: kernel/bpf/cgroup.c:1207
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff811facc0-ffffffff811fad42: copy_sysctl_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_sysctl_value(char *dst, size_t dst_len, char *src, size_t src_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812092e0)
Location: kernel/bpf/cgroup.c:1207
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_new_value
  - kernel/bpf/cgroup.c:bpf_sysctl_get_current_value
```
**Symbols:**

```
ffffffff812092e0-ffffffff81209362: copy_sysctl_value (STB_LOCAL)
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
