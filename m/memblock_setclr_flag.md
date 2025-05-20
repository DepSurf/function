# Function: <code>memblock_setclr_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181ea7e)
Location: mm/memblock.c:767
Inline: True
Direct callers:
  - mm/memblock.c:memblock_mark_hotplug
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_mirror
```
**Symbols:**

```
ffffffff8181ea7e-ffffffff8181eb27: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81898f2f)
Location: mm/memblock.c:746
Inline: True
Direct callers:
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81898f2f-ffffffff81898fe1: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cd5d7)
Location: mm/memblock.c:746
Inline: True
Direct callers:
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff818cd5d7-ffffffff818cd689: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81904a16)
Location: mm/memblock.c:730
Inline: True
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81904a16-ffffffff81904ad2: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198ea1f)
Location: mm/memblock.c:730
Inline: True
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff8198ea1f-ffffffff8198eadb: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819eb301)
Location: mm/memblock.c:738
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff819eb301-ffffffff819eb3bd: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a26581)
Location: mm/memblock.c:851
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81a26581-ffffffff81a26635: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a96d32)
Location: mm/memblock.c:848
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81a96d32-ffffffff81a96de7: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ace5a2)
Location: mm/memblock.c:848
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81ace5a2-ffffffff81ace657: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc6cc7)
Location: mm/memblock.c:856
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81bc6cc7-ffffffff81bc6d75: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3f9e9)
Location: mm/memblock.c:843
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81c3f9e9-ffffffff81c3fa97: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c31aa9)
Location: mm/memblock.c:843
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81c31aa9-ffffffff81c31b57: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d50440)
Location: mm/memblock.c:870
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81d50440-ffffffff81d504ee: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f2089e)
Location: mm/memblock.c:871
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81f2089e-ffffffff81f20965: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820c9e30)
Location: mm/memblock.c:886
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff820c9e30-ffffffff820c9f04: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214e0b0)
Location: mm/memblock.c:899
Inline: False
Direct callers:
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff8214e0b0-ffffffff8214e195: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int memblock_setclr_flag(struct memblock_type *type, phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82230fdd)
Location: mm/memblock.c:940
Inline: True
Inline callers:
  - mm/memblock.c:memblock_clear_nomap
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_reserved_mark_noinit
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff82230c70-ffffffff82230d49: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031cb70)
Location: mm/memblock.c:848
Inline: True
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffff80001031cb70-ffff80001031cc70: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0536a78)
Location: mm/memblock.c:848
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
c0536a78-c0536b58: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003f0a00)
Location: mm/memblock.c:848
Inline: True
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
c0000000003f0a00-c0000000003f0b40: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000048748)
Location: mm/memblock.c:848
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffe000048748-ffffffe0000487dc: memblock_setclr_flag (STB_LOCAL)
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
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6d412)
Location: mm/memblock.c:848
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81a6d412-ffffffff81a6d4c7: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a29959)
Location: mm/memblock.c:848
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81a29959-ffffffff81a29a0e: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad9822)
Location: mm/memblock.c:848
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81ad9822-ffffffff81ad98d7: memblock_setclr_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int memblock_setclr_flag(phys_addr_t base, phys_addr_t size, int set, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae5cd8)
Location: mm/memblock.c:848
Inline: False
Direct callers:
  - mm/memblock.c:memblock_clear_nomap
  - mm/memblock.c:memblock_mark_nomap
  - mm/memblock.c:memblock_mark_mirror
  - mm/memblock.c:memblock_clear_hotplug
  - mm/memblock.c:memblock_mark_hotplug
```
**Symbols:**

```
ffffffff81ae5cd8-ffffffff81ae5d8d: memblock_setclr_flag (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct memblock_type *type</code>
</li>
<li>
<b>Param reordered. </b>
<code>base, size, set, flag</code> ➡️ <code>type, base, size, set, flag</code>
</li>
</ul>
</details>
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
