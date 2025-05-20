# Function: <code>cdrom_mrw_open_write</code>

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
In drivers/cdrom/cdrom.c (ffffffff81600e98)
Location: drivers/cdrom/cdrom.c:777
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff81660cdb)
Location: drivers/cdrom/cdrom.c:777
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff8168eacb)
Location: drivers/cdrom/cdrom.c:777
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff816a3c32)
Location: drivers/cdrom/cdrom.c:775
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff8170ef7e)
Location: drivers/cdrom/cdrom.c:775
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff8174dd45)
Location: drivers/cdrom/cdrom.c:775
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff81771f75)
Location: drivers/cdrom/cdrom.c:775
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff817b0339)
Location: drivers/cdrom/cdrom.c:776
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff817e0668)
Location: drivers/cdrom/cdrom.c:776
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cdrom_mrw_open_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:779
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
```
**Symbols:**

```
ffffffff818af1f0-ffffffff818af265: cdrom_mrw_open_write (STB_LOCAL)
ffffffff818b0f39-ffffffff818b0f9c: cdrom_mrw_open_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cdrom_mrw_open_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:779
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
```
**Symbols:**

```
ffffffff818bdf70-ffffffff818bdfe5: cdrom_mrw_open_write (STB_LOCAL)
ffffffff81c1a72f-ffffffff81c1a792: cdrom_mrw_open_write.cold (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffffffff818a119a)
Location: drivers/cdrom/cdrom.c:779
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
In drivers/cdrom/cdrom.c (ffffffff819359e6)
Location: drivers/cdrom/cdrom.c:779
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
In drivers/cdrom/cdrom.c (ffffffff81a8e6c2)
Location: drivers/cdrom/cdrom.c:779
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
In drivers/cdrom/cdrom.c (ffffffff81c0fbe2)
Location: drivers/cdrom/cdrom.c:779
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
In drivers/cdrom/cdrom.c (ffffffff81c754bd)
Location: drivers/cdrom/cdrom.c:780
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
In drivers/cdrom/cdrom.c (ffffffff81d29ebd)
Location: drivers/cdrom/cdrom.c:780
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
In drivers/cdrom/cdrom.c (ffff800010a0cf88)
Location: drivers/cdrom/cdrom.c:776
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cdrom_mrw_open_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c0ae47d8)
Location: drivers/cdrom/cdrom.c:776
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
c0ae47d8-c0ae49d4: cdrom_mrw_open_write (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (c000000000ac4ba0)
Location: drivers/cdrom/cdrom.c:776
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffe000634740)
Location: drivers/cdrom/cdrom.c:776
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff81798a48)
Location: drivers/cdrom/cdrom.c:776
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff8178a718)
Location: drivers/cdrom/cdrom.c:776
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff817d54e8)
Location: drivers/cdrom/cdrom.c:776
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
In drivers/cdrom/cdrom.c (ffffffff817ef788)
Location: drivers/cdrom/cdrom.c:776
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open
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
<b>Arch</b>
<ul>
</ul>
