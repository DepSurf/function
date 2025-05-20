# Function: <code>configfs_do_depend_item</code>

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
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812df0c0)
Location: fs/configfs/dir.c:1064
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
ffffffff812df0c0-ffffffff812df110: configfs_do_depend_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81303a30)
Location: fs/configfs/dir.c:1064
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
ffffffff81303a30-ffffffff81303a80: configfs_do_depend_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81331a70)
Location: fs/configfs/dir.c:1064
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
ffffffff81331a70-ffffffff81331ac0: configfs_do_depend_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81348f20)
Location: fs/configfs/dir.c:1064
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
ffffffff81348f20-ffffffff81348f70: configfs_do_depend_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813713d0)
Location: fs/configfs/dir.c:1085
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
ffffffff813713d0-ffffffff81371422: configfs_do_depend_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81389820)
Location: fs/configfs/dir.c:1080
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
ffffffff81389820-ffffffff81389872: configfs_do_depend_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813d4861)
Location: fs/configfs/dir.c:1080
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813e6581)
Location: fs/configfs/dir.c:1081
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
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
In fs/configfs/dir.c (ffffffff813ed261)
Location: fs/configfs/dir.c:1079
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
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
In fs/configfs/dir.c (ffffffff8143f161)
Location: fs/configfs/dir.c:1062
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
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
In fs/configfs/dir.c (ffffffff814ba710)
Location: fs/configfs/dir.c:1062
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
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
In fs/configfs/dir.c (ffffffff81551fb0)
Location: fs/configfs/dir.c:1064
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
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
In fs/configfs/dir.c (ffffffff81589cf0)
Location: fs/configfs/dir.c:1064
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
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
In fs/configfs/dir.c (ffffffff815c2916)
Location: fs/configfs/dir.c:1064
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
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
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff80001045a1a8)
Location: fs/configfs/dir.c:1080
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
ffff80001045a1a8-ffff80001045a258: configfs_do_depend_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061ba78)
Location: fs/configfs/dir.c:1080
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
c061ba78-c061bae8: configfs_do_depend_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c000000000575020)
Location: fs/configfs/dir.c:1080
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
c000000000575020-c000000000575110: configfs_do_depend_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002eac52)
Location: fs/configfs/dir.c:1080
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
ffffffe0002eac52-ffffffe0002eace4: configfs_do_depend_item (STB_LOCAL)
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
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81381e00)
Location: fs/configfs/dir.c:1080
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
ffffffff81381e00-ffffffff81381e52: configfs_do_depend_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81372890)
Location: fs/configfs/dir.c:1080
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
ffffffff81372890-ffffffff813728e2: configfs_do_depend_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8137f8d0)
Location: fs/configfs/dir.c:1080
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
ffffffff8137f8d0-ffffffff8137f922: configfs_do_depend_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int configfs_do_depend_item(struct dentry *subsys_dentry, struct config_item *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81393320)
Location: fs/configfs/dir.c:1080
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
**Symbols:**

```
ffffffff81393320-ffffffff81393370: configfs_do_depend_item (STB_LOCAL)
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
