# Function: <code>sysfs_groups_change_owner</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81388390)
Location: fs/sysfs/group.c:554
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff81388390-ffffffff81388406: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813d2fb0)
Location: fs/sysfs/group.c:560
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff813d2fb0-ffffffff813d3026: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813e4d10)
Location: fs/sysfs/group.c:560
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff813e4d10-ffffffff813e4d86: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813eb910)
Location: fs/sysfs/group.c:560
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff813eb910-ffffffff813eb986: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8143d6a0)
Location: fs/sysfs/group.c:560
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff8143d6a0-ffffffff8143d716: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff814b90f0)
Location: fs/sysfs/group.c:559
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff814b90f0-ffffffff814b918a: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81550810)
Location: fs/sysfs/group.c:559
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff81550810-ffffffff815508aa: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81588500)
Location: fs/sysfs/group.c:563
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff81588500-ffffffff8158859a: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815c10c0)
Location: fs/sysfs/group.c:563
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff815c10c0-ffffffff815c115a: sysfs_groups_change_owner (STB_GLOBAL)
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
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffff800010458600)
Location: fs/sysfs/group.c:554
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffff800010458600-ffff80001045869c: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c061a2a0)
Location: fs/sysfs/group.c:554
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
c061a2a0-c061a318: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c000000000573080)
Location: fs/sysfs/group.c:554
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
c000000000573080-c000000000573180: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffe0002e96d2)
Location: fs/sysfs/group.c:554
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffe0002e96d2-ffffffe0002e9742: sysfs_groups_change_owner (STB_GLOBAL)
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
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81380970)
Location: fs/sysfs/group.c:554
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff81380970-ffffffff813809e6: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81371400)
Location: fs/sysfs/group.c:554
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff81371400-ffffffff81371476: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8137e440)
Location: fs/sysfs/group.c:554
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff8137e440-ffffffff8137e4b6: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysfs_groups_change_owner(struct kobject *kobj, const struct attribute_group **groups, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81392040)
Location: fs/sysfs/group.c:554
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
  - drivers/base/core.c:device_change_owner
```
**Symbols:**

```
ffffffff81392040-ffffffff813920b6: sysfs_groups_change_owner (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
