# Function: <code>__zs_map_object</code>

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
In mm/zsmalloc.c (ffffffff81205586)
Location: mm/zsmalloc.c:1052
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
In mm/zsmalloc.c (ffffffff8122ab5c)
Location: mm/zsmalloc.c:1187
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (ffffffff8123d0a9)
Location: mm/zsmalloc.c:1187
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (ffffffff812496d4)
Location: mm/zsmalloc.c:1177
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (ffffffff81269588)
Location: mm/zsmalloc.c:1181
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (ffffffff8128d479)
Location: mm/zsmalloc.c:1164
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (ffffffff812a26b9)
Location: mm/zsmalloc.c:1151
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (ffffffff812bd994)
Location: mm/zsmalloc.c:1141
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (ffffffff812cf884)
Location: mm/zsmalloc.c:1138
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__zs_map_object(struct mapping_area *area, struct page **pages, int off, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81305cb0)
Location: mm/zsmalloc.c:1178
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff81305cb0-ffffffff81305dc7: __zs_map_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__zs_map_object(struct mapping_area *area, struct page **pages, int off, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81311a10)
Location: mm/zsmalloc.c:1129
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff81311a10-ffffffff81311b27: __zs_map_object (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff813189d5)
Location: mm/zsmalloc.c:1128
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (ffffffff81364d26)
Location: mm/zsmalloc.c:1128
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__zs_map_object(struct mapping_area *area, struct page **pages, int off, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e1470)
Location: mm/zsmalloc.c:1125
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff813e1470-ffffffff813e15f1: __zs_map_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__zs_map_object(struct mapping_area *area, struct page **pages, int off, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81468970)
Location: mm/zsmalloc.c:1233
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff81468970-ffffffff81468af1: __zs_map_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__zs_map_object(struct mapping_area *area, struct page **pages, int off, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149da00)
Location: mm/zsmalloc.c:1058
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff8149da00-ffffffff8149db07: __zs_map_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__zs_map_object(struct mapping_area *area, struct page **pages, int off, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814cd6d0)
Location: mm/zsmalloc.c:1053
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff814cd6d0-ffffffff814cd7d7: __zs_map_object (STB_LOCAL)
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
In mm/zsmalloc.c (ffff800010375424)
Location: mm/zsmalloc.c:1138
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (c0562438)
Location: mm/zsmalloc.c:1138
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (c000000000466d14)
Location: mm/zsmalloc.c:1138
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (ffffffe00024cf0a)
Location: mm/zsmalloc.c:1176
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (ffffffff812c7e64)
Location: mm/zsmalloc.c:1138
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (ffffffff812b8ea4)
Location: mm/zsmalloc.c:1138
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (ffffffff812c5c74)
Location: mm/zsmalloc.c:1138
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
In mm/zsmalloc.c (ffffffff812d6e6d)
Location: mm/zsmalloc.c:1138
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
