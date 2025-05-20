# Function: <code>gnttab_foreach_grant</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff814c61f0)
Location: drivers/xen/grant-table.c:805
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff814c61f0-ffffffff814c62d3: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815169b0)
Location: drivers/xen/grant-table.c:804
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff815169b0-ffffffff81516a75: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81542e20)
Location: drivers/xen/grant-table.c:804
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff81542e20-ffffffff81542ee2: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81556cd0)
Location: drivers/xen/grant-table.c:805
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff81556cd0-ffffffff81556d9d: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815bad00)
Location: drivers/xen/grant-table.c:897
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff815bad00-ffffffff815badd0: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815f3260)
Location: drivers/xen/grant-table.c:897
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff815f3260-ffffffff815f332f: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160e2c0)
Location: drivers/xen/grant-table.c:1010
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff8160e2c0-ffffffff8160e38f: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81641fd0)
Location: drivers/xen/grant-table.c:1010
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff81641fd0-ffffffff81642095: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81664590)
Location: drivers/xen/grant-table.c:1010
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff81664590-ffffffff81664655: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81713b30)
Location: drivers/xen/grant-table.c:1008
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff81713b30-ffffffff81713bf5: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81730a20)
Location: drivers/xen/grant-table.c:1131
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff81730a20-ffffffff81730ae5: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff817145b0)
Location: drivers/xen/grant-table.c:1131
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff817145b0-ffffffff81714679: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81791350)
Location: drivers/xen/grant-table.c:1138
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff81791350-ffffffff81791419: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c9a50)
Location: drivers/xen/grant-table.c:1204
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff818c9a50-ffffffff818c9b28: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a1a960)
Location: drivers/xen/grant-table.c:1207
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff81a1a960-ffffffff81a1aa38: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a63b10)
Location: drivers/xen/grant-table.c:1225
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff81a63b10-ffffffff81a63be8: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab6350)
Location: drivers/xen/grant-table.c:1223
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff81ab6350-ffffffff81ab6428: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082e300)
Location: drivers/xen/grant-table.c:1010
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffff80001082e300-ffff80001082e384: gnttab_foreach_grant (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8162a400)
Location: drivers/xen/grant-table.c:1010
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff8162a400-ffffffff8162a4c5: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816583d0)
Location: drivers/xen/grant-table.c:1010
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff816583d0-ffffffff81658495: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gnttab_foreach_grant(struct page **pages, unsigned int nr_grefs, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816729d0)
Location: drivers/xen/grant-table.c:1010
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff816729d0-ffffffff81672a95: gnttab_foreach_grant (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
