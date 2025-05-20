# Function: <code>ext4_sync_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff81292b00)
Location: fs/ext4/fsync.c:87
Inline: False
```
**Symbols:**

```
ffffffff81292b00-ffffffff81292e27: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff812c0050)
Location: fs/ext4/fsync.c:87
Inline: False
```
**Symbols:**

```
ffffffff812c0050-ffffffff812c03d7: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff812d5680)
Location: fs/ext4/fsync.c:94
Inline: False
```
**Symbols:**

```
ffffffff812d5680-ffffffff812d5a0a: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff812f3370)
Location: fs/ext4/fsync.c:94
Inline: False
```
**Symbols:**

```
ffffffff812f3370-ffffffff812f3714: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff81317900)
Location: fs/ext4/fsync.c:95
Inline: False
```
**Symbols:**

```
ffffffff81317900-ffffffff81317cae: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff813457a0)
Location: fs/ext4/fsync.c:95
Inline: False
```
**Symbols:**

```
ffffffff813457a0-ffffffff81345b9c: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff8135d8f0)
Location: fs/ext4/fsync.c:95
Inline: False
```
**Symbols:**

```
ffffffff8135d8f0-ffffffff8135dce6: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff81386aa0)
Location: fs/ext4/fsync.c:95
Inline: False
```
**Symbols:**

```
ffffffff81386aa0-ffffffff81386e71: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff8139f4f0)
Location: fs/ext4/fsync.c:95
Inline: False
```
**Symbols:**

```
ffffffff8139f4f0-ffffffff8139f8c1: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff813eb400)
Location: fs/ext4/fsync.c:129
Inline: False
```
**Symbols:**

```
ffffffff813eb400-ffffffff813eb6fc: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/fsync.c (0)
Location: fs/ext4/fsync.c:129
Inline: False
```
**Symbols:**

```
ffffffff81bec33a-ffffffff81bec362: ext4_sync_file.cold (STB_LOCAL)
ffffffff813fd630-ffffffff813fd91b: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/fsync.c (0)
Location: fs/ext4/fsync.c:129
Inline: False
```
**Symbols:**

```
ffffffff81bde3e5-ffffffff81bde40d: ext4_sync_file.cold (STB_LOCAL)
ffffffff81403a40-ffffffff81403d7c: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/fsync.c (0)
Location: fs/ext4/fsync.c:129
Inline: False
```
**Symbols:**

```
ffffffff81cca166-ffffffff81cca18e: ext4_sync_file.cold (STB_LOCAL)
ffffffff81456210-ffffffff81456530: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/fsync.c (0)
Location: fs/ext4/fsync.c:129
Inline: False
```
**Symbols:**

```
ffffffff81e7ce7e-ffffffff81e7cea6: ext4_sync_file.cold (STB_LOCAL)
ffffffff814d3c10-ffffffff814d3f7f: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff8156c860)
Location: fs/ext4/fsync.c:129
Inline: False
```
**Symbols:**

```
ffffffff8156c860-ffffffff8156cbff: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/fsync.c (0)
Location: fs/ext4/fsync.c:129
Inline: False
```
**Symbols:**

```
ffffffff820ed242-ffffffff820ed24a: ext4_sync_file.cold (STB_LOCAL)
ffffffff815a4700-ffffffff815a4a77: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/fsync.c (0)
Location: fs/ext4/fsync.c:129
Inline: False
```
**Symbols:**

```
ffffffff821ca388-ffffffff821ca390: ext4_sync_file.cold (STB_LOCAL)
ffffffff815dd540-ffffffff815dd8b6: ext4_sync_file (STB_GLOBAL)
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
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffff800010472908)
Location: fs/ext4/fsync.c:95
Inline: False
```
**Symbols:**

```
ffff800010472908-ffff800010472d24: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (c0633d38)
Location: fs/ext4/fsync.c:95
Inline: False
```
**Symbols:**

```
c0633d38-c06341cc: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (c000000000593760)
Location: fs/ext4/fsync.c:95
Inline: False
```
**Symbols:**

```
c000000000593760-c000000000593ca0: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffe0002fe7a8)
Location: fs/ext4/fsync.c:95
Inline: False
```
**Symbols:**

```
ffffffe0002fe7a8-ffffffe0002feb28: ext4_sync_file (STB_GLOBAL)
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
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff81397ad0)
Location: fs/ext4/fsync.c:95
Inline: False
```
**Symbols:**

```
ffffffff81397ad0-ffffffff81397ea1: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff81388560)
Location: fs/ext4/fsync.c:95
Inline: False
```
**Symbols:**

```
ffffffff81388560-ffffffff81388931: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff81395430)
Location: fs/ext4/fsync.c:95
Inline: False
```
**Symbols:**

```
ffffffff81395430-ffffffff81395801: ext4_sync_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_sync_file(struct file *file, loff_t start, loff_t end, int datasync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff813a9550)
Location: fs/ext4/fsync.c:95
Inline: False
```
**Symbols:**

```
ffffffff813a9550-ffffffff813a9958: ext4_sync_file (STB_GLOBAL)
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
