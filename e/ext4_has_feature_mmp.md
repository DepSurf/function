# Function: <code>ext4_has_feature_mmp</code>

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
In fs/ext4/super.c (ffffffff812bb63f)
Location: fs/ext4/ext4.h:1713
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff812ea5ca)
Location: fs/ext4/ext4.h:1781
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff8130036f)
Location: fs/ext4/ext4.h:1766
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff813351c0)
Location: fs/ext4/ext4.h:1771
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff813596c8)
Location: fs/ext4/ext4.h:1731
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff81388001)
Location: fs/ext4/ext4.h:1734
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff813a0bcb)
Location: fs/ext4/ext4.h:1747
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff813cb447)
Location: fs/ext4/ext4.h:1767
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff813e47fe)
Location: fs/ext4/ext4.h:1824
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff81431c8a)
Location: fs/ext4/ext4.h:1921
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff8144aaa8)
Location: fs/ext4/ext4.h:2046
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mmp.c (ffffffff81427b99)
Location: fs/ext4/ext4.h:2055
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8144fee1)
Location: fs/ext4/ext4.h:2055
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mmp.c (ffffffff8147b879)
Location: fs/ext4/ext4.h:2122
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff814a6b59)
Location: fs/ext4/ext4.h:2122
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mmp.c (ffffffff814fdd69)
Location: fs/ext4/ext4.h:2124
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8152b5a7)
Location: fs/ext4/ext4.h:2124
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mmp.c (ffffffff8159855a)
Location: fs/ext4/ext4.h:2134
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff815ca5d7)
Location: fs/ext4/ext4.h:2134
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mmp.c (ffffffff815cf02a)
Location: fs/ext4/ext4.h:2128
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff816025a0)
Location: fs/ext4/ext4.h:2128
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mmp.c (ffffffff816078c9)
Location: fs/ext4/ext4.h:2146
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8163b396)
Location: fs/ext4/ext4.h:2146
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
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
In fs/ext4/super.c (ffff8000104bdda4)
Location: fs/ext4/ext4.h:1824
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (c06814f4)
Location: fs/ext4/ext4.h:1824
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (c0000000005f4014)
Location: fs/ext4/ext4.h:1824
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffe000339896)
Location: fs/ext4/ext4.h:1824
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff813dcdde)
Location: fs/ext4/ext4.h:1824
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff813cd85e)
Location: fs/ext4/ext4.h:1824
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff813da27e)
Location: fs/ext4/ext4.h:1824
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff813ef55e)
Location: fs/ext4/ext4.h:1824
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
</ul>

## Differences
