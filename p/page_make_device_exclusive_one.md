# Function: <code>page_make_device_exclusive_one</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool page_make_device_exclusive_one(struct page *page, struct vm_area_struct *vma, long unsigned int address, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2044
Inline: False
```
**Symbols:**

```
ffffffff812f8a90-ffffffff812f8dae: page_make_device_exclusive_one (STB_LOCAL)
ffffffff81cbcd7e-ffffffff81cbcdb7: page_make_device_exclusive_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool page_make_device_exclusive_one(struct folio *folio, struct vm_area_struct *vma, long unsigned int address, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2172
Inline: False
```
**Symbols:**

```
ffffffff8135f010-ffffffff8135f43d: page_make_device_exclusive_one (STB_LOCAL)
ffffffff81e6e9f7-ffffffff81e6ea1d: page_make_device_exclusive_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool page_make_device_exclusive_one(struct folio *folio, struct vm_area_struct *vma, long unsigned int address, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2186
Inline: False
```
**Symbols:**

```
ffffffff813d9ed0-ffffffff813da25c: page_make_device_exclusive_one (STB_LOCAL)
ffffffff82064944-ffffffff8206496a: page_make_device_exclusive_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool page_make_device_exclusive_one(struct folio *folio, struct vm_area_struct *vma, long unsigned int address, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2182
Inline: False
```
**Symbols:**

```
ffffffff8140e5e0-ffffffff8140e99c: page_make_device_exclusive_one (STB_LOCAL)
ffffffff820e4049-ffffffff820e406f: page_make_device_exclusive_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool page_make_device_exclusive_one(struct folio *folio, struct vm_area_struct *vma, long unsigned int address, void *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2339
Inline: False
```
**Symbols:**

```
ffffffff8143adc0-ffffffff8143b202: page_make_device_exclusive_one (STB_LOCAL)
ffffffff821c0c86-ffffffff821c0cae: page_make_device_exclusive_one.cold (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
