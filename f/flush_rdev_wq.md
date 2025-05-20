# Function: <code>flush_rdev_wq</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196f3ba)
Location: drivers/md/md.c:4550
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:new_dev_store
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
In drivers/md/md.c (ffffffff81976144)
Location: drivers/md/md.c:4580
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:new_dev_store
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
In drivers/md/md.c (ffffffff8195a317)
Location: drivers/md/md.c:4544
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:new_dev_store
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
In drivers/md/md.c (ffffffff819ffae6)
Location: drivers/md/md.c:4563
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:new_dev_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flush_rdev_wq(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b572f0)
Location: drivers/md/md.c:4552
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff81b572f0-ffffffff81b57346: flush_rdev_wq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flush_rdev_wq(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cf0800)
Location: drivers/md/md.c:4515
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:new_dev_store
```
**Symbols:**

```
ffffffff81cf0800-ffffffff81cf0856: flush_rdev_wq (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
