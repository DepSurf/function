# Function: <code>ext4_getfsmap_helper</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff812f2050)
Location: fs/ext4/fsmap.c:97
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff812f2050-ffffffff812f239e: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff813165d0)
Location: fs/ext4/fsmap.c:97
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff813165d0-ffffffff8131692c: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff81344460)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff81344460-ffffffff813447a2: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff8135c5b0)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff8135c5b0-ffffffff8135c8f2: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff81385700)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff81385700-ffffffff81385a52: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff8139e150)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff8139e150-ffffffff8139e4a2: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff813ea000)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff813ea000-ffffffff813ea329: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff813fc3e0)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff813fc3e0-ffffffff813fc64f: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff81402c50)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff81402c50-ffffffff81402ed4: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/fsmap.c (0)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff81455320-ffffffff814555e6: ext4_getfsmap_helper (STB_LOCAL)
ffffffff81cc9f56-ffffffff81cc9ffc: ext4_getfsmap_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/fsmap.c (0)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff814d2b80-ffffffff814d2ebc: ext4_getfsmap_helper (STB_LOCAL)
ffffffff81e7cc50-ffffffff81e7cd1a: ext4_getfsmap_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/fsmap.c (0)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff8156b730-ffffffff8156ba75: ext4_getfsmap_helper (STB_LOCAL)
ffffffff8206d246-ffffffff8206d310: ext4_getfsmap_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/fsmap.c (0)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff815a35e0-ffffffff815a3925: ext4_getfsmap_helper (STB_LOCAL)
ffffffff820ed017-ffffffff820ed0e1: ext4_getfsmap_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/fsmap.c (0)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff815dc420-ffffffff815dc765: ext4_getfsmap_helper (STB_LOCAL)
ffffffff821ca15d-ffffffff821ca227: ext4_getfsmap_helper.cold (STB_LOCAL)
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
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffff800010471728)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffff800010471728-ffff800010471a90: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (c06325ec)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
c06325ec-c0632ac8: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (c000000000592020)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
c000000000592020-c0000000005924c4: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffe0002fd90a)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffe0002fd90a-ffffffe0002fdb82: ext4_getfsmap_helper (STB_LOCAL)
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
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff81396730)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff81396730-ffffffff81396a82: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff813871c0)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff813871c0-ffffffff81387512: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff81394090)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff81394090-ffffffff813943e2: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_getfsmap_helper(struct super_block *sb, struct ext4_getfsmap_info *info, struct ext4_fsmap *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff813a8120)
Location: fs/ext4/fsmap.c:84
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
**Symbols:**

```
ffffffff813a8120-ffffffff813a84a7: ext4_getfsmap_helper (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
