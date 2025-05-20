# Function: <code>__bpf_prog_uncharge</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118caad)
Location: kernel/bpf/syscall.c:661
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffff8118d820-ffffffff8118d837: __bpf_prog_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191c0d)
Location: kernel/bpf/syscall.c:702
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffff811924b0-ffffffff811924c7: __bpf_prog_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119f07d)
Location: kernel/bpf/syscall.c:862
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffff8119f6e0-ffffffff8119f6f9: __bpf_prog_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3a4d)
Location: kernel/bpf/syscall.c:954
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffff811b5ac0-ffffffff811b5ad8: __bpf_prog_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c1f0d)
Location: kernel/bpf/syscall.c:1137
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffff811c36e0-ffffffff811c36f8: __bpf_prog_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d267d)
Location: kernel/bpf/syscall.c:1243
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffff811d4e30-ffffffff811d4e47: __bpf_prog_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811dec3d)
Location: kernel/bpf/syscall.c:1256
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffff811e1540-ffffffff811e1557: __bpf_prog_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812004f6)
Location: kernel/bpf/syscall.c:1642
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffff811ffca0-ffffffff811ffcb7: __bpf_prog_uncharge (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010264b7c)
Location: kernel/bpf/syscall.c:1256
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffff800010264188-ffff8000102641e0: __bpf_prog_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0492db8)
Location: kernel/bpf/syscall.c:1256
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_uncharge_memlock
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
c0496774-c04967b0: __bpf_prog_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0000000003096ec)
Location: kernel/bpf/syscall.c:1256
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
c000000000309060-c000000000309088: __bpf_prog_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe0001a0770)
Location: kernel/bpf/syscall.c:1256
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffe0001a029c-ffffffe0001a02d8: __bpf_prog_uncharge (STB_GLOBAL)
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
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d725d)
Location: kernel/bpf/syscall.c:1256
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffff811d9b60-ffffffff811d9b77: __bpf_prog_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ca01d)
Location: kernel/bpf/syscall.c:1256
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffff811cc920-ffffffff811cc937: __bpf_prog_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d502d)
Location: kernel/bpf/syscall.c:1256
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffff811d7930-ffffffff811d7947: __bpf_prog_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_uncharge(struct user_struct *user, u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e335d)
Location: kernel/bpf/syscall.c:1256
Inline: True
Direct callers:
  - kernel/bpf/core.c:bpf_prog_realloc
```
**Symbols:**

```
ffffffff811e5cd0-ffffffff811e5ce7: __bpf_prog_uncharge (STB_GLOBAL)
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
