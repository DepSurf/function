# Function: <code>ext4_group_desc_csum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ada00)
Location: fs/ext4/super.c:2054
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812ada00-ffffffff812adbd1: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e6460)
Location: fs/ext4/super.c:2173
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
```
**Symbols:**

```
ffffffff812e6460-ffffffff812e66a6: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fc010)
Location: fs/ext4/super.c:2198
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
```
**Symbols:**

```
ffffffff812fc010-ffffffff812fc256: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81330ce0)
Location: fs/ext4/super.c:2256
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff81330ce0-ffffffff81330ee3: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813551a0)
Location: fs/ext4/super.c:2259
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff813551a0-ffffffff813553a3: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813835d0)
Location: fs/ext4/super.c:2300
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff813835d0-ffffffff813837d3: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8139bff0)
Location: fs/ext4/super.c:2362
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff8139bff0-ffffffff8139c1f3: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c6260)
Location: fs/ext4/super.c:2405
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff813c6260-ffffffff813c6451: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813df620)
Location: fs/ext4/super.c:2423
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff813df620-ffffffff813df811: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8142bf60)
Location: fs/ext4/super.c:2577
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
```
**Symbols:**

```
ffffffff8142bf60-ffffffff8142c151: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81444b90)
Location: fs/ext4/super.c:2782
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
```
**Symbols:**

```
ffffffff81444b90-ffffffff81444d81: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81449e10)
Location: fs/ext4/super.c:2808
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
```
**Symbols:**

```
ffffffff81449e10-ffffffff8144a001: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8149cad0)
Location: fs/ext4/super.c:2794
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
```
**Symbols:**

```
ffffffff8149cad0-ffffffff8149ccc1: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81524500)
Location: fs/ext4/super.c:3173
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff81524500-ffffffff81524747: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c10b0)
Location: fs/ext4/super.c:3162
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff815c10b0-ffffffff815c12f7: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f8830)
Location: fs/ext4/super.c:3218
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff815f8830-ffffffff815f8a6d: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff816313c0)
Location: fs/ext4/super.c:3224
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff816313c0-ffffffff816315fd: ext4_group_desc_csum (STB_LOCAL)
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
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b2cd8)
Location: fs/ext4/super.c:2423
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffff8000104b2cd8-ffff8000104b2e74: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067ab50)
Location: fs/ext4/super.c:2423
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
c067ab50-c067ad14: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005ed450)
Location: fs/ext4/super.c:2423
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
c0000000005ed450-c0000000005ed6e8: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000334f0a)
Location: fs/ext4/super.c:2423
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffe000334f0a-ffffffe000335090: ext4_group_desc_csum (STB_LOCAL)
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
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d7c00)
Location: fs/ext4/super.c:2423
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff813d7c00-ffffffff813d7df1: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c8680)
Location: fs/ext4/super.c:2423
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff813c8680-ffffffff813c8871: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d5090)
Location: fs/ext4/super.c:2423
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff813d5090-ffffffff813d5281: ext4_group_desc_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ea320)
Location: fs/ext4/super.c:2423
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
```
**Symbols:**

```
ffffffff813ea320-ffffffff813ea511: ext4_group_desc_csum (STB_LOCAL)
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
