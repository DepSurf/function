# Function: <code>aafs_create_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aafs_create_dir(struct aa_fs_entry *fs_dir, struct dentry *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81f991cd)
Location: security/apparmor/apparmorfs.c:1131
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_create_dir
```
**Symbols:**

```
ffffffff81f991cd-ffffffff81f9926b: aafs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aafs_create_dir(struct aa_fs_entry *fs_dir, struct dentry *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81fc3e99)
Location: security/apparmor/apparmorfs.c:1628
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_create_dir
```
**Symbols:**

```
ffffffff81fc3e99-ffffffff81fc3f37: aafs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aafs_create_dir(struct aa_fs_entry *fs_dir, struct dentry *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8200088d)
Location: security/apparmor/apparmorfs.c:1745
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_create_dir
```
**Symbols:**

```
ffffffff8200088d-ffffffff8200092b: aafs_create_dir (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff813dc139)
Location: security/apparmor/apparmorfs.c:305
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff81402bb9)
Location: security/apparmor/apparmorfs.c:305
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff81433b5e)
Location: security/apparmor/apparmorfs.c:302
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff8145085e)
Location: security/apparmor/apparmorfs.c:302
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff8147e32e)
Location: security/apparmor/apparmorfs.c:307
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff8149802e)
Location: security/apparmor/apparmorfs.c:307
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff814f03b6)
Location: security/apparmor/apparmorfs.c:337
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff8150d836)
Location: security/apparmor/apparmorfs.c:337
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff8151424d)
Location: security/apparmor/apparmorfs.c:337
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff815720dd)
Location: security/apparmor/apparmorfs.c:337
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff8160ef42)
Location: security/apparmor/apparmorfs.c:340
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff816c1212)
Location: security/apparmor/apparmorfs.c:341
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff816f9d22)
Location: security/apparmor/apparmorfs.c:342
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff81736ac2)
Location: security/apparmor/apparmorfs.c:342
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffff80001058db58)
Location: security/apparmor/apparmorfs.c:307
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (c073ea10)
Location: security/apparmor/apparmorfs.c:307
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (c000000000700494)
Location: security/apparmor/apparmorfs.c:307
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffe0003dbc8e)
Location: security/apparmor/apparmorfs.c:307
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff8149060e)
Location: security/apparmor/apparmorfs.c:307
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff8148102e)
Location: security/apparmor/apparmorfs.c:307
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff8148c6ae)
Location: security/apparmor/apparmorfs.c:307
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
In security/apparmor/apparmorfs.c (ffffffff814a44ee)
Location: security/apparmor/apparmorfs.c:307
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
</ul>
