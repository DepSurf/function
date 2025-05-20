# Function: <code>page_vma_mapped_walk</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff811f6d00)
Location: mm/page_vma_mapped.c:102
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff811f6d00-ffffffff811f728b: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff81201bf0)
Location: mm/page_vma_mapped.c:102
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff81201bf0-ffffffff8120217d: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff8121a620)
Location: mm/page_vma_mapped.c:116
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff8121a620-ffffffff8121ad7f: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff8123c490)
Location: mm/page_vma_mapped.c:116
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff8123c490-ffffffff8123cbcd: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff812508b0)
Location: mm/page_vma_mapped.c:138
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff812508b0-ffffffff81251098: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff81262b90)
Location: mm/page_vma_mapped.c:138
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff81262b90-ffffffff8126337d: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff81271340)
Location: mm/page_vma_mapped.c:138
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff81271340-ffffffff81271b2d: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff812a1a90)
Location: mm/page_vma_mapped.c:142
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff812a1a90-ffffffff812a2151: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff812ad340)
Location: mm/page_vma_mapped.c:143
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff812ad340-ffffffff812ada86: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff812b24c0)
Location: mm/page_vma_mapped.c:150
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff812b24c0-ffffffff812b2f34: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_vma_mapped.c (0)
Location: mm/page_vma_mapped.c:153
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_mlock_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff81cbcb13-ffffffff81cbcba7: page_vma_mapped_walk.cold (STB_LOCAL)
ffffffff812f40b0-ffffffff812f4aca: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_vma_mapped.c (0)
Location: mm/page_vma_mapped.c:151
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced_one
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff81e6e769-ffffffff81e6e7e2: page_vma_mapped_walk.cold (STB_LOCAL)
ffffffff813580d0-ffffffff81358a11: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_vma_mapped.c (0)
Location: mm/page_vma_mapped.c:151
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced_one
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff82064669-ffffffff820646ed: page_vma_mapped_walk.cold (STB_LOCAL)
ffffffff813d2740-ffffffff813d3135: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_vma_mapped.c (0)
Location: mm/page_vma_mapped.c:171
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced_one
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff820e3da7-ffffffff820e3e2b: page_vma_mapped_walk.cold (STB_LOCAL)
ffffffff81407530-ffffffff81407cba: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_vma_mapped.c (0)
Location: mm/page_vma_mapped.c:173
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced_one
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff821c0950-ffffffff821c09fb: page_vma_mapped_walk.cold (STB_LOCAL)
ffffffff81433ba0-ffffffff8143438f: page_vma_mapped_walk (STB_GLOBAL)
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffff800010307100)
Location: mm/page_vma_mapped.c:138
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/rmap.c:page_referenced_one
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffff800010307100-ffff800010307640: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (c0524c94)
Location: mm/page_vma_mapped.c:138
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
c0524c94-c0524e8c: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (c0000000003d5450)
Location: mm/page_vma_mapped.c:138
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
c0000000003d5450-c0000000003d6148: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffe000212652)
Location: mm/page_vma_mapped.c:138
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/rmap.c:page_referenced_one
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffe000212652-ffffffe00021281e: page_vma_mapped_walk (STB_GLOBAL)
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff81269990)
Location: mm/page_vma_mapped.c:138
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff81269990-ffffffff8126a17d: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff8125bc60)
Location: mm/page_vma_mapped.c:138
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff8125bc60-ffffffff8125c363: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff81267730)
Location: mm/page_vma_mapped.c:138
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff81267730-ffffffff81267f1d: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk *pvmw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (ffffffff812770c0)
Location: mm/page_vma_mapped.c:138
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff812770c0-ffffffff8127789c: page_vma_mapped_walk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
