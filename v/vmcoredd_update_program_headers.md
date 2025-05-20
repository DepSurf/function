# Function: <code>vmcoredd_update_program_headers</code>

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
In fs/proc/vmcore.c (ffffffff813293ab)
Location: fs/proc/vmcore.c:1340
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
In fs/proc/vmcore.c (ffffffff8134065b)
Location: fs/proc/vmcore.c:1362
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
In fs/proc/vmcore.c (ffffffff813689e4)
Location: fs/proc/vmcore.c:1367
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
In fs/proc/vmcore.c (ffffffff81380c34)
Location: fs/proc/vmcore.c:1367
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vmcoredd_update_program_headers(char *elfptr, size_t elfnotesz, size_t vmcoreddsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813cb000)
Location: fs/proc/vmcore.c:1367
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
**Symbols:**

```
ffffffff813cb000-ffffffff813cb0ea: vmcoredd_update_program_headers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vmcoredd_update_program_headers(char *elfptr, size_t elfnotesz, size_t vmcoreddsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813dccc0)
Location: fs/proc/vmcore.c:1367
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_add_device_dump
```
**Symbols:**

```
ffffffff813dccc0-ffffffff813dcdaa: vmcoredd_update_program_headers (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff813e3bde)
Location: fs/proc/vmcore.c:1367
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcoredd_update_size
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
In fs/proc/vmcore.c (ffffffff8143578e)
Location: fs/proc/vmcore.c:1371
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcoredd_update_size
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
In fs/proc/vmcore.c (ffffffff814afa1e)
Location: fs/proc/vmcore.c:1389
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcoredd_update_size
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
In fs/proc/vmcore.c (ffffffff815461ce)
Location: fs/proc/vmcore.c:1388
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcoredd_update_size
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
In fs/proc/vmcore.c (ffffffff8157dd8e)
Location: fs/proc/vmcore.c:1387
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcoredd_update_size
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
In fs/proc/vmcore.c (ffffffff815b67ce)
Location: fs/proc/vmcore.c:1387
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcoredd_update_size
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
In fs/proc/vmcore.c (ffff80001044e8c4)
Location: fs/proc/vmcore.c:1367
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
In fs/proc/vmcore.c (c0611c18)
Location: fs/proc/vmcore.c:1367
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
In fs/proc/vmcore.c (c0000000005664f0)
Location: fs/proc/vmcore.c:1367
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
In fs/proc/vmcore.c (ffffffff81379214)
Location: fs/proc/vmcore.c:1367
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
In fs/proc/vmcore.c (ffffffff81369ce4)
Location: fs/proc/vmcore.c:1367
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
In fs/proc/vmcore.c (ffffffff81376ce4)
Location: fs/proc/vmcore.c:1367
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
In fs/proc/vmcore.c (ffffffff8138a794)
Location: fs/proc/vmcore.c:1367
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
