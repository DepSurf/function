# Function: <code>virtio_features_ok</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int virtio_features_ok(struct virtio_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio.c (0)
Location: drivers/virtio/virtio.c:170
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff81785ae0-ffffffff81785b71: virtio_features_ok (STB_LOCAL)
ffffffff81cf4347-ffffffff81cf4398: virtio_features_ok.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int virtio_features_ok(struct virtio_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio.c (0)
Location: drivers/virtio/virtio.c:171
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff818bc7d0-ffffffff818bc876: virtio_features_ok (STB_LOCAL)
ffffffff81ebc47c-ffffffff81ebc4bd: virtio_features_ok.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int virtio_features_ok(struct virtio_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81a0b4b0)
Location: drivers/virtio/virtio.c:171
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff81a0b4b0-ffffffff81a0b58c: virtio_features_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int virtio_features_ok(struct virtio_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81a54340)
Location: drivers/virtio/virtio.c:171
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff81a54340-ffffffff81a5441c: virtio_features_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int virtio_features_ok(struct virtio_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81aa4fe0)
Location: drivers/virtio/virtio.c:171
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff81aa4fe0-ffffffff81aa50bc: virtio_features_ok (STB_LOCAL)
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
