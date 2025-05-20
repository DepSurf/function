# Function: <code>init_kernel_text</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff8109e968)
Location: kernel/extable.c:61
Inline: True
Inline callers:
  - kernel/extable.c:__kernel_text_address
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810a214c)
Location: kernel/extable.c:61
Inline: True
Inline callers:
  - kernel/extable.c:__kernel_text_address
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810a720c)
Location: kernel/extable.c:61
Inline: True
Inline callers:
  - kernel/extable.c:__kernel_text_address
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810a4255)
Location: kernel/extable.c:65
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810aa875)
Location: kernel/extable.c:67
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:__kernel_text_address
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810b14f3)
Location: kernel/extable.c:67
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810b12e0-ffffffff810b1302: init_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810ba633)
Location: kernel/extable.c:67
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810ba420-ffffffff810ba442: init_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c0543)
Location: kernel/extable.c:55
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810c0330-ffffffff810c0352: init_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c6943)
Location: kernel/extable.c:62
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810c6730-ffffffff810c6752: init_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810ce943)
Location: kernel/extable.c:65
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:__kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810ce7b0-ffffffff810ce7d2: init_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c9463)
Location: kernel/extable.c:65
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:__kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810c92d0-ffffffff810c92f2: init_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810caf73)
Location: kernel/extable.c:65
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810cad60-ffffffff810cad82: init_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810de053)
Location: kernel/extable.c:65
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810dde40-ffffffff810dde62: init_kernel_text (STB_GLOBAL)
```
</details>
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
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffff8000101255a4)
Location: kernel/extable.c:62
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffff800010125278-ffff8000101252cc: init_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (c0378358)
Location: kernel/extable.c:62
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
c0378074-c03780b8: init_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (c00000000016f430)
Location: kernel/extable.c:62
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
c00000000016f020-c00000000016f068: init_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffe0000dd27a)
Location: kernel/extable.c:62
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffe0000dd020-ffffffe0000dd05a: init_kernel_text (STB_GLOBAL)
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
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c0cc3)
Location: kernel/extable.c:62
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810c0ab0-ffffffff810c0ad2: init_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810af4b3)
Location: kernel/extable.c:62
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810af2a0-ffffffff810af2c2: init_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c0213)
Location: kernel/extable.c:62
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810c0000-ffffffff810c0022: init_kernel_text (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int init_kernel_text(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c8643)
Location: kernel/extable.c:62
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff810c8430-ffffffff810c8452: init_kernel_text (STB_GLOBAL)
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
