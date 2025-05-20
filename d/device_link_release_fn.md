# Function: <code>device_link_release_fn</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_link_release_fn(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aa4e0)
Location: drivers/base/core.c:469
Inline: False
```
**Symbols:**

```
ffffffff817aa4e0-ffffffff817aa558: device_link_release_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_link_release_fn(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff818336c0)
Location: drivers/base/core.c:481
Inline: False
```
**Symbols:**

```
ffffffff818336c0-ffffffff8183371e: device_link_release_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void device_link_release_fn(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:482
Inline: False
```
**Symbols:**

```
ffffffff81976790-ffffffff81976841: device_link_release_fn (STB_LOCAL)
ffffffff81ecb2a8-ffffffff81ecb2bd: device_link_release_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void device_link_release_fn(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:554
Inline: False
```
**Symbols:**

```
ffffffff81ae29d0-ffffffff81ae2a81: device_link_release_fn (STB_LOCAL)
ffffffff820982fa-ffffffff8209830f: device_link_release_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void device_link_release_fn(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:499
Inline: False
```
**Symbols:**

```
ffffffff81b308f0-ffffffff81b309a1: device_link_release_fn (STB_LOCAL)
ffffffff82119326-ffffffff8211933b: device_link_release_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void device_link_release_fn(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:502
Inline: False
```
**Symbols:**

```
ffffffff81b87ef0-ffffffff81b87fa1: device_link_release_fn (STB_LOCAL)
ffffffff821f72e9-ffffffff821f72fe: device_link_release_fn.cold (STB_LOCAL)
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
