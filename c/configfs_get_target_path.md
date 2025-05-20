# Function: <code>configfs_get_target_path</code>

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
In fs/configfs/symlink.c (ffffffff812e10e1)
Location: fs/configfs/symlink.c:234
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
In fs/configfs/symlink.c (ffffffff81305a78)
Location: fs/configfs/symlink.c:234
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
In fs/configfs/symlink.c (ffffffff81333a78)
Location: fs/configfs/symlink.c:234
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
In fs/configfs/symlink.c (ffffffff8134ae10)
Location: fs/configfs/symlink.c:234
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
In fs/configfs/symlink.c (ffffffff81373790)
Location: fs/configfs/symlink.c:220
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
Location: fs/configfs/symlink.c:58
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
int configfs_get_target_path(struct config_item *item, struct config_item *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813d6d40)
Location: fs/configfs/symlink.c:58
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff813d6d40-ffffffff813d6e31: configfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int configfs_get_target_path(struct config_item *item, struct config_item *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813e89e0)
Location: fs/configfs/symlink.c:58
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff813e89e0-ffffffff813e8ad1: configfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int configfs_get_target_path(struct config_item *item, struct config_item *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813ef4e0)
Location: fs/configfs/symlink.c:56
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff813ef4e0-ffffffff813ef650: configfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int configfs_get_target_path(struct config_item *item, struct config_item *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff814413d0)
Location: fs/configfs/symlink.c:56
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff814413d0-ffffffff8144153d: configfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int configfs_get_target_path(struct config_item *item, struct config_item *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff814bcfb0)
Location: fs/configfs/symlink.c:56
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff814bcfb0-ffffffff814bd126: configfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int configfs_get_target_path(struct config_item *item, struct config_item *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81554c50)
Location: fs/configfs/symlink.c:56
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81554c50-ffffffff81554d76: configfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int configfs_get_target_path(struct config_item *item, struct config_item *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff8158c9d0)
Location: fs/configfs/symlink.c:56
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff8158c9d0-ffffffff8158cb19: configfs_get_target_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int configfs_get_target_path(struct config_item *item, struct config_item *target, char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff815c56e0)
Location: fs/configfs/symlink.c:56
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff815c56e0-ffffffff815c5829: configfs_get_target_path (STB_LOCAL)
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
In fs/configfs/symlink.c (ffff80001045d0d0)
Location: fs/configfs/symlink.c:58
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
In fs/configfs/symlink.c (c061ded4)
Location: fs/configfs/symlink.c:58
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
In fs/configfs/symlink.c (c000000000578be4)
Location: fs/configfs/symlink.c:58
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
In fs/configfs/symlink.c (ffffffe0002ed376)
Location: fs/configfs/symlink.c:58
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
Location: fs/configfs/symlink.c:58
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
Location: fs/configfs/symlink.c:58
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
Location: fs/configfs/symlink.c:58
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
In fs/configfs/symlink.c (ffffffff81395641)
Location: fs/configfs/symlink.c:58
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
