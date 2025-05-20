# Function: <code>dm_get_dev_t</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81705120)
Location: drivers/md/dm-table.c:373
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81705120-ffffffff8170515a: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81736fd0)
Location: drivers/md/dm-table.c:373
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81736fd0-ffffffff8173700a: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817503e0)
Location: drivers/md/dm-table.c:408
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff817503e0-ffffffff8175041a: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c25c0)
Location: drivers/md/dm-table.c:408
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff817c25c0-ffffffff817c25fa: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180af30)
Location: drivers/md/dm-table.c:408
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff8180af30-ffffffff8180af6a: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81836f30)
Location: drivers/md/dm-table.c:407
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81836f30-ffffffff81836f6a: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81879b10)
Location: drivers/md/dm-table.c:407
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81879b10-ffffffff81879b51: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818ab910)
Location: drivers/md/dm-table.c:405
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff818ab910-ffffffff818ab94f: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197c79e)
Location: drivers/md/dm-table.c:388
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff8197bb50-ffffffff8197bb93: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81980ea9)
Location: drivers/md/dm-table.c:347
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff819801a0-ffffffff819801f5: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff819650b5)
Location: drivers/md/dm-table.c:333
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81964290-ffffffff819642e5: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0d035)
Location: drivers/md/dm-table.c:333
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81a0c270-ffffffff81a0c2c5: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b7598e)
Location: drivers/md/dm-table.c:332
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81b74ac0-ffffffff81b74b25: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d12cbe)
Location: drivers/md/dm-table.c:331
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff81d11af0-ffffffff81d11b55: dm_get_dev_t (STB_GLOBAL)
```
</details>
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
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b020f8)
Location: drivers/md/dm-table.c:405
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffff800010b020f8-ffff800010b02154: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be12fc)
Location: drivers/md/dm-table.c:405
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
c0be12fc-c0be1344: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf1060)
Location: drivers/md/dm-table.c:405
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
c000000000bf1060-c000000000bf10e8: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f1af8)
Location: drivers/md/dm-table.c:405
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffe0006f1af8-ffffffe0006f1b4e: dm_get_dev_t (STB_GLOBAL)
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
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81851790)
Location: drivers/md/dm-table.c:405
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81851790-ffffffff818517cf: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81818da0)
Location: drivers/md/dm-table.c:405
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81818da0-ffffffff81818ddf: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a0dc0)
Location: drivers/md/dm-table.c:405
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff818a0dc0-ffffffff818a0dff: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
dev_t dm_get_dev_t(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818bd000)
Location: drivers/md/dm-table.c:405
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff818bd000-ffffffff818bd03f: dm_get_dev_t (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
