# Function: <code>ext4_dx_readdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8129126e)
Location: fs/ext4/dir.c:508
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812be77d)
Location: fs/ext4/dir.c:524
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812d3def)
Location: fs/ext4/dir.c:525
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812e573a)
Location: fs/ext4/dir.c:525
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8130a167)
Location: fs/ext4/dir.c:526
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8133809b)
Location: fs/ext4/dir.c:527
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8134f32c)
Location: fs/ext4/dir.c:527
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813779e0)
Location: fs/ext4/dir.c:527
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff813779e0-ffffffff81377da2: ext4_dx_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8138fd60)
Location: fs/ext4/dir.c:534
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff8138fd60-ffffffff81390122: ext4_dx_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813db330)
Location: fs/ext4/dir.c:532
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff813db330-ffffffff813db6dd: ext4_dx_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813ecd60)
Location: fs/ext4/dir.c:530
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff813ecd60-ffffffff813ed10d: ext4_dx_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813f3290)
Location: fs/ext4/dir.c:549
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff813f3290-ffffffff813f363d: ext4_dx_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff814452d0)
Location: fs/ext4/dir.c:549
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff814452d0-ffffffff814456f6: ext4_dx_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff814c13b0)
Location: fs/ext4/dir.c:548
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff814c13b0-ffffffff814c1770: ext4_dx_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81559650)
Location: fs/ext4/dir.c:548
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff81559650-ffffffff81559a0d: ext4_dx_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81591460)
Location: fs/ext4/dir.c:548
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff81591460-ffffffff81591836: ext4_dx_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff815ca1a0)
Location: fs/ext4/dir.c:548
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff815ca1a0-ffffffff815ca5a5: ext4_dx_readdir (STB_LOCAL)
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
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffff8000104626e0)
Location: fs/ext4/dir.c:534
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffff8000104626e0-ffff8000104629e8: ext4_dx_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c06234c4)
Location: fs/ext4/dir.c:534
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c00000000057fbfc)
Location: fs/ext4/dir.c:534
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffe0002f19a2)
Location: fs/ext4/dir.c:534
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
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
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81388340)
Location: fs/ext4/dir.c:534
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff81388340-ffffffff81388702: ext4_dx_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81378dd0)
Location: fs/ext4/dir.c:534
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff81378dd0-ffffffff81379192: ext4_dx_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81385ca0)
Location: fs/ext4/dir.c:534
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff81385ca0-ffffffff81386062: ext4_dx_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_dx_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81399990)
Location: fs/ext4/dir.c:534
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff81399990-ffffffff81399d52: ext4_dx_readdir (STB_LOCAL)
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
