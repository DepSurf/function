# Function: <code>btf_id</code>

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
u32 btf_id(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c9710)
Location: kernel/bpf/btf.c:2357
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811c9710-ffffffff811c971e: btf_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 btf_id(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811dd010)
Location: kernel/bpf/btf.c:3009
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811dd010-ffffffff811dd01e: btf_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 btf_id(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f2660)
Location: kernel/bpf/btf.c:3499
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811f2660-ffffffff811f266e: btf_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 btf_id(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fed80)
Location: kernel/bpf/btf.c:3511
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811fed80-ffffffff811fed8e: btf_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 btf_id(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81226150)
Location: kernel/bpf/btf.c:4703
Inline: False
```
**Symbols:**

```
ffffffff81226150-ffffffff8122615e: btf_id (STB_GLOBAL)
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
u32 btf_id(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff8000102861d0)
Location: kernel/bpf/btf.c:3511
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffff8000102861d0-ffff8000102861f8: btf_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 btf_id(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b64f4)
Location: kernel/bpf/btf.c:3511
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
```
**Symbols:**

```
c04b64f4-c04b6510: btf_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 btf_id(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c000000000330ec0)
Location: kernel/bpf/btf.c:3511
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
c000000000330ec0-c000000000330ed0: btf_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 btf_id(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001bb0c8)
Location: kernel/bpf/btf.c:3511
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffe0001bb0c8-ffffffe0001bb0ea: btf_id (STB_GLOBAL)
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
u32 btf_id(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f73a0)
Location: kernel/bpf/btf.c:3511
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811f73a0-ffffffff811f73ae: btf_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 btf_id(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ea0f0)
Location: kernel/bpf/btf.c:3511
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811ea0f0-ffffffff811ea0fe: btf_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 btf_id(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f5170)
Location: kernel/bpf/btf.c:3511
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811f5170-ffffffff811f517e: btf_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 btf_id(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812036a0)
Location: kernel/bpf/btf.c:3511
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff812036a0-ffffffff812036ae: btf_id (STB_GLOBAL)
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
