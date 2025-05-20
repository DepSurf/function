# Function: <code>__put_anon_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811cb630)
Location: mm/rmap.c:1534
Inline: False
Direct callers:
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:anon_vma_prepare
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811cb630-ffffffff811cb6c3: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e8840)
Location: mm/rmap.c:1710
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811e8840-ffffffff811e88d3: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f9ba0)
Location: mm/rmap.c:1709
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811f9ba0-ffffffff811f9c33: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81204900)
Location: mm/rmap.c:1619
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81204900-ffffffff81204997: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121d8b0)
Location: mm/rmap.c:1704
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8121d8b0-ffffffff8121d947: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123f760)
Location: mm/rmap.c:1722
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8123f760-ffffffff8123f7f9: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81253e60)
Location: mm/rmap.c:1757
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81253e60-ffffffff81253ef9: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81266110)
Location: mm/rmap.c:1767
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81266110-ffffffff812661a9: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81274a30)
Location: mm/rmap.c:1767
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81274a30-ffffffff81274ac9: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a5e40)
Location: mm/rmap.c:1805
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812a5e40-ffffffff812a5ed9: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b12c0)
Location: mm/rmap.c:1799
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812b12c0-ffffffff812b1359: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b6990)
Location: mm/rmap.c:1821
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812b6990-ffffffff812b6a29: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f8db0)
Location: mm/rmap.c:2222
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812f8db0-ffffffff812f8e49: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135f610)
Location: mm/rmap.c:2349
Inline: False
Direct callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8135f610-ffffffff8135f6bd: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813da470)
Location: mm/rmap.c:2363
Inline: False
Direct callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff813da470-ffffffff813da51d: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140ebb0)
Location: mm/rmap.c:2361
Inline: False
Direct callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_undo_src
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8140ebb0-ffffffff8140ec5d: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8143b570)
Location: mm/rmap.c:2518
Inline: False
Direct callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_undo_src
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/userfaultfd.c:move_pages_pte
```
**Symbols:**

```
ffffffff8143b570-ffffffff8143b61d: __put_anon_vma (STB_GLOBAL)
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
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff80001030a680)
Location: mm/rmap.c:1767
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffff80001030a680-ffff80001030a768: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0526b84)
Location: mm/rmap.c:1767
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
c0526b84-c0526c50: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003da280)
Location: mm/rmap.c:1767
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
c0000000003da280-c0000000003da3bc: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe0002142ea)
Location: mm/rmap.c:1767
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffe0002142ea-ffffffe0002143ae: __put_anon_vma (STB_GLOBAL)
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
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126d080)
Location: mm/rmap.c:1767
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8126d080-ffffffff8126d119: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125f0b0)
Location: mm/rmap.c:1767
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8125f0b0-ffffffff8125f149: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126ae20)
Location: mm/rmap.c:1767
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8126ae20-ffffffff8126aeb9: __put_anon_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8127a7a0)
Location: mm/rmap.c:1767
Inline: False
Direct callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8127a7a0-ffffffff8127a82e: __put_anon_vma (STB_GLOBAL)
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
