# Function: <code>dm_ima_reset_data</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dm_ima_reset_data(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81a0740f)
Location: drivers/md/dm-ima.c:169
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81a06650-ffffffff81a06695: dm_ima_reset_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dm_ima_reset_data(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81b6e350)
Location: drivers/md/dm-ima.c:170
Inline: True
Direct callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81b6e350-ffffffff81b6e3a1: dm_ima_reset_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_ima_reset_data(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81d0a8b0)
Location: drivers/md/dm-ima.c:170
Inline: False
Direct callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81d0a8b0-ffffffff81d0a901: dm_ima_reset_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_ima_reset_data(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81d739f0)
Location: drivers/md/dm-ima.c:169
Inline: False
Direct callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81d739f0-ffffffff81d73a41: dm_ima_reset_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_ima_reset_data(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81e2ab00)
Location: drivers/md/dm-ima.c:169
Inline: False
Direct callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_device_remove
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81e2ab00-ffffffff81e2ab51: dm_ima_reset_data (STB_GLOBAL)
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
