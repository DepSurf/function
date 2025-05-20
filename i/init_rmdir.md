# Function: <code>init_rmdir</code>

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
int init_rmdir(const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff82fee0d1)
Location: fs/init.c:238
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
```
**Symbols:**

```
ffffffff82fee0d1-ffffffff82fee0ee: init_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_rmdir(const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff831f890e)
Location: fs/init.c:242
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
```
**Symbols:**

```
ffffffff831f890e-ffffffff831f892b: init_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_rmdir(const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff832df886)
Location: fs/init.c:242
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
```
**Symbols:**

```
ffffffff832df886-ffffffff832df8a3: init_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_rmdir(const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff8349557a)
Location: fs/init.c:242
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
```
**Symbols:**

```
ffffffff8349557a-ffffffff8349559f: init_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_rmdir(const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83eca040)
Location: fs/init.c:242
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
```
**Symbols:**

```
ffffffff83eca040-ffffffff83eca065: init_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_rmdir(const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff836ef080)
Location: fs/init.c:242
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
```
**Symbols:**

```
ffffffff836ef080-ffffffff836ef0a5: init_rmdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_rmdir(const char *pathname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff839220d0)
Location: fs/init.c:240
Inline: False
Direct callers:
  - init/initramfs.c:clean_path
```
**Symbols:**

```
ffffffff839220d0-ffffffff839220f5: init_rmdir (STB_GLOBAL)
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
