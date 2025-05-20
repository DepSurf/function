# Function: <code>lookup_address_in_mm</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pte_t *lookup_address_in_mm(struct mm_struct *mm, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d2b0)
Location: arch/x86/mm/pat/set_memory.c:634
Inline: False
```
**Symbols:**

```
ffffffff8108d2b0-ffffffff8108d2d9: lookup_address_in_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pte_t *lookup_address_in_mm(struct mm_struct *mm, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d180)
Location: arch/x86/mm/pat/set_memory.c:634
Inline: False
```
**Symbols:**

```
ffffffff8108d180-ffffffff8108d1a9: lookup_address_in_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pte_t *lookup_address_in_mm(struct mm_struct *mm, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108dd30)
Location: arch/x86/mm/pat/set_memory.c:642
Inline: False
```
**Symbols:**

```
ffffffff8108dd30-ffffffff8108dd59: lookup_address_in_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
pte_t *lookup_address_in_mm(struct mm_struct *mm, long unsigned int address, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:642
Inline: False
```
**Symbols:**

```
ffffffff81ca129c-ffffffff81ca12bd: lookup_address_in_mm.cold (STB_LOCAL)
ffffffff8109d600-ffffffff8109d646: lookup_address_in_mm (STB_GLOBAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
