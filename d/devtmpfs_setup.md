# Function: <code>devtmpfs_setup</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff817c4275)
Location: drivers/base/devtmpfs.c:381
Inline: True
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
In drivers/base/devtmpfs.c (ffffffff81c3c094)
Location: drivers/base/devtmpfs.c:405
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devtmpfs_setup(void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff83217a4d)
Location: drivers/base/devtmpfs.c:408
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff83217a4d-ffffffff83217ab5: devtmpfs_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devtmpfs_setup(void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff83301463)
Location: drivers/base/devtmpfs.c:415
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff83301463-ffffffff833014cb: devtmpfs_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devtmpfs_setup(void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff834ba2aa)
Location: drivers/base/devtmpfs.c:419
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff834ba2aa-ffffffff834ba31f: devtmpfs_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devtmpfs_setup(void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff83ef7980)
Location: drivers/base/devtmpfs.c:419
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff83ef7980-ffffffff83ef7a0f: devtmpfs_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devtmpfs_setup(void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff8371d520)
Location: drivers/base/devtmpfs.c:412
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff8371d520-ffffffff8371d5af: devtmpfs_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devtmpfs_setup(void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff83951090)
Location: drivers/base/devtmpfs.c:412
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff83951090-ffffffff8395111f: devtmpfs_setup (STB_LOCAL)
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
