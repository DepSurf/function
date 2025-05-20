# Function: <code>__set_pte_vaddr</code>

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
void __set_pte_vaddr(pud_t *pud, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106c100)
Location: arch/x86/mm/init_64.c:248
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff8106c100-ffffffff8106c13e: __set_pte_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __set_pte_vaddr(pud_t *pud, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81070b60)
Location: arch/x86/mm/init_64.c:248
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff81070b60-ffffffff81070bab: __set_pte_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __set_pte_vaddr(pud_t *pud, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81073900)
Location: arch/x86/mm/init_64.c:259
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff81073900-ffffffff8107394b: __set_pte_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __set_pte_vaddr(pud_t *pud, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81079b50)
Location: arch/x86/mm/init_64.c:258
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff81079b50-ffffffff81079b9b: __set_pte_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __set_pte_vaddr(pud_t *pud, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d870)
Location: arch/x86/mm/init_64.c:290
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff8107d870-ffffffff8107d8bb: __set_pte_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __set_pte_vaddr(pud_t *pud, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e900)
Location: arch/x86/mm/init_64.c:290
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff8107e900-ffffffff8107e94b: __set_pte_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81085485)
Location: arch/x86/mm/init_64.c:295
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086551)
Location: arch/x86/mm/init_64.c:290
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810872f1)
Location: arch/x86/mm/init_64.c:290
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81096611)
Location: arch/x86/mm/init_64.c:291
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810a8ef1)
Location: arch/x86/mm/init_64.c:290
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c2591)
Location: arch/x86/mm/init_64.c:296
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c5c71)
Location: arch/x86/mm/init_64.c:296
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810ce0c1)
Location: arch/x86/mm/init_64.c:296
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __set_pte_vaddr(pud_t *pud, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d900)
Location: arch/x86/mm/init_64.c:290
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff8107d900-ffffffff8107d94b: __set_pte_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __set_pte_vaddr(pud_t *pud, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106c9f0)
Location: arch/x86/mm/init_64.c:290
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff8106c9f0-ffffffff8106ca31: __set_pte_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __set_pte_vaddr(pud_t *pud, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d8b0)
Location: arch/x86/mm/init_64.c:290
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff8107d8b0-ffffffff8107d8fb: __set_pte_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __set_pte_vaddr(pud_t *pud, long unsigned int vaddr, pte_t new_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107f9a0)
Location: arch/x86/mm/init_64.c:290
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
**Symbols:**

```
ffffffff8107f9a0-ffffffff8107f9eb: __set_pte_vaddr (STB_LOCAL)
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
