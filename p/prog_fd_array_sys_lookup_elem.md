# Function: <code>prog_fd_array_sys_lookup_elem</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8119c940)
Location: kernel/bpf/arraymap.c:423
Inline: False
```
**Symbols:**

```
ffffffff8119c940-ffffffff8119c952: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ac2a0)
Location: kernel/bpf/arraymap.c:468
Inline: False
```
**Symbols:**

```
ffffffff811ac2a0-ffffffff811ac2b2: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811c37b0)
Location: kernel/bpf/arraymap.c:523
Inline: False
```
**Symbols:**

```
ffffffff811c37b0-ffffffff811c37c2: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811d5571)
Location: kernel/bpf/arraymap.c:542
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811d5290-ffffffff811d52a2: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e9d91)
Location: kernel/bpf/arraymap.c:590
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811e9a50-ffffffff811e9a62: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811f64f1)
Location: kernel/bpf/arraymap.c:590
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811f61b0-ffffffff811f61c2: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81219ae1)
Location: kernel/bpf/arraymap.c:658
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff81219810-ffffffff81219822: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121c891)
Location: kernel/bpf/arraymap.c:797
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff8121c260-ffffffff8121c272: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812203b1)
Location: kernel/bpf/arraymap.c:839
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff8121fc60-ffffffff8121fc72: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81257a31)
Location: kernel/bpf/arraymap.c:860
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff81257450-ffffffff81257462: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812a0695)
Location: kernel/bpf/arraymap.c:891
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff8129ff50-ffffffff8129ff68: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812fd475)
Location: kernel/bpf/arraymap.c:897
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff812fcf90-ffffffff812fcfa8: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8132c0b5)
Location: kernel/bpf/arraymap.c:921
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff8132bbc0-ffffffff8132bbd8: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81350585)
Location: kernel/bpf/arraymap.c:927
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff81350090-ffffffff813500a8: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffff80001027ac04)
Location: kernel/bpf/arraymap.c:590
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffff80001027a900-ffff80001027a92c: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c04acc0c)
Location: kernel/bpf/arraymap.c:590
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
c04ac928-c04ac948: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c000000000323ff0)
Location: kernel/bpf/arraymap.c:590
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
c000000000323a50-c000000000323a64: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffe0001b29f0)
Location: kernel/bpf/arraymap.c:590
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffe0001b25ec-ffffffe0001b2610: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811eeb11)
Location: kernel/bpf/arraymap.c:590
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811ee7d0-ffffffff811ee7e2: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e18a1)
Location: kernel/bpf/arraymap.c:590
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811e1560-ffffffff811e1572: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ec8e1)
Location: kernel/bpf/arraymap.c:590
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811ec5a0-ffffffff811ec5b2: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u32 prog_fd_array_sys_lookup_elem(void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811fad7b)
Location: kernel/bpf/arraymap.c:590
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811faa10-ffffffff811faa22: prog_fd_array_sys_lookup_elem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
