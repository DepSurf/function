# Function: <code>create_files</code>

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
In fs/sysfs/group.c (ffffffff8128d618)
Location: fs/sysfs/group.c:35
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (ffffffff812bac98)
Location: fs/sysfs/group.c:35
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (ffffffff812d03c8)
Location: fs/sysfs/group.c:35
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (ffffffff812dda81)
Location: fs/sysfs/group.c:35
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (ffffffff813023b1)
Location: fs/sysfs/group.c:35
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (ffffffff81330221)
Location: fs/sysfs/group.c:33
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (ffffffff813475af)
Location: fs/sysfs/group.c:33
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (ffffffff8136f9af)
Location: fs/sysfs/group.c:33
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (ffffffff81387d0f)
Location: fs/sysfs/group.c:34
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int create_files(struct kernfs_node *parent, struct kobject *kobj, kuid_t uid, kgid_t gid, const struct attribute_group *grp, int update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813d2790)
Location: fs/sysfs/group.c:34
Inline: False
Direct callers:
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813d2790-ffffffff813d2984: create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int create_files(struct kernfs_node *parent, struct kobject *kobj, kuid_t uid, kgid_t gid, const struct attribute_group *grp, int update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813e44f0)
Location: fs/sysfs/group.c:34
Inline: False
Direct callers:
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813e44f0-ffffffff813e46e4: create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int create_files(struct kernfs_node *parent, struct kobject *kobj, kuid_t uid, kgid_t gid, const struct attribute_group *grp, int update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813eb0f0)
Location: fs/sysfs/group.c:34
Inline: False
Direct callers:
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813eb0f0-ffffffff813eb2e4: create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int create_files(struct kernfs_node *parent, struct kobject *kobj, kuid_t uid, kgid_t gid, const struct attribute_group *grp, int update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8143ce80)
Location: fs/sysfs/group.c:34
Inline: False
Direct callers:
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8143ce80-ffffffff8143d074: create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int create_files(struct kernfs_node *parent, struct kobject *kobj, kuid_t uid, kgid_t gid, const struct attribute_group *grp, int update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff814b8660)
Location: fs/sysfs/group.c:34
Inline: False
Direct callers:
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff814b8660-ffffffff814b8861: create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int create_files(struct kernfs_node *parent, struct kobject *kobj, kuid_t uid, kgid_t gid, const struct attribute_group *grp, int update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8154fca0)
Location: fs/sysfs/group.c:34
Inline: False
Direct callers:
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8154fca0-ffffffff8154fea1: create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int create_files(struct kernfs_node *parent, struct kobject *kobj, kuid_t uid, kgid_t gid, const struct attribute_group *grp, int update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81587970)
Location: fs/sysfs/group.c:34
Inline: False
Direct callers:
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81587970-ffffffff81587b74: create_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int create_files(struct kernfs_node *parent, struct kobject *kobj, kuid_t uid, kgid_t gid, const struct attribute_group *grp, int update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815c0530)
Location: fs/sysfs/group.c:34
Inline: False
Direct callers:
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff815c0530-ffffffff815c0734: create_files (STB_LOCAL)
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
In fs/sysfs/group.c (ffff800010457ea8)
Location: fs/sysfs/group.c:34
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (c0619a00)
Location: fs/sysfs/group.c:34
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (c0000000005726f8)
Location: fs/sysfs/group.c:34
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (ffffffe0002e90f0)
Location: fs/sysfs/group.c:34
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (ffffffff813802ef)
Location: fs/sysfs/group.c:34
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (ffffffff81370d7f)
Location: fs/sysfs/group.c:34
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (ffffffff8137ddbf)
Location: fs/sysfs/group.c:34
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
In fs/sysfs/group.c (ffffffff813919bf)
Location: fs/sysfs/group.c:34
Inline: True
Inline callers:
  - fs/sysfs/group.c:internal_create_group
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
