# Function: <code>tomoyo_path_number_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8136f300)
Location: security/tomoyo/file.c:690
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
```
**Symbols:**

```
ffffffff8136f300-ffffffff8136f4be: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813a55f0)
Location: security/tomoyo/file.c:690
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff813a55f0-ffffffff813a57d2: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813bc170)
Location: security/tomoyo/file.c:690
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff813bc170-ffffffff813bc352: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813d2a70)
Location: security/tomoyo/file.c:690
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff813d2a70-ffffffff813d2c6c: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813f8f80)
Location: security/tomoyo/file.c:691
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff813f8f80-ffffffff813f917c: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81429f70)
Location: security/tomoyo/file.c:691
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff81429f70-ffffffff8142a152: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81446840)
Location: security/tomoyo/file.c:691
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff81446840-ffffffff81446a22: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81474430)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff81474430-ffffffff81474624: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8148e1d0)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff8148e1d0-ffffffff8148e3c4: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff814e5460)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff814e5460-ffffffff814e5654: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81502860)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff81502860-ffffffff81502a54: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81509430)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff81509430-ffffffff81509624: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff815667a0)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff815667a0-ffffffff81566a1e: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816021d0)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff816021d0-ffffffff816024e0: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816b3300)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff816b3300-ffffffff816b3612: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816ebcd0)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff816ebcd0-ffffffff816ebfde: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81728aa0)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff81728aa0-ffffffff81728dae: tomoyo_path_number_perm (STB_GLOBAL)
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
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffff800010581b80)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffff800010581b80-ffff800010581d90: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (c0733aa4)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
c0733aa4-c0733cb8: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (c0000000006f0260)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
c0000000006f0260-c0000000006f04fc: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffe0003d225e)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffe0003d225e-ffffffe0003d240c: tomoyo_path_number_perm (STB_GLOBAL)
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
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff814867b0)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff814867b0-ffffffff814869a4: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff814771d0)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff814771d0-ffffffff814773c4: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81482850)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff81482850-ffffffff81482a44: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tomoyo_path_number_perm(const u8 type, const struct path *path, long unsigned int number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8149a3e0)
Location: security/tomoyo/file.c:708
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/tomoyo/tomoyo.c:tomoyo_path_chmod
  - security/tomoyo/tomoyo.c:tomoyo_file_ioctl
  - security/tomoyo/tomoyo.c:tomoyo_path_mknod
  - security/tomoyo/tomoyo.c:tomoyo_path_mkdir
```
**Symbols:**

```
ffffffff8149a3e0-ffffffff8149a5d4: tomoyo_path_number_perm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
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
