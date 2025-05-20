# Function: <code>__aa_fs_ns_rmdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __aa_fs_ns_rmdir(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81376760)
Location: security/apparmor/apparmorfs.c:692
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/policy_ns.c:destroy_ns
```
**Symbols:**

```
ffffffff81376760-ffffffff81376842: __aa_fs_ns_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __aa_fs_ns_rmdir(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813aed00)
Location: security/apparmor/apparmorfs.c:1119
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/policy_ns.c:destroy_ns
```
**Symbols:**

```
ffffffff813aed00-ffffffff813aef93: __aa_fs_ns_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __aa_fs_ns_rmdir(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813c5dd0)
Location: security/apparmor/apparmorfs.c:1215
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/policy_ns.c:destroy_ns
```
**Symbols:**

```
ffffffff813c5dd0-ffffffff813c60d5: __aa_fs_ns_rmdir (STB_GLOBAL)
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
