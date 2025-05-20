# Function: <code>queue_attr_visible</code>

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
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814ce130)
Location: block/blk-sysfs.c:773
Inline: False
```
**Symbols:**

```
ffffffff814ce130-ffffffff814ce15c: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814e7450)
Location: block/blk-sysfs.c:772
Inline: False
```
**Symbols:**

```
ffffffff814e7450-ffffffff814e747c: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff815463c0)
Location: block/blk-sysfs.c:785
Inline: False
```
**Symbols:**

```
ffffffff815463c0-ffffffff815463ec: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81561fd0)
Location: block/blk-sysfs.c:665
Inline: False
```
**Symbols:**

```
ffffffff81561fd0-ffffffff81562020: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8156a730)
Location: block/blk-sysfs.c:683
Inline: False
```
**Symbols:**

```
ffffffff8156a730-ffffffff8156a780: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff815cec30)
Location: block/blk-sysfs.c:687
Inline: False
```
**Symbols:**

```
ffffffff815cec30-ffffffff815cec80: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8167a120)
Location: block/blk-sysfs.c:673
Inline: False
```
**Symbols:**

```
ffffffff8167a120-ffffffff8167a18e: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff817365e0)
Location: block/blk-sysfs.c:683
Inline: False
```
**Symbols:**

```
ffffffff817365e0-ffffffff81736655: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81772c20)
Location: block/blk-sysfs.c:673
Inline: False
```
**Symbols:**

```
ffffffff81772c20-ffffffff81772c6e: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-sysfs.c (0)
Location: block/blk-sysfs.c:670
Inline: False
```
**Symbols:**

```
ffffffff817b60c0-ffffffff817b6120: queue_attr_visible (STB_LOCAL)
ffffffff821d2f76-ffffffff821d2f8b: queue_attr_visible.cold (STB_LOCAL)
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
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffff8000105e4f40)
Location: block/blk-sysfs.c:772
Inline: False
```
**Symbols:**

```
ffff8000105e4f40-ffff8000105e4f94: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (c0791f90)
Location: block/blk-sysfs.c:772
Inline: False
```
**Symbols:**

```
c0791f90-c0791fdc: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (c000000000778dd0)
Location: block/blk-sysfs.c:772
Inline: False
```
**Symbols:**

```
c000000000778dd0-c000000000778e20: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffe00042637e)
Location: block/blk-sysfs.c:772
Inline: False
```
**Symbols:**

```
ffffffe00042637e-ffffffe0004263c2: queue_attr_visible (STB_LOCAL)
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
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814dfa30)
Location: block/blk-sysfs.c:772
Inline: False
```
**Symbols:**

```
ffffffff814dfa30-ffffffff814dfa5c: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814d03d0)
Location: block/blk-sysfs.c:772
Inline: False
```
**Symbols:**

```
ffffffff814d03d0-ffffffff814d03fc: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814dbac0)
Location: block/blk-sysfs.c:772
Inline: False
```
**Symbols:**

```
ffffffff814dbac0-ffffffff814dbaec: queue_attr_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
umode_t queue_attr_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff814f4930)
Location: block/blk-sysfs.c:772
Inline: False
```
**Symbols:**

```
ffffffff814f4930-ffffffff814f495c: queue_attr_visible (STB_LOCAL)
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
