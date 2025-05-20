# Function: <code>__aa_fs_profile_rmdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __aa_fs_profile_rmdir(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813762a0)
Location: security/apparmor/apparmorfs.c:546
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/policy.c:__remove_profile
```
**Symbols:**

```
ffffffff813762a0-ffffffff81376365: __aa_fs_profile_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __aa_fs_profile_rmdir(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813ae770)
Location: security/apparmor/apparmorfs.c:868
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/apparmor/policy.c:__remove_profile
```
**Symbols:**

```
ffffffff813ae770-ffffffff813ae85a: __aa_fs_profile_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __aa_fs_profile_rmdir(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813c5840)
Location: security/apparmor/apparmorfs.c:964
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/apparmor/policy.c:__remove_profile
```
**Symbols:**

```
ffffffff813c5840-ffffffff813c592e: __aa_fs_profile_rmdir (STB_GLOBAL)
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
