# Function: <code>ext4_acl_to_disk</code>

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
In fs/ext4/acl.c (ffffffff812e3eae)
Location: fs/ext4/acl.c:93
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (ffffffff81313e70)
Location: fs/ext4/acl.c:93
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (ffffffff81329e13)
Location: fs/ext4/acl.c:93
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (ffffffff8133f010)
Location: fs/ext4/acl.c:94
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (ffffffff81363620)
Location: fs/ext4/acl.c:95
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (ffffffff81391da7)
Location: fs/ext4/acl.c:95
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (ffffffff813aa9e7)
Location: fs/ext4/acl.c:95
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (ffffffff813d4be6)
Location: fs/ext4/acl.c:95
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (ffffffff813ee2be)
Location: fs/ext4/acl.c:91
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/acl.c (ffffffff8143b2a0)
Location: fs/ext4/acl.c:91
Inline: True
Direct callers:
  - fs/ext4/acl.c:__ext4_set_acl
```
**Symbols:**

```
ffffffff8143b2a0-ffffffff8143b3d0: ext4_acl_to_disk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/acl.c (ffffffff814575d0)
Location: fs/ext4/acl.c:91
Inline: True
Direct callers:
  - fs/ext4/acl.c:__ext4_set_acl
```
**Symbols:**

```
ffffffff814575d0-ffffffff81457700: ext4_acl_to_disk.constprop.0 (STB_LOCAL)
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
In fs/ext4/acl.c (ffffffff8145cf60)
Location: fs/ext4/acl.c:91
Inline: True
Direct callers:
  - fs/ext4/acl.c:__ext4_set_acl
```
**Symbols:**

```
ffffffff8145cf60-ffffffff8145d0a7: ext4_acl_to_disk.constprop.0 (STB_LOCAL)
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
In fs/ext4/acl.c (ffffffff814b2400)
Location: fs/ext4/acl.c:91
Inline: True
Direct callers:
  - fs/ext4/acl.c:__ext4_set_acl
```
**Symbols:**

```
ffffffff814b2400-ffffffff814b2547: ext4_acl_to_disk.constprop.0 (STB_LOCAL)
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
In fs/ext4/acl.c (ffffffff8153b020)
Location: fs/ext4/acl.c:91
Inline: True
Direct callers:
  - fs/ext4/acl.c:__ext4_set_acl
```
**Symbols:**

```
ffffffff8153b020-ffffffff8153b18c: ext4_acl_to_disk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/acl.c (ffffffff815d9600)
Location: fs/ext4/acl.c:91
Inline: True
Direct callers:
  - fs/ext4/acl.c:__ext4_set_acl
```
**Symbols:**

```
ffffffff815d9600-ffffffff815d976c: ext4_acl_to_disk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/acl.c (ffffffff816111c0)
Location: fs/ext4/acl.c:91
Inline: True
Direct callers:
  - fs/ext4/acl.c:__ext4_set_acl
```
**Symbols:**

```
ffffffff816111c0-ffffffff81611328: ext4_acl_to_disk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/acl.c (ffffffff81649f80)
Location: fs/ext4/acl.c:91
Inline: True
Direct callers:
  - fs/ext4/acl.c:__ext4_set_acl
```
**Symbols:**

```
ffffffff81649f80-ffffffff8164a0e8: ext4_acl_to_disk.constprop.0 (STB_LOCAL)
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
In fs/ext4/acl.c (ffff8000104c76c4)
Location: fs/ext4/acl.c:91
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (c068b31c)
Location: fs/ext4/acl.c:91
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (c0000000005ff9b8)
Location: fs/ext4/acl.c:91
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (ffffffe00034160a)
Location: fs/ext4/acl.c:91
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (ffffffff813e689e)
Location: fs/ext4/acl.c:91
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (ffffffff813d731e)
Location: fs/ext4/acl.c:91
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (ffffffff813e3c1e)
Location: fs/ext4/acl.c:91
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
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
In fs/ext4/acl.c (ffffffff813f902e)
Location: fs/ext4/acl.c:91
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
```
</details>
</li>
</ul>

## Differences
