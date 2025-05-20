# Function: <code>ctl_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ctl_ioctl(uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff816a9da0)
Location: drivers/md/dm-ioctl.c:1793
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff816a9da0-ffffffff816aa26f: ctl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ctl_ioctl(uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8170a1f0)
Location: drivers/md/dm-ioctl.c:1797
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff8170a1f0-ffffffff8170a6da: ctl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ctl_ioctl(uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8173c0c0)
Location: drivers/md/dm-ioctl.c:1797
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff8173c0c0-ffffffff8173c5aa: ctl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81755980)
Location: drivers/md/dm-ioctl.c:1812
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff81755980-ffffffff81755eb2: ctl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817c7c20)
Location: drivers/md/dm-ioctl.c:1820
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff817c7c20-ffffffff817c8187: ctl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1821
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff8180f7d0-ffffffff8180fbe3: ctl_ioctl (STB_LOCAL)
ffffffff81811766-ffffffff81811866: ctl_ioctl.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1815
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff8183b7b0-ffffffff8183bbed: ctl_ioctl (STB_LOCAL)
ffffffff8183d766-ffffffff8183d82f: ctl_ioctl.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1815
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff8187f380-ffffffff8187f80a: ctl_ioctl (STB_LOCAL)
ffffffff818805f1-ffffffff81880705: ctl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1841
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff818b1200-ffffffff818b16c7: ctl_ioctl (STB_LOCAL)
ffffffff818b24b1-ffffffff818b25c5: ctl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1841
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff819812e0-ffffffff81981586: ctl_ioctl (STB_LOCAL)
ffffffff81982acc-ffffffff81982bac: ctl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1842
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff81985900-ffffffff81985ba6: ctl_ioctl (STB_LOCAL)
ffffffff81c2840a-ffffffff81c284ea: ctl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1919
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff81969240-ffffffff819694ee: ctl_ioctl (STB_LOCAL)
ffffffff81c1a452-ffffffff81c1a54e: ctl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1934
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff81a11460-ffffffff81a1175f: ctl_ioctl (STB_LOCAL)
ffffffff81d2a1ff-ffffffff81d2a2fb: ctl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1945
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff81b79b60-ffffffff81b79ebe: ctl_ioctl (STB_LOCAL)
ffffffff81ef644f-ffffffff81ef6513: ctl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d17ff0)
Location: drivers/md/dm-ioctl.c:1952
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff81d17ff0-ffffffff81d1840c: ctl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d812d0)
Location: drivers/md/dm-ioctl.c:2022
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff81d812d0-ffffffff81d816d9: ctl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81e38940)
Location: drivers/md/dm-ioctl.c:2028
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff81e38940-ffffffff81e38d49: ctl_ioctl (STB_LOCAL)
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
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffff800010b09138)
Location: drivers/md/dm-ioctl.c:1841
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffff800010b09138-ffff800010b099e4: ctl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c0be7950)
Location: drivers/md/dm-ioctl.c:1841
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_ctl_ioctl
```
**Symbols:**

```
c0be7950-c0be7ff8: ctl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c000000000bfac70)
Location: drivers/md/dm-ioctl.c:1841
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
c000000000bfac70-c000000000bfb308: ctl_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffe0006f7816)
Location: drivers/md/dm-ioctl.c:1841
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_ctl_ioctl
```
**Symbols:**

```
ffffffe0006f7816-ffffffe0006f7bac: ctl_ioctl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1841
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff81857080-ffffffff81857547: ctl_ioctl (STB_LOCAL)
ffffffff81858331-ffffffff81858445: ctl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1841
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff8181e690-ffffffff8181eb57: ctl_ioctl (STB_LOCAL)
ffffffff8181f941-ffffffff8181fa55: ctl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1841
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff818a66b0-ffffffff818a6b77: ctl_ioctl (STB_LOCAL)
ffffffff818a7961-ffffffff818a7a75: ctl_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ctl_ioctl(struct file *file, uint command, struct dm_ioctl *user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1841
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dm_compat_ctl_ioctl
```
**Symbols:**

```
ffffffff818c28f0-ffffffff818c2db7: ctl_ioctl (STB_LOCAL)
ffffffff818c3ba1-ffffffff818c3cb5: ctl_ioctl.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param reordered. </b>
<code>command, user</code> ➡️ <code>file, command, user</code>
</li>
</ul>
</details>
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
