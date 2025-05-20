# Function: <code>configfs_is_root</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff812e1960)
Location: fs/configfs/mount.c:56
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
```
**Symbols:**

```
ffffffff812e1960-ffffffff812e1977: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff813062b0)
Location: fs/configfs/mount.c:56
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
```
**Symbols:**

```
ffffffff813062b0-ffffffff813062c7: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff813342b0)
Location: fs/configfs/mount.c:56
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
```
**Symbols:**

```
ffffffff813342b0-ffffffff813342c7: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff8134b620)
Location: fs/configfs/mount.c:56
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
```
**Symbols:**

```
ffffffff8134b620-ffffffff8134b637: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81374010)
Location: fs/configfs/mount.c:43
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
```
**Symbols:**

```
ffffffff81374010-ffffffff81374027: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff8138c290)
Location: fs/configfs/mount.c:52
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff8138c290-ffffffff8138c2a7: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff813d75e0)
Location: fs/configfs/mount.c:52
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:link_group
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:fill_item_path
  - fs/configfs/symlink.c:item_path_length
```
**Symbols:**

```
ffffffff813d75e0-ffffffff813d75f7: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff813e9280)
Location: fs/configfs/mount.c:52
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:link_group
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:fill_item_path
  - fs/configfs/symlink.c:item_path_length
```
**Symbols:**

```
ffffffff813e9280-ffffffff813e9297: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff813efdf0)
Location: fs/configfs/mount.c:50
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:link_group
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:configfs_get_target_path
```
**Symbols:**

```
ffffffff813efdf0-ffffffff813efe07: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81441ce0)
Location: fs/configfs/mount.c:50
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:link_group
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:configfs_get_target_path
```
**Symbols:**

```
ffffffff81441ce0-ffffffff81441cf7: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff814bd8e0)
Location: fs/configfs/mount.c:50
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:link_group
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:configfs_get_target_path
```
**Symbols:**

```
ffffffff814bd8e0-ffffffff814bd8fd: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff815555b0)
Location: fs/configfs/mount.c:50
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:link_group
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:fill_item_path
```
**Symbols:**

```
ffffffff815555b0-ffffffff815555cd: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff8158d350)
Location: fs/configfs/mount.c:50
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:link_group
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:fill_item_path
```
**Symbols:**

```
ffffffff8158d350-ffffffff8158d36d: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff815c6090)
Location: fs/configfs/mount.c:50
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:link_group
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:configfs_get_target_path
  - fs/configfs/symlink.c:fill_item_path
```
**Symbols:**

```
ffffffff815c6090-ffffffff815c60ad: configfs_is_root (STB_GLOBAL)
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
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffff80001045dca8)
Location: fs/configfs/mount.c:52
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffff80001045dca8-ffff80001045dce0: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (c061e848)
Location: fs/configfs/mount.c:52
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
c061e848-c061e874: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (c0000000005798d0)
Location: fs/configfs/mount.c:52
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
c0000000005798d0-c0000000005798f8: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffe0002edae4)
Location: fs/configfs/mount.c:52
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffe0002edae4-ffffffe0002edb14: configfs_is_root (STB_GLOBAL)
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
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81384870)
Location: fs/configfs/mount.c:52
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81384870-ffffffff81384887: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81375300)
Location: fs/configfs/mount.c:52
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81375300-ffffffff81375317: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81382340)
Location: fs/configfs/mount.c:52
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81382340-ffffffff81382357: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int configfs_is_root(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/mount.c (ffffffff81395e60)
Location: fs/configfs/mount.c:52
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81395e60-ffffffff81395e77: configfs_is_root (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
