# Function: <code>put_user_page</code>

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
In mm/gup.c (ffffffff8124a8d6)
Location: include/linux/mm.h:1055
Inline: True
Inline callers:
  - mm/gup.c:put_user_pages
  - mm/gup.c:__put_user_pages_dirty
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
In mm/gup.c (ffffffff81258da6)
Location: include/linux/mm.h:1068
Inline: True
```
```
In fs/io_uring.c (ffffffff8134108a)
Location: include/linux/mm.h:1068
Inline: True
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/gup.c (ffff8000102f0d7c)
Location: include/linux/mm.h:1068
Inline: True
```
```
In fs/io_uring.c (ffff80001040115c)
Location: include/linux/mm.h:1068
Inline: True
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
In mm/gup.c (c0514550)
Location: include/linux/mm.h:1068
Inline: True
```
```
In fs/io_uring.c (c05d2eec)
Location: include/linux/mm.h:1068
Inline: True
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
In mm/gup.c (c0000000003b5934)
Location: include/linux/mm.h:1068
Inline: True
```
```
In fs/io_uring.c (c00000000050ab7c)
Location: include/linux/mm.h:1068
Inline: True
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
In mm/gup.c (ffffffe000204462)
Location: include/linux/mm.h:1068
Inline: True
```
```
In fs/io_uring.c (ffffffe0002ad4dc)
Location: include/linux/mm.h:1068
Inline: True
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
In mm/gup.c (ffffffff812513f6)
Location: include/linux/mm.h:1068
Inline: True
```
```
In fs/io_uring.c (ffffffff8133966a)
Location: include/linux/mm.h:1068
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
In mm/gup.c (ffffffff812442e6)
Location: include/linux/mm.h:1068
Inline: True
```
```
In fs/io_uring.c (ffffffff8132a39a)
Location: include/linux/mm.h:1068
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
In mm/gup.c (ffffffff8124f196)
Location: include/linux/mm.h:1068
Inline: True
```
```
In fs/io_uring.c (ffffffff8133713a)
Location: include/linux/mm.h:1068
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
In mm/gup.c (ffffffff8125eb06)
Location: include/linux/mm.h:1068
Inline: True
```
```
In fs/io_uring.c (ffffffff8134a1fa)
Location: include/linux/mm.h:1068
Inline: True
```
</details>
</li>
</ul>

## Differences
