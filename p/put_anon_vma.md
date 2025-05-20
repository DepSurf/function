# Function: <code>put_anon_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811cb6d0)
Location: include/linux/rmap.h:105
Inline: True
Inline callers:
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff811e4746)
Location: include/linux/rmap.h:105
Inline: True
Inline callers:
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/migrate.c (ffffffff811f2802)
Location: include/linux/rmap.h:105
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff811f7256)
Location: include/linux/rmap.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811cb6d0-ffffffff811cb6e2: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e8f65)
Location: include/linux/rmap.h:109
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff81203aa4)
Location: include/linux/rmap.h:109
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff81211ffd)
Location: include/linux/rmap.h:109
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812178fe)
Location: include/linux/rmap.h:109
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811e88e0-ffffffff811e88f2: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811fa445)
Location: include/linux/rmap.h:110
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff81215ac4)
Location: include/linux/rmap.h:110
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812241cb)
Location: include/linux/rmap.h:110
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff81229eae)
Location: include/linux/rmap.h:110
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811f9c40-ffffffff811f9c52: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812050e5)
Location: include/linux/rmap.h:108
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff812211e5)
Location: include/linux/rmap.h:108
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8122fb5c)
Location: include/linux/rmap.h:108
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff81235c3b)
Location: include/linux/rmap.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812049a0-ffffffff812049b3: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121e095)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff8123c4d2)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8124d318)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812549ef)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8121d950-ffffffff8121d963: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123ff87)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff8125fa4e)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff81271208)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff8127880e)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8123f800-ffffffff8123f813: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81254687)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff8127418e)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8128581f)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff8128cebe)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81253f00-ffffffff81253f13: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81266951)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff812902fc)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8129fb49)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812a7d11)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812661b0-ffffffff812661c2: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81275271)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff812a007c)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812b0ee9)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812b91e6)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81274ad0-ffffffff81274ae2: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a6693)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff812d46e0)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812e5f77)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
```
```
In mm/huge_memory.c (ffffffff812edc01)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812a5ee0-ffffffff812a5ef2: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b1b35)
Location: include/linux/rmap.h:111
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff812e00bc)
Location: include/linux/rmap.h:111
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812f13d8)
Location: include/linux/rmap.h:111
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
```
```
In mm/huge_memory.c (ffffffff812f92bf)
Location: include/linux/rmap.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812b1360-ffffffff812b1372: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b7205)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff812e72e0)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812f76d9)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
```
```
In mm/huge_memory.c (ffffffff812ff8c8)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812b6a30-ffffffff812b6a42: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f9625)
Location: include/linux/rmap.h:108
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff8132f20d)
Location: include/linux/rmap.h:108
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff81341d43)
Location: include/linux/rmap.h:108
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
```
```
In mm/huge_memory.c (ffffffff813494e3)
Location: include/linux/rmap.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812f8e50-ffffffff812f8e62: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135fee9)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff8139f418)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff813b3a99)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/huge_memory.c (ffffffff813bf990)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8135f6c0-ffffffff8135f6de: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813dade1)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff8141e5c8)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8143492b)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/huge_memory.c (ffffffff81441e79)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff813da530-ffffffff813da54e: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140f521)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff81453258)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8146aa39)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_undo_src
```
```
In mm/huge_memory.c (ffffffff8147771f)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8140ec70-ffffffff8140ec8e: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8143bf45)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff8148daa8)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff81499bf3)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_undo_src
```
```
In mm/huge_memory.c (ffffffff814a6f06)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:move_pages_huge_pmd
```
```
In mm/userfaultfd.c (ffffffff814d2cd4)
Location: include/linux/rmap.h:113
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
```
**Symbols:**

```
ffffffff8143b630-ffffffff8143b64e: put_anon_vma (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff80001030b0cc)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/ksm.c (ffff80001033f830)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffff8000103514d0)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffff8000103596f8)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0527528)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (c0545b1c)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (c0552a34)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
c0526c50-c0526c90: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003db0f0)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (c00000000041bf78)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (c0000000004377d4)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (c000000000442c64)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
c0000000003da3c0-c0000000003da3f4: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe000214afc)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/ksm.c (ffffffe000233eb0)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffe00023fd4a)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126d8c1)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff8129865c)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812a94c9)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812b17c6)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8126d120-ffffffff8126d132: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125f8f1)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff8128a21c)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8129ae29)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812a2b96)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8125f150-ffffffff8125f162: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126b661)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff8129646c)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812a72d9)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812af5d6)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8126aec0-ffffffff8126aed2: put_anon_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_anon_vma(struct anon_vma *anon_vma);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8127afec)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
Direct callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/ksm.c (ffffffff812a5112)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812b75e4)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812bf924)
Location: include/linux/rmap.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8127a830-ffffffff8127a842: put_anon_vma (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
