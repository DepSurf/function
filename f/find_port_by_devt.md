# Function: <code>find_port_by_devt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815183c1)
Location: drivers/char/virtio_console.c:289
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8156b0d1)
Location: drivers/char/virtio_console.c:295
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81597841)
Location: drivers/char/virtio_console.c:294
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815ab861)
Location: drivers/char/virtio_console.c:294
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81612201)
Location: drivers/char/virtio_console.c:294
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8164bb7f)
Location: drivers/char/virtio_console.c:294
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81669d8f)
Location: drivers/char/virtio_console.c:294
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8169f3b0)
Location: drivers/char/virtio_console.c:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816c2140)
Location: drivers/char/virtio_console.c:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct port *find_port_by_devt(dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81774840)
Location: drivers/char/virtio_console.c:281
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:port_fops_open
```
**Symbols:**

```
ffffffff81774840-ffffffff81774948: find_port_by_devt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct port *find_port_by_devt(dev_t dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8178f5a0)
Location: drivers/char/virtio_console.c:281
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:port_fops_open
```
**Symbols:**

```
ffffffff8178f5a0-ffffffff8178f6a8: find_port_by_devt (STB_LOCAL)
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
In drivers/char/virtio_console.c (ffffffff81774e6d)
Location: drivers/char/virtio_console.c:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
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
In drivers/char/virtio_console.c (ffffffff817fabad)
Location: drivers/char/virtio_console.c:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
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
In drivers/char/virtio_console.c (ffffffff81939b4d)
Location: drivers/char/virtio_console.c:282
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
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
In drivers/char/virtio_console.c (ffffffff81a99ddd)
Location: drivers/char/virtio_console.c:274
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
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
In drivers/char/virtio_console.c (ffffffff81ae564d)
Location: drivers/char/virtio_console.c:275
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
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
In drivers/char/virtio_console.c (ffffffff81b389dd)
Location: drivers/char/virtio_console.c:272
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b3fa4)
Location: drivers/char/virtio_console.c:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c09ae830)
Location: drivers/char/virtio_console.c:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094e26c)
Location: drivers/char/virtio_console.c:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffe00056714a)
Location: drivers/char/virtio_console.c:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81687b90)
Location: drivers/char/virtio_console.c:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81665740)
Location: drivers/char/virtio_console.c:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
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
In drivers/char/virtio_console.c (ffffffff816b5ed0)
Location: drivers/char/virtio_console.c:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
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
In drivers/char/virtio_console.c (ffffffff816cfbd0)
Location: drivers/char/virtio_console.c:281
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
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
</ul>
