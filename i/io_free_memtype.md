# Function: <code>io_free_memtype</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void io_free_memtype(resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810703d0)
Location: arch/x86/mm/pat.c:684
Inline: False
```
**Symbols:**

```
ffffffff810703d0-ffffffff810703e0: io_free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void io_free_memtype(resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81070120)
Location: arch/x86/mm/pat.c:728
Inline: False
```
**Symbols:**

```
ffffffff81070120-ffffffff81070130: io_free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void io_free_memtype(resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073d4c)
Location: arch/x86/mm/pat.c:728
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
```
**Symbols:**

```
ffffffff81073d60-ffffffff81073d70: io_free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void io_free_memtype(resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810732fc)
Location: arch/x86/mm/pat.c:725
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
```
**Symbols:**

```
ffffffff81073310-ffffffff81073320: io_free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void io_free_memtype(resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81078c8c)
Location: arch/x86/mm/pat.c:744
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
```
**Symbols:**

```
ffffffff81078ca0-ffffffff81078cb0: io_free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void io_free_memtype(resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8107b125)
Location: arch/x86/mm/pat.c:760
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
```
**Symbols:**

```
ffffffff8107b6b0-ffffffff8107b6ca: io_free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void io_free_memtype(resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81081a65)
Location: arch/x86/mm/pat.c:769
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
```
**Symbols:**

```
ffffffff81082020-ffffffff8108203a: io_free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void io_free_memtype(resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810856f5)
Location: arch/x86/mm/pat.c:770
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
```
**Symbols:**

```
ffffffff81085ca0-ffffffff81085cba: io_free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void io_free_memtype(resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810863e5)
Location: arch/x86/mm/pat.c:770
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
```
**Symbols:**

```
ffffffff81086990-ffffffff810869aa: io_free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void io_free_memtype(resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810853e5)
Location: arch/x86/mm/pat.c:770
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
```
**Symbols:**

```
ffffffff81085990-ffffffff810859aa: io_free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void io_free_memtype(resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810740b5)
Location: arch/x86/mm/pat.c:770
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
```
**Symbols:**

```
ffffffff81074710-ffffffff8107472a: io_free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void io_free_memtype(resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085395)
Location: arch/x86/mm/pat.c:770
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
```
**Symbols:**

```
ffffffff81085940-ffffffff8108595a: io_free_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void io_free_memtype(resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810875d5)
Location: arch/x86/mm/pat.c:770
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
```
**Symbols:**

```
ffffffff81087a90-ffffffff81087aaa: io_free_memtype (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
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
