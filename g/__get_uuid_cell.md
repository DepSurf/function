# Function: <code>__get_uuid_cell</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff816a8490)
Location: drivers/md/dm-ioctl.c:125
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff816a8490-ffffffff816a851d: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81708900)
Location: drivers/md/dm-ioctl.c:125
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff81708900-ffffffff81708991: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8173a7d0)
Location: drivers/md/dm-ioctl.c:125
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff8173a7d0-ffffffff8173a861: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81754150)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff81754150-ffffffff817541e1: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817c6300)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff817c6300-ffffffff817c6391: __get_uuid_cell (STB_LOCAL)
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
In drivers/md/dm-ioctl.c (ffffffff818109ee)
Location: drivers/md/dm-ioctl.c:126
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff8180fc30-ffffffff8180fcc1: __get_uuid_cell.part.8 (STB_LOCAL)
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
In drivers/md/dm-ioctl.c (ffffffff8183c9ee)
Location: drivers/md/dm-ioctl.c:126
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff8183bc30-ffffffff8183bcc1: __get_uuid_cell.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8187dbd0)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff8187dbd0-ffffffff8187dc63: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818af9b0)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff818af9b0-ffffffff818afa43: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8197fcf0)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff8197fcf0-ffffffff8197fd83: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff819840e0)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff819840e0-ffffffff81984173: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff819684d0)
Location: drivers/md/dm-ioctl.c:99
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff819684d0-ffffffff8196852b: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81a108e0)
Location: drivers/md/dm-ioctl.c:100
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff81a108e0-ffffffff81a1093b: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81b78f00)
Location: drivers/md/dm-ioctl.c:101
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff81b78f00-ffffffff81b78f5e: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d165b0)
Location: drivers/md/dm-ioctl.c:101
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff81d165b0-ffffffff81d1660e: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d7f740)
Location: drivers/md/dm-ioctl.c:108
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff81d7f740-ffffffff81d7f79e: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81e36d60)
Location: drivers/md/dm-ioctl.c:108
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff81e36d60-ffffffff81e36dbe: __get_uuid_cell (STB_LOCAL)
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
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffff800010b068b8)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffff800010b068b8-ffff800010b06984: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c0be5450)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
c0be5450-c0be5508: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c000000000bf73f0)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
c000000000bf73f0-c000000000bf76a4: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffe0006f558a)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffe0006f558a-ffffffe0006f5630: __get_uuid_cell (STB_LOCAL)
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
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81855830)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff81855830-ffffffff818558c3: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8181ce40)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff8181ce40-ffffffff8181ced3: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818a4e60)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff818a4e60-ffffffff818a4ef3: __get_uuid_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hash_cell *__get_uuid_cell(const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818c10a0)
Location: drivers/md/dm-ioctl.c:126
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
**Symbols:**

```
ffffffff818c10a0-ffffffff818c1133: __get_uuid_cell (STB_LOCAL)
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
