# Function: <code>free_tind_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff812cc9ef)
Location: fs/ext4/migrate.c:256
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff812fc54f)
Location: fs/ext4/migrate.c:256
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/migrate.c (ffffffff813124ff)
Location: fs/ext4/migrate.c:256
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/migrate.c (ffffffff81313fc9)
Location: fs/ext4/migrate.c:256
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/migrate.c (ffffffff81338789)
Location: fs/ext4/migrate.c:256
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/migrate.c (ffffffff81366d08)
Location: fs/ext4/migrate.c:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/migrate.c (ffffffff8137f174)
Location: fs/ext4/migrate.c:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/migrate.c (ffffffff813a85b7)
Location: fs/ext4/migrate.c:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/migrate.c (ffffffff813c144d)
Location: fs/ext4/migrate.c:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int free_tind_blocks(handle_t *handle, struct inode *inode, __le32 i_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff8140cf80)
Location: fs/ext4/migrate.c:220
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
**Symbols:**

```
ffffffff8140cf80-ffffffff8140d0ba: free_tind_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int free_tind_blocks(handle_t *handle, struct inode *inode, __le32 i_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff814203e0)
Location: fs/ext4/migrate.c:220
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
**Symbols:**

```
ffffffff814203e0-ffffffff8142051a: free_tind_blocks (STB_LOCAL)
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
In fs/ext4/migrate.c (ffffffff81426e44)
Location: fs/ext4/migrate.c:220
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
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
In fs/ext4/migrate.c (ffffffff8147aad4)
Location: fs/ext4/migrate.c:220
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
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
In fs/ext4/migrate.c (ffffffff814fced2)
Location: fs/ext4/migrate.c:220
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
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
In fs/ext4/migrate.c (ffffffff81597662)
Location: fs/ext4/migrate.c:219
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
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
In fs/ext4/migrate.c (ffffffff815ce08b)
Location: fs/ext4/migrate.c:219
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
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
In fs/ext4/migrate.c (ffffffff8160690b)
Location: fs/ext4/migrate.c:219
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
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
In fs/ext4/migrate.c (ffff800010498494)
Location: fs/ext4/migrate.c:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
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
In fs/ext4/migrate.c (c065a538)
Location: fs/ext4/migrate.c:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/migrate.c (c0000000005c2c24)
Location: fs/ext4/migrate.c:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/migrate.c (ffffffe00031c736)
Location: fs/ext4/migrate.c:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/migrate.c (ffffffff813b9a2d)
Location: fs/ext4/migrate.c:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/migrate.c (ffffffff813aa4bd)
Location: fs/ext4/migrate.c:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/migrate.c (ffffffff813b728d)
Location: fs/ext4/migrate.c:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/migrate.c (ffffffff813cbf9b)
Location: fs/ext4/migrate.c:249
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
