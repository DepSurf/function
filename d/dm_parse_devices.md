# Function: <code>dm_parse_devices</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int dm_parse_devices(struct list_head *devices, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff82908874)
Location: drivers/md/dm-init.c:232
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff82908874-ffffffff82908be4: dm_parse_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dm_parse_devices(struct list_head *devices, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff82912279)
Location: drivers/md/dm-init.c:232
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff82912279-ffffffff829125e9: dm_parse_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dm_parse_devices(struct list_head *devices, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff82d250cb)
Location: drivers/md/dm-init.c:232
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff82d250cb-ffffffff82d2519f: dm_parse_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dm_parse_devices(struct list_head *devices, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff8301366a)
Location: drivers/md/dm-init.c:232
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff8301366a-ffffffff8301373e: dm_parse_devices (STB_LOCAL)
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
In drivers/md/dm-init.c (ffffffff8321e82d)
Location: drivers/md/dm-init.c:232
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
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
In drivers/md/dm-init.c (ffffffff83307d76)
Location: drivers/md/dm-init.c:232
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
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
In drivers/md/dm-init.c (ffffffff834c12be)
Location: drivers/md/dm-init.c:232
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
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
In drivers/md/dm-init.c (ffffffff83f004d3)
Location: drivers/md/dm-init.c:238
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
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
In drivers/md/dm-init.c (ffffffff83726353)
Location: drivers/md/dm-init.c:237
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
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
In drivers/md/dm-init.c (ffffffff8395a213)
Location: drivers/md/dm-init.c:237
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
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
In drivers/md/dm-init.c (0)
Location: drivers/md/dm-init.c:232
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
In drivers/md/dm-init.c (0)
Location: drivers/md/dm-init.c:232
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_parse_devices(struct list_head *devices, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (c0000000013b74dc)
Location: drivers/md/dm-init.c:232
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
c0000000013b74dc-c0000000013b7914: dm_parse_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_parse_devices(struct list_head *devices, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffe00003887c)
Location: drivers/md/dm-init.c:232
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffe00003887c-ffffffe000038b86: dm_parse_devices (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int dm_parse_devices(struct list_head *devices, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff828f808d)
Location: drivers/md/dm-init.c:232
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff828f808d-ffffffff828f83fd: dm_parse_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dm_parse_devices(struct list_head *devices, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff828ef99f)
Location: drivers/md/dm-init.c:232
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff828ef99f-ffffffff828efd0f: dm_parse_devices (STB_LOCAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dm_parse_devices(struct list_head *devices, char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-init.c (ffffffff829132db)
Location: drivers/md/dm-init.c:232
Inline: False
Direct callers:
  - drivers/md/dm-init.c:dm_init_init
```
**Symbols:**

```
ffffffff829132db-ffffffff8291364b: dm_parse_devices (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
