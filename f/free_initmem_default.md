# Function: <code>free_initmem_default</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002a05)
Location: include/linux/mm.h:2165
Inline: True
Inline callers:
  - init/main.c:free_initmem
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
In init/main.c (ffffffff81002a05)
Location: include/linux/mm.h:2137
Inline: True
Inline callers:
  - init/main.c:free_initmem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81003a25)
Location: include/linux/mm.h:2406
Inline: True
Inline callers:
  - init/main.c:free_initmem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81003ab5)
Location: include/linux/mm.h:2422
Inline: True
Inline callers:
  - init/main.c:free_initmem
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
In init/main.c (ffffffff81003a95)
Location: include/linux/mm.h:2418
Inline: True
Inline callers:
  - init/main.c:free_initmem
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
In init/main.c (ffffffff81003ad5)
Location: include/linux/mm.h:2447
Inline: True
Inline callers:
  - init/main.c:free_initmem
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
In init/main.c (ffffffff81001745)
Location: include/linux/mm.h:2524
Inline: True
Inline callers:
  - init/main.c:free_initmem
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
In init/main.c (ffffffff81001d95)
Location: include/linux/mm.h:2688
Inline: True
Inline callers:
  - init/main.c:free_initmem
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
In init/main.c (ffffffff81001c45)
Location: include/linux/mm.h:3013
Inline: True
Inline callers:
  - init/main.c:free_initmem
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
In init/main.c (ffffffff81001c55)
Location: include/linux/mm.h:3139
Inline: True
Inline callers:
  - init/main.c:free_initmem
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
In init/main.c (ffff800010085040)
Location: include/linux/mm.h:2137
Inline: True
Inline callers:
  - init/main.c:free_initmem
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
In init/main.c (c0303844)
Location: include/linux/mm.h:2137
Inline: True
Inline callers:
  - init/main.c:free_initmem
```
```
In arch/arm/mm/init.c (c031ab5c)
Location: include/linux/mm.h:2137
Inline: True
Inline callers:
  - arch/arm/mm/init.c:free_initmem
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
In init/main.c (c00000000001035c)
Location: include/linux/mm.h:2137
Inline: True
Inline callers:
  - init/main.c:free_initmem
```
```
In arch/powerpc/mm/mem.c (c000000000087444)
Location: include/linux/mm.h:2137
Inline: True
Inline callers:
  - arch/powerpc/mm/mem.c:free_initmem
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
In init/main.c (ffffffe0000b447e)
Location: include/linux/mm.h:2137
Inline: True
Inline callers:
  - init/main.c:free_initmem
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
In init/main.c (ffffffff81002a05)
Location: include/linux/mm.h:2137
Inline: True
Inline callers:
  - init/main.c:free_initmem
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
In init/main.c (ffffffff81000ee5)
Location: include/linux/mm.h:2137
Inline: True
Inline callers:
  - init/main.c:free_initmem
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
In init/main.c (ffffffff81002a05)
Location: include/linux/mm.h:2137
Inline: True
Inline callers:
  - init/main.c:free_initmem
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
In init/main.c (ffffffff81002a35)
Location: include/linux/mm.h:2137
Inline: True
Inline callers:
  - init/main.c:free_initmem
```
</details>
</li>
</ul>

## Differences
