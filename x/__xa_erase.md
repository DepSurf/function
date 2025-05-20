# Function: <code>__xa_erase</code>

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
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a18a80)
Location: lib/xarray.c:1305
Inline: False
Direct callers:
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff81a18a80-ffffffff81a18b13: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a88790)
Location: lib/xarray.c:1323
Inline: False
Direct callers:
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff81a88790-ffffffff81a88823: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abfa30)
Location: lib/xarray.c:1334
Inline: False
Direct callers:
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff81abfa30-ffffffff81abfac3: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fc6a5)
Location: lib/xarray.c:1336
Inline: True
Inline callers:
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff815fbd20-ffffffff815fbdb3: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816212c5)
Location: lib/xarray.c:1486
Inline: True
Inline callers:
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff816208c0-ffffffff81620953: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816044a5)
Location: lib/xarray.c:1487
Inline: True
Inline callers:
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff816040a0-ffffffff81604133: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81672d95)
Location: lib/xarray.c:1487
Inline: True
Inline callers:
  - lib/xarray.c:xa_erase
Direct callers:
  - drivers/vfio/vfio.c:vfio_uninit_group_dev
```
**Symbols:**

```
ffffffff81672910-ffffffff816729a3: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178d0e0)
Location: lib/xarray.c:1494
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_reparent_list_lrus
  - security/apparmor/secid.c:aa_free_secid
  - lib/xarray.c:xa_erase
  - drivers/vfio/vfio.c:vfio_uninit_group_dev
```
**Symbols:**

```
ffffffff8178d0e0-ffffffff8178d17b: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8204a700)
Location: lib/xarray.c:1494
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_reparent_list_lrus
  - security/apparmor/secid.c:aa_free_secid
  - net/core/devlink.c:__devlink_snapshot_id_decrement
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff8204a700-ffffffff8204a79b: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c9000)
Location: lib/xarray.c:1492
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_reparent_list_lrus
  - security/apparmor/secid.c:aa_free_secid
  - net/devlink/leftover.c:__devlink_snapshot_id_decrement
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff820c9000-ffffffff820c909b: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a3980)
Location: lib/xarray.c:1492
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_reparent_list_lrus
  - security/apparmor/secid.c:aa_free_secid
  - net/devlink/region.c:__devlink_snapshot_id_decrement
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff821a3980-ffffffff821a3a1b: __xa_erase (STB_GLOBAL)
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
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9ab88)
Location: lib/xarray.c:1334
Inline: False
Direct callers:
  - lib/xarray.c:xa_erase
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffff800010d9ab88-ffff800010d9ac24: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e97978)
Location: lib/xarray.c:1334
Inline: False
Direct callers:
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
c0e97978-c0e97a3c: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee1450)
Location: lib/xarray.c:1334
Inline: False
Direct callers:
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
c000000000ee1450-c000000000ee1528: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c30e6)
Location: lib/xarray.c:1334
Inline: False
Direct callers:
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffe0008c30e6-ffffffe0008c315c: __xa_erase (STB_GLOBAL)
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
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5e880)
Location: lib/xarray.c:1334
Inline: False
Direct callers:
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff81a5e880-ffffffff81a5e913: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1b950)
Location: lib/xarray.c:1334
Inline: False
Direct callers:
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff81a1b950-ffffffff81a1b9e3: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81acac70)
Location: lib/xarray.c:1334
Inline: False
Direct callers:
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff81acac70-ffffffff81acad03: __xa_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__xa_erase(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad7240)
Location: lib/xarray.c:1334
Inline: False
Direct callers:
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff81ad7240-ffffffff81ad72d3: __xa_erase (STB_GLOBAL)
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
