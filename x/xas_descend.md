# Function: <code>xas_descend</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17e70)
Location: lib/xarray.c:195
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff81a87a39)
Location: lib/xarray.c:200
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff81abecd9)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff815fb240)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff8161fda9)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff81603529)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *xas_descend(struct xa_state *xas, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff81671ed5)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
Direct callers:
  - lib/xarray.c:xas_find_conflict
```
**Symbols:**

```
ffffffff81670090-ffffffff81670119: xas_descend (STB_LOCAL)
ffffffff81cdfc69-ffffffff81cdfc87: xas_descend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *xas_descend(struct xa_state *xas, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff8178c68c)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
Direct callers:
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff8178a710-ffffffff8178a7c7: xas_descend (STB_LOCAL)
ffffffff81ea64c4-ffffffff81ea64e2: xas_descend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *xas_descend(struct xa_state *xas, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff82049d2c)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
Direct callers:
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff82047c30-ffffffff82047ce7: xas_descend (STB_LOCAL)
ffffffff820b7d4a-ffffffff820b7d68: xas_descend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *xas_descend(struct xa_state *xas, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:203
Inline: False
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff820c63c0-ffffffff820c648f: xas_descend (STB_LOCAL)
ffffffff821391ba-ffffffff821391d8: xas_descend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *xas_descend(struct xa_state *xas, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:203
Inline: False
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff821a0d40-ffffffff821a0e0f: xas_descend (STB_LOCAL)
ffffffff8221af5f-ffffffff8221af7d: xas_descend.cold (STB_LOCAL)
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
In lib/xarray.c (ffff800010d99cdc)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (c0e96850)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (c000000000edfd54)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffe0008c28ea)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff81a5db29)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff81a1abf9)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff81ac9f19)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff81ad649d)
Location: lib/xarray.c:201
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
