# Function: <code>device_unbind_cleanup</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_unbind_cleanup(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8197cbd0)
Location: drivers/base/dd.c:523
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff8197cbd0-ffffffff8197cc49: device_unbind_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_unbind_cleanup(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81ae9de0)
Location: drivers/base/dd.c:528
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff81ae9de0-ffffffff81ae9e59: device_unbind_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_unbind_cleanup(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b38160)
Location: drivers/base/dd.c:547
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff81b38160-ffffffff81b381d9: device_unbind_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_unbind_cleanup(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b8fc00)
Location: drivers/base/dd.c:547
Inline: False
Direct callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff81b8fc00-ffffffff81b8fc79: device_unbind_cleanup (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
