# Function: <code>new_id_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816148c0)
Location: drivers/usb/core/driver.c:135
Inline: False
```
**Symbols:**

```
ffffffff816148c0-ffffffff816148e4: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81674870)
Location: drivers/usb/core/driver.c:135
Inline: False
```
**Symbols:**

```
ffffffff81674870-ffffffff81674894: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816a2500)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff816a2500-ffffffff816a2524: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814b1b90)
Location: drivers/pci/pci-driver.c:99
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff816b7590)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff814b1b90-ffffffff814b1d45: new_id_store (STB_LOCAL)
ffffffff816b7590-ffffffff816b75b4: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814f1270)
Location: drivers/pci/pci-driver.c:99
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff81722e50)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff814f1270-ffffffff814f1425: new_id_store (STB_LOCAL)
ffffffff81722e50-ffffffff81722e74: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81521250)
Location: drivers/pci/pci-driver.c:98
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff81761bf0)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff81521250-ffffffff81521405: new_id_store (STB_LOCAL)
ffffffff81761bf0-ffffffff81761c14: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81537130)
Location: drivers/pci/pci-driver.c:98
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff81786200)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff81537130-ffffffff815372e3: new_id_store (STB_LOCAL)
ffffffff81786200-ffffffff81786224: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81566a90)
Location: drivers/pci/pci-driver.c:98
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81740030)
Location: drivers/dax/bus.c:110
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff817c46b0)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff81566a90-ffffffff81566c42: new_id_store (STB_LOCAL)
ffffffff81740030-ffffffff81740045: new_id_store (STB_LOCAL)
ffffffff817c46b0-ffffffff817c46d4: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81587df0)
Location: drivers/pci/pci-driver.c:98
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81764210)
Location: drivers/dax/bus.c:110
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff817f5050)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff81587df0-ffffffff81587fa2: new_id_store (STB_LOCAL)
ffffffff81764210-ffffffff81764225: new_id_store (STB_LOCAL)
ffffffff817f5050-ffffffff817f5074: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8162e650)
Location: drivers/pci/pci-driver.c:98
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81824130)
Location: drivers/dax/bus.c:110
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff818c5080)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff8162e650-ffffffff8162e802: new_id_store (STB_LOCAL)
ffffffff81824130-ffffffff81824145: new_id_store (STB_LOCAL)
ffffffff818c5080-ffffffff818c50a4: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81653d50)
Location: drivers/pci/pci-driver.c:173
Inline: False
```
```
In drivers/dax/bus.c (ffffffff818336f0)
Location: drivers/dax/bus.c:111
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff818d0f60)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff81653d50-ffffffff81653ef4: new_id_store (STB_LOCAL)
ffffffff818336f0-ffffffff81833705: new_id_store (STB_LOCAL)
ffffffff818d0f60-ffffffff818d0f84: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81636b90)
Location: drivers/pci/pci-driver.c:173
Inline: False
```
```
In drivers/dax/bus.c (ffffffff818167b0)
Location: drivers/dax/bus.c:109
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff818b4580)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff81636b90-ffffffff81636d35: new_id_store (STB_LOCAL)
ffffffff818167b0-ffffffff818167c5: new_id_store (STB_LOCAL)
ffffffff818b4580-ffffffff818b45a4: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816a6dd0)
Location: drivers/pci/pci-driver.c:187
Inline: False
```
```
In drivers/dax/bus.c (ffffffff818a0df0)
Location: drivers/dax/bus.c:109
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff81949ab0)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff816a6dd0-ffffffff816a6f75: new_id_store (STB_LOCAL)
ffffffff818a0df0-ffffffff818a0e05: new_id_store (STB_LOCAL)
ffffffff81949ab0-ffffffff81949ad4: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff817c9220)
Location: drivers/pci/pci-driver.c:188
Inline: False
```
```
In drivers/dax/bus.c (ffffffff819ea470)
Location: drivers/dax/bus.c:107
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff81aa1b60)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff817c9220-ffffffff817c93ed: new_id_store (STB_LOCAL)
ffffffff819ea470-ffffffff819ea491: new_id_store (STB_LOCAL)
ffffffff81aa1b60-ffffffff81aa1b93: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff818e6b80)
Location: drivers/pci/pci-driver.c:188
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81b66ef0)
Location: drivers/dax/bus.c:107
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff81c27470)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff818e6b80-ffffffff818e6d4d: new_id_store (STB_LOCAL)
ffffffff81b66ef0-ffffffff81b66f11: new_id_store (STB_LOCAL)
ffffffff81c27470-ffffffff81c274a3: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8192a1a0)
Location: drivers/pci/pci-driver.c:188
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81bba2b0)
Location: drivers/dax/bus.c:126
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff81c8e430)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff8192a1a0-ffffffff8192a36d: new_id_store (STB_LOCAL)
ffffffff81bba2b0-ffffffff81bba2d1: new_id_store (STB_LOCAL)
ffffffff81c8e430-ffffffff81c8e463: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81972890)
Location: drivers/pci/pci-driver.c:188
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81c0f430)
Location: drivers/dax/bus.c:126
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff81d42f80)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff81972890-ffffffff81972a8c: new_id_store (STB_LOCAL)
ffffffff81c0f430-ffffffff81c0f451: new_id_store (STB_LOCAL)
ffffffff81d42f80-ffffffff81d42fb3: new_id_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffff8000106ec128)
Location: drivers/pci/pci-driver.c:98
Inline: False
```
```
In drivers/dax/bus.c (ffff800010964740)
Location: drivers/dax/bus.c:110
Inline: False
```
```
In drivers/usb/core/driver.c (ffff800010a25dc8)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffff8000106ec128-ffff8000106ec2bc: new_id_store (STB_LOCAL)
ffff800010964740-ffff800010964788: new_id_store (STB_LOCAL)
ffff800010a25dc8-ffff800010a25e14: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c0887618)
Location: drivers/pci/pci-driver.c:98
Inline: False
```
```
In drivers/dax/bus.c (c0a3b0ac)
Location: drivers/dax/bus.c:110
Inline: False
```
```
In drivers/usb/core/driver.c (c0afb1f8)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
c0887618-c08877e8: new_id_store (STB_LOCAL)
c0a3b0ac-c0a3b0cc: new_id_store (STB_LOCAL)
c0afb1f8-c0afb230: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c000000000867ed0)
Location: drivers/pci/pci-driver.c:98
Inline: False
```
```
In drivers/dax/bus.c (c000000000a1b220)
Location: drivers/dax/bus.c:110
Inline: False
```
```
In drivers/usb/core/driver.c (c000000000ae1210)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
c000000000867ed0-c0000000008680e8: new_id_store (STB_LOCAL)
c000000000a1b220-c000000000a1b238: new_id_store (STB_LOCAL)
c000000000ae1210-c000000000ae1238: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffe0004c12a0)
Location: drivers/pci/pci-driver.c:98
Inline: False
```
```
In drivers/dax/bus.c (ffffffe0005d1406)
Location: drivers/dax/bus.c:110
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffe000647dc6)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffe0004c12a0-ffffffe0004c1414: new_id_store (STB_LOCAL)
ffffffe0005d1406-ffffffe0005d1442: new_id_store (STB_LOCAL)
ffffffe000647dc6-ffffffe000647e08: new_id_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157bc80)
Location: drivers/pci/pci-driver.c:98
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81718900)
Location: drivers/dax/bus.c:110
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff817ad430)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff8157bc80-ffffffff8157be32: new_id_store (STB_LOCAL)
ffffffff81718900-ffffffff81718915: new_id_store (STB_LOCAL)
ffffffff817ad430-ffffffff817ad454: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8156aa50)
Location: drivers/pci/pci-driver.c:98
Inline: False
```
```
In drivers/dax/bus.c (ffffffff816f0e30)
Location: drivers/dax/bus.c:110
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff8179ee30)
Location: drivers/usb/core/driver.c:138
Inline: False
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184ee10)
Location: drivers/hv/vmbus_drv.c:770
Inline: False
```
**Symbols:**

```
ffffffff8156aa50-ffffffff8156ac02: new_id_store (STB_LOCAL)
ffffffff816f0e30-ffffffff816f0e45: new_id_store (STB_LOCAL)
ffffffff8179ee30-ffffffff8179ee54: new_id_store (STB_LOCAL)
ffffffff8184ee10-ffffffff8184ef26: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157bb40)
Location: drivers/pci/pci-driver.c:98
Inline: False
```
```
In drivers/dax/bus.c (ffffffff817576d0)
Location: drivers/dax/bus.c:110
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff817e9ed0)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff8157bb40-ffffffff8157bcf2: new_id_store (STB_LOCAL)
ffffffff817576d0-ffffffff817576e5: new_id_store (STB_LOCAL)
ffffffff817e9ed0-ffffffff817e9ef4: new_id_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t new_id_store(struct device_driver *driver, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81596140)
Location: drivers/pci/pci-driver.c:98
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81772b70)
Location: drivers/dax/bus.c:110
Inline: False
```
```
In drivers/usb/core/driver.c (ffffffff818034d0)
Location: drivers/usb/core/driver.c:138
Inline: False
```
**Symbols:**

```
ffffffff81596140-ffffffff815962f2: new_id_store (STB_LOCAL)
ffffffff81772b70-ffffffff81772b85: new_id_store (STB_LOCAL)
ffffffff818034d0-ffffffff818034f4: new_id_store (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
