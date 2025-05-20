# Function: <code>xhci_stream_id_open</code>

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
int xhci_stream_id_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81927a90)
Location: drivers/usb/host/xhci-debugfs.c:493
Inline: False
```
**Symbols:**

```
ffffffff81927a90-ffffffff81927ab4: xhci_stream_id_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_stream_id_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190b110)
Location: drivers/usb/host/xhci-debugfs.c:493
Inline: False
```
**Symbols:**

```
ffffffff8190b110-ffffffff8190b134: xhci_stream_id_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xhci_stream_id_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff819aba30)
Location: drivers/usb/host/xhci-debugfs.c:499
Inline: False
```
**Symbols:**

```
ffffffff819aba30-ffffffff819aba54: xhci_stream_id_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xhci_stream_id_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b09e80)
Location: drivers/usb/host/xhci-debugfs.c:499
Inline: False
```
**Symbols:**

```
ffffffff81b09e80-ffffffff81b09eae: xhci_stream_id_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_stream_id_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c99cf0)
Location: drivers/usb/host/xhci-debugfs.c:499
Inline: False
```
**Symbols:**

```
ffffffff81c99cf0-ffffffff81c99d1e: xhci_stream_id_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_stream_id_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d010b0)
Location: drivers/usb/host/xhci-debugfs.c:500
Inline: False
```
**Symbols:**

```
ffffffff81d010b0-ffffffff81d010de: xhci_stream_id_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_stream_id_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db6be0)
Location: drivers/usb/host/xhci-debugfs.c:500
Inline: False
```
**Symbols:**

```
ffffffff81db6be0-ffffffff81db6c0e: xhci_stream_id_open (STB_LOCAL)
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
