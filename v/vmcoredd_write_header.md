# Function: <code>vmcoredd_write_header</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813292cf)
Location: fs/proc/vmcore.c:1317
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
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
In fs/proc/vmcore.c (ffffffff8134057f)
Location: fs/proc/vmcore.c:1339
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
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
In fs/proc/vmcore.c (ffffffff81368900)
Location: fs/proc/vmcore.c:1344
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
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
In fs/proc/vmcore.c (ffffffff81380b50)
Location: fs/proc/vmcore.c:1344
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
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
In fs/proc/vmcore.c (ffffffff813cb1a0)
Location: fs/proc/vmcore.c:1344
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
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
In fs/proc/vmcore.c (ffffffff813dce40)
Location: fs/proc/vmcore.c:1344
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
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
In fs/proc/vmcore.c (ffffffff813e3db7)
Location: fs/proc/vmcore.c:1344
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
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
In fs/proc/vmcore.c (ffffffff814359db)
Location: fs/proc/vmcore.c:1348
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
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
In fs/proc/vmcore.c (ffffffff814afdc0)
Location: fs/proc/vmcore.c:1366
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vmcoredd_write_header(void *buf, struct vmcoredd_data *data, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81546520)
Location: fs/proc/vmcore.c:1365
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
**Symbols:**

```
ffffffff81546520-ffffffff81546585: vmcoredd_write_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vmcoredd_write_header(void *buf, struct vmcoredd_data *data, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8157e0e0)
Location: fs/proc/vmcore.c:1364
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
**Symbols:**

```
ffffffff8157e0e0-ffffffff8157e145: vmcoredd_write_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vmcoredd_write_header(void *buf, struct vmcoredd_data *data, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff815b6b20)
Location: fs/proc/vmcore.c:1364
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
**Symbols:**

```
ffffffff815b6b20-ffffffff815b6b85: vmcoredd_write_header (STB_LOCAL)
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
In fs/proc/vmcore.c (ffff80001044e810)
Location: fs/proc/vmcore.c:1344
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
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
In fs/proc/vmcore.c (c0611b08)
Location: fs/proc/vmcore.c:1344
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
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
In fs/proc/vmcore.c (c00000000056641c)
Location: fs/proc/vmcore.c:1344
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In fs/proc/vmcore.c (ffffffff81379130)
Location: fs/proc/vmcore.c:1344
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
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
In fs/proc/vmcore.c (ffffffff81369c00)
Location: fs/proc/vmcore.c:1344
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
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
In fs/proc/vmcore.c (ffffffff81376c00)
Location: fs/proc/vmcore.c:1344
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
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
In fs/proc/vmcore.c (ffffffff8138a6b0)
Location: fs/proc/vmcore.c:1344
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
