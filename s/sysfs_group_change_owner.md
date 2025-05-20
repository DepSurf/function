# Function: <code>sysfs_group_change_owner</code>

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
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813881c0)
Location: fs/sysfs/group.c:511
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff813881c0-ffffffff81388381: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813d2dd0)
Location: fs/sysfs/group.c:517
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:queue_change_owner
  - net/core/net-sysfs.c:queue_change_owner
```
**Symbols:**

```
ffffffff813d2dd0-ffffffff813d2fa1: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813e4b30)
Location: fs/sysfs/group.c:517
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:queue_change_owner
  - net/core/net-sysfs.c:queue_change_owner
```
**Symbols:**

```
ffffffff813e4b30-ffffffff813e4d01: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813eb730)
Location: fs/sysfs/group.c:517
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff813eb730-ffffffff813eb901: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8143d4c0)
Location: fs/sysfs/group.c:517
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff8143d4c0-ffffffff8143d691: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff814b8f10)
Location: fs/sysfs/group.c:516
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff814b8f10-ffffffff814b90ea: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81550620)
Location: fs/sysfs/group.c:516
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff81550620-ffffffff815507fa: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81588310)
Location: fs/sysfs/group.c:520
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff81588310-ffffffff815884ea: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815c0ed0)
Location: fs/sysfs/group.c:520
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff815c0ed0-ffffffff815c10aa: sysfs_group_change_owner (STB_GLOBAL)
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
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffff800010458460)
Location: fs/sysfs/group.c:511
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffff800010458460-ffff8000104585fc: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c061a0e0)
Location: fs/sysfs/group.c:511
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
c061a0e0-c061a2a0: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c000000000572e30)
Location: fs/sysfs/group.c:511
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
c000000000572e30-c000000000573078: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffe0002e958a)
Location: fs/sysfs/group.c:511
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffe0002e958a-ffffffe0002e96d2: sysfs_group_change_owner (STB_GLOBAL)
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
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813807a0)
Location: fs/sysfs/group.c:511
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff813807a0-ffffffff81380961: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81371230)
Location: fs/sysfs/group.c:511
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff81371230-ffffffff813713f1: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8137e270)
Location: fs/sysfs/group.c:511
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff8137e270-ffffffff8137e431: sysfs_group_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysfs_group_change_owner(struct kobject *kobj, const struct attribute_group *grp, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81391e70)
Location: fs/sysfs/group.c:511
Inline: False
Direct callers:
  - fs/sysfs/group.c:sysfs_groups_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff81391e70-ffffffff81392031: sysfs_group_change_owner (STB_GLOBAL)
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
