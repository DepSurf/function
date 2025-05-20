# Function: <code>bpf_fd_array_map_update_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81187d80)
Location: kernel/bpf/arraymap.c:331
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff81187d80-ffffffff81187de5: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81195d40)
Location: kernel/bpf/arraymap.c:327
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff81195d40-ffffffff81195da5: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8119d2c0)
Location: kernel/bpf/arraymap.c:358
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff8119d2c0-ffffffff8119d31e: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ace60)
Location: kernel/bpf/arraymap.c:403
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff811ace60-ffffffff811acecb: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811c4420)
Location: kernel/bpf/arraymap.c:458
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811c4420-ffffffff811c4495: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811d5fc0)
Location: kernel/bpf/arraymap.c:477
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d5fc0-ffffffff811d6035: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ea9a0)
Location: kernel/bpf/arraymap.c:525
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811ea9a0-ffffffff811eaa12: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811f7100)
Location: kernel/bpf/arraymap.c:525
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811f7100-ffffffff811f7172: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121ad80)
Location: kernel/bpf/arraymap.c:578
Inline: False
```
**Symbols:**

```
ffffffff8121ad80-ffffffff8121ae62: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121db10)
Location: kernel/bpf/arraymap.c:717
Inline: False
```
**Symbols:**

```
ffffffff8121db10-ffffffff8121dbf2: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81221630)
Location: kernel/bpf/arraymap.c:759
Inline: False
```
**Symbols:**

```
ffffffff81221630-ffffffff81221710: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81259030)
Location: kernel/bpf/arraymap.c:780
Inline: False
```
**Symbols:**

```
ffffffff81259030-ffffffff81259110: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812a1f40)
Location: kernel/bpf/arraymap.c:812
Inline: False
```
**Symbols:**

```
ffffffff812a1f40-ffffffff812a2029: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812ff640)
Location: kernel/bpf/arraymap.c:818
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff812ff640-ffffffff812ff729: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8132e1a0)
Location: kernel/bpf/arraymap.c:842
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff8132e1a0-ffffffff8132e28e: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81352570)
Location: kernel/bpf/arraymap.c:842
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff81352570-ffffffff8135266e: bpf_fd_array_map_update_elem (STB_GLOBAL)
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
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffff80001027bc58)
Location: kernel/bpf/arraymap.c:525
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffff80001027bc58-ffff80001027bd20: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c04adad0)
Location: kernel/bpf/arraymap.c:525
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
c04adad0-c04adb70: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c000000000325340)
Location: kernel/bpf/arraymap.c:525
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
c000000000325340-c00000000032546c: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffe0001b3760)
Location: kernel/bpf/arraymap.c:525
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffe0001b3760-ffffffe0001b37e6: bpf_fd_array_map_update_elem (STB_GLOBAL)
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
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ef720)
Location: kernel/bpf/arraymap.c:525
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811ef720-ffffffff811ef792: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e24b0)
Location: kernel/bpf/arraymap.c:525
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811e24b0-ffffffff811e2522: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ed4f0)
Location: kernel/bpf/arraymap.c:525
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811ed4f0-ffffffff811ed562: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_fd_array_map_update_elem(struct bpf_map *map, struct file *map_file, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811fb9c0)
Location: kernel/bpf/arraymap.c:525
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811fb9c0-ffffffff811fba32: bpf_fd_array_map_update_elem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
