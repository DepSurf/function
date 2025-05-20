# Function: <code>page_ref_dec_return</code>

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
In mm/memory_hotplug.c (ffffffff8120f203)
Location: include/linux/page_ref.h:145
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
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
In mm/memory_hotplug.c (ffffffff812212d3)
Location: include/linux/page_ref.h:145
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
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
In mm/memory_hotplug.c (ffffffff8122ca33)
Location: include/linux/page_ref.h:145
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
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
In kernel/memremap.c (ffffffff811c9286)
Location: include/linux/page_ref.h:146
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81248268)
Location: include/linux/page_ref.h:146
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
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
In kernel/memremap.c (ffffffff811e93a5)
Location: include/linux/page_ref.h:146
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8126bc98)
Location: include/linux/page_ref.h:146
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
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
In kernel/memremap.c (ffffffff811f9f85)
Location: include/linux/page_ref.h:146
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81280598)
Location: include/linux/page_ref.h:146
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
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
In mm/memory_hotplug.c (ffffffff8129c8d3)
Location: include/linux/page_ref.h:146
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (ffffffff812c23d5)
Location: include/linux/page_ref.h:146
Inline: True
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
In mm/memory_hotplug.c (ffffffff812ac573)
Location: include/linux/page_ref.h:146
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (ffffffff812d4305)
Location: include/linux/page_ref.h:146
Inline: True
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
In mm/swap.c (ffffffff8125e53e)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/memory_hotplug.c (ffffffff812e1613)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
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
In mm/swap.c (ffffffff812685fb)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/memory_hotplug.c (ffffffff812ec563)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
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
In mm/swap.c (ffffffff8126df8b)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/memory_hotplug.c (ffffffff812c6e03)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
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
In mm/swap.c (ffffffff812aaed8)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/bootmem_info.c (ffffffff8136cb33)
Location: include/linux/page_ref.h:155
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
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
In mm/bootmem_info.c (ffffffff813eaec3)
Location: include/linux/page_ref.h:222
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
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
In mm/bootmem_info.c (ffffffff814730c3)
Location: include/linux/page_ref.h:222
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
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
In mm/bootmem_info.c (ffffffff814a7833)
Location: include/linux/page_ref.h:222
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
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
In mm/bootmem_info.c (ffffffff814d8863)
Location: include/linux/page_ref.h:222
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
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
In mm/memory_hotplug.c (ffff80001034e0e8)
Location: include/linux/page_ref.h:146
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042e828)
Location: include/linux/page_ref.h:146
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (c00000000046d8f4)
Location: include/linux/page_ref.h:146
Inline: True
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a4b53)
Location: include/linux/page_ref.h:146
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (ffffffff812cc8e5)
Location: include/linux/page_ref.h:146
Inline: True
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
In mm/memory_hotplug.c (ffffffff81296623)
Location: include/linux/page_ref.h:146
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (ffffffff812bd755)
Location: include/linux/page_ref.h:146
Inline: True
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
In mm/memory_hotplug.c (ffffffff812a2963)
Location: include/linux/page_ref.h:146
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (ffffffff812ca6f5)
Location: include/linux/page_ref.h:146
Inline: True
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
In mm/memory_hotplug.c (ffffffff812b2bf3)
Location: include/linux/page_ref.h:146
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (ffffffff812db3f5)
Location: include/linux/page_ref.h:146
Inline: True
```
</details>
</li>
</ul>

## Differences
