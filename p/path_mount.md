# Function: <code>path_mount</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int path_mount(const char *dev_name, struct path *path, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134bc30)
Location: fs/namespace.c:3145
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/init.c:init_mount
```
**Symbols:**

```
ffffffff8134bc30-ffffffff8134c107: path_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int path_mount(const char *dev_name, struct path *path, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3178
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/init.c:init_mount
```
**Symbols:**

```
ffffffff81bdc831-ffffffff81bdc846: path_mount.cold (STB_LOCAL)
ffffffff813524c0-ffffffff81352cd5: path_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int path_mount(const char *dev_name, struct path *path, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3252
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/init.c:init_mount
```
**Symbols:**

```
ffffffff81cc3ffa-ffffffff81cc4047: path_mount.cold (STB_LOCAL)
ffffffff813a08b0-ffffffff813a112c: path_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int path_mount(const char *dev_name, struct path *path, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3295
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/init.c:init_mount
```
**Symbols:**

```
ffffffff81e768f9-ffffffff81e7692c: path_mount.cold (STB_LOCAL)
ffffffff81424230-ffffffff81424a9e: path_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int path_mount(const char *dev_name, struct path *path, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3400
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/init.c:init_mount
```
**Symbols:**

```
ffffffff82068cce-ffffffff82068ce9: path_mount.cold (STB_LOCAL)
ffffffff814b0980-ffffffff814b11a0: path_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int path_mount(const char *dev_name, struct path *path, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3587
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/init.c:init_mount
```
**Symbols:**

```
ffffffff820e85f0-ffffffff820e860b: path_mount.cold (STB_LOCAL)
ffffffff814e59c0-ffffffff814e61e0: path_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int path_mount(const char *dev_name, struct path *path, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:3604
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/init.c:init_mount
```
**Symbols:**

```
ffffffff821c534a-ffffffff821c5365: path_mount.cold (STB_LOCAL)
ffffffff815197f0-ffffffff8151a013: path_mount (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
