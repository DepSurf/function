# Function: <code>aafs_remove_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aafs_remove_dir(struct aa_fs_entry *fs_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81f9916b)
Location: security/apparmor/apparmorfs.c:1177
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_remove_dir
  - security/apparmor/apparmorfs.c:aafs_create_dir
  - security/apparmor/apparmorfs.c:aa_destroy_aafs
```
**Symbols:**

```
ffffffff81f9916b-ffffffff81f991cd: aafs_remove_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aafs_remove_dir(struct aa_fs_entry *fs_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81fc3e37)
Location: security/apparmor/apparmorfs.c:1674
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_create_dir
  - security/apparmor/apparmorfs.c:aafs_remove_dir
  - security/apparmor/apparmorfs.c:aa_destroy_aafs
```
**Symbols:**

```
ffffffff81fc3e37-ffffffff81fc3e99: aafs_remove_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aafs_remove_dir(struct aa_fs_entry *fs_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8200082b)
Location: security/apparmor/apparmorfs.c:1791
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_create_dir
  - security/apparmor/apparmorfs.c:aafs_remove_dir
  - security/apparmor/apparmorfs.c:aa_destroy_aafs
```
**Symbols:**

```
ffffffff8200082b-ffffffff8200088d: aafs_remove_dir (STB_LOCAL)
```
</details>
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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
