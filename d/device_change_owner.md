# Function: <code>device_change_owner</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f9be0)
Location: drivers/base/core.c:3231
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff816f9be0-ffffffff816f9d5c: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b2bc0)
Location: drivers/base/core.c:3699
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff817b2bc0-ffffffff817b2d3c: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c7650)
Location: drivers/base/core.c:4111
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff817c7650-ffffffff817c77cc: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aaac0)
Location: drivers/base/core.c:4338
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff817aaac0-ffffffff817aac3c: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81833c80)
Location: drivers/base/core.c:4403
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff81833c80-ffffffff81833dfc: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81975480)
Location: drivers/base/core.c:4437
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff81975480-ffffffff8197561b: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae0cb0)
Location: drivers/base/core.c:4656
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff81ae0cb0-ffffffff81ae0e4b: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2eee0)
Location: drivers/base/core.c:4662
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff81b2eee0-ffffffff81b2f09c: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b866e0)
Location: drivers/base/core.c:4675
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff81b866e0-ffffffff81b8689c: device_change_owner (STB_GLOBAL)
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
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e4070)
Location: drivers/base/core.c:3231
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffff8000108e4070-ffff8000108e4210: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d2b9c)
Location: drivers/base/core.c:3231
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
c09d2b9c-c09d2d30: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000979490)
Location: drivers/base/core.c:3231
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
c000000000979490-c0000000009796a8: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe0005790c4)
Location: drivers/base/core.c:3231
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffe0005790c4-ffffffe000579202: device_change_owner (STB_GLOBAL)
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
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bf3d0)
Location: drivers/base/core.c:3231
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff816bf3d0-ffffffff816bf54c: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169a680)
Location: drivers/base/core.c:3231
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff8169a680-ffffffff8169a7fc: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ed8a0)
Location: drivers/base/core.c:3231
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff816ed8a0-ffffffff816eda1c: device_change_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_change_owner(struct device *dev, kuid_t kuid, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817080e0)
Location: drivers/base/core.c:3231
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - net/core/net-sysfs.c:netdev_change_owner
```
**Symbols:**

```
ffffffff817080e0-ffffffff8170825c: device_change_owner (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
