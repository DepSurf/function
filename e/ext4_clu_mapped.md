# Function: <code>ext4_clu_mapped</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81359520)
Location: fs/ext4/extents.c:5876
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff81359520-ffffffff81359687: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813824b0)
Location: fs/ext4/extents.c:5886
Inline: False
```
**Symbols:**

```
ffffffff813824b0-ffffffff81382603: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139aa60)
Location: fs/ext4/extents.c:5964
Inline: False
```
**Symbols:**

```
ffffffff8139aa60-ffffffff8139abb3: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e5f10)
Location: fs/ext4/extents.c:5723
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_insert_delayed_block
```
**Symbols:**

```
ffffffff813e5f10-ffffffff813e60c1: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f7730)
Location: fs/ext4/extents.c:5736
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_insert_delayed_block
```
**Symbols:**

```
ffffffff813f7730-ffffffff813f78e1: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813fdbc0)
Location: fs/ext4/extents.c:5742
Inline: False
```
**Symbols:**

```
ffffffff813fdbc0-ffffffff813fdd73: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:5773
Inline: False
```
**Symbols:**

```
ffffffff81cc98f7-ffffffff81cc9992: ext4_clu_mapped.cold (STB_LOCAL)
ffffffff8144fe70-ffffffff81450071: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:5786
Inline: False
```
**Symbols:**

```
ffffffff81e7c608-ffffffff81e7c6a2: ext4_clu_mapped.cold (STB_LOCAL)
ffffffff814ccda0-ffffffff814ccfb2: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:5792
Inline: False
```
**Symbols:**

```
ffffffff8206cc52-ffffffff8206ccec: ext4_clu_mapped.cold (STB_LOCAL)
ffffffff815654d0-ffffffff815656e6: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:5762
Inline: False
```
**Symbols:**

```
ffffffff820ec9ca-ffffffff820eca74: ext4_clu_mapped.cold (STB_LOCAL)
ffffffff8159d120-ffffffff8159d377: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:5797
Inline: False
```
**Symbols:**

```
ffffffff821c9c06-ffffffff821c9cb0: ext4_clu_mapped.cold (STB_LOCAL)
ffffffff815d5d70-ffffffff815d5fc7: ext4_clu_mapped (STB_GLOBAL)
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
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff80001046d340)
Location: fs/ext4/extents.c:5964
Inline: False
```
**Symbols:**

```
ffff80001046d340-ffff80001046d508: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062ea18)
Location: fs/ext4/extents.c:5964
Inline: False
```
**Symbols:**

```
c062ea18-c062eba0: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c00000000058d1c0)
Location: fs/ext4/extents.c:5964
Inline: False
```
**Symbols:**

```
c00000000058d1c0-c00000000058d420: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002fa728)
Location: fs/ext4/extents.c:5964
Inline: False
```
**Symbols:**

```
ffffffe0002fa728-ffffffe0002fa8c0: ext4_clu_mapped (STB_GLOBAL)
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
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81393040)
Location: fs/ext4/extents.c:5964
Inline: False
```
**Symbols:**

```
ffffffff81393040-ffffffff81393193: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81383ad0)
Location: fs/ext4/extents.c:5964
Inline: False
```
**Symbols:**

```
ffffffff81383ad0-ffffffff81383c23: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813909a0)
Location: fs/ext4/extents.c:5964
Inline: False
```
**Symbols:**

```
ffffffff813909a0-ffffffff81390af3: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_clu_mapped(struct inode *inode, ext4_lblk_t lclu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813a4830)
Location: fs/ext4/extents.c:5964
Inline: False
```
**Symbols:**

```
ffffffff813a4830-ffffffff813a4983: ext4_clu_mapped (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
