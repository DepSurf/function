# Function: <code>memblock_remove_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181da0d)
Location: mm/memblock.c:285
Inline: True
Direct callers:
  - mm/memblock.c:memblock_remove_range
  - mm/memblock.c:memblock_trim_memory
```
**Symbols:**

```
ffffffff8181da0d-ffffffff8181da99: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81897e39)
Location: mm/memblock.c:281
Inline: True
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_mem_limit_remove_map
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81897e39-ffffffff81897ec5: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cc4d8)
Location: mm/memblock.c:281
Inline: True
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_mem_limit_remove_map
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff818cc4d8-ffffffff818cc564: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8190391b)
Location: mm/memblock.c:269
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff8190391b-ffffffff81903998: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198d926)
Location: mm/memblock.c:269
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff8198d926-ffffffff8198d9a3: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819ea1e0)
Location: mm/memblock.c:272
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff819ea1e0-ffffffff819ea25d: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a25460)
Location: mm/memblock.c:349
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81a25460-ffffffff81a254d9: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a95b8f)
Location: mm/memblock.c:356
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81a95b8f-ffffffff81a95c14: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81acd472)
Location: mm/memblock.c:356
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81acd472-ffffffff81acd4eb: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc5ea7)
Location: mm/memblock.c:352
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81bc5ea7-ffffffff81bc5f20: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3ee07)
Location: mm/memblock.c:337
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81c3ee07-ffffffff81c3ee80: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c30ed6)
Location: mm/memblock.c:337
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81c30ed6-ffffffff81c30f4f: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d4f7f6)
Location: mm/memblock.c:339
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81d4f7f6-ffffffff81d4f86f: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f1f8af)
Location: mm/memblock.c:339
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81f1f8af-ffffffff81f1f930: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820c8c80)
Location: mm/memblock.c:343
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_phys_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff820c8c80-ffffffff820c8d15: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214cef0)
Location: mm/memblock.c:343
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_phys_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff8214cef0-ffffffff8214cf85: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8222fa00)
Location: mm/memblock.c:349
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_phys_free
  - mm/memblock.c:memblock_remove
```
**Symbols:**

```
ffffffff8222fa00-ffffffff8222fa95: memblock_remove_region (STB_LOCAL)
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
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031b388)
Location: mm/memblock.c:356
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffff80001031b388-ffff80001031b438: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c053535c)
Location: mm/memblock.c:356
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
c053535c-c0535410: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003eec10)
Location: mm/memblock.c:356
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
c0000000003eec10-c0000000003eecd4: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000047904)
Location: mm/memblock.c:356
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffe000047904-ffffffe000047972: memblock_remove_region (STB_LOCAL)
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
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6c2e2)
Location: mm/memblock.c:356
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81a6c2e2-ffffffff81a6c35b: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a28829)
Location: mm/memblock.c:356
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81a28829-ffffffff81a288a2: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad86f2)
Location: mm/memblock.c:356
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81ad86f2-ffffffff81ad876b: memblock_remove_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memblock_remove_region(struct memblock_type *type, long unsigned int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae4ba8)
Location: mm/memblock.c:356
Inline: False
Direct callers:
  - mm/memblock.c:memblock_trim_memory
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_cap_memory_range
  - mm/memblock.c:memblock_remove_range
```
**Symbols:**

```
ffffffff81ae4ba8-ffffffff81ae4c21: memblock_remove_region (STB_LOCAL)
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
