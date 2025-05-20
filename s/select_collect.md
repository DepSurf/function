# Function: <code>select_collect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81223290)
Location: fs/dcache.c:1353
Inline: False
Direct callers:
  - fs/dcache.c:detach_and_collect
```
**Symbols:**

```
ffffffff81223290-ffffffff81223327: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124b0b0)
Location: fs/dcache.c:1364
Inline: False
Direct callers:
  - fs/dcache.c:detach_and_collect
```
**Symbols:**

```
ffffffff8124b0b0-ffffffff8124b144: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125e0a0)
Location: fs/dcache.c:1373
Inline: False
Direct callers:
  - fs/dcache.c:detach_and_collect
```
**Symbols:**

```
ffffffff8125e0a0-ffffffff8125e12c: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126b870)
Location: fs/dcache.c:1406
Inline: True
Direct callers:
  - fs/dcache.c:detach_and_collect
```
**Symbols:**

```
ffffffff8126b870-ffffffff8126b8f2: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128e100)
Location: fs/dcache.c:1418
Inline: True
Direct callers:
  - fs/dcache.c:detach_and_collect
```
**Symbols:**

```
ffffffff8128e100-ffffffff8128e182: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b46a0)
Location: fs/dcache.c:1444
Inline: True
```
**Symbols:**

```
ffffffff812b46a0-ffffffff812b475f: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812c9920)
Location: fs/dcache.c:1453
Inline: True
```
**Symbols:**

```
ffffffff812c9920-ffffffff812c99df: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e6390)
Location: fs/dcache.c:1473
Inline: True
```
**Symbols:**

```
ffffffff812e6390-ffffffff812e6416: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f7d80)
Location: fs/dcache.c:1473
Inline: False
```
**Symbols:**

```
ffffffff812f7d80-ffffffff812f7e43: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81330c10)
Location: fs/dcache.c:1494
Inline: False
```
**Symbols:**

```
ffffffff81330c10-ffffffff81330cd3: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133c5a0)
Location: fs/dcache.c:1501
Inline: False
```
**Symbols:**

```
ffffffff8133c5a0-ffffffff8133c663: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81342a20)
Location: fs/dcache.c:1528
Inline: False
```
**Symbols:**

```
ffffffff81342a20-ffffffff81342ae3: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81390340)
Location: fs/dcache.c:1529
Inline: False
```
**Symbols:**

```
ffffffff81390340-ffffffff81390403: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81411790)
Location: fs/dcache.c:1553
Inline: False
```
**Symbols:**

```
ffffffff81411790-ffffffff81411874: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149d450)
Location: fs/dcache.c:1553
Inline: False
```
**Symbols:**

```
ffffffff8149d450-ffffffff8149d534: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d1490)
Location: fs/dcache.c:1553
Inline: False
```
**Symbols:**

```
ffffffff814d1490-ffffffff814d158d: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81503cb0)
Location: fs/dcache.c:1421
Inline: False
```
**Symbols:**

```
ffffffff81503cb0-ffffffff81503d44: select_collect (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a6518)
Location: fs/dcache.c:1473
Inline: True
```
**Symbols:**

```
ffff8000103a6518-ffff8000103a65c8: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0587d14)
Location: fs/dcache.c:1473
Inline: True
```
**Symbols:**

```
c0587d14-c0587db8: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a0030)
Location: fs/dcache.c:1473
Inline: True
```
**Symbols:**

```
c0000000004a0030-c0000000004a0138: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026c4f0)
Location: fs/dcache.c:1473
Inline: True
```
**Symbols:**

```
ffffffe00026c4f0-ffffffe00026c580: select_collect (STB_LOCAL)
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
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0360)
Location: fs/dcache.c:1473
Inline: False
```
**Symbols:**

```
ffffffff812f0360-ffffffff812f0423: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e0f90)
Location: fs/dcache.c:1473
Inline: False
```
**Symbols:**

```
ffffffff812e0f90-ffffffff812e1053: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ee170)
Location: fs/dcache.c:1473
Inline: False
```
**Symbols:**

```
ffffffff812ee170-ffffffff812ee233: select_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum d_walk_ret select_collect(void *_data, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ff630)
Location: fs/dcache.c:1473
Inline: False
```
**Symbols:**

```
ffffffff812ff630-ffffffff812ff6f3: select_collect (STB_LOCAL)
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
