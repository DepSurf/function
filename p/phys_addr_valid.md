# Function: <code>phys_addr_valid</code>

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
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/physaddr.h:3
Inline: True
```
```
In arch/x86/mm/physaddr.c (0)
Location: arch/x86/mm/physaddr.h:3
Inline: True
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
In arch/x86/mm/ioremap.c (ffffffff8106b88a)
Location: arch/x86/mm/physaddr.h:3
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/physaddr.c (ffffffff8107131b)
Location: arch/x86/mm/physaddr.h:3
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff8106f4aa)
Location: arch/x86/mm/physaddr.h:3
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/physaddr.c (ffffffff81074e9b)
Location: arch/x86/mm/physaddr.h:3
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff8106ebfa)
Location: arch/x86/mm/physaddr.h:3
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/physaddr.c (ffffffff8107444b)
Location: arch/x86/mm/physaddr.h:3
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff81073d05)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff81078175)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff81079feb)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff8107675e)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff8107ac45)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff8107cdab)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff8107cdb2)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff81081585)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff810837bb)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff8108052e)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff81085205)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff8108742f)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff8108170e)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff81085ef5)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff8108811f)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff810886b2)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff81089655)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a5bf)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff810888f2)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff81089835)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a85f)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff81089552)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff8108a525)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff8108b507)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff810989ec)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff81099a93)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff8109aab6)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff810ab799)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff810ac9e3)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff810add46)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff810c510c)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff810c6aa3)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff810c7f86)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff810c889f)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff810ca233)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff810cb6c2)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff810d0f9f)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff810d2693)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff810d3d22)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8108070e)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff81084ef5)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff8108711f)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff8106f65e)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff81073bc5)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff81075cef)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff810806be)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff81084ea5)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff810870cf)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
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
In arch/x86/mm/ioremap.c (ffffffff810827de)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/mmap.c (ffffffff81086ff5)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_mmap_phys_addr_range
```
```
In arch/x86/mm/physaddr.c (ffffffff810891ff)
Location: arch/x86/mm/physaddr.h:4
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
</details>
</li>
</ul>

## Differences
