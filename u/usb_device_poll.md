# Function: <code>usb_device_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff8161df80)
Location: drivers/usb/core/devices.c:650
Inline: False
```
**Symbols:**

```
ffffffff8161df80-ffffffff8161dfc9: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff8167e7c0)
Location: drivers/usb/core/devices.c:644
Inline: False
```
**Symbols:**

```
ffffffff8167e7c0-ffffffff8167e809: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff816ac540)
Location: drivers/usb/core/devices.c:638
Inline: False
```
**Symbols:**

```
ffffffff816ac540-ffffffff816ac589: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff816c17a0)
Location: drivers/usb/core/devices.c:638
Inline: False
```
**Symbols:**

```
ffffffff816c17a0-ffffffff816c17e6: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff8172d570)
Location: drivers/usb/core/devices.c:625
Inline: False
```
**Symbols:**

```
ffffffff8172d570-ffffffff8172d5b9: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__poll_t usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff8176c3a0)
Location: drivers/usb/core/devices.c:625
Inline: False
```
**Symbols:**

```
ffffffff8176c3a0-ffffffff8176c3e9: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__poll_t usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff817909f0)
Location: drivers/usb/core/devices.c:625
Inline: False
```
**Symbols:**

```
ffffffff817909f0-ffffffff81790a39: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__poll_t usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff817cf2d0)
Location: drivers/usb/core/devices.c:625
Inline: False
```
**Symbols:**

```
ffffffff817cf2d0-ffffffff817cf31e: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__poll_t usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff81800140)
Location: drivers/usb/core/devices.c:625
Inline: False
```
**Symbols:**

```
ffffffff81800140-ffffffff8180018e: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__poll_t usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff818d1360)
Location: drivers/usb/core/devices.c:623
Inline: False
```
**Symbols:**

```
ffffffff818d1360-ffffffff818d13b1: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
__poll_t usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffff800010a33fd8)
Location: drivers/usb/core/devices.c:625
Inline: False
```
**Symbols:**

```
ffff800010a33fd8-ffff800010a3404c: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__poll_t usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (c0b07800)
Location: drivers/usb/core/devices.c:625
Inline: False
```
**Symbols:**

```
c0b07800-c0b0786c: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__poll_t usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (c000000000af1880)
Location: drivers/usb/core/devices.c:625
Inline: False
```
**Symbols:**

```
c000000000af1880-c000000000af1908: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__poll_t usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffe000651c3a)
Location: drivers/usb/core/devices.c:625
Inline: False
```
**Symbols:**

```
ffffffe000651c3a-ffffffe000651c8e: usb_device_poll (STB_LOCAL)
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
__poll_t usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff817b8520)
Location: drivers/usb/core/devices.c:625
Inline: False
```
**Symbols:**

```
ffffffff817b8520-ffffffff817b856e: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__poll_t usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff817a9f50)
Location: drivers/usb/core/devices.c:625
Inline: False
```
**Symbols:**

```
ffffffff817a9f50-ffffffff817a9f9e: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__poll_t usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff817f4fc0)
Location: drivers/usb/core/devices.c:625
Inline: False
```
**Symbols:**

```
ffffffff817f4fc0-ffffffff817f500e: usb_device_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__poll_t usb_device_poll(struct file *file, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff8180f200)
Location: drivers/usb/core/devices.c:625
Inline: False
```
**Symbols:**

```
ffffffff8180f200-ffffffff8180f24e: usb_device_poll (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>__poll_t</code>
</li>
</ul>
</details>
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
