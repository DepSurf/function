# Function: <code>fill_item_path</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff812e11c0)
Location: fs/configfs/symlink.c:57
Inline: True
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
In fs/configfs/symlink.c (ffffffff81305b19)
Location: fs/configfs/symlink.c:57
Inline: True
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
In fs/configfs/symlink.c (ffffffff81333b12)
Location: fs/configfs/symlink.c:57
Inline: True
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
In fs/configfs/symlink.c (ffffffff8134aeaa)
Location: fs/configfs/symlink.c:57
Inline: True
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
In fs/configfs/symlink.c (ffffffff81373824)
Location: fs/configfs/symlink.c:43
Inline: True
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
In fs/configfs/symlink.c (ffffffff8138bafb)
Location: fs/configfs/symlink.c:43
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fill_item_path(struct config_item *item, char *buffer, int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813d6cd0)
Location: fs/configfs/symlink.c:43
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_get_target_path
```
**Symbols:**

```
ffffffff813d6cd0-ffffffff813d6d39: fill_item_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fill_item_path(struct config_item *item, char *buffer, int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813e8970)
Location: fs/configfs/symlink.c:43
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_get_target_path
```
**Symbols:**

```
ffffffff813e8970-ffffffff813e89d9: fill_item_path (STB_LOCAL)
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
In fs/configfs/symlink.c (ffffffff813ef598)
Location: fs/configfs/symlink.c:41
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_get_target_path
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
In fs/configfs/symlink.c (ffffffff81441488)
Location: fs/configfs/symlink.c:41
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_get_target_path
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
In fs/configfs/symlink.c (ffffffff814bd063)
Location: fs/configfs/symlink.c:41
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_get_target_path
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fill_item_path(struct config_item *item, char *buffer, int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81554bb0)
Location: fs/configfs/symlink.c:41
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_get_target_path
```
**Symbols:**

```
ffffffff81554bb0-ffffffff81554c31: fill_item_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fill_item_path(struct config_item *item, char *buffer, int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff8158c930)
Location: fs/configfs/symlink.c:41
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_get_target_path
```
**Symbols:**

```
ffffffff8158c930-ffffffff8158c9b1: fill_item_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fill_item_path(struct config_item *item, char *buffer, int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff815c5640)
Location: fs/configfs/symlink.c:41
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_get_target_path
```
**Symbols:**

```
ffffffff815c5640-ffffffff815c56c1: fill_item_path (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffff80001045d16c)
Location: fs/configfs/symlink.c:43
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/symlink.c (c061df98)
Location: fs/configfs/symlink.c:43
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (c000000000578cdc)
Location: fs/configfs/symlink.c:43
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffe0002ed432)
Location: fs/configfs/symlink.c:43
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
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
In fs/configfs/symlink.c (ffffffff813840db)
Location: fs/configfs/symlink.c:43
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/symlink.c (ffffffff81374b6b)
Location: fs/configfs/symlink.c:43
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/symlink.c (ffffffff81381bab)
Location: fs/configfs/symlink.c:43
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/symlink.c (ffffffff813956dd)
Location: fs/configfs/symlink.c:43
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
