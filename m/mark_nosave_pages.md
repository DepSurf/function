# Function: <code>mark_nosave_pages</code>

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
In kernel/power/snapshot.c (ffffffff810d11d9)
Location: kernel/power/snapshot.c:930
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff810d5f24)
Location: kernel/power/snapshot.c:1030
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff810dca74)
Location: kernel/power/snapshot.c:1030
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff810dbb91)
Location: kernel/power/snapshot.c:1032
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff810e3db1)
Location: kernel/power/snapshot.c:1034
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff810ec056)
Location: kernel/power/snapshot.c:1034
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff810f76f6)
Location: kernel/power/snapshot.c:1035
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff810ffc56)
Location: kernel/power/snapshot.c:1036
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff8110c0b6)
Location: kernel/power/snapshot.c:1043
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mark_nosave_pages(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81116c90)
Location: kernel/power/snapshot.c:1042
Inline: False
Direct callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
**Symbols:**

```
ffffffff81116c90-ffffffff81116df0: mark_nosave_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mark_nosave_pages(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81113110)
Location: kernel/power/snapshot.c:1076
Inline: False
Direct callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
**Symbols:**

```
ffffffff81113110-ffffffff81113270: mark_nosave_pages (STB_LOCAL)
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
In kernel/power/snapshot.c (ffffffff81113d74)
Location: kernel/power/snapshot.c:1076
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mark_nosave_pages(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811330e0)
Location: kernel/power/snapshot.c:1069
Inline: False
Direct callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
**Symbols:**

```
ffffffff811330e0-ffffffff811331f0: mark_nosave_pages (STB_LOCAL)
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
In kernel/power/snapshot.c (ffffffff81155e29)
Location: kernel/power/snapshot.c:1073
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff81186399)
Location: kernel/power/snapshot.c:1073
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff81197519)
Location: kernel/power/snapshot.c:1073
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff811a60c7)
Location: kernel/power/snapshot.c:1083
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03be894)
Location: kernel/power/snapshot.c:1043
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
</details>
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
In kernel/power/snapshot.c (ffffffff811042d6)
Location: kernel/power/snapshot.c:1042
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff810f5576)
Location: kernel/power/snapshot.c:1043
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff81102586)
Location: kernel/power/snapshot.c:1043
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
In kernel/power/snapshot.c (ffffffff8110d956)
Location: kernel/power/snapshot.c:1043
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
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
