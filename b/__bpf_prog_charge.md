# Function: <code>__bpf_prog_charge</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118d370)
Location: kernel/bpf/syscall.c:645
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff8118d370-ffffffff8118d3bf: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191f60)
Location: kernel/bpf/syscall.c:686
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff81191f60-ffffffff81191fac: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119f690)
Location: kernel/bpf/syscall.c:846
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff8119f690-ffffffff8119f6dc: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b5a70)
Location: kernel/bpf/syscall.c:938
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811b5a70-ffffffff811b5abc: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c3690)
Location: kernel/bpf/syscall.c:1121
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811c3690-ffffffff811c36dc: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4de0)
Location: kernel/bpf/syscall.c:1227
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811d4de0-ffffffff811d4e2c: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e14f0)
Location: kernel/bpf/syscall.c:1240
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811e14f0-ffffffff811e153c: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ffc50)
Location: kernel/bpf/syscall.c:1626
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811ffc50-ffffffff811ffc9c: __bpf_prog_charge (STB_GLOBAL)
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
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff8000102640f0)
Location: kernel/bpf/syscall.c:1240
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffff8000102640f0-ffff800010264188: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c04966ec)
Location: kernel/bpf/syscall.c:1240
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
c04966ec-c0496774: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000308ff0)
Location: kernel/bpf/syscall.c:1240
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
c000000000308ff0-c000000000309054: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe0001a052c)
Location: kernel/bpf/syscall.c:1240
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffe0001a0242-ffffffe0001a029c: __bpf_prog_charge (STB_GLOBAL)
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
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d9b10)
Location: kernel/bpf/syscall.c:1240
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811d9b10-ffffffff811d9b5c: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cc8d0)
Location: kernel/bpf/syscall.c:1240
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811cc8d0-ffffffff811cc91c: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d78e0)
Location: kernel/bpf/syscall.c:1240
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811d78e0-ffffffff811d792c: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __bpf_prog_charge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e5c80)
Location: kernel/bpf/syscall.c:1240
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811e5c80-ffffffff811e5ccc: __bpf_prog_charge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
