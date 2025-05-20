# Function: <code>ext4_get_verity_descriptor_location</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813ef0cc)
Location: fs/ext4/verity.c:252
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/verity.c (ffffffff8143c4b0)
Location: fs/ext4/verity.c:255
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff8143c4b0-ffffffff8143c66c: ext4_get_verity_descriptor_location.constprop.0 (STB_LOCAL)
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
In fs/ext4/verity.c (ffffffff81458800)
Location: fs/ext4/verity.c:276
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff81458800-ffffffff814589bc: ext4_get_verity_descriptor_location.constprop.0 (STB_LOCAL)
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
In fs/ext4/verity.c (ffffffff8145e170)
Location: fs/ext4/verity.c:270
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff8145e170-ffffffff8145e334: ext4_get_verity_descriptor_location.constprop.0 (STB_LOCAL)
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
In fs/ext4/verity.c (0)
Location: fs/ext4/verity.c:270
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff814b3690-ffffffff814b3861: ext4_get_verity_descriptor_location.constprop.0 (STB_LOCAL)
ffffffff81cce400-ffffffff81cce445: ext4_get_verity_descriptor_location.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/verity.c (0)
Location: fs/ext4/verity.c:271
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff8153c2c0-ffffffff8153c49f: ext4_get_verity_descriptor_location.constprop.0 (STB_LOCAL)
ffffffff81e81461-ffffffff81e814a6: ext4_get_verity_descriptor_location.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/verity.c (0)
Location: fs/ext4/verity.c:271
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff815da990-ffffffff815dab5f: ext4_get_verity_descriptor_location.constprop.0 (STB_LOCAL)
ffffffff82071305-ffffffff8207134a: ext4_get_verity_descriptor_location.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/verity.c (0)
Location: fs/ext4/verity.c:269
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff81612630-ffffffff816127ff: ext4_get_verity_descriptor_location.constprop.0 (STB_LOCAL)
ffffffff820f0fc9-ffffffff820f100f: ext4_get_verity_descriptor_location.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/verity.c (0)
Location: fs/ext4/verity.c:269
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff8164b3e0-ffffffff8164b5af: ext4_get_verity_descriptor_location.constprop.0 (STB_LOCAL)
ffffffff821ce17e-ffffffff821ce1c4: ext4_get_verity_descriptor_location.constprop.0.cold (STB_LOCAL)
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
In fs/ext4/verity.c (ffff8000104c83f8)
Location: fs/ext4/verity.c:252
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/verity.c (c068c34c)
Location: fs/ext4/verity.c:252
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/verity.c (c0000000006010f8)
Location: fs/ext4/verity.c:252
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/verity.c (ffffffe0003422a4)
Location: fs/ext4/verity.c:252
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/verity.c (ffffffff813e76ac)
Location: fs/ext4/verity.c:252
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/verity.c (ffffffff813d812c)
Location: fs/ext4/verity.c:252
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/verity.c (ffffffff813e4a2c)
Location: fs/ext4/verity.c:252
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
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
In fs/ext4/verity.c (ffffffff813f9e7c)
Location: fs/ext4/verity.c:252
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
</details>
</li>
</ul>

## Differences
