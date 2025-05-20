# Function: <code>follow_dotdot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int follow_dotdot(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81218cd0)
Location: fs/namei.c:1416
Inline: False
Direct callers:
  - fs/namei.c:walk_component
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81218cd0-ffffffff81218d96: follow_dotdot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812424c5)
Location: fs/namei.c:1447
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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812553ca)
Location: fs/namei.c:1443
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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812611d2)
Location: fs/namei.c:1455
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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81283902)
Location: fs/namei.c:1453
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
In fs/namei.c (0)
Location: fs/namei.c:1440
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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bd874)
Location: fs/namei.c:1481
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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dcd1d)
Location: fs/namei.c:1479
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (ffffffff812ee855)
Location: fs/namei.c:1474
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *follow_dotdot(struct nameidata *nd, struct inode **inodep, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81322610)
Location: fs/namei.c:1759
Inline: False
```
**Symbols:**

```
ffffffff81322610-ffffffff8132274d: follow_dotdot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *follow_dotdot(struct nameidata *nd, struct inode **inodep, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132dbb0)
Location: fs/namei.c:1755
Inline: False
```
**Symbols:**

```
ffffffff8132dbb0-ffffffff8132dce7: follow_dotdot (STB_LOCAL)
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
In fs/namei.c (ffffffff813340bb)
Location: fs/namei.c:1841
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
In fs/namei.c (ffffffff81381a0b)
Location: fs/namei.c:1869
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
In fs/namei.c (ffffffff8140572b)
Location: fs/namei.c:1915
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
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
In fs/namei.c (ffffffff8148fba1)
Location: fs/namei.c:1906
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
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
In fs/namei.c (ffffffff814c4ee6)
Location: fs/namei.c:1911
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
In fs/namei.c (ffffffff814f76c6)
Location: fs/namei.c:1918
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (0)
Location: fs/namei.c:1474
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (c057e5b8)
Location: fs/namei.c:1474
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (0)
Location: fs/namei.c:1474
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (ffffffe000265e90)
Location: fs/namei.c:1474
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (ffffffff812e6e35)
Location: fs/namei.c:1474
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (ffffffff812d7a75)
Location: fs/namei.c:1474
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (ffffffff812e4c45)
Location: fs/namei.c:1474
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (ffffffff812f5bc5)
Location: fs/namei.c:1474
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
</ul>
