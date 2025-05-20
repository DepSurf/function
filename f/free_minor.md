# Function: <code>free_minor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_minor(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a1060)
Location: drivers/md/dm.c:2170
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff816a1060-ffffffff816a1097: free_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_minor(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817023d0)
Location: drivers/md/dm.c:1332
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff817023d0-ffffffff81702407: free_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_minor(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817342c0)
Location: drivers/md/dm.c:1387
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff817342c0-ffffffff817342f7: free_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_minor(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174d6a0)
Location: drivers/md/dm.c:1580
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8174d6a0-ffffffff8174d6da: free_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_minor(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bf890)
Location: drivers/md/dm.c:1571
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff817bf890-ffffffff817bf8ca: free_minor (STB_LOCAL)
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
In drivers/md/dm.c (ffffffff81809b6c)
Location: drivers/md/dm.c:1743
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:free_dev
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
In drivers/md/dm.c (ffffffff81835bf7)
Location: drivers/md/dm.c:1795
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:free_dev
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
In drivers/md/dm.c (ffffffff81877ac9)
Location: drivers/md/dm.c:1827
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff818a9a49)
Location: drivers/md/dm.c:1828
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff81979caa)
Location: drivers/md/dm.c:1832
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff8197e5b5)
Location: drivers/md/dm.c:1721
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff81962405)
Location: drivers/md/dm.c:1725
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff81a09772)
Location: drivers/md/dm.c:1607
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff81b717e6)
Location: drivers/md/dm.c:1813
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff81d0e627)
Location: drivers/md/dm.c:1880
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff81d77c31)
Location: drivers/md/dm.c:1924
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff81e2ee61)
Location: drivers/md/dm.c:1932
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
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
void free_minor(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afdc00)
Location: drivers/md/dm.c:1828
Inline: False
Direct callers:
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffff800010afdc00-ffff800010afdc98: free_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_minor(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdd11c)
Location: drivers/md/dm.c:1828
Inline: False
Direct callers:
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c0bdd11c-c0bdd170: free_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_minor(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000beb300)
Location: drivers/md/dm.c:1828
Inline: False
Direct callers:
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c000000000beb300-c000000000beb3c8: free_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_minor(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006eef82)
Location: drivers/md/dm.c:1828
Inline: False
Direct callers:
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffe0006eef82-ffffffe0006ef008: free_minor (STB_LOCAL)
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
In drivers/md/dm.c (ffffffff8184f8c9)
Location: drivers/md/dm.c:1828
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff81816ed9)
Location: drivers/md/dm.c:1828
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff8189eef9)
Location: drivers/md/dm.c:1828
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff818ba6c9)
Location: drivers/md/dm.c:1828
Inline: True
Inline callers:
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
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
</ul>
<b>Arch</b>
<ul>
</ul>
