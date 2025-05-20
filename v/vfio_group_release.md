# Function: <code>vfio_group_release</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d0418)
Location: drivers/vfio/vfio.c:400
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_put
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_group_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189b870)
Location: drivers/vfio/vfio.c:401
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_put_external_user
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put_bg
```
**Symbols:**

```
ffffffff8189b870-ffffffff8189b9bb: vfio_group_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_group_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818aa480)
Location: drivers/vfio/vfio.c:401
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_put_external_user
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/vfio/vfio.c:vfio_group_put_bg
```
**Symbols:**

```
ffffffff818aa480-ffffffff818aa5cb: vfio_group_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_group_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188dcb0)
Location: drivers/vfio/vfio.c:391
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_put_external_user
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_group_put_bg
```
**Symbols:**

```
ffffffff8188dcb0-ffffffff8188ddfb: vfio_group_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vfio_group_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff819212f0)
Location: drivers/vfio/vfio.c:464
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_put_external_user
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_group_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_group_put_bg
```
**Symbols:**

```
ffffffff819212f0-ffffffff8192143b: vfio_group_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vfio_group_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a76340)
Location: drivers/vfio/vfio.c:330
Inline: False
```
**Symbols:**

```
ffffffff81a76340-ffffffff81a76387: vfio_group_release (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aae3dc)
Location: drivers/vfio/vfio.c:400
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_put
```
</details>
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
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177a4c8)
Location: drivers/vfio/vfio.c:400
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_put
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c5298)
Location: drivers/vfio/vfio.c:400
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_put
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817df538)
Location: drivers/vfio/vfio.c:400
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_put
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kref *kref</code>
</li>
</ul>
</details>
</li>
</ul>
