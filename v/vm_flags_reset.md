# Function: <code>vm_flags_reset</code>

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
In mm/mlock.c (ffffffff813f72cf)
Location: include/linux/mm.h:783
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mprotect.c (ffffffff81403ea1)
Location: include/linux/mm.h:783
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/madvise.c (ffffffff814286d9)
Location: include/linux/mm.h:783
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In fs/userfaultfd.c (ffffffff815239e5)
Location: include/linux/mm.h:783
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_set_vm_flags
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
In mm/mlock.c (ffffffff814227dc)
Location: include/linux/mm.h:824
Inline: True
Inline callers:
  - mm/mlock.c:mlock_fixup
```
```
In mm/mprotect.c (ffffffff814303de)
Location: include/linux/mm.h:824
Inline: True
Inline callers:
  - mm/mprotect.c:mprotect_fixup
```
```
In mm/madvise.c (ffffffff81461f86)
Location: include/linux/mm.h:824
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
```
In fs/userfaultfd.c (ffffffff81559c12)
Location: include/linux/mm.h:824
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
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
