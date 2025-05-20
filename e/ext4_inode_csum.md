# Function: <code>ext4_inode_csum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff81297ad0)
Location: fs/ext4/inode.c:50
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff81297ad0-ffffffff81297c0a: ext4_inode_csum.isra.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c5450)
Location: fs/ext4/inode.c:50
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff812c5450-ffffffff812c5647: ext4_inode_csum.isra.57 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dac70)
Location: fs/ext4/inode.c:51
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff812dac70-ffffffff812dae79: ext4_inode_csum.isra.57 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff812fea30)
Location: fs/ext4/inode.c:51
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff812fea30-ffffffff812fec3f: ext4_inode_csum.isra.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff813231e0)
Location: fs/ext4/inode.c:52
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff813231e0-ffffffff813233ef: ext4_inode_csum.isra.56 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff81351750)
Location: fs/ext4/inode.c:53
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff81351750-ffffffff8135195f: ext4_inode_csum.isra.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff81369010)
Location: fs/ext4/inode.c:53
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff81369010-ffffffff8136921f: ext4_inode_csum.isra.64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff81392450)
Location: fs/ext4/inode.c:53
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff81392450-ffffffff81392638: ext4_inode_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff813aade0)
Location: fs/ext4/inode.c:53
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813aade0-ffffffff813aafc8: ext4_inode_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__u32 ext4_inode_csum(struct inode *inode, struct ext4_inode *raw, struct ext4_inode_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f7170)
Location: fs/ext4/inode.c:51
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813f7170-ffffffff813f7361: ext4_inode_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__u32 ext4_inode_csum(struct inode *inode, struct ext4_inode *raw, struct ext4_inode_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81409870)
Location: fs/ext4/inode.c:51
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff81409870-ffffffff81409a5f: ext4_inode_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__u32 ext4_inode_csum(struct inode *inode, struct ext4_inode *raw, struct ext4_inode_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140fa10)
Location: fs/ext4/inode.c:52
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff8140fa10-ffffffff8140fc02: ext4_inode_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__u32 ext4_inode_csum(struct inode *inode, struct ext4_inode *raw, struct ext4_inode_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81462ae0)
Location: fs/ext4/inode.c:52
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff81462ae0-ffffffff81462cd2: ext4_inode_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__u32 ext4_inode_csum(struct inode *inode, struct ext4_inode *raw, struct ext4_inode_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e1110)
Location: fs/ext4/inode.c:52
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff814e1110-ffffffff814e137e: ext4_inode_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__u32 ext4_inode_csum(struct inode *inode, struct ext4_inode *raw, struct ext4_inode_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157a6f0)
Location: fs/ext4/inode.c:52
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff8157a6f0-ffffffff8157a95e: ext4_inode_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__u32 ext4_inode_csum(struct inode *inode, struct ext4_inode *raw, struct ext4_inode_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b22b0)
Location: fs/ext4/inode.c:52
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff815b22b0-ffffffff815b251e: ext4_inode_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__u32 ext4_inode_csum(struct inode *inode, struct ext4_inode *raw, struct ext4_inode_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815eb0f0)
Location: fs/ext4/inode.c:52
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff815eb0f0-ffffffff815eb35e: ext4_inode_csum (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffff80001047da78)
Location: fs/ext4/inode.c:53
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffff80001047da78-ffff80001047dbb4: ext4_inode_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__u32 ext4_inode_csum(struct inode *inode, struct ext4_inode *raw, struct ext4_inode_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c063f6dc)
Location: fs/ext4/inode.c:53
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
c063f6dc-c063f80c: ext4_inode_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__u32 ext4_inode_csum(struct inode *inode, struct ext4_inode *raw, struct ext4_inode_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a32d0)
Location: fs/ext4/inode.c:53
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
c0000000005a32d0-c0000000005a3534: ext4_inode_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__u32 ext4_inode_csum(struct inode *inode, struct ext4_inode *raw, struct ext4_inode_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe0003084f4)
Location: fs/ext4/inode.c:53
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffe0003084f4-ffffffe00030868e: ext4_inode_csum (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a33c0)
Location: fs/ext4/inode.c:53
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813a33c0-ffffffff813a35a8: ext4_inode_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff81393e50)
Location: fs/ext4/inode.c:53
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff81393e50-ffffffff81394038: ext4_inode_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a0c20)
Location: fs/ext4/inode.c:53
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813a0c20-ffffffff813a0e08: ext4_inode_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b5820)
Location: fs/ext4/inode.c:53
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813b5820-ffffffff813b5a08: ext4_inode_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
