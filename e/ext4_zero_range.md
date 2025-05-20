# Function: <code>ext4_zero_range</code>

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
In fs/ext4/extents.c (ffffffff812ca868)
Location: fs/ext4/extents.c:4760
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
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
In fs/ext4/extents.c (ffffffff812fa1eb)
Location: fs/ext4/extents.c:4758
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
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
In fs/ext4/extents.c (ffffffff813101bb)
Location: fs/ext4/extents.c:4743
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
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
In fs/ext4/extents.c (ffffffff812ee75c)
Location: fs/ext4/extents.c:4738
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
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
In fs/ext4/extents.c (ffffffff8131320c)
Location: fs/ext4/extents.c:4739
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
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
In fs/ext4/extents.c (ffffffff8134111e)
Location: fs/ext4/extents.c:4733
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
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
In fs/ext4/extents.c (ffffffff81358756)
Location: fs/ext4/extents.c:4632
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137a200)
Location: fs/ext4/extents.c:4642
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff8137a200-ffffffff8137a7c3: ext4_zero_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813926d0)
Location: fs/ext4/extents.c:4688
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff813926d0-ffffffff81392c93: ext4_zero_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813decc0)
Location: fs/ext4/extents.c:4469
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff813decc0-ffffffff813df1fd: ext4_zero_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f0570)
Location: fs/ext4/extents.c:4466
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff813f0570-ffffffff813f0aa5: ext4_zero_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f6a20)
Location: fs/ext4/extents.c:4472
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff813f6a20-ffffffff813f6f3e: ext4_zero_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4511
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff81449690-ffffffff81449c10: ext4_zero_range (STB_LOCAL)
ffffffff81cc8fcc-ffffffff81cc9199: ext4_zero_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4507
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff814c5d40-ffffffff814c6301: ext4_zero_range (STB_LOCAL)
ffffffff81e7bcef-ffffffff81e7be76: ext4_zero_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4511
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff8155e2e0-ffffffff8155e890: ext4_zero_range (STB_LOCAL)
ffffffff8206c370-ffffffff8206c4d5: ext4_zero_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4503
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff815960f0-ffffffff8159667a: ext4_zero_range (STB_LOCAL)
ffffffff820ec1e9-ffffffff820ec378: ext4_zero_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4536
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff815ceda0-ffffffff815cf327: ext4_zero_range (STB_LOCAL)
ffffffff821c9421-ffffffff821c95ac: ext4_zero_range.cold (STB_LOCAL)
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
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010464ed0)
Location: fs/ext4/extents.c:4688
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffff800010464ed0-ffff800010465458: ext4_zero_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062614c)
Location: fs/ext4/extents.c:4688
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
c062614c-c06269b4: ext4_zero_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0000000005834c0)
Location: fs/ext4/extents.c:4688
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
c0000000005834c0-c000000000583c74: ext4_zero_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f3792)
Location: fs/ext4/extents.c:4688
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffe0002f3792-ffffffe0002f3cae: ext4_zero_range (STB_LOCAL)
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
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138acb0)
Location: fs/ext4/extents.c:4688
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff8138acb0-ffffffff8138b273: ext4_zero_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137b740)
Location: fs/ext4/extents.c:4688
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff8137b740-ffffffff8137bd03: ext4_zero_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81388610)
Location: fs/ext4/extents.c:4688
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff81388610-ffffffff81388bd3: ext4_zero_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int ext4_zero_range(struct file *file, loff_t offset, loff_t len, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139c310)
Location: fs/ext4/extents.c:4688
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff8139c310-ffffffff8139c8ec: ext4_zero_range (STB_LOCAL)
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
