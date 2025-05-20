# Function: <code>lookup_mountpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122b5a0)
Location: fs/namespace.c:730
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:__detach_mounts
```
**Symbols:**

```
ffffffff8122b5a0-ffffffff8122b606: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81253d10)
Location: fs/namespace.c:730
Inline: False
Direct callers:
  - fs/namespace.c:lock_mount
  - fs/namespace.c:__detach_mounts
```
**Symbols:**

```
ffffffff81253d10-ffffffff81253d71: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81266f60)
Location: fs/namespace.c:707
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff81266f60-ffffffff81266fc1: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812747b0)
Location: fs/namespace.c:708
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff812747b0-ffffffff81274819: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812970b0)
Location: fs/namespace.c:768
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff812970b0-ffffffff81297119: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bd2f0)
Location: fs/namespace.c:778
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff812bd2f0-ffffffff812bd359: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d2610)
Location: fs/namespace.c:690
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff812d2610-ffffffff812d2663: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ef660)
Location: fs/namespace.c:687
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff812ef660-ffffffff812ef6ab: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81301130)
Location: fs/namespace.c:687
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff81301130-ffffffff8130117b: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133a3a0)
Location: fs/namespace.c:703
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff8133a3a0-ffffffff8133a3eb: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81346090)
Location: fs/namespace.c:703
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff81346090-ffffffff813460db: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134c400)
Location: fs/namespace.c:717
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff8134c400-ffffffff8134c44b: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:719
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff8139ab60-ffffffff8139abc6: lookup_mountpoint (STB_LOCAL)
ffffffff81cc3ee7-ffffffff81cc3f03: lookup_mountpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:762
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff8141dbc0-ffffffff8141dc32: lookup_mountpoint (STB_LOCAL)
ffffffff81e76804-ffffffff81e76820: lookup_mountpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:873
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff814aa4d0-ffffffff814aa542: lookup_mountpoint (STB_LOCAL)
ffffffff82068c1a-ffffffff82068c36: lookup_mountpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:782
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff814df490-ffffffff814df502: lookup_mountpoint (STB_LOCAL)
ffffffff820e8558-ffffffff820e8574: lookup_mountpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:770
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff815121f0-ffffffff81512262: lookup_mountpoint (STB_LOCAL)
ffffffff821c52b2-ffffffff821c52ce: lookup_mountpoint.cold (STB_LOCAL)
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
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b39b0)
Location: fs/namespace.c:687
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffff8000103b39b0-ffff8000103b3a24: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0592564)
Location: fs/namespace.c:687
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
c0592564-c05925d4: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004af610)
Location: fs/namespace.c:687
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
c0000000004af610-c0000000004af688: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe0002770c8)
Location: fs/namespace.c:687
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffe0002770c8-ffffffe000277126: lookup_mountpoint (STB_LOCAL)
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
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9710)
Location: fs/namespace.c:687
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff812f9710-ffffffff812f975b: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ea330)
Location: fs/namespace.c:687
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff812ea330-ffffffff812ea37b: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f7500)
Location: fs/namespace.c:687
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff812f7500-ffffffff812f754b: lookup_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mountpoint *lookup_mountpoint(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81308740)
Location: fs/namespace.c:687
Inline: False
Direct callers:
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
```
**Symbols:**

```
ffffffff81308740-ffffffff8130878b: lookup_mountpoint (STB_LOCAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
