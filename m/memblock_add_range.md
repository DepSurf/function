# Function: <code>memblock_add_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181e5c3)
Location: mm/memblock.c:524
Inline: False
Direct callers:
  - mm/memblock.c:memblock_add_node
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_reserve
```
**Symbols:**

```
ffffffff8181e5c3-ffffffff8181e7c4: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81898a51)
Location: mm/memblock.c:520
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff81898a51-ffffffff81898c69: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cd0f9)
Location: mm/memblock.c:520
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff818cd0f9-ffffffff818cd311: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8190452f)
Location: mm/memblock.c:504
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff8190452f-ffffffff819046be: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198e538)
Location: mm/memblock.c:504
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff8198e538-ffffffff8198e6c7: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819eadbb)
Location: mm/memblock.c:507
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff819eadbb-ffffffff819eaf4a: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a2603d)
Location: mm/memblock.c:585
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff81a2603d-ffffffff81a261ca: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a96766)
Location: mm/memblock.c:582
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff81a96766-ffffffff81a9697f: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ace03d)
Location: mm/memblock.c:582
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff81ace03d-ffffffff81ace1ef: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (ffffffff81bc6ddf)
Location: mm/memblock.c:578
Inline: True
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff81bc6ddf-ffffffff81bc6f84: memblock_add_range.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (ffffffff81c3fb01)
Location: mm/memblock.c:565
Inline: True
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff81c3fb01-ffffffff81c3fca6: memblock_add_range.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (ffffffff81c31bc1)
Location: mm/memblock.c:565
Inline: True
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff81c31bc1-ffffffff81c31d68: memblock_add_range.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (ffffffff81d50558)
Location: mm/memblock.c:573
Inline: True
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff81d50558-ffffffff81d506ff: memblock_add_range.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f201cf)
Location: mm/memblock.c:573
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff81f201cf-ffffffff81f20399: memblock_add_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820c96f0)
Location: mm/memblock.c:577
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff820c96f0-ffffffff820c99ab: memblock_add_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214d950)
Location: mm/memblock.c:582
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff8214d950-ffffffff8214dc2f: memblock_add_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82230510)
Location: mm/memblock.c:588
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff82230510-ffffffff822307ef: memblock_add_range (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031c360)
Location: mm/memblock.c:582
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffff80001031c360-ffff80001031c618: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0536254)
Location: mm/memblock.c:582
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
c0536254-c0536528: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003f0040)
Location: mm/memblock.c:582
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
c0000000003f0040-c0000000003f03b8: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe0000482fa)
Location: mm/memblock.c:582
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffe0000482fa-ffffffe00004844a: memblock_add_range (STB_GLOBAL)
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
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6cead)
Location: mm/memblock.c:582
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff81a6cead-ffffffff81a6d05f: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a293f4)
Location: mm/memblock.c:582
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff81a293f4-ffffffff81a295a6: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad92bd)
Location: mm/memblock.c:582
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff81ad92bd-ffffffff81ad946f: memblock_add_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int memblock_add_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae5773)
Location: mm/memblock.c:582
Inline: False
Direct callers:
  - mm/memblock.c:memblock_reserve
  - mm/memblock.c:memblock_add
  - mm/memblock.c:memblock_add_node
```
**Symbols:**

```
ffffffff81ae5773-ffffffff81ae5925: memblock_add_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int flags</code> ➡️ <code>enum memblock_flags flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
