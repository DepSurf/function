# Function: <code>virtio_add_status</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8154e632)
Location: drivers/virtio/virtio.c:162
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff8154e090-ffffffff8154e0c5: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff815b1d58)
Location: drivers/virtio/virtio.c:162
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff815b1770-ffffffff815b17ad: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff815ea198)
Location: drivers/virtio/virtio.c:162
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff815e9ba0-ffffffff815e9bdd: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff816046a8)
Location: drivers/virtio/virtio.c:162
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff816040b0-ffffffff816040ed: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81636ae0)
Location: drivers/virtio/virtio.c:163
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff81636ae0-ffffffff81636b24: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81658840)
Location: drivers/virtio/virtio.c:163
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff81658840-ffffffff81658884: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff817096c5)
Location: drivers/virtio/virtio.c:163
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff817090d0-ffffffff81709114: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81726675)
Location: drivers/virtio/virtio.c:163
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff81726080-ffffffff817260c4: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8170a315)
Location: drivers/virtio/virtio.c:161
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff81709c90-ffffffff81709cd4: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81785cd5)
Location: drivers/virtio/virtio.c:162
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_features_ok
```
**Symbols:**

```
ffffffff81785640-ffffffff81785684: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff818bc9e5)
Location: drivers/virtio/virtio.c:163
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_features_ok
```
**Symbols:**

```
ffffffff818bc390-ffffffff818bc3e0: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81a0b705)
Location: drivers/virtio/virtio.c:163
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_features_ok
```
**Symbols:**

```
ffffffff81a0af90-ffffffff81a0afe0: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81a54595)
Location: drivers/virtio/virtio.c:163
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_features_ok
```
**Symbols:**

```
ffffffff81a53e20-ffffffff81a53e70: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81aa5235)
Location: drivers/virtio/virtio.c:163
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_features_ok
```
**Symbols:**

```
ffffffff81aa4aa0-ffffffff81aa4af0: virtio_add_status (STB_GLOBAL)
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
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffff800010820c88)
Location: drivers/virtio/virtio.c:163
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffff800010820c88-ffff800010820cdc: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (c093eab4)
Location: drivers/virtio/virtio.c:163
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
c093eab4-c093eafc: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (c0000000008ca480)
Location: drivers/virtio/virtio.c:163
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
c0000000008ca480-c0000000008ca514: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffe000517c60)
Location: drivers/virtio/virtio.c:163
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffe000517c60-ffffffe000517cac: virtio_add_status (STB_GLOBAL)
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
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8161e6e0)
Location: drivers/virtio/virtio.c:163
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff8161e6e0-ffffffff8161e724: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81612dd0)
Location: drivers/virtio/virtio.c:163
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff81612dd0-ffffffff81612e14: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8164c680)
Location: drivers/virtio/virtio.c:163
Inline: False
Direct callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff8164c680-ffffffff8164c6c4: virtio_add_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void virtio_add_status(struct virtio_device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81667255)
Location: drivers/virtio/virtio.c:163
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
```
**Symbols:**

```
ffffffff81666cb0-ffffffff81666ceb: virtio_add_status (STB_GLOBAL)
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
