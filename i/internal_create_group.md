# Function: <code>internal_create_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8128d590)
Location: fs/sysfs/group.c:107
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff8128d590-ffffffff8128d893: internal_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812bac10)
Location: fs/sysfs/group.c:107
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff812bac10-ffffffff812baefa: internal_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812d0340)
Location: fs/sysfs/group.c:107
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_groups
```
**Symbols:**

```
ffffffff812d0340-ffffffff812d062a: internal_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812dda00)
Location: fs/sysfs/group.c:107
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
```
**Symbols:**

```
ffffffff812dda00-ffffffff812ddcb0: internal_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81302330)
Location: fs/sysfs/group.c:107
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
```
**Symbols:**

```
ffffffff81302330-ffffffff813025e1: internal_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81330160)
Location: fs/sysfs/group.c:107
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
```
**Symbols:**

```
ffffffff81330160-ffffffff8133048d: internal_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (0)
Location: fs/sysfs/group.c:107
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
```
**Symbols:**

```
ffffffff81347500-ffffffff81347860: internal_create_group (STB_LOCAL)
ffffffff81347aff-ffffffff81347b1b: internal_create_group.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (0)
Location: fs/sysfs/group.c:107
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff8136f900-ffffffff8136fc5c: internal_create_group (STB_LOCAL)
ffffffff8136ff3d-ffffffff8136ff72: internal_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (0)
Location: fs/sysfs/group.c:108
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff81387c60-ffffffff81387fcc: internal_create_group (STB_LOCAL)
ffffffff813884fd-ffffffff8138851a: internal_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (0)
Location: fs/sysfs/group.c:108
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff813d2990-ffffffff813d2b76: internal_create_group (STB_LOCAL)
ffffffff813d323f-ffffffff813d325d: internal_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (0)
Location: fs/sysfs/group.c:108
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff813e46f0-ffffffff813e48d6: internal_create_group (STB_LOCAL)
ffffffff81bec175-ffffffff81bec193: internal_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (0)
Location: fs/sysfs/group.c:108
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff813eb2f0-ffffffff813eb4d6: internal_create_group (STB_LOCAL)
ffffffff81bde1d3-ffffffff81bde1f1: internal_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (0)
Location: fs/sysfs/group.c:108
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff8143d080-ffffffff8143d266: internal_create_group (STB_LOCAL)
ffffffff81cc86d9-ffffffff81cc86f7: internal_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (0)
Location: fs/sysfs/group.c:107
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:internal_create_groups
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff814b8870-ffffffff814b8a64: internal_create_group (STB_LOCAL)
ffffffff81e7b432-ffffffff81e7b44a: internal_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8154fec0)
Location: fs/sysfs/group.c:107
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:internal_create_groups
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff8154fec0-ffffffff815500cc: internal_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81587b90)
Location: fs/sysfs/group.c:107
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:internal_create_groups
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff81587b90-ffffffff81587dca: internal_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815c0750)
Location: fs/sysfs/group.c:107
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:internal_create_groups
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff815c0750-ffffffff815c098a: internal_create_group (STB_LOCAL)
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
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffff800010457e10)
Location: fs/sysfs/group.c:108
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffff800010457e10-ffff800010458194: internal_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c0619948)
Location: fs/sysfs/group.c:108
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
c0619948-c0619d64: internal_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c000000000572620)
Location: fs/sysfs/group.c:108
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
c000000000572620-c000000000572b00: internal_create_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffe0002e9072)
Location: fs/sysfs/group.c:108
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffe0002e9072-ffffffe0002e9320: internal_create_group (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (0)
Location: fs/sysfs/group.c:108
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff81380240-ffffffff813805ac: internal_create_group (STB_LOCAL)
ffffffff81380add-ffffffff81380afa: internal_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (0)
Location: fs/sysfs/group.c:108
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff81370cd0-ffffffff8137103c: internal_create_group (STB_LOCAL)
ffffffff8137156d-ffffffff8137158a: internal_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (0)
Location: fs/sysfs/group.c:108
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff8137dd10-ffffffff8137e07c: internal_create_group (STB_LOCAL)
ffffffff8137e5ad-ffffffff8137e5ca: internal_create_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int internal_create_group(struct kobject *kobj, int update, const struct attribute_group *grp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/sysfs/group.c (0)
Location: fs/sysfs/group.c:108
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_update_group
  - fs/sysfs/group.c:sysfs_create_group
```
**Symbols:**

```
ffffffff81391910-ffffffff81391c7c: internal_create_group (STB_LOCAL)
ffffffff813920b6-ffffffff813920d3: internal_create_group.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
