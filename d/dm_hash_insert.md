# Function: <code>dm_hash_insert</code>

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
In drivers/md/dm-ioctl.c (ffffffff816aa714)
Location: drivers/md/dm-ioctl.c:207
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_create
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
In drivers/md/dm-ioctl.c (ffffffff8170ab97)
Location: drivers/md/dm-ioctl.c:207
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_create
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
In drivers/md/dm-ioctl.c (ffffffff8173ca67)
Location: drivers/md/dm-ioctl.c:207
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_create
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
In drivers/md/dm-ioctl.c (ffffffff8175638d)
Location: drivers/md/dm-ioctl.c:208
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_create
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
In drivers/md/dm-ioctl.c (ffffffff817c859d)
Location: drivers/md/dm-ioctl.c:208
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_create
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
In drivers/md/dm-ioctl.c (ffffffff81811032)
Location: drivers/md/dm-ioctl.c:208
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_create
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
In drivers/md/dm-ioctl.c (ffffffff8183d032)
Location: drivers/md/dm-ioctl.c:208
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8187f850)
Location: drivers/md/dm-ioctl.c:208
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8187f850-ffffffff8187fa7c: dm_hash_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818b1710)
Location: drivers/md/dm-ioctl.c:208
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818b1710-ffffffff818b193c: dm_hash_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff819815d0)
Location: drivers/md/dm-ioctl.c:208
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff819815d0-ffffffff819817fc: dm_hash_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81985bf0)
Location: drivers/md/dm-ioctl.c:208
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81985bf0-ffffffff81985e1c: dm_hash_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81969990)
Location: drivers/md/dm-ioctl.c:245
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81969990-ffffffff81969ba3: dm_hash_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:246
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81a11e20-ffffffff81a1203f: dm_hash_insert (STB_LOCAL)
ffffffff81d2a399-ffffffff81d2a3b5: dm_hash_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:247
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81b7a610-ffffffff81b7a843: dm_hash_insert (STB_LOCAL)
ffffffff81ef65b3-ffffffff81ef65cf: dm_hash_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:247
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81d197e0-ffffffff81d19a13: dm_hash_insert (STB_LOCAL)
ffffffff820a8704-ffffffff820a8720: dm_hash_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:262
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81d82990-ffffffff81d82bb9: dm_hash_insert (STB_LOCAL)
ffffffff82129919-ffffffff82129935: dm_hash_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:262
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81e3a020-ffffffff81e3a278: dm_hash_insert (STB_LOCAL)
ffffffff8220b668-ffffffff8220b684: dm_hash_insert.cold (STB_LOCAL)
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
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffff800010b08518)
Location: drivers/md/dm-ioctl.c:208
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffff800010b08518-ffff800010b08728: dm_hash_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c0be7284)
Location: drivers/md/dm-ioctl.c:208
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
c0be7284-c0be74b0: dm_hash_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c000000000bf9e20)
Location: drivers/md/dm-ioctl.c:208
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
c000000000bf9e20-c000000000bfa120: dm_hash_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffe0006f6c84)
Location: drivers/md/dm-ioctl.c:208
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffe0006f6c84-ffffffe0006f6eaa: dm_hash_insert (STB_LOCAL)
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
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81857590)
Location: drivers/md/dm-ioctl.c:208
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81857590-ffffffff818577bc: dm_hash_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8181eba0)
Location: drivers/md/dm-ioctl.c:208
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8181eba0-ffffffff8181edcc: dm_hash_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818a6bc0)
Location: drivers/md/dm-ioctl.c:208
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818a6bc0-ffffffff818a6dec: dm_hash_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dm_hash_insert(const char *name, const char *uuid, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818c2e00)
Location: drivers/md/dm-ioctl.c:208
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818c2e00-ffffffff818c302c: dm_hash_insert (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
