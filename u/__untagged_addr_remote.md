# Function: <code>__untagged_addr_remote</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e2b45)
Location: arch/x86/include/asm/uaccess_64.h:38
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff813f5237)
Location: arch/x86/include/asm/uaccess_64.h:38
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/madvise.c (ffffffff814291e8)
Location: arch/x86/include/asm/uaccess_64.h:38
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In mm/migrate.c (ffffffff81468d40)
Location: arch/x86/include/asm/uaccess_64.h:38
Inline: True
Inline callers:
  - mm/migrate.c:add_page_for_migration
```
```
In fs/proc/task_mmu.c (ffffffff815650fc)
Location: arch/x86/include/asm/uaccess_64.h:38
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
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
In mm/gup.c (ffffffff8140d385)
Location: arch/x86/include/asm/uaccess_64.h:38
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81415843)
Location: arch/x86/include/asm/uaccess_64.h:38
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/madvise.c (ffffffff81462a18)
Location: arch/x86/include/asm/uaccess_64.h:38
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In mm/migrate.c (ffffffff8149738f)
Location: arch/x86/include/asm/uaccess_64.h:38
Inline: True
Inline callers:
  - mm/migrate.c:add_page_for_migration
```
```
In fs/proc/task_mmu.c (ffffffff8159c530)
Location: arch/x86/include/asm/uaccess_64.h:38
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
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
