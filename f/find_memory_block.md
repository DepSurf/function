# Function: <code>find_memory_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81561990)
Location: drivers/base/memory.c:564
Inline: True
Inline callers:
  - drivers/base/memory.c:register_new_memory
  - drivers/base/memory.c:unregister_memory_section
```
**Symbols:**

```
ffffffff81561990-ffffffff815619a2: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815b639f)
Location: drivers/base/memory.c:597
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff815b6260-ffffffff815b6272: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815e56bf)
Location: drivers/base/memory.c:598
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff815e5580-ffffffff815e5592: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815fa12d)
Location: drivers/base/memory.c:606
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff815fa010-ffffffff815fa022: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816622cd)
Location: drivers/base/memory.c:617
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff816621b0-ffffffff816621c2: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8169dab5)
Location: drivers/base/memory.c:619
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:hotplug_memory_register
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8169d9a0-ffffffff8169d9b2: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816be225)
Location: drivers/base/memory.c:606
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:hotplug_memory_register
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff816be140-ffffffff816be152: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816f8f70)
Location: drivers/base/memory.c:608
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff816f8f70-ffffffff816f8fa7: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8171d2f0)
Location: drivers/base/memory.c:580
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8171d2f0-ffffffff8171d327: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d91d0)
Location: drivers/base/memory.c:518
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
```
**Symbols:**

```
ffffffff817d91d0-ffffffff817d9215: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817edbb0)
Location: drivers/base/memory.c:515
Inline: False
```
**Symbols:**

```
ffffffff817edbb0-ffffffff817edbf5: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d24f0)
Location: drivers/base/memory.c:581
Inline: False
```
**Symbols:**

```
ffffffff817d24f0-ffffffff817d2535: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct memory_block *find_memory_block(long unsigned int section_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8185d630)
Location: drivers/base/memory.c:589
Inline: False
```
**Symbols:**

```
ffffffff8185d630-ffffffff8185d673: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct memory_block *find_memory_block(long unsigned int section_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff819a49b0)
Location: drivers/base/memory.c:595
Inline: False
```
**Symbols:**

```
ffffffff819a49b0-ffffffff819a49fe: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct memory_block *find_memory_block(long unsigned int section_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b16a70)
Location: drivers/base/memory.c:607
Inline: False
```
**Symbols:**

```
ffffffff81b16a70-ffffffff81b16abe: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct memory_block *find_memory_block(long unsigned int section_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b657e0)
Location: drivers/base/memory.c:602
Inline: False
```
**Symbols:**

```
ffffffff81b657e0-ffffffff81b6582e: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct memory_block *find_memory_block(long unsigned int section_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81bb9660)
Location: drivers/base/memory.c:652
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory_blocks_and_altmaps
```
**Symbols:**

```
ffffffff81bb9660-ffffffff81bb96ae: find_memory_block (STB_GLOBAL)
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
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffff800010910f38)
Location: drivers/base/memory.c:580
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffff800010910f38-ffff800010910f94: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (c0000000009b2280)
Location: drivers/base/memory.c:580
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
c0000000009b2280-c0000000009b22e8: find_memory_block (STB_GLOBAL)
```
</details>
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
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816e3620)
Location: drivers/base/memory.c:580
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff816e3620-ffffffff816e3657: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bdc60)
Location: drivers/base/memory.c:580
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff816bdc60-ffffffff816bdc97: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817107b0)
Location: drivers/base/memory.c:580
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff817107b0-ffffffff817107e7: find_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct memory_block *find_memory_block(struct mem_section *section);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8172b910)
Location: drivers/base/memory.c:580
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8172b910-ffffffff8172b947: find_memory_block (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int section_nr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mem_section *section</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
