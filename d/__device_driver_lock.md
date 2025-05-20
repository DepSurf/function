# Function: <code>__device_driver_lock</code>

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
void __device_driver_lock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816dabd0)
Location: drivers/base/dd.c:941
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffff816dabd0-ffffffff816dac19: __device_driver_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __device_driver_lock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816feb90)
Location: drivers/base/dd.c:956
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffff816feb90-ffffffff816febd9: __device_driver_lock (STB_LOCAL)
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
In drivers/base/dd.c (ffffffff817ba1f7)
Location: drivers/base/dd.c:930
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
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
In drivers/base/dd.c (ffffffff817cf047)
Location: drivers/base/dd.c:976
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
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
In drivers/base/dd.c (ffffffff817b2a57)
Location: drivers/base/dd.c:997
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
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
In drivers/base/dd.c (ffffffff8183bee6)
Location: drivers/base/dd.c:1031
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:device_driver_detach
  - drivers/base/dd.c:device_release_driver
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
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
In drivers/base/dd.c (ffffffff8197e395)
Location: drivers/base/dd.c:1050
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
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
In drivers/base/dd.c (ffffffff81aeb905)
Location: drivers/base/dd.c:1069
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
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
In drivers/base/dd.c (ffffffff81b39b75)
Location: drivers/base/dd.c:1091
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
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
In drivers/base/dd.c (ffffffff81b91635)
Location: drivers/base/dd.c:1091
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __device_driver_lock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108e9b00)
Location: drivers/base/dd.c:956
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffff8000108e9b00-ffff8000108e9b5c: __device_driver_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __device_driver_lock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d7bc8)
Location: drivers/base/dd.c:956
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
c09d7bc8-c09d7c10: __device_driver_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __device_driver_lock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c000000000980820)
Location: drivers/base/dd.c:956
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
c000000000980820-c0000000009808ac: __device_driver_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __device_driver_lock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057da40)
Location: drivers/base/dd.c:956
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffe00057da40-ffffffe00057da8c: __device_driver_lock (STB_LOCAL)
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
void __device_driver_lock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816c4380)
Location: drivers/base/dd.c:956
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffff816c4380-ffffffff816c43c9: __device_driver_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __device_driver_lock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8169f630)
Location: drivers/base/dd.c:956
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffff8169f630-ffffffff8169f679: __device_driver_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __device_driver_lock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816f2850)
Location: drivers/base/dd.c:956
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffff816f2850-ffffffff816f2899: __device_driver_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __device_driver_lock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8170d090)
Location: drivers/base/dd.c:956
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffff8170d090-ffffffff8170d0d9: __device_driver_lock (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
