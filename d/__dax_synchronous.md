# Function: <code>__dax_synchronous</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173eb30)
Location: drivers/dax/super.c:378
Inline: False
Direct callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
**Symbols:**

```
ffffffff8173eb30-ffffffff8173eb49: __dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81762d10)
Location: drivers/dax/super.c:378
Inline: False
Direct callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
**Symbols:**

```
ffffffff81762d10-ffffffff81762d29: __dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81822b10)
Location: drivers/dax/super.c:399
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_mmap
  - drivers/md/dm-table.c:device_dax_synchronous
```
**Symbols:**

```
ffffffff81822b10-ffffffff81822b29: __dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831820)
Location: drivers/dax/super.c:407
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_mmap
  - drivers/md/dm-table.c:device_not_dax_synchronous_capable
```
**Symbols:**

```
ffffffff81831820-ffffffff81831839: __dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81814a50)
Location: drivers/dax/super.c:407
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_mmap
  - drivers/md/dm-table.c:device_not_dax_synchronous_capable
```
**Symbols:**

```
ffffffff81814a50-ffffffff81814a69: __dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f210)
Location: drivers/dax/super.c:399
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_mmap
  - drivers/md/dm-table.c:device_not_dax_synchronous_capable
```
**Symbols:**

```
ffffffff8189f210-ffffffff8189f229: __dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010962a28)
Location: drivers/dax/super.c:378
Inline: False
Direct callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
**Symbols:**

```
ffff800010962a28-ffff800010962a54: __dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a3990c)
Location: drivers/dax/super.c:378
Inline: False
Direct callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
**Symbols:**

```
c0a3990c-c0a3992c: __dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a18ad0)
Location: drivers/dax/super.c:378
Inline: False
Direct callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
**Symbols:**

```
c000000000a18ad0-c000000000a18ae4: __dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d004a)
Location: drivers/dax/super.c:378
Inline: False
Direct callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
**Symbols:**

```
ffffffe0005d004a-ffffffe0005d0072: __dax_synchronous (STB_GLOBAL)
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
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717400)
Location: drivers/dax/super.c:378
Inline: False
Direct callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
**Symbols:**

```
ffffffff81717400-ffffffff81717419: __dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816ef930)
Location: drivers/dax/super.c:378
Inline: False
Direct callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
**Symbols:**

```
ffffffff816ef930-ffffffff816ef949: __dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817561d0)
Location: drivers/dax/super.c:378
Inline: False
Direct callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
**Symbols:**

```
ffffffff817561d0-ffffffff817561e9: __dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771640)
Location: drivers/dax/super.c:378
Inline: False
Direct callers:
  - drivers/md/dm-table.c:device_dax_synchronous
```
**Symbols:**

```
ffffffff81771640-ffffffff81771659: __dax_synchronous (STB_GLOBAL)
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
