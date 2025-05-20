# Function: <code>item_path_length</code>

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
In fs/configfs/symlink.c (ffffffff812e111c)
Location: fs/configfs/symlink.c:46
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
In fs/configfs/symlink.c (ffffffff81305ab3)
Location: fs/configfs/symlink.c:46
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
In fs/configfs/symlink.c (0)
Location: fs/configfs/symlink.c:46
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
In fs/configfs/symlink.c (0)
Location: fs/configfs/symlink.c:46
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
In fs/configfs/symlink.c (0)
Location: fs/configfs/symlink.c:32
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
In fs/configfs/symlink.c (0)
Location: fs/configfs/symlink.c:32
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
int item_path_length(struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813d6c80)
Location: fs/configfs/symlink.c:32
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_get_target_path
```
**Symbols:**

```
ffffffff813d6c80-ffffffff813d6cc8: item_path_length (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int item_path_length(struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813e8920)
Location: fs/configfs/symlink.c:32
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_get_target_path
```
**Symbols:**

```
ffffffff813e8920-ffffffff813e8968: item_path_length (STB_LOCAL)
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
In fs/configfs/symlink.c (ffffffff813ef52c)
Location: fs/configfs/symlink.c:30
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
In fs/configfs/symlink.c (ffffffff8144141c)
Location: fs/configfs/symlink.c:30
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
In fs/configfs/symlink.c (ffffffff814bcffd)
Location: fs/configfs/symlink.c:30
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_get_target_path
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
In fs/configfs/symlink.c (ffffffff81554c9e)
Location: fs/configfs/symlink.c:30
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_get_target_path
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
In fs/configfs/symlink.c (ffffffff8158ca1e)
Location: fs/configfs/symlink.c:30
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_get_target_path
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
In fs/configfs/symlink.c (ffffffff815c572e)
Location: fs/configfs/symlink.c:30
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_get_target_path
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
In fs/configfs/symlink.c (0)
Location: fs/configfs/symlink.c:32
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
In fs/configfs/symlink.c (c061df10)
Location: fs/configfs/symlink.c:32
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
In fs/configfs/symlink.c (0)
Location: fs/configfs/symlink.c:32
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
In fs/configfs/symlink.c (ffffffe0002ed39a)
Location: fs/configfs/symlink.c:32
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
In fs/configfs/symlink.c (0)
Location: fs/configfs/symlink.c:32
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
In fs/configfs/symlink.c (0)
Location: fs/configfs/symlink.c:32
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
In fs/configfs/symlink.c (0)
Location: fs/configfs/symlink.c:32
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
In fs/configfs/symlink.c (0)
Location: fs/configfs/symlink.c:32
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
</ul>
