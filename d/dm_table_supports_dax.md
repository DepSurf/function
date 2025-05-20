# Function: <code>dm_table_supports_dax</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81706871)
Location: drivers/md/dm-table.c:856
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In drivers/md/dm-table.c (ffffffff8173870c)
Location: drivers/md/dm-table.c:850
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In drivers/md/dm-table.c (ffffffff81751c5d)
Location: drivers/md/dm-table.c:890
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In drivers/md/dm-table.c (ffffffff817c3e49)
Location: drivers/md/dm-table.c:892
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180b800)
Location: drivers/md/dm-table.c:891
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff8180b800-ffffffff8180b8aa: dm_table_supports_dax.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818377c0)
Location: drivers/md/dm-table.c:889
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff818377c0-ffffffff8183786a: dm_table_supports_dax.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8187ae50)
Location: drivers/md/dm-table.c:900
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff8187ae50-ffffffff8187aee0: dm_table_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818acc40)
Location: drivers/md/dm-table.c:898
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff818acc40-ffffffff818accd0: dm_table_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197d090)
Location: drivers/md/dm-table.c:885
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_determine_type
```
**Symbols:**

```
ffffffff8197d090-ffffffff8197d120: dm_table_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff819816c0)
Location: drivers/md/dm-table.c:843
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_determine_type
```
**Symbols:**

```
ffffffff819816c0-ffffffff81981750: dm_table_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81965900)
Location: drivers/md/dm-table.c:829
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_determine_type
```
**Symbols:**

```
ffffffff81965900-ffffffff81965990: dm_table_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0d890)
Location: drivers/md/dm-table.c:824
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_determine_type
```
**Symbols:**

```
ffffffff81a0d890-ffffffff81a0d920: dm_table_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b74410)
Location: drivers/md/dm-table.c:827
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_determine_type
```
**Symbols:**

```
ffffffff81b74410-ffffffff81b744b4: dm_table_supports_dax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d112b0)
Location: drivers/md/dm-table.c:826
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_determine_type
```
**Symbols:**

```
ffffffff81d112b0-ffffffff81d11354: dm_table_supports_dax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7a740)
Location: drivers/md/dm-table.c:821
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_determine_type
```
**Symbols:**

```
ffffffff81d7a740-ffffffff81d7a7e3: dm_table_supports_dax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e318e0)
Location: drivers/md/dm-table.c:842
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_determine_type
```
**Symbols:**

```
ffffffff81e318e0-ffffffff81e31988: dm_table_supports_dax (STB_LOCAL)
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
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b03660)
Location: drivers/md/dm-table.c:898
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffff800010b03660-ffff800010b03708: dm_table_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be274c)
Location: drivers/md/dm-table.c:898
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
c0be274c-c0be27d8: dm_table_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf2c50)
Location: drivers/md/dm-table.c:898
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
c000000000bf2c50-c000000000bf2d4c: dm_table_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f2bce)
Location: drivers/md/dm-table.c:898
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffe0006f2bce-ffffffe0006f2c42: dm_table_supports_dax (STB_GLOBAL)
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
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81852ac0)
Location: drivers/md/dm-table.c:898
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81852ac0-ffffffff81852b50: dm_table_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8181a0d0)
Location: drivers/md/dm-table.c:898
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff8181a0d0-ffffffff8181a160: dm_table_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a20f0)
Location: drivers/md/dm-table.c:898
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff818a20f0-ffffffff818a2180: dm_table_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool dm_table_supports_dax(struct dm_table *t, iterate_devices_callout_fn iterate_fn, int *blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818be330)
Location: drivers/md/dm-table.c:898
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff818be330-ffffffff818be3c0: dm_table_supports_dax (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *blocksize</code>
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
