# Function: <code>shrink_lock_dentry</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b665a)
Location: fs/dcache.c:1016
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dentry_list
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
In fs/dcache.c (ffffffff812cb80a)
Location: fs/dcache.c:1029
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dentry_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812e8bf7)
Location: fs/dcache.c:1055
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff812e81d0-ffffffff812e82bd: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812fa797)
Location: fs/dcache.c:1055
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff812f9d60-ffffffff812f9e4d: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff81333827)
Location: fs/dcache.c:1076
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff81332700-ffffffff813327ed: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff8133f193)
Location: fs/dcache.c:1083
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff8133e8d0-ffffffff8133e9bd: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff81345613)
Location: fs/dcache.c:1111
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff81344cc0-ffffffff81344dad: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff81393223)
Location: fs/dcache.c:1111
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff813927b0-ffffffff8139289d: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool shrink_lock_dentry(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81411220)
Location: fs/dcache.c:1136
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff81411220-ffffffff8141132e: shrink_lock_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool shrink_lock_dentry(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149bde0)
Location: fs/dcache.c:1136
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff8149bde0-ffffffff8149beee: shrink_lock_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool shrink_lock_dentry(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d1020)
Location: fs/dcache.c:1136
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff814d1020-ffffffff814d112c: shrink_lock_dentry (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffff8000103a989c)
Location: fs/dcache.c:1055
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffff8000103a8f10-ffff8000103a91e0: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (c058aa08)
Location: fs/dcache.c:1055
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
c0587aa4-c0587bf4: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (c0000000004a43e8)
Location: fs/dcache.c:1055
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
c00000000049fbd0-c00000000049fe5c: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffe00026f728)
Location: fs/dcache.c:1055
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffe00026eb90-ffffffe00026ed6c: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812f2d77)
Location: fs/dcache.c:1055
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff812f2340-ffffffff812f242d: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812e39a7)
Location: fs/dcache.c:1055
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff812e2f70-ffffffff812e305d: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812f0b87)
Location: fs/dcache.c:1055
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff812f0150-ffffffff812f023d: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff81301d3e)
Location: fs/dcache.c:1055
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
Direct callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff812ff400-ffffffff812ff4e3: shrink_lock_dentry.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
