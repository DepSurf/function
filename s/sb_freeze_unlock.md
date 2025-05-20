# Function: <code>sb_freeze_unlock</code>

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
In fs/super.c (ffffffff8120ef88)
Location: fs/super.c:1293
Inline: True
Inline callers:
  - fs/super.c:freeze_super
  - fs/super.c:thaw_super
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
In fs/super.c (ffffffff81235a6a)
Location: fs/super.c:1313
Inline: True
Inline callers:
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff81248629)
Location: fs/super.c:1371
Inline: True
Inline callers:
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff81253f47)
Location: fs/super.c:1413
Inline: True
Inline callers:
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff8127605a)
Location: fs/super.c:1413
Inline: True
Inline callers:
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff8129c586)
Location: fs/super.c:1476
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff812b16c6)
Location: fs/super.c:1462
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff812ce408)
Location: fs/super.c:1618
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff812dfeb8)
Location: fs/super.c:1719
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sb_freeze_unlock(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813177bc)
Location: fs/super.c:1717
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
Direct callers:
  - fs/super.c:freeze_super
```
**Symbols:**

```
ffffffff81316350-ffffffff81316387: sb_freeze_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sb_freeze_unlock(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81322a1c)
Location: fs/super.c:1617
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
Direct callers:
  - fs/super.c:freeze_super
```
**Symbols:**

```
ffffffff81321870-ffffffff813218a7: sb_freeze_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff81328adc)
Location: fs/super.c:1619
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
Direct callers:
  - fs/super.c:freeze_super
```
**Symbols:**

```
ffffffff81327b70-ffffffff81327ba7: sb_freeze_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff813760ac)
Location: fs/super.c:1619
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
Direct callers:
  - fs/super.c:freeze_super
```
**Symbols:**

```
ffffffff81375140-ffffffff8137517b: sb_freeze_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff813f506d)
Location: fs/super.c:1619
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
Direct callers:
  - fs/super.c:freeze_super
```
**Symbols:**

```
ffffffff813f4440-ffffffff813f4485: sb_freeze_unlock.constprop.0 (STB_LOCAL)
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
In fs/super.c (ffffffff8147e215)
Location: fs/super.c:1624
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff814b31c5)
Location: fs/super.c:1641
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff814e4cdf)
Location: fs/super.c:1901
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
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
In fs/super.c (ffff800010386be8)
Location: fs/super.c:1719
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
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
In fs/super.c (c056f484)
Location: fs/super.c:1719
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
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
In fs/super.c (c00000000047cc0c)
Location: fs/super.c:1719
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffe0002593fc)
Location: fs/super.c:1719
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff812d8498)
Location: fs/super.c:1719
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff812c9118)
Location: fs/super.c:1719
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff812d62a8)
Location: fs/super.c:1719
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff812e6e68)
Location: fs/super.c:1719
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
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
</ul>
