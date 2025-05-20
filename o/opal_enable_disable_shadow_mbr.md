# Function: <code>opal_enable_disable_shadow_mbr</code>

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
int opal_enable_disable_shadow_mbr(struct opal_dev *dev, struct opal_mbr_data *opal_mbr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8145aa30)
Location: block/sed-opal.c:2066
Inline: False
Direct callers:
  - block/sed-opal.c:sed_ioctl
```
**Symbols:**

```
ffffffff8145aa30-ffffffff8145ab48: opal_enable_disable_shadow_mbr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int opal_enable_disable_shadow_mbr(struct opal_dev *dev, struct opal_mbr_data *opal_mbr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814867d0)
Location: block/sed-opal.c:2078
Inline: False
Direct callers:
  - block/sed-opal.c:sed_ioctl
```
**Symbols:**

```
ffffffff814867d0-ffffffff814868e8: opal_enable_disable_shadow_mbr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int opal_enable_disable_shadow_mbr(struct opal_dev *dev, struct opal_mbr_data *opal_mbr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814bb720)
Location: block/sed-opal.c:2095
Inline: False
Direct callers:
  - block/sed-opal.c:sed_ioctl
```
**Symbols:**

```
ffffffff814bb720-ffffffff814bb819: opal_enable_disable_shadow_mbr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int opal_enable_disable_shadow_mbr(struct opal_dev *dev, struct opal_mbr_data *opal_mbr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814cfae0)
Location: block/sed-opal.c:2095
Inline: False
Direct callers:
  - block/sed-opal.c:sed_ioctl
```
**Symbols:**

```
ffffffff814cfae0-ffffffff814cfbd9: opal_enable_disable_shadow_mbr (STB_LOCAL)
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
In block/sed-opal.c (ffffffff8150153a)
Location: block/sed-opal.c:2068
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffff8151f46a)
Location: block/sed-opal.c:2085
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffff8157f5db)
Location: block/sed-opal.c:2200
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffff8159c61b)
Location: block/sed-opal.c:2200
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffff815a30cc)
Location: block/sed-opal.c:2200
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffff8160b924)
Location: block/sed-opal.c:2200
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffff816bf994)
Location: block/sed-opal.c:2200
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffff81780b55)
Location: block/sed-opal.c:2266
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffff817c07cd)
Location: block/sed-opal.c:2456
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffff81806f3c)
Location: block/sed-opal.c:2635
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffff800010624d00)
Location: block/sed-opal.c:2085
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (c07cc870)
Location: block/sed-opal.c:2085
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (c0000000007c9e30)
Location: block/sed-opal.c:2085
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffe0004595d2)
Location: block/sed-opal.c:2085
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffff81517a4a)
Location: block/sed-opal.c:2085
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffff81507d5a)
Location: block/sed-opal.c:2085
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffff81513ada)
Location: block/sed-opal.c:2085
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
In block/sed-opal.c (ffffffff8152d29a)
Location: block/sed-opal.c:2085
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
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
</ul>
