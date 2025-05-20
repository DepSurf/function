# Function: <code>shmem_delete_from_page_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a8506)
Location: mm/shmem.c:333
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c36e5)
Location: mm/shmem.c:598
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
In mm/shmem.c (ffffffff811d3755)
Location: mm/shmem.c:604
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
In mm/shmem.c (ffffffff811dbf5f)
Location: mm/shmem.c:620
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f1dff)
Location: mm/shmem.c:643
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812108b5)
Location: mm/shmem.c:652
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122396e)
Location: mm/shmem.c:643
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
In mm/shmem.c (ffffffff81232e59)
Location: mm/shmem.c:650
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
In mm/shmem.c (ffffffff81241079)
Location: mm/shmem.c:665
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void shmem_delete_from_page_cache(struct page *page, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126cf60)
Location: mm/shmem.c:681
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffff8126cf60-ffffffff8126d19f: shmem_delete_from_page_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void shmem_delete_from_page_cache(struct page *page, void *radswap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81277610)
Location: mm/shmem.c:740
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
```
**Symbols:**

```
ffffffff81277610-ffffffff8127775f: shmem_delete_from_page_cache (STB_LOCAL)
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
In mm/shmem.c (ffffffff8127e73f)
Location: mm/shmem.c:740
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
In mm/shmem.c (ffffffff812bc2bf)
Location: mm/shmem.c:770
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
In mm/shmem.c (ffffffff8131bb91)
Location: mm/shmem.c:767
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
In mm/shmem.c (ffffffff8138f657)
Location: mm/shmem.c:764
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
In mm/shmem.c (ffffffff813bf499)
Location: mm/shmem.c:764
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
In mm/shmem.c (ffffffff813ea4d6)
Location: mm/shmem.c:814
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
In mm/shmem.c (ffff8000102d2bb8)
Location: mm/shmem.c:665
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fb728)
Location: mm/shmem.c:665
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c0000000003924bc)
Location: mm/shmem.c:665
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ee7c4)
Location: mm/shmem.c:665
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
</details>
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
In mm/shmem.c (ffffffff812396c9)
Location: mm/shmem.c:665
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
In mm/shmem.c (ffffffff8122c703)
Location: mm/shmem.c:665
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
In mm/shmem.c (ffffffff81237469)
Location: mm/shmem.c:665
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
In mm/shmem.c (ffffffff81246a1b)
Location: mm/shmem.c:665
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
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
</ul>
