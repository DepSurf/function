# Function: <code>recovery_show</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t recovery_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff819cc310)
Location: drivers/remoteproc/remoteproc_sysfs.c:13
Inline: False
```
**Symbols:**

```
ffffffff819cc310-ffffffff819cc349: recovery_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t recovery_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff819b16c0)
Location: drivers/remoteproc/remoteproc_sysfs.c:13
Inline: False
```
**Symbols:**

```
ffffffff819b16c0-ffffffff819b16f9: recovery_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t recovery_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:13
Inline: False
```
**Symbols:**

```
ffffffff81a5fe10-ffffffff81a5fe5a: recovery_show (STB_LOCAL)
ffffffff81d32abe-ffffffff81d32ad2: recovery_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t recovery_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:13
Inline: False
```
**Symbols:**

```
ffffffff81bd0250-ffffffff81bd02a7: recovery_show (STB_LOCAL)
ffffffff81efef9b-ffffffff81efefb0: recovery_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t recovery_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:13
Inline: False
```
**Symbols:**

```
ffffffff81d7b490-ffffffff81d7b4e7: recovery_show (STB_LOCAL)
ffffffff820aa328-ffffffff820aa33d: recovery_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t recovery_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:13
Inline: False
```
**Symbols:**

```
ffffffff81de9650-ffffffff81de96a7: recovery_show (STB_LOCAL)
ffffffff8212b827-ffffffff8212b83c: recovery_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t recovery_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:13
Inline: False
```
**Symbols:**

```
ffffffff81e9f890-ffffffff81e9f8e7: recovery_show (STB_LOCAL)
ffffffff8220d44e-ffffffff8220d463: recovery_show.cold (STB_LOCAL)
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
