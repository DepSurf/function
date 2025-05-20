# Function: <code>ext4_ext_swap_inode_data</code>

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
In fs/ext4/migrate.c (ffffffff812cc9b8)
Location: fs/ext4/migrate.c:316
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
In fs/ext4/migrate.c (ffffffff812fc307)
Location: fs/ext4/migrate.c:316
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
In fs/ext4/migrate.c (ffffffff813122b7)
Location: fs/ext4/migrate.c:316
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
In fs/ext4/migrate.c (ffffffff81313d6f)
Location: fs/ext4/migrate.c:316
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
In fs/ext4/migrate.c (ffffffff8133852f)
Location: fs/ext4/migrate.c:316
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
In fs/ext4/migrate.c (ffffffff81366acc)
Location: fs/ext4/migrate.c:309
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
In fs/ext4/migrate.c (ffffffff8137ef1c)
Location: fs/ext4/migrate.c:309
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
In fs/ext4/migrate.c (ffffffff813a835b)
Location: fs/ext4/migrate.c:309
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
In fs/ext4/migrate.c (ffffffff813c120c)
Location: fs/ext4/migrate.c:309
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
int ext4_ext_swap_inode_data(handle_t *handle, struct inode *inode, struct inode *tmp_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff8140d0c0)
Location: fs/ext4/migrate.c:287
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff8140d0c0-ffffffff8140d345: ext4_ext_swap_inode_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_swap_inode_data(handle_t *handle, struct inode *inode, struct inode *tmp_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff81420520)
Location: fs/ext4/migrate.c:287
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff81420520-ffffffff814207a5: ext4_ext_swap_inode_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_swap_inode_data(handle_t *handle, struct inode *inode, struct inode *tmp_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff81426bf0)
Location: fs/ext4/migrate.c:287
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff81426bf0-ffffffff81426f5e: ext4_ext_swap_inode_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ext_swap_inode_data(handle_t *handle, struct inode *inode, struct inode *tmp_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff8147a880)
Location: fs/ext4/migrate.c:287
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff8147a880-ffffffff8147abee: ext4_ext_swap_inode_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ext_swap_inode_data(handle_t *handle, struct inode *inode, struct inode *tmp_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff814fcc50)
Location: fs/ext4/migrate.c:287
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff814fcc50-ffffffff814fcff3: ext4_ext_swap_inode_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ext_swap_inode_data(handle_t *handle, struct inode *inode, struct inode *tmp_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff815973e0)
Location: fs/ext4/migrate.c:286
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff815973e0-ffffffff81597783: ext4_ext_swap_inode_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ext_swap_inode_data(handle_t *handle, struct inode *inode, struct inode *tmp_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff815cde20)
Location: fs/ext4/migrate.c:286
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff815cde20-ffffffff815ce1a3: ext4_ext_swap_inode_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ext_swap_inode_data(handle_t *handle, struct inode *inode, struct inode *tmp_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffffffff816066a0)
Location: fs/ext4/migrate.c:286
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff816066a0-ffffffff81606a23: ext4_ext_swap_inode_data (STB_LOCAL)
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
int ext4_ext_swap_inode_data(handle_t *handle, struct inode *inode, struct inode *tmp_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/migrate.c (ffff8000104982c0)
Location: fs/ext4/migrate.c:309
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffff8000104982c0-ffff8000104985f4: ext4_ext_swap_inode_data (STB_LOCAL)
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
In fs/ext4/migrate.c (c065a2dc)
Location: fs/ext4/migrate.c:309
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
In fs/ext4/migrate.c (c0000000005c29d8)
Location: fs/ext4/migrate.c:309
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
In fs/ext4/migrate.c (ffffffe00031c63a)
Location: fs/ext4/migrate.c:309
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
In fs/ext4/migrate.c (ffffffff813b97ec)
Location: fs/ext4/migrate.c:309
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
In fs/ext4/migrate.c (ffffffff813aa27c)
Location: fs/ext4/migrate.c:309
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
In fs/ext4/migrate.c (ffffffff813b704c)
Location: fs/ext4/migrate.c:309
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
In fs/ext4/migrate.c (ffffffff813cbd5c)
Location: fs/ext4/migrate.c:309
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
</ul>
