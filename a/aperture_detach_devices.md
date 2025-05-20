# Function: <code>aperture_detach_devices</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void aperture_detach_devices(resource_size_t base, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/aperture.c (ffffffff8192e950)
Location: drivers/video/aperture.c:247
Inline: False
Direct callers:
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
```
**Symbols:**

```
ffffffff8192e950-ffffffff8192ea1c: aperture_detach_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aperture_detach_devices(resource_size_t base, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/aperture.c (ffffffff81972be0)
Location: drivers/video/aperture.c:247
Inline: False
Direct callers:
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
  - drivers/video/aperture.c:aperture_remove_conflicting_devices
```
**Symbols:**

```
ffffffff81972be0-ffffffff81972cac: aperture_detach_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aperture_detach_devices(resource_size_t base, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/aperture.c (ffffffff819bcc50)
Location: drivers/video/aperture.c:247
Inline: False
Direct callers:
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
  - drivers/video/aperture.c:aperture_remove_conflicting_devices
```
**Symbols:**

```
ffffffff819bcc50-ffffffff819bcd1c: aperture_detach_devices (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
