# Function: <code>inode_get_rsv_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
qsize_t inode_get_rsv_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81270e70)
Location: fs/quota/dquot.c:1604
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_transfer
```
**Symbols:**

```
ffffffff81270e70-ffffffff81270ebd: inode_get_rsv_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
qsize_t inode_get_rsv_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8129d360)
Location: fs/quota/dquot.c:1612
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff8129d360-ffffffff8129d3b0: inode_get_rsv_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
qsize_t inode_get_rsv_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812b2ca0)
Location: fs/quota/dquot.c:1609
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff812b2ca0-ffffffff812b2cf0: inode_get_rsv_space (STB_LOCAL)
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
In fs/quota/dquot.c (ffffffff812c19b9)
Location: fs/quota/dquot.c:1635
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
Direct callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff812c0420-ffffffff812c045b: inode_get_rsv_space.part.20 (STB_LOCAL)
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
In fs/quota/dquot.c (ffffffff812e57cb)
Location: fs/quota/dquot.c:1617
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_initialize
Direct callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff812e40b0-ffffffff812e40fd: inode_get_rsv_space.part.18 (STB_LOCAL)
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
In fs/quota/dquot.c (ffffffff81312c7e)
Location: fs/quota/dquot.c:1614
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_initialize
Direct callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff81310510-ffffffff8131055d: inode_get_rsv_space.part.23 (STB_LOCAL)
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
In fs/quota/dquot.c (ffffffff81329c0e)
Location: fs/quota/dquot.c:1614
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_initialize
Direct callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff81327570-ffffffff813275bd: inode_get_rsv_space.part.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813526d5)
Location: fs/quota/dquot.c:1624
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8136aa55)
Location: fs/quota/dquot.c:1626
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b2c60)
Location: fs/quota/dquot.c:1624
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c4250)
Location: fs/quota/dquot.c:1625
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813caf29)
Location: fs/quota/dquot.c:1623
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8141bd3e)
Location: fs/quota/dquot.c:1628
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81491651)
Location: fs/quota/dquot.c:1638
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81525281)
Location: fs/quota/dquot.c:1638
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8155d701)
Location: fs/quota/dquot.c:1696
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81593de1)
Location: fs/quota/dquot.c:1650
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffff800010433868)
Location: fs/quota/dquot.c:1626
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
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
In fs/quota/dquot.c (c05f986c)
Location: fs/quota/dquot.c:1626
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
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
In fs/quota/dquot.c (c000000000542588)
Location: fs/quota/dquot.c:1626
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
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
In fs/quota/dquot.c (ffffffe0002cf0b8)
Location: fs/quota/dquot.c:1626
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81363035)
Location: fs/quota/dquot.c:1626
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81353cd5)
Location: fs/quota/dquot.c:1626
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81360b05)
Location: fs/quota/dquot.c:1626
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81371d93)
Location: fs/quota/dquot.c:1626
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_initialize
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
</ul>
