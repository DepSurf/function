# Function: <code>dm_ima_measure_on_device_resume</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dm_ima_measure_on_device_resume(struct mapped_device *md, bool swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ima.c (0)
Location: drivers/md/dm-ima.c:372
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
```
**Symbols:**

```
ffffffff81d29e91-ffffffff81d29e9d: dm_ima_measure_on_device_resume.cold (STB_LOCAL)
ffffffff81a06ce0-ffffffff81a07040: dm_ima_measure_on_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dm_ima_measure_on_device_resume(struct mapped_device *md, bool swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ima.c (0)
Location: drivers/md/dm-ima.c:373
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
```
**Symbols:**

```
ffffffff81ef6199-ffffffff81ef61a5: dm_ima_measure_on_device_resume.cold (STB_LOCAL)
ffffffff81b6ea10-ffffffff81b6ed64: dm_ima_measure_on_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_ima_measure_on_device_resume(struct mapped_device *md, bool swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81d0afb0)
Location: drivers/md/dm-ima.c:370
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
```
**Symbols:**

```
ffffffff81d0afb0-ffffffff81d0b310: dm_ima_measure_on_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_ima_measure_on_device_resume(struct mapped_device *md, bool swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81d740e0)
Location: drivers/md/dm-ima.c:369
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
```
**Symbols:**

```
ffffffff81d740e0-ffffffff81d74440: dm_ima_measure_on_device_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_ima_measure_on_device_resume(struct mapped_device *md, bool swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81e2b1f0)
Location: drivers/md/dm-ima.c:369
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
```
**Symbols:**

```
ffffffff81e2b1f0-ffffffff81e2b550: dm_ima_measure_on_device_resume (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
