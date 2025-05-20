# Function: <code>devtmpfs_work_loop</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void devtmpfs_work_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devtmpfs.c (0)
Location: drivers/base/devtmpfs.c:382
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff817d8d00-ffffffff817d8d48: devtmpfs_work_loop (STB_LOCAL)
ffffffff81c0ebc9-ffffffff81c0ec38: devtmpfs_work_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void devtmpfs_work_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devtmpfs.c (0)
Location: drivers/base/devtmpfs.c:385
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff817bce70-ffffffff817bd117: devtmpfs_work_loop (STB_LOCAL)
ffffffff81c00da8-ffffffff81c00dbe: devtmpfs_work_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void devtmpfs_work_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devtmpfs.c (0)
Location: drivers/base/devtmpfs.c:392
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff818471f0-ffffffff81847496: devtmpfs_work_loop (STB_LOCAL)
ffffffff81d03832-ffffffff81d03848: devtmpfs_work_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void devtmpfs_work_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devtmpfs.c (0)
Location: drivers/base/devtmpfs.c:396
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff8198bc90-ffffffff8198bfe9: devtmpfs_work_loop (STB_LOCAL)
ffffffff81ecbfde-ffffffff81ecbff8: devtmpfs_work_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devtmpfs_work_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff81afb6d0)
Location: drivers/base/devtmpfs.c:396
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff81afb6d0-ffffffff81afba98: devtmpfs_work_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devtmpfs_work_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff81b49ad0)
Location: drivers/base/devtmpfs.c:389
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff81b49ad0-ffffffff81b49e8b: devtmpfs_work_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devtmpfs_work_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff81ba1ec0)
Location: drivers/base/devtmpfs.c:389
Inline: False
Direct callers:
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff81ba1ec0-ffffffff81ba227b: devtmpfs_work_loop (STB_LOCAL)
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
