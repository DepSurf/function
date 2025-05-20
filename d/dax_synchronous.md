# Function: <code>dax_synchronous</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81385108)
Location: include/linux/dax.h:50
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff8187a0be)
Location: include/linux/dax.h:50
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff8139dba8)
Location: include/linux/dax.h:50
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff818abe9e)
Location: include/linux/dax.h:50
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813e9818)
Location: include/linux/dax.h:52
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
```
```
In drivers/md/dm-table.c (ffffffff8197c2ee)
Location: include/linux/dax.h:52
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813fb918)
Location: include/linux/dax.h:52
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
```
```
In drivers/md/dm-table.c (ffffffff8198094e)
Location: include/linux/dax.h:52
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_dax_synchronous_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81401c1a)
Location: include/linux/dax.h:52
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
```
```
In drivers/md/dm-table.c (ffffffff81964b5e)
Location: include/linux/dax.h:52
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_dax_synchronous_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff8145438a)
Location: include/linux/dax.h:51
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_mmap
```
```
In drivers/md/dm-table.c (ffffffff81a0cafe)
Location: include/linux/dax.h:51
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_dax_synchronous_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e8db0)
Location: drivers/dax/super.c:238
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_mmap
  - drivers/md/dm-table.c:device_not_dax_synchronous_capable
```
**Symbols:**

```
ffffffff819e8db0-ffffffff819e8dcf: dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65410)
Location: drivers/dax/super.c:283
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_mmap
  - drivers/md/dm-table.c:device_not_dax_synchronous_capable
```
**Symbols:**

```
ffffffff81b65410-ffffffff81b6542f: dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb8a10)
Location: drivers/dax/super.c:286
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_mmap
  - drivers/md/dm-table.c:device_not_dax_synchronous_capable
```
**Symbols:**

```
ffffffff81bb8a10-ffffffff81bb8a2f: dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d070)
Location: drivers/dax/super.c:286
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_mmap
  - drivers/md/dm-table.c:device_not_dax_synchronous_capable
```
**Symbols:**

```
ffffffff81c0d070-ffffffff81c0d08f: dax_synchronous (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffff8000104710cc)
Location: include/linux/dax.h:50
Inline: True
```
```
In drivers/md/dm-table.c (ffff800010b027ec)
Location: include/linux/dax.h:50
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_dax_synchronous
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
In drivers/md/dm-table.c (c0be1dc4)
Location: include/linux/dax.h:50
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (c000000000591970)
Location: include/linux/dax.h:50
Inline: True
```
```
In drivers/md/dm-table.c (c000000000bf19a8)
Location: include/linux/dax.h:50
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffe0002fd452)
Location: include/linux/dax.h:50
Inline: True
```
```
In drivers/md/dm-table.c (ffffffe0006f1fd4)
Location: include/linux/dax.h:50
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81396188)
Location: include/linux/dax.h:50
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff81851d1e)
Location: include/linux/dax.h:50
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81386c18)
Location: include/linux/dax.h:50
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff8181932e)
Location: include/linux/dax.h:50
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81393ae8)
Location: include/linux/dax.h:50
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff818a134e)
Location: include/linux/dax.h:50
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813a7b78)
Location: include/linux/dax.h:50
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff818bd58e)
Location: include/linux/dax.h:50
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
