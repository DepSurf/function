# Function: <code>rproc_is_visible</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
umode_t rproc_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:222
Inline: False
```
**Symbols:**

```
ffffffff81bd01c0-ffffffff81bd0249: rproc_is_visible (STB_LOCAL)
ffffffff81efef86-ffffffff81efef9b: rproc_is_visible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
umode_t rproc_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:222
Inline: False
```
**Symbols:**

```
ffffffff81d7b3f0-ffffffff81d7b479: rproc_is_visible (STB_LOCAL)
ffffffff820aa313-ffffffff820aa328: rproc_is_visible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
umode_t rproc_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:222
Inline: False
```
**Symbols:**

```
ffffffff81de95b0-ffffffff81de9639: rproc_is_visible (STB_LOCAL)
ffffffff8212b812-ffffffff8212b827: rproc_is_visible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
umode_t rproc_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:222
Inline: False
```
**Symbols:**

```
ffffffff81e9f7f0-ffffffff81e9f879: rproc_is_visible (STB_LOCAL)
ffffffff8220d439-ffffffff8220d44e: rproc_is_visible.cold (STB_LOCAL)
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
