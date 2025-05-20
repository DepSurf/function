# Function: <code>PageBuddy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811929cf)
Location: include/linux/page-flags.h:516
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:is_free_buddy_page
```
```
In mm/compaction.c (ffffffff811b5951)
Location: include/linux/page-flags.h:516
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory_hotplug.c (ffffffff811f0221)
Location: include/linux/page-flags.h:516
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff81203b12)
Location: include/linux/page-flags.h:516
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/proc/page.c (ffffffff81288114)
Location: include/linux/page-flags.h:516
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811acd84)
Location: include/linux/page-flags.h:646
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/compaction.c (ffffffff811cf99e)
Location: include/linux/page-flags.h:646
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff8120f541)
Location: include/linux/page-flags.h:646
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff81228ff0)
Location: include/linux/page-flags.h:646
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffffffff812b54ce)
Location: include/linux/page-flags.h:646
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bd2e1)
Location: include/linux/page-flags.h:662
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/compaction.c (ffffffff811df9e3)
Location: include/linux/page-flags.h:662
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff8122164f)
Location: include/linux/page-flags.h:662
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff8123b585)
Location: include/linux/page-flags.h:662
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffffffff812cad2f)
Location: include/linux/page-flags.h:662
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c5541)
Location: include/linux/page-flags.h:665
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/compaction.c (ffffffff811e96ba)
Location: include/linux/page-flags.h:665
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff8122d261)
Location: include/linux/page-flags.h:665
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812471a0)
Location: include/linux/page-flags.h:665
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffffffff812d81bf)
Location: include/linux/page-flags.h:665
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/page_alloc.c (ffffffff811da2f1)
Location: include/linux/page-flags.h:666
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/compaction.c (ffffffff811ffa0d)
Location: include/linux/page-flags.h:666
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81248ae1)
Location: include/linux/page-flags.h:666
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812672e3)
Location: include/linux/page-flags.h:666
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffffffff812fc8bf)
Location: include/linux/page-flags.h:666
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/page_alloc.c (ffffffff811fabe1)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/compaction.c (ffffffff81220e6c)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff8126c54a)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff8128bbdf)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffffffff8132a4bc)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/page_alloc.c (ffffffff8120d421)
Location: include/linux/page-flags.h:706
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/compaction.c (ffffffff81233ebc)
Location: include/linux/page-flags.h:706
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81280da6)
Location: include/linux/page-flags.h:706
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812a0b3f)
Location: include/linux/page-flags.h:706
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffffffff813417df)
Location: include/linux/page-flags.h:706
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81245313)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81273881)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff81a9582e)
Location: include/linux/page-flags.h:740
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8129d208)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812bbdd3)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffffffff81369bfe)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812537d3)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812826f1)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff81acd111)
Location: include/linux/page-flags.h:756
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812ac9d8)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812cdcb3)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffffffff81381e1e)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81282473)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812b4859)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff81bc5b06)
Location: include/linux/page-flags.h:772
Inline: True
```
```
In mm/page_isolation.c (ffffffff81303f0b)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff8130ceef)
Location: include/linux/page-flags.h:772
Inline: True
```
```
In fs/proc/page.c (ffffffff813cc44e)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128c5d6)
Location: include/linux/page-flags.h:748
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812c0208)
Location: include/linux/page-flags.h:748
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff81c3eaec)
Location: include/linux/page-flags.h:748
Inline: True
```
```
In mm/page_isolation.c (ffffffff8130fdd6)
Location: include/linux/page-flags.h:748
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff81318e47)
Location: include/linux/page-flags.h:748
Inline: True
```
```
In fs/proc/page.c (ffffffff813de092)
Location: include/linux/page-flags.h:748
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81291492)
Location: include/linux/page-flags.h:742
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812c597f)
Location: include/linux/page-flags.h:742
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff81c30bbb)
Location: include/linux/page-flags.h:742
Inline: True
```
```
In mm/page_isolation.c (ffffffff81315f2d)
Location: include/linux/page-flags.h:742
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff8131f036)
Location: include/linux/page-flags.h:742
Inline: True
```
```
In fs/proc/page.c (ffffffff813e4e7f)
Location: include/linux/page-flags.h:742
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812d2dd2)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff8130a09d)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff81d4f4e3)
Location: include/linux/page-flags.h:751
Inline: True
```
```
In mm/page_isolation.c (ffffffff8136201a)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff8136c406)
Location: include/linux/page-flags.h:751
Inline: True
```
```
In fs/proc/page.c (ffffffff81436a4f)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8132ff22)
Location: include/linux/page-flags.h:974
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff8137290c)
Location: include/linux/page-flags.h:974
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff81f1f441)
Location: include/linux/page-flags.h:974
Inline: True
```
```
In mm/page_isolation.c (ffffffff813dea90)
Location: include/linux/page-flags.h:974
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff813ea704)
Location: include/linux/page-flags.h:974
Inline: True
```
```
In fs/proc/page.c (ffffffff814b11ed)
Location: include/linux/page-flags.h:974
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a6af2)
Location: include/linux/page-flags.h:953
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff813f007c)
Location: include/linux/page-flags.h:953
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff820c865c)
Location: include/linux/page-flags.h:953
Inline: True
```
```
In mm/page_isolation.c (ffffffff81465750)
Location: include/linux/page-flags.h:953
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff81472894)
Location: include/linux/page-flags.h:953
Inline: True
```
```
In fs/proc/page.c (ffffffff81547bad)
Location: include/linux/page-flags.h:953
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813da312)
Location: include/linux/page-flags.h:942
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81423bf9)
Location: include/linux/page-flags.h:942
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff8214c8dc)
Location: include/linux/page-flags.h:942
Inline: True
```
```
In mm/page_isolation.c (ffffffff8149b21b)
Location: include/linux/page-flags.h:942
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff814a7004)
Location: include/linux/page-flags.h:942
Inline: True
```
```
In fs/proc/page.c (ffffffff8157f7cc)
Location: include/linux/page-flags.h:942
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81402215)
Location: include/linux/page-flags.h:988
Inline: True
Inline callers:
  - mm/compaction.c:suitable_migration_target
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81450b36)
Location: include/linux/page-flags.h:988
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff8222f3ec)
Location: include/linux/page-flags.h:988
Inline: True
```
```
In mm/page_isolation.c (ffffffff814ca8fb)
Location: include/linux/page-flags.h:988
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff814d8004)
Location: include/linux/page-flags.h:988
Inline: True
```
```
In fs/proc/page.c (ffffffff815b8209)
Location: include/linux/page-flags.h:988
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/compaction.c (ffff8000102eaca4)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffff80001031ac80)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffff800010da0130)
Location: include/linux/page-flags.h:756
Inline: True
```
```
In mm/page_isolation.c (ffff8000103720d0)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffff800010450018)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050ef90)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (c0535088)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (c15bdff0)
Location: include/linux/page-flags.h:756
Inline: True
```
```
In mm/page_isolation.c (c055ee94)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (c06132cc)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003adb88)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (c0000000003ee464)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (c000000000eecd8c)
Location: include/linux/page-flags.h:756
Inline: True
```
```
In mm/memory_hotplug.c (c00000000042ee3c)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (c0000000004639b4)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (c00000000056802c)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/compaction.c (ffffffe0001ff210)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffe000220186)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffe0000474be)
Location: include/linux/page-flags.h:756
Inline: True
```
```
In mm/page_isolation.c (ffffffe00024b3ea)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffffffe0002e3218)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124be23)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff8127ad41)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff81a6bf81)
Location: include/linux/page-flags.h:756
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812a4fb8)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812c6293)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffffffff8137a3fe)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8123edc3)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff8126cc21)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff81a284c8)
Location: include/linux/page-flags.h:756
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81296a88)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812b72d3)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffffffff8136aece)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81249bc3)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81278ae1)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff81ad8391)
Location: include/linux/page-flags.h:756
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812a2dc8)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812c40a3)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffffffff81377ece)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81259443)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812886d1)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffff81ae484c)
Location: include/linux/page-flags.h:756
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812b3053)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812d4b43)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In fs/proc/page.c (ffffffff8138b97e)
Location: include/linux/page-flags.h:756
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
</ul>

## Differences
