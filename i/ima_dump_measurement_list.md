# Function: <code>ima_dump_measurement_list</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_kexec.c (0)
Location: security/integrity/ima/ima_kexec.c:18
Inline: True
Direct callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
**Symbols:**

```
ffffffff81700d10-ffffffff81700f04: ima_dump_measurement_list.constprop.0.isra.0 (STB_LOCAL)
ffffffff82075581-ffffffff82075595: ima_dump_measurement_list.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_kexec.c (0)
Location: security/integrity/ima/ima_kexec.c:18
Inline: True
Direct callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
**Symbols:**

```
ffffffff8173adb0-ffffffff8173afa4: ima_dump_measurement_list.constprop.0.isra.0 (STB_LOCAL)
ffffffff820f50e3-ffffffff820f50f7: ima_dump_measurement_list.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_kexec.c (0)
Location: security/integrity/ima/ima_kexec.c:18
Inline: True
Direct callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
**Symbols:**

```
ffffffff8177b920-ffffffff8177bb14: ima_dump_measurement_list.constprop.0.isra.0 (STB_LOCAL)
ffffffff821d2271-ffffffff821d2285: ima_dump_measurement_list.constprop.0.isra.0.cold (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_dump_measurement_list(long unsigned int *buffer_size, void **buffer, long unsigned int segment_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_kexec.c (c0000000007381e0)
Location: security/integrity/ima/ima_kexec.c:17
Inline: False
Direct callers:
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
**Symbols:**

```
c0000000007381e0-c0000000007383b0: ima_dump_measurement_list (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
