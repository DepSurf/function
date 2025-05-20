# Function: <code>migrate_vma_check_page</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool migrate_vma_check_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81249ab0)
Location: mm/migrate.c:2384
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
```
**Symbols:**

```
ffffffff81249ab0-ffffffff81249b70: migrate_vma_check_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool migrate_vma_check_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126d140)
Location: mm/migrate.c:2397
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
```
**Symbols:**

```
ffffffff8126d140-ffffffff8126d202: migrate_vma_check_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool migrate_vma_check_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812819e0)
Location: mm/migrate.c:2376
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
```
**Symbols:**

```
ffffffff812819e0-ffffffff81281aa7: migrate_vma_check_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool migrate_vma_check_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812acf70)
Location: mm/migrate.c:2388
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812acf70-ffffffff812ad020: migrate_vma_check_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool migrate_vma_check_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e20a0)
Location: mm/migrate.c:2408
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
```
**Symbols:**

```
ffffffff812e20a0-ffffffff812e2150: migrate_vma_check_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool migrate_vma_check_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ed7e0)
Location: mm/migrate.c:2578
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
```
**Symbols:**

```
ffffffff812ed7e0-ffffffff812ed88d: migrate_vma_check_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool migrate_vma_check_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f32f0)
Location: mm/migrate.c:2541
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
```
**Symbols:**

```
ffffffff812f32f0-ffffffff812f33a2: migrate_vma_check_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool migrate_vma_check_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133d760)
Location: mm/migrate.c:2474
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
```
**Symbols:**

```
ffffffff8133d760-ffffffff8133d812: migrate_vma_check_page (STB_LOCAL)
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
In mm/migrate_device.c (ffffffff813b6887)
Location: mm/migrate_device.c:303
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_unmap
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
In mm/migrate_device.c (ffffffff814381f5)
Location: mm/migrate_device.c:328
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
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
In mm/migrate_device.c (ffffffff8146dec5)
Location: mm/migrate_device.c:322
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
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
In mm/migrate_device.c (ffffffff8149e88f)
Location: mm/migrate_device.c:325
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool migrate_vma_check_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000431c90)
Location: mm/migrate.c:2388
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
c000000000431c90-c000000000431dd8: migrate_vma_check_page (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool migrate_vma_check_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a5550)
Location: mm/migrate.c:2388
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812a5550-ffffffff812a5600: migrate_vma_check_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool migrate_vma_check_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81297020)
Location: mm/migrate.c:2388
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff81297020-ffffffff812970d0: migrate_vma_check_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool migrate_vma_check_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a3360)
Location: mm/migrate.c:2388
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812a3360-ffffffff812a3410: migrate_vma_check_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool migrate_vma_check_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b35f0)
Location: mm/migrate.c:2388
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812b35f0-ffffffff812b36a0: migrate_vma_check_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
</ul>
<b>Arch</b>
<ul>
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
