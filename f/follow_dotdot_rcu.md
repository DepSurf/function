# Function: <code>follow_dotdot_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81216730)
Location: fs/namei.c:1294
Inline: False
Direct callers:
  - fs/namei.c:walk_component
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81216730-ffffffff81216879: follow_dotdot_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123d650)
Location: fs/namei.c:1316
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8123d650-ffffffff8123d79e: follow_dotdot_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812503f0)
Location: fs/namei.c:1313
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812503f0-ffffffff8125053e: follow_dotdot_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125c630)
Location: fs/namei.c:1325
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8125c630-ffffffff8125c789: follow_dotdot_rcu (STB_LOCAL)
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
In fs/namei.c (ffffffff81283889)
Location: fs/namei.c:1323
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (ffffffff812aa824)
Location: fs/namei.c:1310
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bb9e0)
Location: fs/namei.c:1351
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812bb9e0-ffffffff812bbb3f: follow_dotdot_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d7d00)
Location: fs/namei.c:1349
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812d7d00-ffffffff812d7e42: follow_dotdot_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9880)
Location: fs/namei.c:1344
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812e9880-ffffffff812e99bd: follow_dotdot_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *follow_dotdot_rcu(struct nameidata *nd, struct inode **inodep, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81321a40)
Location: fs/namei.c:1719
Inline: False
```
**Symbols:**

```
ffffffff81321a40-ffffffff81321b64: follow_dotdot_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *follow_dotdot_rcu(struct nameidata *nd, struct inode **inodep, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132cfe0)
Location: fs/namei.c:1715
Inline: False
```
**Symbols:**

```
ffffffff8132cfe0-ffffffff8132d126: follow_dotdot_rcu (STB_LOCAL)
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
In fs/namei.c (ffffffff8133415d)
Location: fs/namei.c:1801
Inline: True
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
In fs/namei.c (ffffffff81381aad)
Location: fs/namei.c:1829
Inline: True
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
In fs/namei.c (ffffffff814056c6)
Location: fs/namei.c:1875
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148a3a0)
Location: fs/namei.c:1866
Inline: False
Direct callers:
  - fs/namei.c:handle_dots
```
**Symbols:**

```
ffffffff8148a3a0-ffffffff8148a514: follow_dotdot_rcu (STB_LOCAL)
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
In fs/namei.c (ffffffff814c4e26)
Location: fs/namei.c:1871
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
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
In fs/namei.c (ffffffff814f7606)
Location: fs/namei.c:1878
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
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
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010392cf8)
Location: fs/namei.c:1344
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffff800010392cf8-ffff800010392eec: follow_dotdot_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057944c)
Location: fs/namei.c:1344
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
c057944c-c0579680: follow_dotdot_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048c0c0)
Location: fs/namei.c:1344
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
c00000000048c0c0-c00000000048c378: follow_dotdot_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000261dfc)
Location: fs/namei.c:1344
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffe000261dfc-ffffffe000261f82: follow_dotdot_rcu (STB_LOCAL)
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
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e1e60)
Location: fs/namei.c:1344
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812e1e60-ffffffff812e1f9d: follow_dotdot_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d2aa0)
Location: fs/namei.c:1344
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812d2aa0-ffffffff812d2bdd: follow_dotdot_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dfc70)
Location: fs/namei.c:1344
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812dfc70-ffffffff812dfdad: follow_dotdot_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int follow_dotdot_rcu(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1330)
Location: fs/namei.c:1344
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812f1330-ffffffff812f146d: follow_dotdot_rcu (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode **inodep</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int *seqp</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct dentry *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
