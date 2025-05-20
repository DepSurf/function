# Function: <code>set_pte_vaddr_p4d</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106c67a)
Location: arch/x86/mm/init_64.c:262
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8106c610-ffffffff8106c63a: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107114a)
Location: arch/x86/mm/init_64.c:262
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff810710e0-ffffffff8107110a: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81073ede)
Location: arch/x86/mm/init_64.c:273
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff81073e60-ffffffff81073e8a: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81079dce)
Location: arch/x86/mm/init_64.c:272
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff81079d50-ffffffff81079d7a: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107daff)
Location: arch/x86/mm/init_64.c:304
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8107da80-ffffffff8107daac: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107eb8f)
Location: arch/x86/mm/init_64.c:304
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8107eb10-ffffffff8107eb3c: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81085420)
Location: arch/x86/mm/init_64.c:309
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff81085420-ffffffff8108547e: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810864d0)
Location: arch/x86/mm/init_64.c:304
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff810864d0-ffffffff8108652e: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81087270)
Location: arch/x86/mm/init_64.c:304
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff81087270-ffffffff810872ce: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81096590)
Location: arch/x86/mm/init_64.c:305
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff81096590-ffffffff810965ee: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810a8e50)
Location: arch/x86/mm/init_64.c:304
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff810a8e50-ffffffff810a8ec7: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c24e0)
Location: arch/x86/mm/init_64.c:310
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff810c24e0-ffffffff810c2557: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c5bc0)
Location: arch/x86/mm/init_64.c:310
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff810c5bc0-ffffffff810c5c37: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810ce010)
Location: arch/x86/mm/init_64.c:310
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff810ce010-ffffffff810ce087: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
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
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107db8f)
Location: arch/x86/mm/init_64.c:304
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8107db10-ffffffff8107db3c: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106ce8f)
Location: arch/x86/mm/init_64.c:304
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8106ce10-ffffffff8106ce3c: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107db3f)
Location: arch/x86/mm/init_64.c:304
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8107dac0-ffffffff8107daec: set_pte_vaddr_p4d (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_pte_vaddr_p4d(p4d_t *p4d_page, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107fc2f)
Location: arch/x86/mm/init_64.c:304
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
```
**Symbols:**

```
ffffffff8107fbb0-ffffffff8107fbdc: set_pte_vaddr_p4d (STB_GLOBAL)
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
