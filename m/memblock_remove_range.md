# Function: <code>memblock_remove_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181e9bc)
Location: mm/memblock.c:709
Inline: False
Direct callers:
  - mm/memblock.c:memblock_remove
  - mm/memblock.c:memblock_free
  - mm/memblock.c:__memblock_free_early
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
```
**Symbols:**

```
ffffffff8181e9bc-ffffffff8181ea21: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81898e65)
Location: mm/memblock.c:698
Inline: False
Direct callers:
  - mm/memblock.c:memblock_mem_limit_remove_map
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:__memblock_free_early
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff81898e65-ffffffff81898ed2: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cd50d)
Location: mm/memblock.c:698
Inline: False
Direct callers:
  - mm/memblock.c:memblock_mem_limit_remove_map
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:__memblock_free_early
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff818cd50d-ffffffff818cd57a: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8190491a)
Location: mm/memblock.c:682
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:__memblock_free_early
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff8190491a-ffffffff81904987: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198e923)
Location: mm/memblock.c:682
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:__memblock_free_early
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff8198e923-ffffffff8198e990: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819eb1a6)
Location: mm/memblock.c:685
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:__memblock_free_early
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff819eb1a6-ffffffff819eb213: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a26426)
Location: mm/memblock.c:786
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff81a26426-ffffffff81a26493: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a96bd3)
Location: mm/memblock.c:783
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff81a96bd3-ffffffff81a96c40: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ace443)
Location: mm/memblock.c:783
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff81ace443-ffffffff81ace4b0: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc6b5a)
Location: mm/memblock.c:779
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff81bc6b5a-ffffffff81bc6bc7: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3f87c)
Location: mm/memblock.c:766
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff81c3f87c-ffffffff81c3f8e9: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3193c)
Location: mm/memblock.c:766
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff81c3193c-ffffffff81c319a9: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d502a0)
Location: mm/memblock.c:779
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff81d502a0-ffffffff81d5030d: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f206b3)
Location: mm/memblock.c:780
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_phys_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff81f206b3-ffffffff81f20739: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820ca1a9)
Location: mm/memblock.c:795
Inline: True
Inline callers:
  - mm/memblock.c:memblock_phys_free
  - mm/memblock.c:memblock_remove
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
```
**Symbols:**

```
ffffffff820c9d80-ffffffff820c9e11: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214e439)
Location: mm/memblock.c:808
Inline: True
Inline callers:
  - mm/memblock.c:memblock_phys_free
  - mm/memblock.c:memblock_remove
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
```
**Symbols:**

```
ffffffff8214e000-ffffffff8214e091: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff822311a9)
Location: mm/memblock.c:848
Inline: True
Inline callers:
  - mm/memblock.c:memblock_phys_free
  - mm/memblock.c:memblock_remove
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
```
**Symbols:**

```
ffffffff82230bc0-ffffffff82230c51: memblock_remove_range (STB_LOCAL)
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
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031c960)
Location: mm/memblock.c:783
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffff80001031c960-ffff80001031ca10: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0536878)
Location: mm/memblock.c:783
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
c0536878-c0536918: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003f07b0)
Location: mm/memblock.c:783
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
c0000000003f07b0-c0000000003f0880: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe00004863a)
Location: mm/memblock.c:783
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffe00004863a-ffffffe00004868c: memblock_remove_range (STB_LOCAL)
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
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6d2b3)
Location: mm/memblock.c:783
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff81a6d2b3-ffffffff81a6d320: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a297fa)
Location: mm/memblock.c:783
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff81a297fa-ffffffff81a29867: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad96c3)
Location: mm/memblock.c:783
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff81ad96c3-ffffffff81ad9730: memblock_remove_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int memblock_remove_range(struct memblock_type *type, phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae5b79)
Location: mm/memblock.c:783
Inline: False
Direct callers:
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_enforce_memory_limit
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff81ae5b79-ffffffff81ae5be6: memblock_remove_range (STB_LOCAL)
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
