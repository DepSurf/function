# Function: <code>role_store</code>

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
ssize_t role_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8192b7e0)
Location: drivers/usb/roles/class.c:224
Inline: False
```
**Symbols:**

```
ffffffff8192b7e0-ffffffff8192b877: role_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t role_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8190ed50)
Location: drivers/usb/roles/class.c:226
Inline: False
```
**Symbols:**

```
ffffffff8190ed50-ffffffff8190ede7: role_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t role_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:235
Inline: False
```
**Symbols:**

```
ffffffff819afb90-ffffffff819afc36: role_store (STB_LOCAL)
ffffffff81d2213a-ffffffff81d2214f: role_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t role_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:235
Inline: False
```
**Symbols:**

```
ffffffff81b0e490-ffffffff81b0e546: role_store (STB_LOCAL)
ffffffff81eedd0a-ffffffff81eedd1f: role_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t role_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:238
Inline: False
```
**Symbols:**

```
ffffffff81c9e6a0-ffffffff81c9e756: role_store (STB_LOCAL)
ffffffff820a5ea6-ffffffff820a5ebb: role_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t role_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:240
Inline: False
```
**Symbols:**

```
ffffffff81d059e0-ffffffff81d05a96: role_store (STB_LOCAL)
ffffffff821272b0-ffffffff821272c5: role_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t role_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (0)
Location: drivers/usb/roles/class.c:248
Inline: False
```
**Symbols:**

```
ffffffff81dbb500-ffffffff81dbb5b6: role_store (STB_LOCAL)
ffffffff82208c1c-ffffffff82208c31: role_store.cold (STB_LOCAL)
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
ssize_t role_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffff800010a916f0)
Location: drivers/usb/roles/class.c:205
Inline: False
```
**Symbols:**

```
ffff800010a916f0-ffff800010a917b0: role_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t role_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (c0b74eec)
Location: drivers/usb/roles/class.c:205
Inline: False
```
**Symbols:**

```
c0b74eec-c0b74fac: role_store (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
