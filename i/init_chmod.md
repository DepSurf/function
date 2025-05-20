# Function: <code>init_chmod</code>

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
int init_chmod(const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff82fedbed)
Location: fs/init.c:100
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff82fedbed-ffffffff82fedc5b: init_chmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_chmod(const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff831f8402)
Location: fs/init.c:100
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff831f8402-ffffffff831f8470: init_chmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_chmod(const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff832df37b)
Location: fs/init.c:100
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff832df37b-ffffffff832df3e9: init_chmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_chmod(const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83494f86)
Location: fs/init.c:100
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff83494f86-ffffffff83495017: init_chmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_chmod(const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83ec9940)
Location: fs/init.c:100
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff83ec9940-ffffffff83ec99c7: init_chmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_chmod(const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff836ee990)
Location: fs/init.c:100
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff836ee990-ffffffff836eea17: init_chmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_chmod(const char *filename, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff839219e0)
Location: fs/init.c:100
Inline: False
Direct callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff839219e0-ffffffff83921a67: init_chmod (STB_GLOBAL)
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
