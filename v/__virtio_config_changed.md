# Function: <code>__virtio_config_changed</code>

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
In drivers/virtio/virtio.c (ffffffff814be9bd)
Location: drivers/virtio/virtio.c:128
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_changed
  - drivers/virtio/virtio.c:virtio_config_enable
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
In drivers/virtio/virtio.c (ffffffff8150ebd5)
Location: drivers/virtio/virtio.c:128
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffff8153ad35)
Location: drivers/virtio/virtio.c:128
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffff8154e5d5)
Location: drivers/virtio/virtio.c:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffff815b1cf5)
Location: drivers/virtio/virtio.c:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffff815ea135)
Location: drivers/virtio/virtio.c:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffff81604645)
Location: drivers/virtio/virtio.c:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffff81637005)
Location: drivers/virtio/virtio.c:124
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffff81658d65)
Location: drivers/virtio/virtio.c:124
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8170903f)
Location: drivers/virtio/virtio.c:124
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffff81725fcf)
Location: drivers/virtio/virtio.c:124
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffff81709fbf)
Location: drivers/virtio/virtio.c:124
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __virtio_config_changed(struct virtio_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio.c (0)
Location: drivers/virtio/virtio.c:125
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
```
**Symbols:**

```
ffffffff817858c0-ffffffff81785914: __virtio_config_changed (STB_LOCAL)
ffffffff81cf431e-ffffffff81cf4332: __virtio_config_changed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __virtio_config_changed(struct virtio_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio.c (0)
Location: drivers/virtio/virtio.c:126
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_config_changed
```
**Symbols:**

```
ffffffff818bc670-ffffffff818bc6d9: __virtio_config_changed (STB_LOCAL)
ffffffff81ebc467-ffffffff81ebc47c: __virtio_config_changed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __virtio_config_changed(struct virtio_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio.c (0)
Location: drivers/virtio/virtio.c:126
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_config_changed
```
**Symbols:**

```
ffffffff81a0b320-ffffffff81a0b389: __virtio_config_changed (STB_LOCAL)
ffffffff820939bf-ffffffff820939d4: __virtio_config_changed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __virtio_config_changed(struct virtio_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio.c (0)
Location: drivers/virtio/virtio.c:126
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_config_changed
```
**Symbols:**

```
ffffffff81a541b0-ffffffff81a54219: __virtio_config_changed (STB_LOCAL)
ffffffff821146cb-ffffffff821146e0: __virtio_config_changed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __virtio_config_changed(struct virtio_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio.c (0)
Location: drivers/virtio/virtio.c:126
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_config_changed
```
**Symbols:**

```
ffffffff81aa4e30-ffffffff81aa4e99: __virtio_config_changed (STB_LOCAL)
ffffffff821f219f-ffffffff821f21b4: __virtio_config_changed.cold (STB_LOCAL)
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
In drivers/virtio/virtio.c (ffff800010821398)
Location: drivers/virtio/virtio.c:124
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (c093ea0c)
Location: drivers/virtio/virtio.c:124
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (c0000000008cae08)
Location: drivers/virtio/virtio.c:124
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffe000518294)
Location: drivers/virtio/virtio.c:124
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffff8161ec05)
Location: drivers/virtio/virtio.c:124
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffff816132e5)
Location: drivers/virtio/virtio.c:124
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffff8164cba5)
Location: drivers/virtio/virtio.c:124
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
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
In drivers/virtio/virtio.c (ffffffff81666c75)
Location: drivers/virtio/virtio.c:124
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
```
</details>
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
