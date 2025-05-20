# Function: <code>__aafs_ns_mkdir</code>

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
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813dc100)
Location: security/apparmor/apparmorfs.c:1844
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff813dc100-ffffffff813dc4e3: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81402b80)
Location: security/apparmor/apparmorfs.c:1908
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81402b80-ffffffff81402f59: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81433b20)
Location: security/apparmor/apparmorfs.c:1905
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81433b20-ffffffff81433f06: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81450820)
Location: security/apparmor/apparmorfs.c:1903
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81450820-ffffffff81450c06: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147e2f0)
Location: security/apparmor/apparmorfs.c:1908
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff8147e2f0-ffffffff8147e6c6: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81497ff0)
Location: security/apparmor/apparmorfs.c:1876
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81497ff0-ffffffff814983c6: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814f02c0)
Location: security/apparmor/apparmorfs.c:1995
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff814f02c0-ffffffff814f03ef: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8150d740)
Location: security/apparmor/apparmorfs.c:1995
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff8150d740-ffffffff8150d86f: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81514150)
Location: security/apparmor/apparmorfs.c:1996
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81514150-ffffffff8151427e: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81571fe0)
Location: security/apparmor/apparmorfs.c:1996
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81571fe0-ffffffff8157210e: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8160ee30)
Location: security/apparmor/apparmorfs.c:2016
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff8160ee30-ffffffff8160ef73: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816c1100)
Location: security/apparmor/apparmorfs.c:2205
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff816c1100-ffffffff816c1243: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f9c10)
Location: security/apparmor/apparmorfs.c:2253
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff816f9c10-ffffffff816f9d53: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff817369b0)
Location: security/apparmor/apparmorfs.c:2251
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff817369b0-ffffffff81736af3: __aafs_ns_mkdir (STB_GLOBAL)
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
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff80001058db18)
Location: security/apparmor/apparmorfs.c:1876
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffff80001058db18-ffff80001058dee4: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c073e9d0)
Location: security/apparmor/apparmorfs.c:1876
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
c073e9d0-c073edc0: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c000000000700430)
Location: security/apparmor/apparmorfs.c:1876
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
c000000000700430-c0000000007008e0: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003dbc56)
Location: security/apparmor/apparmorfs.c:1876
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffe0003dbc56-ffffffe0003dbf98: __aafs_ns_mkdir (STB_GLOBAL)
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
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814905d0)
Location: security/apparmor/apparmorfs.c:1876
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff814905d0-ffffffff814909a6: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81480ff0)
Location: security/apparmor/apparmorfs.c:1876
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81480ff0-ffffffff814813c6: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148c670)
Location: security/apparmor/apparmorfs.c:1876
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff8148c670-ffffffff8148ca46: __aafs_ns_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns *ns, struct dentry *parent, const char *name, struct dentry *dent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a44b0)
Location: security/apparmor/apparmorfs.c:1876
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff814a44b0-ffffffff814a4886: __aafs_ns_mkdir (STB_GLOBAL)
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
