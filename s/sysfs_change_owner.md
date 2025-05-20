# Function: <code>sysfs_change_owner</code>

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
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81386c30)
Location: fs/sysfs/file.c:668
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff81386c30-ffffffff81386cba: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813d19c0)
Location: fs/sysfs/file.c:669
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:queue_change_owner
  - net/core/net-sysfs.c:queue_change_owner
  - net/core/net-sysfs.c:queue_change_owner
```
**Symbols:**

```
ffffffff813d19c0-ffffffff813d1a9a: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813e3720)
Location: fs/sysfs/file.c:670
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:queue_change_owner
  - net/core/net-sysfs.c:queue_change_owner
  - net/core/net-sysfs.c:queue_change_owner
```
**Symbols:**

```
ffffffff813e3720-ffffffff813e37fa: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813ea340)
Location: fs/sysfs/file.c:681
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff813ea340-ffffffff813ea41a: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8143c0c0)
Location: fs/sysfs/file.c:681
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff8143c0c0-ffffffff8143c19a: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff814b75b0)
Location: fs/sysfs/file.c:691
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff814b75b0-ffffffff814b7677: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8154ea00)
Location: fs/sysfs/file.c:691
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff8154ea00-ffffffff8154eac7: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815866d0)
Location: fs/sysfs/file.c:691
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff815866d0-ffffffff81586797: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815bf230)
Location: fs/sysfs/file.c:704
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff815bf230-ffffffff815bf2f7: sysfs_change_owner (STB_GLOBAL)
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
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffff8000104568c8)
Location: fs/sysfs/file.c:668
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffff8000104568c8-ffff80001045698c: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c06188f8)
Location: fs/sysfs/file.c:668
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
c06188f8-c0618998: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c000000000570850)
Location: fs/sysfs/file.c:668
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
c000000000570850-c0000000005709b8: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffe0002e804a)
Location: fs/sysfs/file.c:668
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffe0002e804a-ffffffe0002e80d6: sysfs_change_owner (STB_GLOBAL)
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
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137f210)
Location: fs/sysfs/file.c:668
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff8137f210-ffffffff8137f29a: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8136fca0)
Location: fs/sysfs/file.c:668
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff8136fca0-ffffffff8136fd2a: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137cce0)
Location: fs/sysfs/file.c:668
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff8137cce0-ffffffff8137cd6a: sysfs_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysfs_change_owner(struct kobject *kobj, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813907c0)
Location: fs/sysfs/file.c:668
Inline: False
Direct callers:
  - drivers/base/core.c:device_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff813907c0-ffffffff8139084a: sysfs_change_owner (STB_GLOBAL)
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
