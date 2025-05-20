# Function: <code>io_reserve_memtype</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int io_reserve_memtype(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81070550)
Location: arch/x86/mm/pat.c:649
Inline: False
```
**Symbols:**

```
ffffffff81070550-ffffffff8107066c: io_reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int io_reserve_memtype(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810702d0)
Location: arch/x86/mm/pat.c:693
Inline: False
```
**Symbols:**

```
ffffffff810702d0-ffffffff810703fa: io_reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int io_reserve_memtype(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073f10)
Location: arch/x86/mm/pat.c:693
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff81073f10-ffffffff8107403a: io_reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int io_reserve_memtype(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810734b0)
Location: arch/x86/mm/pat.c:690
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff810734b0-ffffffff810735b7: io_reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int io_reserve_memtype(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81078e70)
Location: arch/x86/mm/pat.c:709
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff81078e70-ffffffff81078f7d: io_reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int io_reserve_memtype(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8107b830)
Location: arch/x86/mm/pat.c:725
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff8107b830-ffffffff8107b94f: io_reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int io_reserve_memtype(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810821a0)
Location: arch/x86/mm/pat.c:734
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff810821a0-ffffffff810822bf: io_reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int io_reserve_memtype(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085e20)
Location: arch/x86/mm/pat.c:735
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff81085e20-ffffffff81085f31: io_reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_reserve_memtype(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81086b10)
Location: arch/x86/mm/pat.c:735
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff81086b10-ffffffff81086c21: io_reserve_memtype (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int io_reserve_memtype(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085b10)
Location: arch/x86/mm/pat.c:735
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff81085b10-ffffffff81085c21: io_reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_reserve_memtype(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81074890)
Location: arch/x86/mm/pat.c:735
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff81074890-ffffffff810749a1: io_reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_reserve_memtype(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81085ac0)
Location: arch/x86/mm/pat.c:735
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff81085ac0-ffffffff81085bd1: io_reserve_memtype (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_reserve_memtype(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81087c10)
Location: arch/x86/mm/pat.c:735
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff81087c10-ffffffff81087d21: io_reserve_memtype (STB_GLOBAL)
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
