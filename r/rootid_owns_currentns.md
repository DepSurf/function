# Function: <code>rootid_owns_currentns</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8139a830)
Location: security/commoncap.c:335
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
ffffffff8139a830-ffffffff8139a890: rootid_owns_currentns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813bfec0)
Location: security/commoncap.c:329
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
ffffffff813bfec0-ffffffff813bff20: rootid_owns_currentns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813f0e20)
Location: security/commoncap.c:329
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
ffffffff813f0e20-ffffffff813f0e80: rootid_owns_currentns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8140c120)
Location: security/commoncap.c:327
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
ffffffff8140c120-ffffffff8140c180: rootid_owns_currentns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814392a0)
Location: security/commoncap.c:322
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
ffffffff814392a0-ffffffff81439300: rootid_owns_currentns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81453110)
Location: security/commoncap.c:322
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
ffffffff81453110-ffffffff81453170: rootid_owns_currentns (STB_LOCAL)
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
In security/commoncap.c (ffffffff814a67a9)
Location: security/commoncap.c:322
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
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
In security/commoncap.c (ffffffff814c3d59)
Location: security/commoncap.c:322
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
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
In security/commoncap.c (ffffffff814ca202)
Location: security/commoncap.c:330
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
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
In security/commoncap.c (ffffffff81522ea2)
Location: security/commoncap.c:330
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
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
In security/commoncap.c (ffffffff815b6c32)
Location: security/commoncap.c:331
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
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
In security/commoncap.c (ffffffff81661dfa)
Location: security/commoncap.c:332
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
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
In security/commoncap.c (ffffffff8169a3d3)
Location: security/commoncap.c:332
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
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
In security/commoncap.c (ffffffff816d6b13)
Location: security/commoncap.c:332
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
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
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffff80001053e068)
Location: security/commoncap.c:322
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
ffff80001053e068-ffff80001053e0e8: rootid_owns_currentns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c06f4020)
Location: security/commoncap.c:322
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
c06f4020-c06f4094: rootid_owns_currentns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c00000000068e330)
Location: security/commoncap.c:322
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
c00000000068e330-c00000000068e3e8: rootid_owns_currentns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffe00039b91e)
Location: security/commoncap.c:322
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
ffffffe00039b91e-ffffffe00039b988: rootid_owns_currentns (STB_LOCAL)
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
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8144b6f0)
Location: security/commoncap.c:322
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
ffffffff8144b6f0-ffffffff8144b750: rootid_owns_currentns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8143c140)
Location: security/commoncap.c:322
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
ffffffff8143c140-ffffffff8143c1a0: rootid_owns_currentns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81447790)
Location: security/commoncap.c:322
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
ffffffff81447790-ffffffff814477f0: rootid_owns_currentns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rootid_owns_currentns(kuid_t kroot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8145eae0)
Location: security/commoncap.c:322
Inline: False
Direct callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
**Symbols:**

```
ffffffff8145eae0-ffffffff8145eb40: rootid_owns_currentns (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
