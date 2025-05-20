# Function: <code>__device_driver_unlock</code>

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
void __device_driver_unlock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816dac70)
Location: drivers/base/dd.c:957
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffff816dac70-ffffffff816dacb4: __device_driver_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __device_driver_unlock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816fec30)
Location: drivers/base/dd.c:972
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffff816fec30-ffffffff816fec74: __device_driver_unlock (STB_LOCAL)
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
In drivers/base/dd.c (ffffffff817ba181)
Location: drivers/base/dd.c:946
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
In drivers/base/dd.c (ffffffff817cefd1)
Location: drivers/base/dd.c:992
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
In drivers/base/dd.c (ffffffff817b29e1)
Location: drivers/base/dd.c:1013
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
In drivers/base/dd.c (ffffffff8183be61)
Location: drivers/base/dd.c:1047
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
In drivers/base/dd.c (ffffffff8197e3f6)
Location: drivers/base/dd.c:1066
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
In drivers/base/dd.c (ffffffff81aeb966)
Location: drivers/base/dd.c:1085
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
In drivers/base/dd.c (ffffffff81b39bd6)
Location: drivers/base/dd.c:1107
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
In drivers/base/dd.c (ffffffff81b91696)
Location: drivers/base/dd.c:1107
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
void __device_driver_unlock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108e9bb8)
Location: drivers/base/dd.c:972
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffff8000108e9bb8-ffff8000108e9c0c: __device_driver_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __device_driver_unlock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d7c58)
Location: drivers/base/dd.c:972
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
c09d7c58-c09d7ca0: __device_driver_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __device_driver_unlock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c000000000980940)
Location: drivers/base/dd.c:972
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
c000000000980940-c0000000009809d4: __device_driver_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __device_driver_unlock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057dad8)
Location: drivers/base/dd.c:972
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffe00057dad8-ffffffe00057db2e: __device_driver_unlock (STB_LOCAL)
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
void __device_driver_unlock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816c4420)
Location: drivers/base/dd.c:972
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffff816c4420-ffffffff816c4464: __device_driver_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __device_driver_unlock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8169f6d0)
Location: drivers/base/dd.c:972
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffff8169f6d0-ffffffff8169f714: __device_driver_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __device_driver_unlock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816f28f0)
Location: drivers/base/dd.c:972
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffff816f28f0-ffffffff816f2934: __device_driver_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __device_driver_unlock(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8170d130)
Location: drivers/base/dd.c:972
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__driver_attach_async_helper
  - drivers/base/dd.c:device_driver_attach
```
**Symbols:**

```
ffffffff8170d130-ffffffff8170d174: __device_driver_unlock (STB_LOCAL)
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
