# Function: <code>__aa_fs_ns_mkdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __aa_fs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81376850)
Location: security/apparmor/apparmorfs.c:721
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/policy_ns.c:aa_prepare_ns
```
**Symbols:**

```
ffffffff81376850-ffffffff81376a1f: __aa_fs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __aa_fs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813aefa0)
Location: security/apparmor/apparmorfs.c:1217
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff813aefa0-ffffffff813af4d4: __aa_fs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __aa_fs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813c60e0)
Location: security/apparmor/apparmorfs.c:1323
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff813c60e0-ffffffff813c6655: __aa_fs_ns_mkdir (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dentry *dent</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
