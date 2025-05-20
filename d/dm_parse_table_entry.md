# Function: <code>dm_parse_table_entry</code>

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
In drivers/md/dm-init.c (ffffffff82908a23)
Location: drivers/md/dm-init.c:106
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
In drivers/md/dm-init.c (ffffffff82912428)
Location: drivers/md/dm-init.c:106
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
char *dm_parse_table_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff82d24dee)
Location: drivers/md/dm-init.c:106
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_parse_device_entry
```
**Symbols:**

```
ffffffff82d24dee-ffffffff82d24f48: dm_parse_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *dm_parse_table_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff8301331f)
Location: drivers/md/dm-init.c:106
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_parse_device_entry
```
**Symbols:**

```
ffffffff8301331f-ffffffff83013479: dm_parse_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *dm_parse_table_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff8321e44e)
Location: drivers/md/dm-init.c:106
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_parse_device_entry
```
**Symbols:**

```
ffffffff8321e44e-ffffffff8321e5a8: dm_parse_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *dm_parse_table_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff8330789b)
Location: drivers/md/dm-init.c:106
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_parse_device_entry
```
**Symbols:**

```
ffffffff8330789b-ffffffff83307aa6: dm_parse_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *dm_parse_table_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff834c0d72)
Location: drivers/md/dm-init.c:106
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_parse_device_entry
```
**Symbols:**

```
ffffffff834c0d72-ffffffff834c0fd9: dm_parse_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *dm_parse_table_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff83effd80)
Location: drivers/md/dm-init.c:112
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_parse_device_entry
```
**Symbols:**

```
ffffffff83effd80-ffffffff83f000de: dm_parse_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *dm_parse_table_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff83725c00)
Location: drivers/md/dm-init.c:111
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_parse_device_entry
```
**Symbols:**

```
ffffffff83725c00-ffffffff83725f5e: dm_parse_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *dm_parse_table_entry(struct dm_device *dev, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff83959a90)
Location: drivers/md/dm-init.c:111
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_parse_device_entry
```
**Symbols:**

```
ffffffff83959a90-ffffffff83959e1d: dm_parse_table_entry (STB_LOCAL)
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
In drivers/md/dm-init.c (ffff8000114a0d10)
Location: drivers/md/dm-init.c:106
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
In drivers/md/dm-init.c (c15a3304)
Location: drivers/md/dm-init.c:106
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
In drivers/md/dm-init.c (c0000000013b7710)
Location: drivers/md/dm-init.c:106
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
In drivers/md/dm-init.c (ffffffe0000389da)
Location: drivers/md/dm-init.c:106
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
In drivers/md/dm-init.c (ffffffff828f823c)
Location: drivers/md/dm-init.c:106
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
In drivers/md/dm-init.c (ffffffff828efb4e)
Location: drivers/md/dm-init.c:106
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
In drivers/md/dm-init.c (ffffffff8291348a)
Location: drivers/md/dm-init.c:106
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
