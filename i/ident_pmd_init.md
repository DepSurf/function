# Function: <code>ident_pmd_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ident_pmd_init(long unsigned int pmd_flag, pmd_t *pmd_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81068cd0)
Location: arch/x86/mm/init_64.c:59
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff81068cd0-ffffffff81068d70: ident_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81068ab0)
Location: arch/x86/mm/ident_map.c:6
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff81068ab0-ffffffff81068b60: ident_pmd_init.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106c700)
Location: arch/x86/mm/ident_map.c:6
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff8106c700-ffffffff8106c7b0: ident_pmd_init.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106bab0)
Location: arch/x86/mm/ident_map.c:6
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff8106bab0-ffffffff8106bb60: ident_pmd_init.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81070620)
Location: arch/x86/mm/ident_map.c:7
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff81070620-ffffffff810706e2: ident_pmd_init.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810732e0)
Location: arch/x86/mm/ident_map.c:7
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff810732e0-ffffffff81073384: ident_pmd_init.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81079380)
Location: arch/x86/mm/ident_map.c:7
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff81079380-ffffffff81079424: ident_pmd_init.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107cf90)
Location: arch/x86/mm/ident_map.c:7
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff8107cf90-ffffffff8107d034: ident_pmd_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e020)
Location: arch/x86/mm/ident_map.c:7
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff8107e020-ffffffff8107e0c4: ident_pmd_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ident_pmd_init(struct x86_mapping_info *info, pmd_t *pmd_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810845f0)
Location: arch/x86/mm/ident_map.c:7
Inline: False
```
**Symbols:**

```
ffffffff810845f0-ffffffff8108468a: ident_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ident_pmd_init(struct x86_mapping_info *info, pmd_t *pmd_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81085ad0)
Location: arch/x86/mm/ident_map.c:7
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff81085ad0-ffffffff81085b6a: ident_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ident_pmd_init(struct x86_mapping_info *info, pmd_t *pmd_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086800)
Location: arch/x86/mm/ident_map.c:7
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff81086800-ffffffff8108689a: ident_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ident_pmd_init(struct x86_mapping_info *info, pmd_t *pmd_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81095af0)
Location: arch/x86/mm/ident_map.c:7
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff81095af0-ffffffff81095b8a: ident_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ident_pmd_init(struct x86_mapping_info *info, pmd_t *pmd_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810a80f0)
Location: arch/x86/mm/ident_map.c:7
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff810a80f0-ffffffff810a81a2: ident_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ident_pmd_init(struct x86_mapping_info *info, pmd_t *pmd_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c10c0)
Location: arch/x86/mm/ident_map.c:7
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff810c10c0-ffffffff810c1195: ident_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ident_pmd_init(struct x86_mapping_info *info, pmd_t *pmd_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c47a0)
Location: arch/x86/mm/ident_map.c:7
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff810c47a0-ffffffff810c4875: ident_pmd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ident_pmd_init(struct x86_mapping_info *info, pmd_t *pmd_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810ccbf0)
Location: arch/x86/mm/ident_map.c:7
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff810ccbf0-ffffffff810cccc5: ident_pmd_init (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d020)
Location: arch/x86/mm/ident_map.c:7
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff8107d020-ffffffff8107d0c4: ident_pmd_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106c5d0)
Location: arch/x86/mm/ident_map.c:7
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff8106c5d0-ffffffff8106c63f: ident_pmd_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107cfd0)
Location: arch/x86/mm/ident_map.c:7
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff8107cfd0-ffffffff8107d074: ident_pmd_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107f0c0)
Location: arch/x86/mm/ident_map.c:7
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
**Symbols:**

```
ffffffff8107f0c0-ffffffff8107f164: ident_pmd_init.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
