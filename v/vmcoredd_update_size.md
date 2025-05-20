# Function: <code>vmcoredd_update_size</code>

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
In fs/proc/vmcore.c (ffffffff81329378)
Location: fs/proc/vmcore.c:1402
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
In fs/proc/vmcore.c (ffffffff81340628)
Location: fs/proc/vmcore.c:1424
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
In fs/proc/vmcore.c (ffffffff813689b0)
Location: fs/proc/vmcore.c:1429
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
In fs/proc/vmcore.c (ffffffff81380c00)
Location: fs/proc/vmcore.c:1429
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
In fs/proc/vmcore.c (ffffffff813cb250)
Location: fs/proc/vmcore.c:1429
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
In fs/proc/vmcore.c (ffffffff813dcef0)
Location: fs/proc/vmcore.c:1429
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vmcoredd_update_size(size_t dump_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813e3ba0)
Location: fs/proc/vmcore.c:1429
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
**Symbols:**

```
ffffffff813e3ba0-ffffffff813e3d24: vmcoredd_update_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vmcoredd_update_size(size_t dump_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81435750)
Location: fs/proc/vmcore.c:1433
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
**Symbols:**

```
ffffffff81435750-ffffffff814358da: vmcoredd_update_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vmcoredd_update_size(size_t dump_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff814af9e0)
Location: fs/proc/vmcore.c:1451
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
**Symbols:**

```
ffffffff814af9e0-ffffffff814afb8a: vmcoredd_update_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vmcoredd_update_size(size_t dump_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81546190)
Location: fs/proc/vmcore.c:1450
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
**Symbols:**

```
ffffffff81546190-ffffffff8154633a: vmcoredd_update_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vmcoredd_update_size(size_t dump_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8157dd50)
Location: fs/proc/vmcore.c:1449
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
**Symbols:**

```
ffffffff8157dd50-ffffffff8157def2: vmcoredd_update_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vmcoredd_update_size(size_t dump_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff815b6790)
Location: fs/proc/vmcore.c:1449
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
**Symbols:**

```
ffffffff815b6790-ffffffff815b6932: vmcoredd_update_size (STB_LOCAL)
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
In fs/proc/vmcore.c (ffff80001044e8a4)
Location: fs/proc/vmcore.c:1429
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
In fs/proc/vmcore.c (c0611bdc)
Location: fs/proc/vmcore.c:1429
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
In fs/proc/vmcore.c (c0000000005664c4)
Location: fs/proc/vmcore.c:1429
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
In fs/proc/vmcore.c (ffffffff813791e0)
Location: fs/proc/vmcore.c:1429
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
In fs/proc/vmcore.c (ffffffff81369cb0)
Location: fs/proc/vmcore.c:1429
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
In fs/proc/vmcore.c (ffffffff81376cb0)
Location: fs/proc/vmcore.c:1429
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
In fs/proc/vmcore.c (ffffffff8138a760)
Location: fs/proc/vmcore.c:1429
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
