# Function: <code>hugepage_init_sysfs</code>

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
In mm/huge_memory.c (ffffffff81f8d5d2)
Location: mm/huge_memory.c:572
Inline: True
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
In mm/huge_memory.c (ffffffff81fb7659)
Location: mm/huge_memory.c:303
Inline: True
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
In mm/huge_memory.c (ffffffff81ff3fd2)
Location: mm/huge_memory.c:333
Inline: True
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
In mm/huge_memory.c (ffffffff820d67af)
Location: mm/huge_memory.c:335
Inline: True
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
In mm/huge_memory.c (ffffffff826df41d)
Location: mm/huge_memory.c:335
Inline: True
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
In mm/huge_memory.c (ffffffff82709841)
Location: mm/huge_memory.c:335
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff828c0a23)
Location: mm/huge_memory.c:345
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff828d9da8)
Location: mm/huge_memory.c:350
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff828e224f)
Location: mm/huge_memory.c:342
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff82cff629)
Location: mm/huge_memory.c:342
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff82febfd5)
Location: mm/huge_memory.c:335
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff831f6834)
Location: mm/huge_memory.c:348
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff832dd34a)
Location: mm/huge_memory.c:348
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff83492b84)
Location: mm/huge_memory.c:347
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff83ec6a7d)
Location: mm/huge_memory.c:408
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff836eba6d)
Location: mm/huge_memory.c:409
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hugepage_init_sysfs(struct kobject **hugepage_kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8391e850)
Location: mm/huge_memory.c:560
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
```
**Symbols:**

```
ffffffff8391e850-ffffffff8391eadf: hugepage_init_sysfs (STB_LOCAL)
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
In mm/huge_memory.c (ffff80001145b414)
Location: mm/huge_memory.c:342
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c000000001385b34)
Location: mm/huge_memory.c:342
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff828cb103)
Location: mm/huge_memory.c:342
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff828c3828)
Location: mm/huge_memory.c:342
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff828dde83)
Location: mm/huge_memory.c:342
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/huge_memory.c (ffffffff828e329a)
Location: mm/huge_memory.c:342
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
