# Function: <code>virtio_config_disable</code>

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
In drivers/virtio/virtio.c (ffffffff814bea0d)
Location: drivers/virtio/virtio.c:148
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_device_freeze
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
In drivers/virtio/virtio.c (ffffffff8150ef1d)
Location: drivers/virtio/virtio.c:148
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
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
In drivers/virtio/virtio.c (ffffffff8153b07d)
Location: drivers/virtio/virtio.c:148
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8154e91d)
Location: drivers/virtio/virtio.c:143
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffffffff8154e570-ffffffff8154e5a7: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff815b20ad)
Location: drivers/virtio/virtio.c:143
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffffffff815b1c90-ffffffff815b1cc7: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff815ea50c)
Location: drivers/virtio/virtio.c:143
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffffffff815ea0d0-ffffffff815ea107: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81604a1c)
Location: drivers/virtio/virtio.c:143
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffffffff816045e0-ffffffff81604617: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81637309)
Location: drivers/virtio/virtio.c:144
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffffffff81636fa0-ffffffff81636fd5: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81659069)
Location: drivers/virtio/virtio.c:144
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffffffff81658d00-ffffffff81658d35: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff817093c0)
Location: drivers/virtio/virtio.c:144
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffffffff817093c0-ffffffff817093f5: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81726370)
Location: drivers/virtio/virtio.c:144
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffffffff81726370-ffffffff817263a5: virtio_config_disable (STB_GLOBAL)
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
In drivers/virtio/virtio.c (ffffffff81709ff9)
Location: drivers/virtio/virtio.c:144
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
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
In drivers/virtio/virtio.c (ffffffff81785979)
Location: drivers/virtio/virtio.c:145
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
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
In drivers/virtio/virtio.c (ffffffff818bc2b9)
Location: drivers/virtio/virtio.c:146
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
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
In drivers/virtio/virtio.c (ffffffff81a0ae99)
Location: drivers/virtio/virtio.c:146
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
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
In drivers/virtio/virtio.c (ffffffff81a53d29)
Location: drivers/virtio/virtio.c:146
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
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
In drivers/virtio/virtio.c (ffffffff81aa4989)
Location: drivers/virtio/virtio.c:146
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffff8000108216e8)
Location: drivers/virtio/virtio.c:144
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffff8000108212a8-ffff80001082133c: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (c093e990)
Location: drivers/virtio/virtio.c:144
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
c093e990-c093e9d8: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (c0000000008cb2f4)
Location: drivers/virtio/virtio.c:144
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
c0000000008cacf0-c0000000008cadb4: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffe000517cc6)
Location: drivers/virtio/virtio.c:144
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffffffe0005181f2-ffffffe000518266: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8161ef09)
Location: drivers/virtio/virtio.c:144
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffffffff8161eba0-ffffffff8161ebd5: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff816135e9)
Location: drivers/virtio/virtio.c:144
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffffffff81613290-ffffffff816132bf: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8164cea9)
Location: drivers/virtio/virtio.c:144
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffffffff8164cb40-ffffffff8164cb75: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void virtio_config_disable(struct virtio_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81666d09)
Location: drivers/virtio/virtio.c:144
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
```
**Symbols:**

```
ffffffff81666c20-ffffffff81666c4c: virtio_config_disable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
