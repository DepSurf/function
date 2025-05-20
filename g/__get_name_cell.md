# Function: <code>__get_name_cell</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff816a8520)
Location: drivers/md/dm-ioctl.c:111
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff816a8520-ffffffff816a85a4: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817089a0)
Location: drivers/md/dm-ioctl.c:111
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff817089a0-ffffffff81708a27: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8173a870)
Location: drivers/md/dm-ioctl.c:111
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff8173a870-ffffffff8173a8f7: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817541f0)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff817541f0-ffffffff81754278: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817c63a0)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff817c63a0-ffffffff817c6428: __get_name_cell (STB_LOCAL)
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
In drivers/md/dm-ioctl.c (ffffffff818109ff)
Location: drivers/md/dm-ioctl.c:112
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff8180fcd0-ffffffff8180fd58: __get_name_cell.part.9 (STB_LOCAL)
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
In drivers/md/dm-ioctl.c (ffffffff8183c9ff)
Location: drivers/md/dm-ioctl.c:112
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff8183bcd0-ffffffff8183bd58: __get_name_cell.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8187dc70)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8187dc70-ffffffff8187dcfa: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818afa50)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818afa50-ffffffff818afada: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8197fd90)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8197fd90-ffffffff8197fe1a: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81984180)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81984180-ffffffff8198420a: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8196a22d)
Location: drivers/md/dm-ioctl.c:82
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
Direct callers:
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81968530-ffffffff81968583: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81a126cd)
Location: drivers/md/dm-ioctl.c:83
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
Direct callers:
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81a10940-ffffffff81a10993: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81b7adcf)
Location: drivers/md/dm-ioctl.c:84
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
Direct callers:
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81b78f60-ffffffff81b78fb7: __get_name_cell (STB_LOCAL)
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
In drivers/md/dm-ioctl.c (ffffffff81d16ae0)
Location: drivers/md/dm-ioctl.c:84
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
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
In drivers/md/dm-ioctl.c (ffffffff81d7fd76)
Location: drivers/md/dm-ioctl.c:89
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
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
In drivers/md/dm-ioctl.c (ffffffff81e373c6)
Location: drivers/md/dm-ioctl.c:89
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
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
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffff800010b06988)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffff800010b06988-ffff800010b06a54: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c0be5508)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
c0be5508-c0be55b4: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c000000000bf76b0)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
c000000000bf76b0-c000000000bf7944: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffe0006f5630)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffe0006f5630-ffffffe0006f56ce: __get_name_cell (STB_LOCAL)
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
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818558d0)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818558d0-ffffffff8185595a: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8181cee0)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8181cee0-ffffffff8181cf6a: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818a4f00)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818a4f00-ffffffff818a4f8a: __get_name_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hash_cell *__get_name_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818c1140)
Location: drivers/md/dm-ioctl.c:112
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818c1140-ffffffff818c11ca: __get_name_cell (STB_LOCAL)
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
