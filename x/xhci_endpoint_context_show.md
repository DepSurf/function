# Function: <code>xhci_endpoint_context_show</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81775320)
Location: drivers/usb/host/xhci-debugfs.c:273
Inline: False
```
**Symbols:**

```
ffffffff81775320-ffffffff81775581: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b6550)
Location: drivers/usb/host/xhci-debugfs.c:274
Inline: False
```
**Symbols:**

```
ffffffff817b6550-ffffffff817b67b1: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dcb40)
Location: drivers/usb/host/xhci-debugfs.c:274
Inline: False
```
**Symbols:**

```
ffffffff817dcb40-ffffffff817dcda1: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181ccf0)
Location: drivers/usb/host/xhci-debugfs.c:274
Inline: False
```
**Symbols:**

```
ffffffff8181ccf0-ffffffff8181cf5c: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184e0b0)
Location: drivers/usb/host/xhci-debugfs.c:274
Inline: False
```
**Symbols:**

```
ffffffff8184e0b0-ffffffff8184e31c: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff819215a0)
Location: drivers/usb/host/xhci-debugfs.c:274
Inline: False
```
**Symbols:**

```
ffffffff819215a0-ffffffff81921809: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81928bf0)
Location: drivers/usb/host/xhci-debugfs.c:275
Inline: False
```
**Symbols:**

```
ffffffff81928bf0-ffffffff81928e59: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190c280)
Location: drivers/usb/host/xhci-debugfs.c:275
Inline: False
```
**Symbols:**

```
ffffffff8190c280-ffffffff8190c4e2: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:278
Inline: False
```
**Symbols:**

```
ffffffff819ac1f0-ffffffff819ac4b1: xhci_endpoint_context_show (STB_LOCAL)
ffffffff81d22024-ffffffff81d22063: xhci_endpoint_context_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:278
Inline: False
```
**Symbols:**

```
ffffffff81b0a700-ffffffff81b0a9fe: xhci_endpoint_context_show (STB_LOCAL)
ffffffff81eedc05-ffffffff81eedc29: xhci_endpoint_context_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:278
Inline: False
```
**Symbols:**

```
ffffffff81c9a620-ffffffff81c9a91e: xhci_endpoint_context_show (STB_LOCAL)
ffffffff820a5e0c-ffffffff820a5e30: xhci_endpoint_context_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:279
Inline: False
```
**Symbols:**

```
ffffffff81d019e0-ffffffff81d01cda: xhci_endpoint_context_show (STB_LOCAL)
ffffffff821271b2-ffffffff821271d6: xhci_endpoint_context_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (0)
Location: drivers/usb/host/xhci-debugfs.c:279
Inline: False
```
**Symbols:**

```
ffffffff81db7060-ffffffff81db735a: xhci_endpoint_context_show (STB_LOCAL)
ffffffff82208b09-ffffffff82208b2d: xhci_endpoint_context_show.cold (STB_LOCAL)
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
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8e838)
Location: drivers/usb/host/xhci-debugfs.c:274
Inline: False
```
**Symbols:**

```
ffff800010a8e838-ffff800010a8eab8: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (c0b6196c)
Location: drivers/usb/host/xhci-debugfs.c:274
Inline: False
```
**Symbols:**

```
c0b6196c-c0b61bdc: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (c000000000b69f10)
Location: drivers/usb/host/xhci-debugfs.c:274
Inline: False
```
**Symbols:**

```
c000000000b69f10-c000000000b6a254: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a22b8)
Location: drivers/usb/host/xhci-debugfs.c:274
Inline: False
```
**Symbols:**

```
ffffffe0006a22b8-ffffffe0006a24f8: xhci_endpoint_context_show (STB_LOCAL)
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
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81803e80)
Location: drivers/usb/host/xhci-debugfs.c:274
Inline: False
```
**Symbols:**

```
ffffffff81803e80-ffffffff818040ec: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cb600)
Location: drivers/usb/host/xhci-debugfs.c:274
Inline: False
```
**Symbols:**

```
ffffffff817cb600-ffffffff817cb86c: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81842f30)
Location: drivers/usb/host/xhci-debugfs.c:274
Inline: False
```
**Symbols:**

```
ffffffff81842f30-ffffffff8184319c: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xhci_endpoint_context_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185d490)
Location: drivers/usb/host/xhci-debugfs.c:274
Inline: False
```
**Symbols:**

```
ffffffff8185d490-ffffffff8185d6fc: xhci_endpoint_context_show (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
