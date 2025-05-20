# Function: <code>vmap_init_free_space</code>

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
In mm/vmalloc.c (ffffffff828d51e3)
Location: mm/vmalloc.c:1851
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
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
In mm/vmalloc.c (ffffffff828dd66a)
Location: mm/vmalloc.c:1859
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vmap_init_free_space();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812acb2a)
Location: mm/vmalloc.c:1962
Inline: False
Direct callers:
  - mm/vmalloc.c:vmalloc_init
```
**Symbols:**

```
ffffffff812acb2a-ffffffff812acbce: vmap_init_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vmap_init_free_space();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81be7ad0)
Location: mm/vmalloc.c:1944
Inline: False
Direct callers:
  - mm/vmalloc.c:vmalloc_init
```
**Symbols:**

```
ffffffff81be7ad0-ffffffff81be7b74: vmap_init_free_space (STB_LOCAL)
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
In mm/vmalloc.c (ffffffff831f1f10)
Location: mm/vmalloc.c:2234
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
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
In mm/vmalloc.c (ffffffff832d7b05)
Location: mm/vmalloc.c:2286
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
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
In mm/vmalloc.c (ffffffff8348c71e)
Location: mm/vmalloc.c:2316
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
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
In mm/vmalloc.c (ffffffff83ebdb74)
Location: mm/vmalloc.c:2378
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
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
In mm/vmalloc.c (ffffffff836e620b)
Location: mm/vmalloc.c:2500
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
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
In mm/vmalloc.c (ffffffff83918a6b)
Location: mm/vmalloc.c:2500
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
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
In mm/vmalloc.c (ffff80001145624c)
Location: mm/vmalloc.c:1859
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c1531398)
Location: mm/vmalloc.c:1859
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c00000000137f274)
Location: mm/vmalloc.c:1859
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
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
In mm/vmalloc.c (ffffffe0000151ac)
Location: mm/vmalloc.c:1859
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
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
In mm/vmalloc.c (ffffffff828c651e)
Location: mm/vmalloc.c:1859
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
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
In mm/vmalloc.c (ffffffff828bec43)
Location: mm/vmalloc.c:1859
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
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
In mm/vmalloc.c (ffffffff828d929e)
Location: mm/vmalloc.c:1859
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
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
In mm/vmalloc.c (ffffffff828de6bf)
Location: mm/vmalloc.c:1859
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
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
