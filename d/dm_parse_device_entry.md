# Function: <code>dm_parse_device_entry</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff82908920)
Location: drivers/md/dm-init.c:187
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_parse_devices
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
In drivers/md/dm-init.c (ffffffff82912325)
Location: drivers/md/dm-init.c:187
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_parse_devices
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *dm_parse_device_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff82d24f48)
Location: drivers/md/dm-init.c:187
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_parse_devices
```
**Symbols:**

```
ffffffff82d24f48-ffffffff82d250cb: dm_parse_device_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *dm_parse_device_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff83013479)
Location: drivers/md/dm-init.c:187
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_parse_devices
```
**Symbols:**

```
ffffffff83013479-ffffffff8301366a: dm_parse_device_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *dm_parse_device_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff8321e5a8)
Location: drivers/md/dm-init.c:187
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff8321e5a8-ffffffff8321e799: dm_parse_device_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *dm_parse_device_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff83307aa6)
Location: drivers/md/dm-init.c:187
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff83307aa6-ffffffff83307ce2: dm_parse_device_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *dm_parse_device_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff834c0fd9)
Location: drivers/md/dm-init.c:187
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff834c0fd9-ffffffff834c122d: dm_parse_device_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *dm_parse_device_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff83f000f0)
Location: drivers/md/dm-init.c:193
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff83f000f0-ffffffff83f00444: dm_parse_device_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *dm_parse_device_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff83725f70)
Location: drivers/md/dm-init.c:192
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff83725f70-ffffffff837262c3: dm_parse_device_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *dm_parse_device_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff83959e30)
Location: drivers/md/dm-init.c:192
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff83959e30-ffffffff8395a183: dm_parse_device_entry (STB_LOCAL)
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
In drivers/md/dm-init.c (ffff8000114a0c0c)
Location: drivers/md/dm-init.c:187
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
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
In drivers/md/dm-init.c (c15a3200)
Location: drivers/md/dm-init.c:187
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
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
In drivers/md/dm-init.c (c0000000013b75f4)
Location: drivers/md/dm-init.c:187
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_parse_devices
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
In drivers/md/dm-init.c (ffffffe000038918)
Location: drivers/md/dm-init.c:187
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_parse_devices
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
In drivers/md/dm-init.c (ffffffff828f8139)
Location: drivers/md/dm-init.c:187
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_parse_devices
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
In drivers/md/dm-init.c (ffffffff828efa4b)
Location: drivers/md/dm-init.c:187
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_parse_devices
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff82913387)
Location: drivers/md/dm-init.c:187
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_parse_devices
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
