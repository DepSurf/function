# Function: <code>dm_ima_measure_on_device_remove</code>

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
void dm_ima_measure_on_device_remove(struct mapped_device *md, bool remove_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ima.c (0)
Location: drivers/md/dm-ima.c:477
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
```
**Symbols:**

```
ffffffff81d29e9d-ffffffff81d29ea9: dm_ima_measure_on_device_remove.cold (STB_LOCAL)
ffffffff81a07040-ffffffff81a0752b: dm_ima_measure_on_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dm_ima_measure_on_device_remove(struct mapped_device *md, bool remove_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ima.c (0)
Location: drivers/md/dm-ima.c:478
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
```
**Symbols:**

```
ffffffff81ef61a5-ffffffff81ef61b1: dm_ima_measure_on_device_remove.cold (STB_LOCAL)
ffffffff81b6ed70-ffffffff81b6f250: dm_ima_measure_on_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_ima_measure_on_device_remove(struct mapped_device *md, bool remove_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81d0b320)
Location: drivers/md/dm-ima.c:475
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
```
**Symbols:**

```
ffffffff81d0b320-ffffffff81d0b80c: dm_ima_measure_on_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_ima_measure_on_device_remove(struct mapped_device *md, bool remove_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81d74450)
Location: drivers/md/dm-ima.c:474
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
```
**Symbols:**

```
ffffffff81d74450-ffffffff81d7493c: dm_ima_measure_on_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_ima_measure_on_device_remove(struct mapped_device *md, bool remove_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81e2b560)
Location: drivers/md/dm-ima.c:474
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_remove
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
```
**Symbols:**

```
ffffffff81e2b560-ffffffff81e2ba4c: dm_ima_measure_on_device_remove (STB_GLOBAL)
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
