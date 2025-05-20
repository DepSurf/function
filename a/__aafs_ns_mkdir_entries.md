# Function: <code>__aafs_ns_mkdir_entries</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813dc139)
Location: security/apparmor/apparmorfs.c:1785
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
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
Location: security/apparmor/apparmorfs.c:1849
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
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
Location: security/apparmor/apparmorfs.c:1846
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
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
Location: security/apparmor/apparmorfs.c:1844
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
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
Location: security/apparmor/apparmorfs.c:1849
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
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
Location: security/apparmor/apparmorfs.c:1817
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __aafs_ns_mkdir_entries(struct aa_ns *ns, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814ed0a0)
Location: security/apparmor/apparmorfs.c:1936
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
**Symbols:**

```
ffffffff814ed0a0-ffffffff814ed4b4: __aafs_ns_mkdir_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __aafs_ns_mkdir_entries(struct aa_ns *ns, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81509610)
Location: security/apparmor/apparmorfs.c:1936
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
**Symbols:**

```
ffffffff81509610-ffffffff81509a50: __aafs_ns_mkdir_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __aafs_ns_mkdir_entries(struct aa_ns *ns, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81510040)
Location: security/apparmor/apparmorfs.c:1937
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
**Symbols:**

```
ffffffff81510040-ffffffff81510470: __aafs_ns_mkdir_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __aafs_ns_mkdir_entries(struct aa_ns *ns, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8156dc40)
Location: security/apparmor/apparmorfs.c:1937
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
**Symbols:**

```
ffffffff8156dc40-ffffffff8156e070: __aafs_ns_mkdir_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __aafs_ns_mkdir_entries(struct aa_ns *ns, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8160b700)
Location: security/apparmor/apparmorfs.c:1957
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
**Symbols:**

```
ffffffff8160b700-ffffffff8160bb54: __aafs_ns_mkdir_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __aafs_ns_mkdir_entries(struct aa_ns *ns, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816bd620)
Location: security/apparmor/apparmorfs.c:2146
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
**Symbols:**

```
ffffffff816bd620-ffffffff816bda74: __aafs_ns_mkdir_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __aafs_ns_mkdir_entries(struct aa_ns *ns, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f60e0)
Location: security/apparmor/apparmorfs.c:2194
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
**Symbols:**

```
ffffffff816f60e0-ffffffff816f6534: __aafs_ns_mkdir_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __aafs_ns_mkdir_entries(struct aa_ns *ns, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81732e40)
Location: security/apparmor/apparmorfs.c:2192
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
**Symbols:**

```
ffffffff81732e40-ffffffff81733294: __aafs_ns_mkdir_entries (STB_LOCAL)
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
Location: security/apparmor/apparmorfs.c:1817
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
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
Location: security/apparmor/apparmorfs.c:1817
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
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
Location: security/apparmor/apparmorfs.c:1817
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
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
Location: security/apparmor/apparmorfs.c:1817
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
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
Location: security/apparmor/apparmorfs.c:1817
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
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
Location: security/apparmor/apparmorfs.c:1817
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
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
Location: security/apparmor/apparmorfs.c:1817
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
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
Location: security/apparmor/apparmorfs.c:1817
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
