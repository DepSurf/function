# Function: <code>xas_find_conflict</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17a80)
Location: lib/xarray.c:1206
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff81a17a80-ffffffff81a17c39: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a87730)
Location: lib/xarray.c:1225
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff81a87730-ffffffff81a878ef: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abe9d0)
Location: lib/xarray.c:1236
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff81abe9d0-ffffffff81abeb8f: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815f9ba0)
Location: lib/xarray.c:1238
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff815f9ba0-ffffffff815f9d52: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161e2a0)
Location: lib/xarray.c:1388
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff8161e2a0-ffffffff8161e452: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81601be0)
Location: lib/xarray.c:1389
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff81601be0-ffffffff81601d94: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81670120)
Location: lib/xarray.c:1389
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff81670120-ffffffff816702c5: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178b0d0)
Location: lib/xarray.c:1396
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff8178b0d0-ffffffff8178b29f: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff82048980)
Location: lib/xarray.c:1396
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff82048980-ffffffff82048b4f: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c7220)
Location: lib/xarray.c:1394
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff820c7220-ffffffff820c73df: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a1ba0)
Location: lib/xarray.c:1394
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff821a1ba0-ffffffff821a1d5f: xas_find_conflict (STB_GLOBAL)
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
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d99d30)
Location: lib/xarray.c:1236
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffff800010d99d30-ffff800010d99f10: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e96874)
Location: lib/xarray.c:1236
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
**Symbols:**

```
c0e96874-c0e96a54: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000edfdb0)
Location: lib/xarray.c:1236
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
c000000000edfdb0-c000000000ee005c: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c2916)
Location: lib/xarray.c:1236
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffe0008c2916-ffffffe0008c2a60: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5d820)
Location: lib/xarray.c:1236
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff81a5d820-ffffffff81a5d9df: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1a8f0)
Location: lib/xarray.c:1236
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff81a1a8f0-ffffffff81a1aaaf: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac9c10)
Location: lib/xarray.c:1236
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff81ac9c10-ffffffff81ac9dcf: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xas_find_conflict(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad6180)
Location: lib/xarray.c:1236
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - fs/dax.c:get_unlocked_entry
```
**Symbols:**

```
ffffffff81ad6180-ffffffff81ad633f: xas_find_conflict (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
