# Function: <code>check_conflicting_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8126204c)
Location: fs/locks.c:1582
Inline: True
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
In fs/locks.c (ffffffff8128e00f)
Location: fs/locks.c:1608
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_conflicting_open(const struct dentry *dentry, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a0410)
Location: fs/locks.c:1641
Inline: False
```
**Symbols:**

```
ffffffff812a0410-ffffffff812a047b: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_conflicting_open(const struct dentry *dentry, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812af240)
Location: fs/locks.c:1641
Inline: False
```
**Symbols:**

```
ffffffff812af240-ffffffff812af2ab: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_conflicting_open(const struct dentry *dentry, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d2c10)
Location: fs/locks.c:1651
Inline: False
```
**Symbols:**

```
ffffffff812d2c10-ffffffff812d2c83: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int check_conflicting_open(const struct dentry *dentry, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fcc00)
Location: fs/locks.c:1649
Inline: False
```
**Symbols:**

```
ffffffff812fcc00-ffffffff812fcc73: check_conflicting_open (STB_LOCAL)
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
In fs/locks.c (ffffffff813147fe)
Location: fs/locks.c:1766
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81339970)
Location: fs/locks.c:1772
Inline: False
```
**Symbols:**

```
ffffffff81339970-ffffffff813399e0: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81351ec0)
Location: fs/locks.c:1800
Inline: False
```
**Symbols:**

```
ffffffff81351ec0-ffffffff81351f30: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81398930)
Location: fs/locks.c:1803
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
**Symbols:**

```
ffffffff81398930-ffffffff813989a0: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813aa410)
Location: fs/locks.c:1804
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
**Symbols:**

```
ffffffff813aa410-ffffffff813aa480: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b18d0)
Location: fs/locks.c:1804
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
**Symbols:**

```
ffffffff813b18d0-ffffffff813b1943: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814015c0)
Location: fs/locks.c:1707
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
**Symbols:**

```
ffffffff814015c0-ffffffff81401633: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814758d0)
Location: fs/locks.c:1682
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
**Symbols:**

```
ffffffff814758d0-ffffffff81475970: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81507dd0)
Location: fs/locks.c:1668
Inline: False
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
**Symbols:**

```
ffffffff81507dd0-ffffffff81507e70: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff81541220)
Location: fs/locks.c:1669
Inline: True
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
**Symbols:**

```
ffffffff81541220-ffffffff815412ba: check_conflicting_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff81576700)
Location: fs/locks.c:1683
Inline: True
Direct callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
**Symbols:**

```
ffffffff81576700-ffffffff81576793: check_conflicting_open.isra.0 (STB_LOCAL)
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
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010413f98)
Location: fs/locks.c:1800
Inline: False
```
**Symbols:**

```
ffff800010413f98-ffff800010414054: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e0110)
Location: fs/locks.c:1800
Inline: False
```
**Symbols:**

```
c05e0110-c05e0194: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c0000000005223e0)
Location: fs/locks.c:1800
Inline: False
```
**Symbols:**

```
c0000000005223e0-c00000000052247c: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bb88c)
Location: fs/locks.c:1800
Inline: False
```
**Symbols:**

```
ffffffe0002bb88c-ffffffe0002bb924: check_conflicting_open (STB_LOCAL)
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
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134a4a0)
Location: fs/locks.c:1800
Inline: False
```
**Symbols:**

```
ffffffff8134a4a0-ffffffff8134a510: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133b180)
Location: fs/locks.c:1800
Inline: False
```
**Symbols:**

```
ffffffff8133b180-ffffffff8133b1f0: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81347f70)
Location: fs/locks.c:1800
Inline: False
```
**Symbols:**

```
ffffffff81347f70-ffffffff81347fe0: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_conflicting_open(struct file *filp, const long int arg, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135b380)
Location: fs/locks.c:1800
Inline: False
```
**Symbols:**

```
ffffffff8135b380-ffffffff8135b3f0: check_conflicting_open (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
