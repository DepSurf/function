# Function: <code>idr_get_empty_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int idr_get_empty_slot(struct idr *idp, int starting_id, struct idr_layer **pa, gfp_t gfp_mask, struct idr *layer_idr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813ea6c0)
Location: lib/idr.c:289
Inline: False
Direct callers:
  - lib/idr.c:idr_alloc
  - lib/idr.c:ida_get_new_above
```
**Symbols:**

```
ffffffff813ea6c0-ffffffff813eaa63: idr_get_empty_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int idr_get_empty_slot(struct idr *idp, int starting_id, struct idr_layer **pa, gfp_t gfp_mask, struct idr *layer_idr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81430a80)
Location: lib/idr.c:289
Inline: False
Direct callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff81430a80-ffffffff81430def: idr_get_empty_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int idr_get_empty_slot(struct idr *idp, int starting_id, struct idr_layer **pa, gfp_t gfp_mask, struct idr *layer_idr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144cc50)
Location: lib/idr.c:289
Inline: False
Direct callers:
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_alloc
```
**Symbols:**

```
ffffffff8144cc50-ffffffff8144cfbe: idr_get_empty_slot (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
