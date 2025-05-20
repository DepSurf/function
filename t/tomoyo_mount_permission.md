# Function: <code>tomoyo_mount_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff813716c0)
Location: security/tomoyo/mount.c:187
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff813716c0-ffffffff81371860: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff813a7ad0)
Location: security/tomoyo/mount.c:187
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff813a7ad0-ffffffff813a7c78: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff813be660)
Location: security/tomoyo/mount.c:187
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff813be660-ffffffff813be808: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff813d4f60)
Location: security/tomoyo/mount.c:187
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff813d4f60-ffffffff813d510a: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff813fb470)
Location: security/tomoyo/mount.c:188
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff813fb470-ffffffff813fb61a: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff8142c3e0)
Location: security/tomoyo/mount.c:188
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff8142c3e0-ffffffff8142c58a: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81448d30)
Location: security/tomoyo/mount.c:189
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff81448d30-ffffffff81448eda: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81476960)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff81476960-ffffffff81476b2a: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81490700)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff81490700-ffffffff814908ca: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff814e7a80)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff814e7a80-ffffffff814e7c4a: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81504e00)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff81504e00-ffffffff81504fca: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff8150b980)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff8150b980-ffffffff8150bb4a: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff815691f0)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff815691f0-ffffffff815693ba: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81604f60)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff81604f60-ffffffff81605146: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff816b6290)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff816b6290-ffffffff816b6476: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff816eeca0)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff816eeca0-ffffffff816eee7e: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff8172ba70)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff8172ba70-ffffffff8172bc4e: tomoyo_mount_permission (STB_GLOBAL)
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
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffff800010584950)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffff800010584950-ffff800010584b1c: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (c07363c0)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
c07363c0-c07365a8: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (c0000000006f3d00)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
c0000000006f3d00-c0000000006f3f68: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffe0003d487a)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffe0003d487a-ffffffe0003d4a08: tomoyo_mount_permission (STB_GLOBAL)
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
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81488ce0)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff81488ce0-ffffffff81488eaa: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81479700)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff81479700-ffffffff814798ca: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff81484d80)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff81484d80-ffffffff81484f4a: tomoyo_mount_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tomoyo_mount_permission(const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/mount.c (ffffffff8149c8c0)
Location: security/tomoyo/mount.c:191
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_mount
```
**Symbols:**

```
ffffffff8149c8c0-ffffffff8149ca8a: tomoyo_mount_permission (STB_GLOBAL)
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
