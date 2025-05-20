# Function: <code>pte_mkdevmap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dd6ae)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ed19e)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f8147)
Location: arch/x86/include/asm/pgtable.h:329
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812102c2)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffffffff81249e3b)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122f9ec)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffffffff8126d698)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81244418)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
```
In mm/migrate.c (ffffffff81281db2)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812563c0)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264950)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
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
In mm/memory.c (ffffffff81292bb4)
Location: arch/x86/include/asm/pgtable.h:395
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
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
In mm/memory.c (ffffffff8129d4c8)
Location: arch/x86/include/asm/pgtable.h:394
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
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
In mm/memory.c (ffffffff812a2af4)
Location: arch/x86/include/asm/pgtable.h:394
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
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
In mm/memory.c (ffffffff812e5f42)
Location: arch/x86/include/asm/pgtable.h:365
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
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
In mm/memory.c (ffffffff81345537)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
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
In mm/memory.c (ffffffff813bd7c7)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
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
In mm/memory.c (ffffffff813f24cc)
Location: arch/x86/include/asm/pgtable.h:386
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
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
In mm/memory.c (ffffffff8141d152)
Location: arch/x86/include/asm/pgtable.h:489
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: arch/arm64/include/asm/pgtable.h:206
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c6510)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:683
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125cfa0)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f41f)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125ad40)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126a70e)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
</details>
</li>
</ul>

## Differences
