# Function: <code>devm_aperture_acquire_release</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devm_aperture_acquire_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/aperture.c (ffffffff8192ed8d)
Location: drivers/video/aperture.c:150
Inline: True
Inline callers:
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
```
**Symbols:**

```
ffffffff8192ea30-ffffffff8192ea9b: devm_aperture_acquire_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devm_aperture_acquire_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/aperture.c (ffffffff81973064)
Location: drivers/video/aperture.c:150
Inline: True
Inline callers:
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
```
**Symbols:**

```
ffffffff81972d60-ffffffff81972dcb: devm_aperture_acquire_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devm_aperture_acquire_release(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/aperture.c (ffffffff819bd0d4)
Location: drivers/video/aperture.c:150
Inline: True
Inline callers:
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
```
**Symbols:**

```
ffffffff819bcdd0-ffffffff819bce3b: devm_aperture_acquire_release (STB_LOCAL)
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
