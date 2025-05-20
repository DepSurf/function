# Function: <code>internal_change_owner</code>

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
int internal_change_owner(struct kernfs_node *kn, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813869f0)
Location: fs/sysfs/file.c:562
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
```
**Symbols:**

```
ffffffff813869f0-ffffffff81386a4a: internal_change_owner (STB_LOCAL)
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
In fs/sysfs/file.c (ffffffff813d1a19)
Location: fs/sysfs/file.c:563
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
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
In fs/sysfs/file.c (ffffffff813e3779)
Location: fs/sysfs/file.c:564
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
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
In fs/sysfs/file.c (ffffffff813ea399)
Location: fs/sysfs/file.c:575
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
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
In fs/sysfs/file.c (ffffffff8143c119)
Location: fs/sysfs/file.c:575
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
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
In fs/sysfs/file.c (ffffffff814b75e3)
Location: fs/sysfs/file.c:585
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
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
In fs/sysfs/file.c (ffffffff8154ea33)
Location: fs/sysfs/file.c:585
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
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
In fs/sysfs/file.c (ffffffff81586703)
Location: fs/sysfs/file.c:585
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
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
In fs/sysfs/file.c (ffffffff815bf263)
Location: fs/sysfs/file.c:598
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
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
int internal_change_owner(struct kernfs_node *kn, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffff8000104565c8)
Location: fs/sysfs/file.c:562
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
```
**Symbols:**

```
ffff8000104565c8-ffff80001045664c: internal_change_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node *kn, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c0618678)
Location: fs/sysfs/file.c:562
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
```
**Symbols:**

```
c0618678-c0618700: internal_change_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node *kn, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c000000000570440)
Location: fs/sysfs/file.c:562
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
```
**Symbols:**

```
c000000000570440-c0000000005704ec: internal_change_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node *kn, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffe0002e7dac)
Location: fs/sysfs/file.c:562
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
```
**Symbols:**

```
ffffffe0002e7dac-ffffffe0002e7e18: internal_change_owner (STB_LOCAL)
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
int internal_change_owner(struct kernfs_node *kn, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137efd0)
Location: fs/sysfs/file.c:562
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
```
**Symbols:**

```
ffffffff8137efd0-ffffffff8137f02a: internal_change_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node *kn, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8136fa60)
Location: fs/sysfs/file.c:562
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
```
**Symbols:**

```
ffffffff8136fa60-ffffffff8136faba: internal_change_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node *kn, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137caa0)
Location: fs/sysfs/file.c:562
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
```
**Symbols:**

```
ffffffff8137caa0-ffffffff8137cafa: internal_change_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node *kn, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81390580)
Location: fs/sysfs/file.c:562
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_change_owner
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
```
**Symbols:**

```
ffffffff81390580-ffffffff813905da: internal_change_owner (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
