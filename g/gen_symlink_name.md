# Function: <code>gen_symlink_name</code>

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
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813d91c0)
Location: security/apparmor/apparmorfs.c:1487
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff813d91c0-ffffffff813d92b4: gen_symlink_name.constprop.32 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff813fff2b)
Location: security/apparmor/apparmorfs.c:1486
Inline: True
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
In security/apparmor/apparmorfs.c (ffffffff81431a5a)
Location: security/apparmor/apparmorfs.c:1483
Inline: True
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
In security/apparmor/apparmorfs.c (ffffffff8144d7da)
Location: security/apparmor/apparmorfs.c:1481
Inline: True
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
In security/apparmor/apparmorfs.c (ffffffff8147d8a5)
Location: security/apparmor/apparmorfs.c:1486
Inline: True
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
In security/apparmor/apparmorfs.c (ffffffff81497575)
Location: security/apparmor/apparmorfs.c:1454
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *gen_symlink_name(int depth, const char *dirname, const char *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814eb870)
Location: security/apparmor/apparmorfs.c:1573
Inline: False
```
**Symbols:**

```
ffffffff814eb870-ffffffff814eb95d: gen_symlink_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *gen_symlink_name(int depth, const char *dirname, const char *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81508c50)
Location: security/apparmor/apparmorfs.c:1573
Inline: False
```
**Symbols:**

```
ffffffff81508c50-ffffffff81508d3d: gen_symlink_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *gen_symlink_name(int depth, const char *dirname, const char *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8150f680)
Location: security/apparmor/apparmorfs.c:1573
Inline: False
```
**Symbols:**

```
ffffffff8150f680-ffffffff8150f76a: gen_symlink_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *gen_symlink_name(int depth, const char *dirname, const char *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8156d1e0)
Location: security/apparmor/apparmorfs.c:1573
Inline: False
```
**Symbols:**

```
ffffffff8156d1e0-ffffffff8156d2ca: gen_symlink_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *gen_symlink_name(int depth, const char *dirname, const char *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81609810)
Location: security/apparmor/apparmorfs.c:1590
Inline: False
```
**Symbols:**

```
ffffffff81609810-ffffffff81609903: gen_symlink_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *gen_symlink_name(int depth, const char *dirname, const char *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816bb340)
Location: security/apparmor/apparmorfs.c:1771
Inline: False
```
**Symbols:**

```
ffffffff816bb340-ffffffff816bb439: gen_symlink_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *gen_symlink_name(int depth, const char *dirname, const char *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f3a30)
Location: security/apparmor/apparmorfs.c:1819
Inline: False
```
**Symbols:**

```
ffffffff816f3a30-ffffffff816f3b6f: gen_symlink_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *gen_symlink_name(int depth, const char *dirname, const char *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff817307c0)
Location: security/apparmor/apparmorfs.c:1822
Inline: False
```
**Symbols:**

```
ffffffff817307c0-ffffffff817308ff: gen_symlink_name (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffff80001058abfc)
Location: security/apparmor/apparmorfs.c:1454
Inline: True
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
In security/apparmor/apparmorfs.c (c073df78)
Location: security/apparmor/apparmorfs.c:1454
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_get_link_base
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
In security/apparmor/apparmorfs.c (c0000000006ff684)
Location: security/apparmor/apparmorfs.c:1454
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_get_link_base
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
In security/apparmor/apparmorfs.c (ffffffe0003d8e30)
Location: security/apparmor/apparmorfs.c:1454
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_get_link_base
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
In security/apparmor/apparmorfs.c (ffffffff8148fb55)
Location: security/apparmor/apparmorfs.c:1454
Inline: True
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
In security/apparmor/apparmorfs.c (ffffffff81480575)
Location: security/apparmor/apparmorfs.c:1454
Inline: True
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
In security/apparmor/apparmorfs.c (ffffffff8148bbf5)
Location: security/apparmor/apparmorfs.c:1454
Inline: True
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
In security/apparmor/apparmorfs.c (ffffffff814a39f1)
Location: security/apparmor/apparmorfs.c:1454
Inline: True
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
