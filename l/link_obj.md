# Function: <code>link_obj</code>

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
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812df2d0)
Location: fs/configfs/dir.c:746
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff812df2d0-ffffffff812df317: link_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81303c40)
Location: fs/configfs/dir.c:746
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81303c40-ffffffff81303c87: link_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813317b0)
Location: fs/configfs/dir.c:746
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff813317b0-ffffffff813317f9: link_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81348ba0)
Location: fs/configfs/dir.c:746
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81348ba0-ffffffff81348be8: link_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81371100)
Location: fs/configfs/dir.c:765
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81371100-ffffffff8137114e: link_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81389580)
Location: fs/configfs/dir.c:760
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81389580-ffffffff813895ce: link_obj (STB_LOCAL)
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
In fs/configfs/dir.c (ffffffff813d64cf)
Location: fs/configfs/dir.c:760
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
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
In fs/configfs/dir.c (ffffffff813e819f)
Location: fs/configfs/dir.c:761
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
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
In fs/configfs/dir.c (ffffffff813eed02)
Location: fs/configfs/dir.c:759
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
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
In fs/configfs/dir.c (ffffffff81440c55)
Location: fs/configfs/dir.c:742
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
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
In fs/configfs/dir.c (ffffffff814bc7cb)
Location: fs/configfs/dir.c:742
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
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
In fs/configfs/dir.c (ffffffff8155431b)
Location: fs/configfs/dir.c:744
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
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
In fs/configfs/dir.c (ffffffff8158c0ab)
Location: fs/configfs/dir.c:744
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
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
In fs/configfs/dir.c (ffffffff815c4dbd)
Location: fs/configfs/dir.c:744
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
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
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff800010459b70)
Location: fs/configfs/dir.c:760
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffff800010459b70-ffff800010459bd0: link_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061bcb4)
Location: fs/configfs/dir.c:760
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
c061bcb4-c061bd10: link_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c000000000575560)
Location: fs/configfs/dir.c:760
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
c000000000575560-c000000000575624: link_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002ea89a)
Location: fs/configfs/dir.c:760
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffe0002ea89a-ffffffe0002ea8f6: link_obj (STB_LOCAL)
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
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81381b60)
Location: fs/configfs/dir.c:760
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81381b60-ffffffff81381bae: link_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813725f0)
Location: fs/configfs/dir.c:760
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff813725f0-ffffffff8137263e: link_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8137f630)
Location: fs/configfs/dir.c:760
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff8137f630-ffffffff8137f67e: link_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void link_obj(struct config_item *parent_item, struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813935d0)
Location: fs/configfs/dir.c:760
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff813935d0-ffffffff8139361e: link_obj (STB_LOCAL)
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
