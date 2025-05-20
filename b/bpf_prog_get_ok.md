# Function: <code>bpf_prog_get_ok</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119f15d)
Location: kernel/bpf/syscall.c:1060
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff8119fcc0-ffffffff8119fcf1: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3c85)
Location: kernel/bpf/syscall.c:1161
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff811b6720-ffffffff811b674f: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c2185)
Location: kernel/bpf/syscall.c:1347
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff811c5870-ffffffff811c589f: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d28e1)
Location: kernel/bpf/syscall.c:1484
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff811d6710-ffffffff811d673f: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ded31)
Location: kernel/bpf/syscall.c:1505
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff811e2e00-ffffffff811e2e2f: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc911)
Location: kernel/bpf/syscall.c:1883
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff81200bf0-ffffffff81200c1f: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fbc61)
Location: kernel/bpf/syscall.c:1857
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff812000b0-ffffffff812000e2: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc981)
Location: kernel/bpf/syscall.c:1865
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff81200a60-ffffffff81200a92: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122e311)
Location: kernel/bpf/syscall.c:1959
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff81cb7b8d-ffffffff81cb7bb8: bpf_prog_get_ok.cold (STB_LOCAL)
ffffffff812327d0-ffffffff81232805: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81270995)
Location: kernel/bpf/syscall.c:2205
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff81e68d18-ffffffff81e68d4f: bpf_prog_get_ok.cold (STB_LOCAL)
ffffffff81275bd0-ffffffff81275c1d: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c64c5)
Location: kernel/bpf/syscall.c:2239
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff8205f9dd-ffffffff8205fa14: bpf_prog_get_ok.cold (STB_LOCAL)
ffffffff812cbca0-ffffffff812cbced: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ed7c8)
Location: kernel/bpf/syscall.c:2318
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff820de936-ffffffff820de96d: bpf_prog_get_ok.cold (STB_LOCAL)
ffffffff812f3610-ffffffff812f365d: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130c378)
Location: kernel/bpf/syscall.c:2358
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff821ba82a-ffffffff821ba861: bpf_prog_get_ok.cold (STB_LOCAL)
ffffffff813124a0-ffffffff813124ed: bpf_prog_get_ok (STB_GLOBAL)
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
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff80001025ffec)
Location: kernel/bpf/syscall.c:1505
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffff800010265de8-ffff800010265e6c: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c04934e8)
Location: kernel/bpf/syscall.c:1505
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
c0497ea4-c0497ef4: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000304fe0)
Location: kernel/bpf/syscall.c:1505
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
c00000000030adb0-c00000000030ae08: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019ddd0)
Location: kernel/bpf/syscall.c:1505
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffe0001a15b8-ffffffe0001a1610: bpf_prog_get_ok (STB_GLOBAL)
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
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d7351)
Location: kernel/bpf/syscall.c:1505
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff811db420-ffffffff811db44f: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ca111)
Location: kernel/bpf/syscall.c:1505
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff811ce1e0-ffffffff811ce20f: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d5121)
Location: kernel/bpf/syscall.c:1505
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff811d91f0-ffffffff811d921f: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_get_ok(struct bpf_prog *prog, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e3451)
Location: kernel/bpf/syscall.c:1505
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_prog_get
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff811e7600-ffffffff811e762f: bpf_prog_get_ok (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
