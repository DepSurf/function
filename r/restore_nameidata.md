# Function: <code>restore_nameidata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81216320)
Location: fs/namei.c:530
Inline: False
Direct callers:
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:do_filp_open
  - fs/namei.c:do_file_open_root
```
**Symbols:**

```
ffffffff81216320-ffffffff81216370: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123d100)
Location: fs/namei.c:540
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff8123d100-ffffffff8123d147: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8124fea0)
Location: fs/namei.c:540
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff8124fea0-ffffffff8124fee7: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125bde0)
Location: fs/namei.c:540
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff8125bde0-ffffffff8125be28: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127e1a0)
Location: fs/namei.c:540
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff8127e1a0-ffffffff8127e1e6: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a50e0)
Location: fs/namei.c:524
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff812a50e0-ffffffff812a5126: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ba250)
Location: fs/namei.c:524
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
```
**Symbols:**

```
ffffffff812ba250-ffffffff812ba296: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d6e40)
Location: fs/namei.c:522
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff812d6e40-ffffffff812d6e87: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e89b0)
Location: fs/namei.c:522
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff812e89b0-ffffffff812e89f7: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813289ac)
Location: fs/namei.c:537
Inline: True
Inline callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333efc)
Location: fs/namei.c:537
Inline: True
Inline callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
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
In fs/namei.c (ffffffff81339ff1)
Location: fs/namei.c:589
Inline: True
Inline callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
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
In fs/namei.c (ffffffff813872c7)
Location: fs/namei.c:616
Inline: True
Inline callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
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
In fs/namei.c (ffffffff814080b4)
Location: fs/namei.c:617
Inline: True
Inline callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
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
In fs/namei.c (ffffffff814925a4)
Location: fs/namei.c:617
Inline: True
Inline callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
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
In fs/namei.c (ffffffff814c75f4)
Location: fs/namei.c:620
Inline: True
Inline callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:__filename_parentat
  - fs/namei.c:filename_lookup
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
In fs/namei.c (ffffffff814f9e74)
Location: fs/namei.c:621
Inline: True
Inline callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:__filename_parentat
  - fs/namei.c:filename_lookup
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
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010391c90)
Location: fs/namei.c:522
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffff800010391c90-ffff800010391cd8: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c05783a8)
Location: fs/namei.c:522
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
c05783a8-c05783fc: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000489d00)
Location: fs/namei.c:522
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
c000000000489d00-c000000000489d64: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000260f68)
Location: fs/namei.c:522
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffe000260f68-ffffffe000260fa4: restore_nameidata (STB_LOCAL)
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
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e0f90)
Location: fs/namei.c:522
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff812e0f90-ffffffff812e0fd7: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d1bd0)
Location: fs/namei.c:522
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff812d1bd0-ffffffff812d1c17: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812deda0)
Location: fs/namei.c:522
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff812deda0-ffffffff812dede7: restore_nameidata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void restore_nameidata();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812efd10)
Location: fs/namei.c:522
Inline: False
Direct callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff812efd10-ffffffff812efd57: restore_nameidata (STB_LOCAL)
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
