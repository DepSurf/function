# Function: <code>filter_device</code>

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
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool filter_device(struct hash_cell *hc, const char *pfx_name, const char *pfx_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:543
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
```
**Symbols:**

```
ffffffff81968cc0-ffffffff81968d7e: filter_device (STB_LOCAL)
ffffffff81c1a446-ffffffff81c1a452: filter_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool filter_device(struct hash_cell *hc, const char *pfx_name, const char *pfx_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:548
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
```
**Symbols:**

```
ffffffff81a10ee0-ffffffff81a10f9e: filter_device (STB_LOCAL)
ffffffff81d2a1f3-ffffffff81d2a1ff: filter_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool filter_device(struct hash_cell *hc, const char *pfx_name, const char *pfx_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:549
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
```
**Symbols:**

```
ffffffff81b795a0-ffffffff81b79674: filter_device (STB_LOCAL)
ffffffff81ef642d-ffffffff81ef6439: filter_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool filter_device(struct hash_cell *hc, const char *pfx_name, const char *pfx_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d16fe0)
Location: drivers/md/dm-ioctl.c:549
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
```
**Symbols:**

```
ffffffff81d16fe0-ffffffff81d170bc: filter_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool filter_device(struct hash_cell *hc, const char *pfx_name, const char *pfx_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d80270)
Location: drivers/md/dm-ioctl.c:567
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
```
**Symbols:**

```
ffffffff81d80270-ffffffff81d8034c: filter_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool filter_device(struct hash_cell *hc, const char *pfx_name, const char *pfx_uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81e378d0)
Location: drivers/md/dm-ioctl.c:567
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
```
**Symbols:**

```
ffffffff81e378d0-ffffffff81e379ac: filter_device (STB_LOCAL)
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
