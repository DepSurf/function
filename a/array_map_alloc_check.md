# Function: <code>array_map_alloc_check</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811c3630)
Location: kernel/bpf/arraymap.c:57
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
```
**Symbols:**

```
ffffffff811c3630-ffffffff811c368a: array_map_alloc_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811d50c0)
Location: kernel/bpf/arraymap.c:57
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff811d50c0-ffffffff811d511a: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e9890)
Location: kernel/bpf/arraymap.c:49
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff811e9890-ffffffff811e98f8: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811f5ff0)
Location: kernel/bpf/arraymap.c:49
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff811f5ff0-ffffffff811f6058: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121aafa)
Location: kernel/bpf/arraymap.c:49
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
Direct callers:
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff812196b0-ffffffff81219728: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121c000)
Location: kernel/bpf/arraymap.c:51
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff8121c000-ffffffff8121c082: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121fa00)
Location: kernel/bpf/arraymap.c:51
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff8121fa00-ffffffff8121fa82: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812571f0)
Location: kernel/bpf/arraymap.c:51
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff812571f0-ffffffff81257272: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8129fc10)
Location: kernel/bpf/arraymap.c:52
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff8129fc10-ffffffff8129fcb7: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812fcbd0)
Location: kernel/bpf/arraymap.c:52
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff812fcbd0-ffffffff812fcc6b: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8132b800)
Location: kernel/bpf/arraymap.c:52
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff8132b800-ffffffff8132b897: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8134fcd0)
Location: kernel/bpf/arraymap.c:52
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff8134fcd0-ffffffff8134fd67: array_map_alloc_check (STB_GLOBAL)
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
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffff80001027a670)
Location: kernel/bpf/arraymap.c:49
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffff80001027a670-ffff80001027a70c: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c04ac6f4)
Location: kernel/bpf/arraymap.c:49
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
c04ac6f4-c04ac788: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c000000000323790)
Location: kernel/bpf/arraymap.c:49
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
c000000000323790-c000000000323828: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffe0001b23a8)
Location: kernel/bpf/arraymap.c:49
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffe0001b23a8-ffffffe0001b2418: array_map_alloc_check (STB_GLOBAL)
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
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ee610)
Location: kernel/bpf/arraymap.c:49
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff811ee610-ffffffff811ee678: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e13a0)
Location: kernel/bpf/arraymap.c:49
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff811e13a0-ffffffff811e1408: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ec3e0)
Location: kernel/bpf/arraymap.c:49
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff811ec3e0-ffffffff811ec448: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811fa850)
Location: kernel/bpf/arraymap.c:49
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:fd_array_map_alloc_check
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc_check
```
**Symbols:**

```
ffffffff811fa850-ffffffff811fa8b8: array_map_alloc_check (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
