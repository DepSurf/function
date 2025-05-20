# Function: <code>create_default_group</code>

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
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (ffffffff812e0550)
Location: fs/configfs/dir.c:664
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff812e0550-ffffffff812e05df: create_default_group.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (ffffffff81304ed0)
Location: fs/configfs/dir.c:664
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff81304ed0-ffffffff81304f5f: create_default_group.isra.29 (STB_LOCAL)
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
In fs/configfs/dir.c (ffffffff81333050)
Location: fs/configfs/dir.c:664
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff81333050-ffffffff813330df: create_default_group.isra.33 (STB_LOCAL)
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
In fs/configfs/dir.c (ffffffff8134a440)
Location: fs/configfs/dir.c:664
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff8134a440-ffffffff8134a4cf: create_default_group.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (ffffffff81372c00)
Location: fs/configfs/dir.c:681
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff81372c00-ffffffff81372c97: create_default_group.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (ffffffff8138b000)
Location: fs/configfs/dir.c:676
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff8138b000-ffffffff8138b097: create_default_group.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int create_default_group(struct config_group *parent_group, struct config_group *group, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813d5fa0)
Location: fs/configfs/dir.c:676
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff813d5fa0-ffffffff813d6072: create_default_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int create_default_group(struct config_group *parent_group, struct config_group *group, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813e7c70)
Location: fs/configfs/dir.c:677
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff813e7c70-ffffffff813e7d42: create_default_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int create_default_group(struct config_group *parent_group, struct config_group *group, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813ef140)
Location: fs/configfs/dir.c:675
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff813ef140-ffffffff813ef1db: create_default_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int create_default_group(struct config_group *parent_group, struct config_group *group, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81441030)
Location: fs/configfs/dir.c:658
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff81441030-ffffffff814410cb: create_default_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int create_default_group(struct config_group *parent_group, struct config_group *group, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff814bcbb0)
Location: fs/configfs/dir.c:658
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff814bcbb0-ffffffff814bcc5e: create_default_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int create_default_group(struct config_group *parent_group, struct config_group *group, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81554720)
Location: fs/configfs/dir.c:660
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff81554720-ffffffff815547ce: create_default_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int create_default_group(struct config_group *parent_group, struct config_group *group, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8158c4a0)
Location: fs/configfs/dir.c:660
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff8158c4a0-ffffffff8158c54e: create_default_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int create_default_group(struct config_group *parent_group, struct config_group *group, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815c5190)
Location: fs/configfs/dir.c:660
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff815c5190-ffffffff815c5241: create_default_group (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (ffff80001045c098)
Location: fs/configfs/dir.c:676
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffff80001045c098-ffff80001045c15c: create_default_group.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int create_default_group(struct config_group *parent_group, struct config_group *group, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061d2c0)
Location: fs/configfs/dir.c:676
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
c061d2c0-c061d36c: create_default_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (c000000000577800)
Location: fs/configfs/dir.c:676
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
c000000000577800-c0000000005778f8: create_default_group.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002ec4b2)
Location: fs/configfs/dir.c:676
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffe0002ec4b2-ffffffe0002ec552: create_default_group.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (ffffffff813835e0)
Location: fs/configfs/dir.c:676
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff813835e0-ffffffff81383677: create_default_group.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (ffffffff81374070)
Location: fs/configfs/dir.c:676
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff81374070-ffffffff81374107: create_default_group.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (ffffffff813810b0)
Location: fs/configfs/dir.c:676
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff813810b0-ffffffff81381147: create_default_group.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (ffffffff81394b70)
Location: fs/configfs/dir.c:676
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_register_group
```
**Symbols:**

```
ffffffff81394b70-ffffffff81394c07: create_default_group.isra.0 (STB_LOCAL)
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
