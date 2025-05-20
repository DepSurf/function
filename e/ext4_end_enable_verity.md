# Function: <code>ext4_end_enable_verity</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813ef2b0)
Location: fs/ext4/verity.c:195
Inline: False
```
**Symbols:**

```
ffffffff813ef2b0-ffffffff813ef4c1: ext4_end_enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8143c0b0)
Location: fs/ext4/verity.c:198
Inline: False
```
**Symbols:**

```
ffffffff8143c0b0-ffffffff8143c2de: ext4_end_enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff81458410)
Location: fs/ext4/verity.c:198
Inline: False
```
**Symbols:**

```
ffffffff81458410-ffffffff81458628: ext4_end_enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8145ddb0)
Location: fs/ext4/verity.c:192
Inline: False
```
**Symbols:**

```
ffffffff8145ddb0-ffffffff8145dfce: ext4_end_enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (0)
Location: fs/ext4/verity.c:192
Inline: False
```
**Symbols:**

```
ffffffff814b32b0-ffffffff814b34e2: ext4_end_enable_verity (STB_LOCAL)
ffffffff81cce385-ffffffff81cce400: ext4_end_enable_verity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (0)
Location: fs/ext4/verity.c:193
Inline: False
```
**Symbols:**

```
ffffffff8153be90-ffffffff8153c0bb: ext4_end_enable_verity (STB_LOCAL)
ffffffff81e813e9-ffffffff81e81461: ext4_end_enable_verity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (0)
Location: fs/ext4/verity.c:193
Inline: False
```
**Symbols:**

```
ffffffff815da540-ffffffff815da770: ext4_end_enable_verity (STB_LOCAL)
ffffffff8207128d-ffffffff82071305: ext4_end_enable_verity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (0)
Location: fs/ext4/verity.c:191
Inline: False
```
**Symbols:**

```
ffffffff81612310-ffffffff81612543: ext4_end_enable_verity (STB_LOCAL)
ffffffff820f0f51-ffffffff820f0fc9: ext4_end_enable_verity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (0)
Location: fs/ext4/verity.c:191
Inline: False
```
**Symbols:**

```
ffffffff8164afe0-ffffffff8164b213: ext4_end_enable_verity (STB_LOCAL)
ffffffff821ce0d0-ffffffff821ce148: ext4_end_enable_verity.cold (STB_LOCAL)
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
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffff8000104c8728)
Location: fs/ext4/verity.c:195
Inline: False
```
**Symbols:**

```
ffff8000104c8728-ffff8000104c8964: ext4_end_enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (c068c0b8)
Location: fs/ext4/verity.c:195
Inline: False
```
**Symbols:**

```
c068c0b8-c068c320: ext4_end_enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (c000000000600e30)
Location: fs/ext4/verity.c:195
Inline: False
```
**Symbols:**

```
c000000000600e30-c0000000006010c4: ext4_end_enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffe0003420f0)
Location: fs/ext4/verity.c:195
Inline: False
```
**Symbols:**

```
ffffffe0003420f0-ffffffe000342282: ext4_end_enable_verity (STB_LOCAL)
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
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813e7890)
Location: fs/ext4/verity.c:195
Inline: False
```
**Symbols:**

```
ffffffff813e7890-ffffffff813e7aa1: ext4_end_enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813d8310)
Location: fs/ext4/verity.c:195
Inline: False
```
**Symbols:**

```
ffffffff813d8310-ffffffff813d8521: ext4_end_enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813e4c10)
Location: fs/ext4/verity.c:195
Inline: False
```
**Symbols:**

```
ffffffff813e4c10-ffffffff813e4e21: ext4_end_enable_verity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_end_enable_verity(struct file *filp, const void *desc, size_t desc_size, u64 merkle_tree_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813fa060)
Location: fs/ext4/verity.c:195
Inline: False
```
**Symbols:**

```
ffffffff813fa060-ffffffff813fa271: ext4_end_enable_verity (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
