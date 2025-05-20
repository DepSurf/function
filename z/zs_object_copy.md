# Function: <code>zs_object_copy</code>

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
In mm/zsmalloc.c (ffffffff81206136)
Location: mm/zsmalloc.c:1503
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff8122bce6)
Location: mm/zsmalloc.c:1665
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff8123e236)
Location: mm/zsmalloc.c:1625
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff81249be6)
Location: mm/zsmalloc.c:1604
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff81269fb2)
Location: mm/zsmalloc.c:1608
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff8128e9cc)
Location: mm/zsmalloc.c:1611
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812a2b6c)
Location: mm/zsmalloc.c:1598
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812bdef9)
Location: mm/zsmalloc.c:1588
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812cfde9)
Location: mm/zsmalloc.c:1585
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void zs_object_copy(struct size_class *class, long unsigned int dst, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81305dd0)
Location: mm/zsmalloc.c:1587
Inline: False
```
**Symbols:**

```
ffffffff81305dd0-ffffffff81306052: zs_object_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void zs_object_copy(struct size_class *class, long unsigned int dst, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81311b30)
Location: mm/zsmalloc.c:1536
Inline: False
```
**Symbols:**

```
ffffffff81311b30-ffffffff81311db2: zs_object_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void zs_object_copy(struct size_class *class, long unsigned int dst, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81317a00)
Location: mm/zsmalloc.c:1535
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
```
**Symbols:**

```
ffffffff81317a00-ffffffff81317c78: zs_object_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void zs_object_copy(struct size_class *class, long unsigned int dst, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81364170)
Location: mm/zsmalloc.c:1534
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
```
**Symbols:**

```
ffffffff81364170-ffffffff813643e8: zs_object_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void zs_object_copy(struct size_class *class, long unsigned int dst, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e2030)
Location: mm/zsmalloc.c:1527
Inline: False
Direct callers:
  - mm/zsmalloc.c:__zs_compact
```
**Symbols:**

```
ffffffff813e2030-ffffffff813e239b: zs_object_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void zs_object_copy(struct size_class *class, long unsigned int dst, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81469610)
Location: mm/zsmalloc.c:1706
Inline: False
Direct callers:
  - mm/zsmalloc.c:__zs_compact
```
**Symbols:**

```
ffffffff81469610-ffffffff8146997a: zs_object_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void zs_object_copy(struct size_class *class, long unsigned int dst, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149e5c0)
Location: mm/zsmalloc.c:1478
Inline: False
```
**Symbols:**

```
ffffffff8149e5c0-ffffffff8149e934: zs_object_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void zs_object_copy(struct size_class *class, long unsigned int dst, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814cdd60)
Location: mm/zsmalloc.c:1481
Inline: False
Direct callers:
  - mm/zsmalloc.c:migrate_zspage
```
**Symbols:**

```
ffffffff814cdd60-ffffffff814ce0d4: zs_object_copy (STB_LOCAL)
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
In mm/zsmalloc.c (ffff8000103749a4)
Location: mm/zsmalloc.c:1585
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (c05617d4)
Location: mm/zsmalloc.c:1585
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (c000000000467dec)
Location: mm/zsmalloc.c:1585
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffe00024d7ec)
Location: mm/zsmalloc.c:1585
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812c83c9)
Location: mm/zsmalloc.c:1585
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812b9409)
Location: mm/zsmalloc.c:1585
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812c61d9)
Location: mm/zsmalloc.c:1585
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812d797a)
Location: mm/zsmalloc.c:1585
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
