# Function: <code>add_ballooned_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff814c6dee)
Location: drivers/xen/balloon.c:597
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8151766a)
Location: drivers/xen/balloon.c:619
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
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
In drivers/xen/balloon.c (ffffffff81543b51)
Location: drivers/xen/balloon.c:617
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
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
In drivers/xen/balloon.c (ffffffff81557a00)
Location: drivers/xen/balloon.c:618
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815bbb34)
Location: drivers/xen/balloon.c:663
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815f40f0)
Location: drivers/xen/balloon.c:663
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8160efa0)
Location: drivers/xen/balloon.c:558
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81642d7d)
Location: drivers/xen/balloon.c:570
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
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
In drivers/xen/balloon.c (ffffffff8166532a)
Location: drivers/xen/balloon.c:566
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_ballooned_pages(int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81714980)
Location: drivers/xen/balloon.c:564
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
**Symbols:**

```
ffffffff81714980-ffffffff81714a83: add_ballooned_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_ballooned_pages(int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81731200)
Location: drivers/xen/balloon.c:549
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
**Symbols:**

```
ffffffff81731200-ffffffff81731303: add_ballooned_pages (STB_LOCAL)
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
In drivers/xen/balloon.c (ffffffff81715201)
Location: drivers/xen/balloon.c:549
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
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
In drivers/xen/balloon.c (ffffffff81792211)
Location: drivers/xen/balloon.c:583
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
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
In drivers/xen/balloon.c (ffffffff818ca49d)
Location: drivers/xen/balloon.c:585
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
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
In drivers/xen/balloon.c (ffffffff81a1b9dd)
Location: drivers/xen/balloon.c:585
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
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
In drivers/xen/balloon.c (ffffffff81a64b7d)
Location: drivers/xen/balloon.c:567
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
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
In drivers/xen/balloon.c (ffffffff81ab73dd)
Location: drivers/xen/balloon.c:566
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
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
In drivers/xen/balloon.c (ffff80001082f070)
Location: drivers/xen/balloon.c:566
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8162af4b)
Location: drivers/xen/balloon.c:566
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8165916a)
Location: drivers/xen/balloon.c:566
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
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
In drivers/xen/balloon.c (ffffffff8167376a)
Location: drivers/xen/balloon.c:566
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
