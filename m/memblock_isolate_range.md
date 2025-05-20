# Function: <code>memblock_isolate_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181e87f)
Location: mm/memblock.c:649
Inline: False
Direct callers:
  - mm/memblock.c:memblock_remove_range
  - mm/memblock.c:memblock_set_node
```
**Symbols:**

```
ffffffff8181e87f-ffffffff8181e9bc: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81898d24)
Location: mm/memblock.c:638
Inline: False
Direct callers:
  - mm/memblock.c:memblock_mem_limit_remove_map
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81898d24-ffffffff81898e65: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cd3cc)
Location: mm/memblock.c:638
Inline: False
Direct callers:
  - mm/memblock.c:memblock_mem_limit_remove_map
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff818cd3cc-ffffffff818cd50d: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819047d9)
Location: mm/memblock.c:622
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff819047d9-ffffffff8190491a: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198e7e2)
Location: mm/memblock.c:622
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff8198e7e2-ffffffff8198e923: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819eb065)
Location: mm/memblock.c:625
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff819eb065-ffffffff819eb1a6: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a262e5)
Location: mm/memblock.c:726
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81a262e5-ffffffff81a26426: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a96a9e)
Location: mm/memblock.c:723
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81a96a9e-ffffffff81a96bd3: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ace30e)
Location: mm/memblock.c:723
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81ace30e-ffffffff81ace443: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc6a25)
Location: mm/memblock.c:719
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81bc6a25-ffffffff81bc6b5a: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3f747)
Location: mm/memblock.c:706
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81c3f747-ffffffff81c3f87c: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c31807)
Location: mm/memblock.c:706
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81c31807-ffffffff81c3193c: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d5016b)
Location: mm/memblock.c:719
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81d5016b-ffffffff81d502a0: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f2056d)
Location: mm/memblock.c:720
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81f2056d-ffffffff81f206b3: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820c9be0)
Location: mm/memblock.c:735
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_phys_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff820c9be0-ffffffff820c9d70: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214de60)
Location: mm/memblock.c:748
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_phys_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff8214de60-ffffffff8214dff0: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82230a20)
Location: mm/memblock.c:788
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_phys_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff82230a20-ffffffff82230bb0: memblock_isolate_range (STB_LOCAL)
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
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031c7e0)
Location: mm/memblock.c:723
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffff80001031c7e0-ffff80001031c960: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c05366e4)
Location: mm/memblock.c:723
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
c05366e4-c0536878: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003f0580)
Location: mm/memblock.c:723
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
c0000000003f0580-c0000000003f07a8: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000048536)
Location: mm/memblock.c:723
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffe000048536-ffffffe00004863a: memblock_isolate_range (STB_LOCAL)
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
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6d17e)
Location: mm/memblock.c:723
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81a6d17e-ffffffff81a6d2b3: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a296c5)
Location: mm/memblock.c:723
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81a296c5-ffffffff81a297fa: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad958e)
Location: mm/memblock.c:723
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81ad958e-ffffffff81ad96c3: memblock_isolate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int memblock_isolate_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int *start_rgn, int *end_rgn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae5a44)
Location: mm/memblock.c:723
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_set_node
  - mm/memblock.c:memblock_setclr_flag
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81ae5a44-ffffffff81ae5b79: memblock_isolate_range (STB_LOCAL)
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
